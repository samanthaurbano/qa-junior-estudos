# Casos de Teste – Login

## CT01 – Login com dados válidos
Dado que o usuário está na tela de login  
Quando informa usuário e senha válidos  
Então o sistema deve permitir o acesso

## CT02 – Login com senha inválida
Dado que o usuário está na tela de login  
Quando informa senha incorreta  
Então o sistema deve exibir mensagem de erro

# Casos de Teste – Cadastro

## CT03 – Cadastro com dados válidos
Dado que o usuário está na tela de cadastro  
Quando preenche todos os campos obrigatórios corretamente  
E clica no botão "Cadastrar"  
Então o sistema deve criar a conta com sucesso  
E exibir mensagem de confirmação

## CT04 – Cadastro com dados inválidos (CPF obrigatório)
Dado que o usuário está na tela de cadastro  
Quando não preenche corretamente o campo CPF  
E clica no botão "Cadastrar"  
Então o sistema deve impedir a criação da conta  
E exibir mensagem informando que o CPF é inválido ou obrigatório
