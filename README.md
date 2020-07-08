# OSistematico-cursor-theme
Tema de cursor baseado no Deepin 15, customizado para uso particular e pensado em temas de tonalidades laranja/vermelho.

Este tema foi uma customização realizada há alguns anos, meu objetivo principal era utilizá-lo com o tema Yaru do Ubuntu. Mas combina perfeitamente com outros que tenham tonalidades alaranjadas ou avermelhadas. Por exemplo o do Pop!_OS.

Alguns aspectos foram customizados, segue o [repositório oficial do projeto Deepin](https://github.com/linuxdeepin/deepin-cursor-theme) na qual me baseei.

![Prévia Osistemático cursor theme](https://github.com/HenriqueAD7/OSistematico-cursor-theme/blob/master/Exemplo.png)

***

## Como utilizar o tema

**[Efetue do download do tema de cursores](https://github.com/HenriqueAD7/OSistematico-cursor-theme/releases/)** e crie o diretório **".icons"** em sua **"home"**, caso não exista. O mesmo é oculto, então você deve habilitar tal meio de visualização em sua distro. Falando do gestor de arquivos do Gnome Shell, o Nautilus, a combinação de teclas para habilitar tal modo é **"CTRL H"**.

Extraia o arquivo e adicione no diretório **".icons"** e faça uso de algum app/meio que permita escolher o tema de cursor.

***

# Como utilizar o script junto ao fonte do projeto

Por meio do utilitário **xcursorgen** é possível criar temas de ícones à partir de imagens "PNG".

Para tal, crie um arquivo de configuração (com o editor de texto) de terminação/extensão "CFG" referente ao componente especifico do cursor.

Segue o [exemplo do fórum do Ubuntu](https://ubuntuforums.org/showthread.php?t=2384798) e [vídeo demonstrativo de um único elemento](https://www.youtube.com/watch?v=joTBaWnagRA).

***

## Automatizando a criação

No caso da customização do Deepin, um script foi utilizado simplificando todo o processo. Porém levando em consideração estes passos:

* Todos os arquivos de configuração estão presente, mas utilizando a terminação/extensão "IN" ao invés de "CFG" ou até mesmo "CURSORS";
* As imagens foram categorizadas em 3 tamanhos: 24p, 32p e 48p;
* O destino final dos arquivos deve ser configurado no script **""make.sh""**. 

Por exemplo utilizei uma pasta na minha "home":

>/home/henriquead/AD/HenriqueAD/cursors/
 
Após todo o ambiente preparado, basta rodar o scrip.

>./make.sh

***

## Considere apoioar o projeto OSistemático

[Apoia.se](https://apoia.se/osistematico) |
[Youtube](https://www.youtube.com/OSistematico) |
[Site](http://www.osistematico.com.br/) |
[Twitter](https://twitter.com/henriquead7)

***Obrigado pela atenção e apoio de todos, SISTEMATICAMENTE!***
