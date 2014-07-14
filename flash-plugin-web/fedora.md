Fedora 19
===

    
### Digite no terminal:

    # rpm -ivh flash-plugin-11.2.202.332-release.x86_64.rpm


### Baixe o arquivo _tar.gz_ no site Adobe: [http://get.adobe.com/br/flashplayer/](http://get.adobe.com/br/flashplayer/)


### Descompactar o diretório

    # tar -zxvf install_flash_player_"version"_linux."processor".tar.gz 


### Mover plugin para instalação do Firefox

    # cd install_flash_player_"version"_linux."processor"
    # cp libflashplayer.so /usr/lib/mozilla/plugins


Reinicie o Firefox e o plugin já estará funcionando, verifique se o plugin precisa ser 
atualizado em [https://www.mozilla.org/pt-BR/plugincheck/](https://www.mozilla.org/pt-BR/plugincheck/)


### Fonte: [https://support.mozilla.org/](https://support.mozilla.org/pt-BR/kb/instalar-o-plugin-flash-para-acessar-videos-animac)