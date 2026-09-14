# api-tests-postman-newman
Automação de testes de API REST com Postman e Newman, cobrindo o fluxo CRUD da Swagger Petstore

# Tecnologias Utilizadas

-Postman
-Newman
-Javascript
-Node.js
-Swagger Petstore
-Git e GitHub

# Cenarios Automatizados
O projeto executa o fluxo CRUD

1. Criar_Pet - POST
2. Ler_PetCriado - GET
3. Atualizar_PetCriado - PUT
4. Ler_PetAtualizado - GET
5. Deletar_Pet - DELETE
6. Confirmar_PetExcluido - GET

# Validações Realizadas
- Status Code
- Nome e status do Pet
- Atualização dos dados
- Exclusão
- Retorno 404 - Pet not found

## Como executar o Postman e o Newman

### Postman
- Importar a collection e o enviroment

### Newman
- Executar o seguinte comando no cmd ou git bash
newman run petstore.postman_collection - e petstore.postman_environment
  
  
