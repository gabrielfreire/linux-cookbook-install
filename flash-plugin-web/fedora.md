Fedora 19
===


Baixe o arquivo _tar.gz_ no site Adobe: [http://get.adobe.com/br/flashplayer/](http://get.adobe.com/br/flashplayer/)


### Descompactar o diretório

    # tar -zxvf install_flash_player_"version"_linux."processor".tar.gz 


### Mover plugin para instalação do Firefox

    # cd install_flash_player_"version"_linux."processor"
    # cp libflashplayer.so /usr/lib/mozilla/plugins

### Digite no terminal:

    # rpm -ivh http://linuxdownload.adobe.com/adobe-release/adobe-release-x86_64-1.0-1.noarch.rpm
    # yum install flash-plugin


Reinicie o Firefox e o plugin já estará funcionando, verifique se o plugin precisa ser 
atualizado em [https://www.mozilla.org/pt-BR/plugincheck/](https://www.mozilla.org/pt-BR/plugincheck/)


### Fonte:             
[https://support.mozilla.org/](https://support.mozilla.org/pt-BR/kb/instalar-o-plugin-flash-para-acessar-videos-animac)
