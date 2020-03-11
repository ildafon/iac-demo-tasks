docker exec -it b8f398652cf0 psql -U zabbix 

CREATE USER test SUPERUSER PASSWORD '98giu2b3eqd98gub98gub3q';
CREATE DATABASE test;
GRANT ALL PRIVILEGES ON DATABASE test TO test;
