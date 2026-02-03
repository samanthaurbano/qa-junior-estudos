# Teste de API – Erro 404 (Recurso inexistente)

## Objetivo
Validar o comportamento da API quando um recurso inexistente é solicitado.

## Endpoint
GET https://jsonplaceholder.typicode.com/posts/999999

## Cenário
- Recurso não existente
- Método GET

## Resultado esperado
- Status Code: 404 Not Found
- Resposta vazia ou objeto vazio

## Testes automatizados (Postman)
- Validação do status code 404
- Validação de resposta vazia

## Evidência
![Teste erro 404](print-erro-404.png)
