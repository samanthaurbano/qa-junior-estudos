Casos de Teste – Login
CT-001 – Login com credenciais válidas

Pré-condição:

Usuário cadastrado no sistema
Página de login acessível
Passos:

Acessar a página de login
Informar e-mail válido
Informar senha válida
Clicar no botão "Entrar"
Resultado Esperado:

Sistema deve autenticar o usuário
Usuário deve ser redirecionado para a página inicial
Nome do usuário deve ser exibido no topo da página

----------------------------------------------------------------------------
CT-002 – Login com senha inválida
Pré-condição:

Usuário cadastrado no sistema
Passos:

Acessar a página de login
Informar e-mail válido
Informar senha inválida
Clicar no botão "Entrar"
Resultado Esperado:

Sistema não deve permitir o login
Deve exibir mensagem de erro
Usuário deve permanecer na página de login

---------------------------------------------------------------------------------------------------
CT-003 – Campo de e-mail vazio no login
Pré-condição:

Usuário cadastrado no sistema
Página de login acessível
Passos:

Acessar a página de login
Deixar o campo "E-mail" vazio
Informar uma senha válida
Clicar no botão "Entrar"
Resultado Esperado:

Sistema não deve permitir o login
Deve exibir mensagem informando que o campo "E-mail" é obrigatório
Usuário deve permanecer na página de login

--------------------------------------------------------------------------------------------------------
CT-004 – Senha abaixo do número mínimo de caracteres
Pré-condição:

Usuário cadastrado no sistema
Página de login acessível
Passos:

Acessar a página de login
Informar e-mail válido
Informar senha com menos caracteres que o mínimo permitido
Clicar no botão "Entrar"
Resultado Esperado:

Sistema não deve permitir o login
Deve exibir mensagem de validação sobre o tamanho mínimo da senha
Usuário deve permanecer na página de login
