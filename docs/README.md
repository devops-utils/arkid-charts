```shell
sudo docker-compose up -d
sudo docker-compose down

sudo docker-compose up phpldapadmin
sudo docker-compose up -d phpldapadmin

docker exec -it arkid-ldap bash
cat /etc/openldap/slapd.conf

docker-compose logs -f

http://49.232.6.131:8989/
admin
admin

http://49.232.6.131:8075/
cn=admin,dc=example,dc=org
admin
```
