# Trilha .NET Squadra

# Projeto de Implementação Arquitetura BFF - BackEnd for FrontEnd

## Tecnologia utilizada 

- DotNet Core 5
- Projeto WebApi

## Escopo
	Projeto de acesso a WebService MedicoAPI



## Utilização do Projeto
	1. Após fazer o clone do projeto, utilizar o comando no pompt de comando na pasta do projeto 
		- dotnet restore

	
##Lista dos EndPoints
	1. Web Api com endpoints utilizando https://localhost:5003/api/medico
	2. Documentação da api para listar os EndPoints - https://localhost:5003/swagger

	3. Acesso a apiMedicos -  "apiMedicos": "https://localhost:5001/api/medico/"
		- Projeto hospedado no repositório: "https://github.com/Alecarlos-spx/SquadraTrilhaNet/tree/Implementando_Testes"
		- Readme - Projeto de Implementação de CRUD de Médicos : "https://github.com/Alecarlos-spx/SquadraTrilhaNet/blob/Implementando_Testes/ReadMe.md"
	
###Lista geral de EndPoints
	1. /api/medico - Lista todos os Médicos - utilizando requisição Get
	2. /api/medico - Adiciona um Novo Médico - utilizando requisição Post
	3. /api/medico/id - Lista um Médico por Id - utilizando requisição Get
	4. /api/medico/id - Apaga um Médico por Id - utilizando requisição Delete
	5. /api/medico/id - Altera um Médico por Id - utilizando requisição Put

	* Onde id é o parametro passado com o código do médico








