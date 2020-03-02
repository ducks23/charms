# charms

This is a my first charm written. Layer example relates to a mysql database


# To deploy: 


1. cd ~/charms/layers 
1. charm proof example 
1. charm build example 
1. juju deploy ./example 
1. juju deploy cs:mysql 
1. juju relate example mysql 


# To see if successful 

1. juju ssh example/0 sudo cat /root/text-file.txt


output should be similar to : 

* DB_HOST = ‘10.170.55.25’
* DB_NAME = ‘example’
* DB_USER = ‘Dae7EGh9Zei0nee’
* DB_PASSWORD = ‘aiRei1siePhewah’
