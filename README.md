# MYSQL-server

DROP INDEX IdxPhone ON customers;

CREATE USER 'bob'@'localhost'
IDENTIFIED BY '_S$cu3r3!';

GRANT INSERT ON salesDB.*
TO 'bob'@'localhost';

ALTER USER 'bob'@'localhost'
IDENTIFIED BY '_P$55!23';
DROP INDEX IdxPhone ON customers;
CREATE USER 'bob'@'localhost'
IDENTIFIED BY '_S$cu3r3!';
GRANT INSERT ON salesDB.*
TO 'bob'@'localhost';
