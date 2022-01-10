# Criar usuário para acesso externo

- CREATE USER 'danilo'@'localhost' IDENTIFIED BY 'passwordADefinir';
- CREATE USER 'danilo'@'%' IDENTIFIED BY 'passwordADefinir';

- GRANT ALL ON _._ TO 'danilo'@'localhost';
- GRANT ALL ON _._ TO 'danilo'@'%';
- flush privileges;

# Acessar mysql terminal

- mysql -u root -p
