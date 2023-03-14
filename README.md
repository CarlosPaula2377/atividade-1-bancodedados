# Atividade 1: Banco de Dados - Aula do Mateus

# Atividade
Foi realizado um exercício proposto em sala para treinar e aperfeiçoar a matéria que foi ministrada em sala de aula.

## Métodos contrução do Banco de dados
Foram utilizados códigos passados em aula e foi feito também a revisão da matéria ministrada, onde foi utilizada a IDE Azure Data Studio para contrução deste banco de dados.
Neste exercício foram usados os comandos : CREAT TABLE, INT, NULL, NOT NULL, FK, PK, entre outros, para construção das tabelas.

#Tabelas
##Cliente
  Criação da tabela com os atributos:Nome,Cpf,Sexo,Estado,Cidade,Bairro,Numero,Rua,Telefone fixo e Celular.
  Sendo PK: CodCliente
##Carro
  Criação da tabela com os atributos:CodCarro,Placa,Marca,Modelo,Ano,Chassi,Cor.
  Sendo PK:
##Apolice
  Criação da tabela com os atributos:CodApolice,ValorCobertura,ValorFranquia,DataInicioVigencia,DataFimVigencia,
  Sendo PK: CodApolice
  senfo FK:Cliente_CodCliente,Carro_CodCarro
  ##Sinistro
  Criação da tabela com os atributos:CodSinistro,HoraSinistro,DataSinistro,LocalSinistro,Condutor.
  Sendo CPK:Carro_CodCarro
  Senfo FK:Carro_CodCarro
  



