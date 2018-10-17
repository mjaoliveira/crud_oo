# crud_oo

mysql

create database crudoo
default character set utf8
default collate utf8_general_ci;

create table contatos(
id int auto_increment primary key not null,
nome varchar(100),
email varchar(100) not null
)default charset = utf8;

select * from contatos;