Instalar a versão 1.8.5.3 do git
----

Download dos arquivos:

	wget http://git-core.googlecode.com/files/git-1.8.5.3.tar.gz
	wget -O git-manpages-1.8.5.3.tar.gz http://code.google.com/p/git-core/downloads/detail?name=git-manpages-1.8.5.3.tar.gz&can=2&q=

Instalar as bibliotecas necessárias:
        
	# yum install zlib-devel perl-CPAN gettext curl-devel gcc

Realizar a instalação:
    
	tar xvfz git-1.8.5.3.tar.gz 
	cd git-1.8.5.3 
	./configure 
	make 
	sudo make prefix=/usr install 
	git --version
	


Referências 
---------
http://www.unixmen.com/how-to-install-latest-git-on-rhel-6-centos-6/ 

http://halyph.blogspot.com.br/2013/08/how-to-install-git-1834-on-centos-64.html
