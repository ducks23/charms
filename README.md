# charms

This is a my first charm written. Layer example relates to a mysql database


to deploy


cd ~/charms/layers
charm proof example
charm build example
juju deploy ./example
juju deploy cs:mysql
juju relate example mysql
