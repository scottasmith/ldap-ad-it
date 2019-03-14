# Simple LDAP server simulating AD used for testing Adldap2-Laravel

This is a simple LDAP server that tries to simulate an AD using Apache Directory Server.

* Mainly forked for use with Adldap2-Laravel using OpenLDAP as the schema
* Is based on https://github.com/dwimberger/ldap-ad-it/

## Docker

1. Build image `docker build -t scottsmith/ldap-ad-it .`
2. Run the image using  
   `docker run -it --rm -p 10389:10389 docker build -t scottsmith/ldap-ad-it .`


