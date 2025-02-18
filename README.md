# DAT151

https://docs.google.com/document/d/1-0YJe_UN34JgEZZ1j5CGhiLRdQ-yT2yL/edit

Server slutter på 164, user iannen General29 sshport 15003

linux root = General29, user iannen samme pass

mariadb, har socketauth
CREATE DATABASE privBase;
CREATE USER 'iannen'@'%' IDENTIFIED BY 'General29';
GRANT ALL PRIVILEGES ON privBase.* TO 'iannen'@'%';

log-bin=mysql-bin
log-bin-trust-function-creators
character-set-server=utf8
collation-server=utf8_danish_ci


