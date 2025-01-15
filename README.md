# JDBC-bytebank

[Gut Hub](https://github.com/alura-cursos/byte-bank-alura.git)


Criação do banco de dados MySQL

````
CREATE DATABASE byte_bank;

````

```

CREATE TABLE conta (

    numero INT PRIMARY KEY,
    saldo DECIMAL(10, 2) NOT NULL,
    cliente_nome VARCHAR(255) NOT NULL,
    cliente_cpf VARCHAR(20) NOT NULL,
    cliente_email VARCHAR(255) NOT NULL,
    esta_ativa tinyint(1) DEFAULT 1
);

````
