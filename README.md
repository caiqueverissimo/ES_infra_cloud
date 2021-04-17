# ES_infra_cloud
Diretorio Destinado as Aulas de Insfra e Cloud - MBA Impacta
Exercio 1 - Subir uma Maquina Virtual com MYSQL instalado utilizando VAGRANT . Ser acessivel pela porta 3306.


/*Criando a Tabela no MYSQL */
 CREATE TABLE Exercicio1
    ->  (
    -> ID_TESTE MEDIUMINT NOT NULL AUTO_INCREMENT,
    -> AULA varchar(20),
    -> STATUS varchar(10),
    -> PRIMARY KEY (ID_TESTE)
    -> )

/* Resultado após inserção de 1 registro */
mysql> select * from Exercicio1;
+----------+------+--------+
| ID_TESTE | AULA | STATUS |
+----------+------+--------+
|        1 | 1    | 1      |
+----------+------+--------+
1 row in set (0.00 sec)
