CENTOS 6.4
===

Talvez seja preciso instalar o EPEL antes:

    # wget http://dl.fedoraproject.org/pub/epel/6/i386/epel-release-6-8.noarch.rpm
    # rpm -ivh EPEL-release-6-8.noarch.rpm 


Instale o software:

    # yum install phpmyadmin -y 


Reinicie o apache

    # /etc/init.d/httpd restart 



### Correção de "phpMyAdmin Error #2002"

É necessário realizar um desligamento do servidor a partir da linha de comando. Isto irá parar os serviços em execução antes de desligar a máquina.                
              
Baseado em Centos, um método adicional para iniciar novamente é mover mysql.sock.          
           
Reiniciar o serviço cria uma nova entrada chamada mqsql.sock
            
	# shutdown -h now
	# mv /var/lib/mysql/mysql.sock /var/lib/mysql/mysql.sock.bak
	# service mysqld start

**Fonte:** http://stackoverflow.com/questions/20407292/centos-another-mysql-daemon-already-running-with-the-same-unix-socket
