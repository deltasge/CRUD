# crud
Test para um crud


# Objetivo do teste
Desenvolver um front na *linguagem a sua escolha*, que lista, cadastra, altera e deleta alunos. 
Consultando uma API JSON REST na *linguagem a sua escolha*, que utilize os métodos (​GET​, ​POST​, ​PUT​,
DELETE​).

# Especificações
Monte uma base de alunos com a seguinte estrutura:

```
nome: varchar
sexo: char
idade: integer
turma: varchar
datanascimento: date
```

Utilize o ​banco de dados​ de sua preferência para armazenar os dados que a API irá
consumir.

# API endpoints

```
GET /aluno
Codes 200
```
Retorna todos os alunos

```
GET /aluno/{id}
Codes 200 / 404
```
Retorna os dados de um aluno

```
POST /aluno
Codes 201 / 400
```
Adiciona um novo aluno

```
PUT /aluno/{id}
Codes 200 / 400
```
Atualiza os dados de um aluno

```
DELETE /aluno/{id}
Codes 204 / 400
```
Apaga o registro de um aluno

# Entrega
A aplicação deve possuir um script para geração das tabelas no banco de dados.

Após finalizado o link do projeto, por e-mail, no github com explicação no README.


