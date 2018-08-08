# academy-store-api

Uma RESTFul API simples em Node JS com mongoDB, criada por [welrikyson felix](https://github.com/welrikyson), para Avaliação Bimestral 2 ministrada por Eder Martins Franco

---

1) Clone ou baixe este repositório e, estando no diretório do projeto, abra o console: 
`npm install`
1) Start mongoDB
`mongod`
1) Para executar, estando no diretório do projeto, abra o console: 
`npm start`

3) Para testar as requisições, utilize o software de sua preferência ([Postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop), por exemplo) e acesse:
`http://localhost:4000`

## Exemplo de requisição (POST):

URL:
`http://localhost:4000/api/item`

Body (JSON):
```
{	
	"name" : "teclado",
	"type" : "periferico",
	"amount" : 20
}
```
