create database if not exists loja;
use loja;

create table if not exists clientes(
	id_cliente int primary key auto_increment,
    nome varchar(100) not null,
    idade int not null,
    cidade varchar(100) not null
);
