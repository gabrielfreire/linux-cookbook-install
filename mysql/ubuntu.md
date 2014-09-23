UBUNTU 12+


	# apt-get install mysql-server


Setar nova senha de root para o mysql(opcional):

	mysqladmin -u root password novasenha
	

Checar se o mysql está funcionando:

	netstat -tap | grep -e mysql
