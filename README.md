# charms
\n
This is a my first charm written. Layer example relates to a mysql database


# to deploy
\n

cd ~/charms/layers \n
charm proof example \n
charm build example \n
juju deploy ./example \n
juju deploy cs:mysql \n
juju relate example mysql 
