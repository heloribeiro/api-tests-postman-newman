# api-tests-postman-newman
Automação de testes de API REST com Postman e Newman, cobrindo o fluxo CRUD da Swagger Petstore

# Tecnologias Utilizadas

-Postman
-Newman
-JavaScript
-Node.js
-Swagger Petstore
-Git 
- GitHub

# Cenarios Automatizados
O projeto executa o fluxo CRUD:

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

## Cenários negativos
Foram implementados os seguintes cenários:
1. Criar Pet com ID Inválido - retorno esperado: 400 Bad Request
2. Consultar Pet com ID Inválido - retorno esperado: 404 Not Found
3. Consultar Pet Inexistente - retorno esperado: 404 Not Found
4. Deletar Pet Inexistente - retorno esperado: 404 Not Found

## Resultado da execução
- 10 requisições executadas
- 18 validações realizadas
- 0 falhas
- Execução realizada pelo Newman
- Relatório HTML disponível no repositório

## Como executar o Postman e o Newman

### Postman
- Importar a collection e o enviroment

### Newman
- Executar o seguinte comando no cmd ou git bash
newman run petstore.postman_collection.json - e petstore.postman_environment.json
  
  
