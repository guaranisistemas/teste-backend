# Teste Backend #

Guarani Sistemas

### Objetivo ###

* Crie uma aplicação web que permita cadastrar e listar empresas com cotação de moeda via AP, utilizando as seguintes tecnologias:

* Java9
* Spring boot (o que julgar necessário da stack)
* PostgreSQL

### Especificações funcionais ###

#### Cadastro de empresa ####

Possibilitar a adição de uma empresa, sendo os campos principais:

* CNPJ
* Nome
* E-mail
* Moeda de trabalho (USD – Dolár, EUR – Euro, ARS - Peso Argentino, GBP – Libra
Esterlina, BTC – Bitcoin)

Deve possuir também um endereço que contenha os campos: 

* Logradouro
* Número
* Complemento
* CEP
* Bairro
* Cidade

#### Listagem de empresas ####

Listar de formas paginadas todas as empresas cadastradas, possibilitando um filtro pelos campos:

* CNPJ
* Nome

Esse retorno deve trazer apenas as informações:

* CNPJ
* Nome
* E-mail
* Moeda de trabalho (USD – Dolár, EUR – Euro, ARS - Peso Argentino, GBP – Libra
Esterlina, BTC – Bitcoin)
* Cotação atual da moeda trabalhada em reais (Ex: Bitcoin = R$60.004,18)

#### Detalhar empresa por id ####

Deve-se retornar as seguintes informações de uma empresa:

* CNPJ
* Nome
* E-mail
* Moeda de trabalho (USD – Dolár, EUR – Euro, ARS - Peso Argentino, GBP – Libra
Esterlina, BTC – Bitcoin)
* Cotação atual da moeda trabalhada em reais (Ex: Bitcoin = R$60.004,18)


* Logradouro
* Número
* Complemento
* CEP
* Bairro
* Cidade

### Especificações não funcionais ###

1 - Quando possível substituir os dados informados no cadastro da empresa com os dados da API ReceitaWS.

(https://receitaws.com.br/). Será necessário um cadastro rápido para obter uma
key.

2 - O valor da cotação deve seguir os valores da API https://docs.awesomeapi.com.br/api-de-moedas


3 - A aplicação deve ser tolerante a falha de terceiros.

4 - A aplicação poderá ser usada na integração com outras aplicações ou serviços.

5 - aplicação deverá “economizar” chamadas a API de terceiros a fim de evitar
custos desnecessários com banda de rede e custos de requisições com API’s.


### O que será avaliado? ###

* Organização do projeto
* Design Pattern
* Lógica do código
* Clean Code

Testes automatizados é um diferencial


### Instruções para o teste ###

Realize um fork nesse repositório, desenvolva o teste e encaminhe o link do repoitório. 


