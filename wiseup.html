

CREATE TABLE diretor(
	id INT PRIMARY KEY AUTO_INCREMENT,
	nome VARCHAR(70) NOT NULL,
	email VARCHAR(70) NOT NULL, 
	idade DATE,
	sexo CHAR(1),
	cpf VARCHAR(11) NOT NULL 
)

CREATE TABLE endereco_professor(
	id INT PRIMARY KEY AUTO_INCREMENT,
	cep VARCHAR(8) NOT NULL,
	rua VARCHAR(50),
	numero VARCHAR(3),
	bairro VARCHAR(25),
	cidade VARCHAR(25),
	estado VARCHAR(25),
	pais VARCHAR(25)
)

CREATE TABLE professor(
	id INT PRIMARY KEY AUTO_INCREMENT,
	nome VARCHAR(70) NOT NULL,
	email VARCHAR(70) NOT NULL, 
	idade DATE,
	sexo CHAR(1),
	cpf VARCHAR(11) NOT NULL 
)

CREATE TABLE curso (
	id INT PRIMARY KEY AUTO_INCREMENT,
	nome VARCHAR(25) NOT NULL,
	email VARCHAR(70),
	modulos INT,
	observacao TEXT
)

CREATE TABLE endereco_aluno (
	id INT PRIMARY KEY AUTO_INCREMENT,
	cep VARCHAR(8) NOT NULL,
	rua VARCHAR(50),
	numero VARCHAR(3),
	bairro VARCHAR(25),
	cidade VARCHAR(25),
	estado VARCHAR(25),
	pais VARCHAR(25)
)

CREATE TABLE responsavel (
	id INT PRIMARY KEY AUTO_INCREMENT,
	nomePai VARCHAR(70),
	telefonePai VARCHAR(11),
	nomeMae VARCHAR(70),
	telefoneMae VARCHAR(11)
)


CREATE TABLE endereco_diretor(
	id INT PRIMARY KEY AUTO_INCREMENT,
	cep VARCHAR(8) NOT NULL,
	rua VARCHAR(50),
	numero VARCHAR(3),
	bairro VARCHAR(25),
	cidade VARCHAR(25),
	estado VARCHAR(25),
	pais VARCHAR(25)
)

CREATE TABLE desempenho (
	id INT PRIMARY KEY AUTO_INCREMENT
)

SELECT * FROM aluno
SELECT * FROM responsavel
SELECT * FROM endereco_aluno
SELECT * FROM curso
SELECT * FROM matricula
SELECT * FROM desempenho
SELECT * FROM nota
SELECT * FROM professor
SELECT * FROM endereco_professor
SELECT * FROM diretor
SELECT * FROM endereco_diretor

-- inserts

INSERT INTO diretor(nome, email, idade, sexo, cpf)
VALUES('Tharcisio Moreira', 'tharcio@wiseup', '1965-03-15', 'M', '85201266907')

INSERT INTO endereco_diretor (cep, rua, numero, bairro, cidade, estado, pais, diretor_endereco)
VALUES ('00581532', 'Antonio Viera Araujo', '27', 'Vila Maria Silva', 'São Paulo', 'São Paulo', 'Brasil', 1)

INSERT INTO desempenho(nota_desempenho, curso_desempenho)
VALUES (10, 3)

INSERT INTO (curso_desempenho, nota_desempenho)
VALUES ()

-- alter table

ALTER TABLE professor
	ADD COLUMN `diretor_id` INT,
	ADD COLUMN `curso_desempenho` INT

ALTER TABLE matricula
	ADD CONSTRAINT `fk_aluno_id`
	FOREIGN KEY (`aluno_id`) 
	REFERENCES `aluno`(id)	

ALTER TABLE endereco_professor
	ADD CONSTRAINT `fk_professor_endereco`
	FOREIGN KEY (`professor_endereco`) 
	REFERENCES `professor`(id)	
	
-- updates

UPDATE professor
	SET diretor_id = 1
	WHERE id = 4

-- consultas

SELECT * FROM aluno
SELECT * FROM responsavel
SELECT * FROM endereco_aluno
SELECT * FROM curso
SELECT * FROM matricula
SELECT * FROM desempenho
SELECT * FROM nota
SELECT * FROM professor
SELECT * FROM endereco_professor
SELECT * FROM diretor
SELECT * FROM endereco_diretor

SELECT matricula.id, aluno.nome, curso.nome, nota.recuperacao, nota.mediaFinal FROM aluno
	INNER JOIN matricula ON aluno.id = matricula.aluno_id
	INNER JOIN curso ON curso.id = matricula.curso_id
	INNER JOIN desempenho ON curso.id = desempenho.curso_desempenho
	INNER JOIN nota ON nota.id = desempenho.nota_desempenho
