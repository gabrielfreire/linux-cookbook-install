Firefox
===

No GNOME, o Firefox já vem instalado. Porém, no KDE precisamos baixar e criar um atalho, siga os passos:


### Download    
[http://www.mozilla.org/pt-BR/firefox/new/](http://www.mozilla.org/pt-BR/firefox/new/)



### Instalar          

    # tar -jxvf firefox-<versao>.tar.bz2
    # mv firefox /opt/
    
    
    
### Criar atalho

    # nano /usr/share/applications/firefox.desktop            

    
Insira o seguinte conteúdo e salve o arquivo

    [Desktop Entry]
    Encoding=UTF-8
    Name=Firefox
    Comment=Navegador web
    GenericName=Web Browser
    Exec=/opt/firefox/firefox %u
    Terminal=false
    X-MultipleArgs=false
    Type=Application
    Icon=/opt/firefox/browser/chrome/icons/default/default48.png
    Categories=Application;Network;
    MimeType=text/html;text/xml;application/xhtml+xml;application/xml;application/vnd.mozilla.xul+xml;ap$
    StartupWMClass=Firefox-bin
    StartupNotify=true


_Pronto, o Firefox está entre os seus aplicativos._

