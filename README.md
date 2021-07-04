Desafio do Chapter #1
===
# Challenge
Chegou a hora de exercitar mais um pouco para fixar os conceitos aprendidos até aqui.

Imagine que você está participando de um processo seletivo, e que a empresa te enviou um desafio a fim de entender melhor sobre os seus conhecimentos com uma determinada tecnologia. Neste desafio, você vai vivenciar essa experiência.

# Introdução
## Desafio empresa GoT - Game of Testers
Vamos usar um outro sistema criado para fins de teste: o Automation Practice.

O Automation Practice é um site que simula um ecommerce, e é muito utilizado em processos seletivos de diversas empresas.

### Este desafio tem os objetivos de:
- Consolidar os aprendizados do Chapter 1
- Adicionar mais um projeto em seu portfólio
- Preparar você para desafios técnicos de processos seletivos com Cypress
### Enunciado do Desafio (Instruções):
Utilizando o site automation practice, criar um novo projeto (do zero) e configurar o projeto para implementar testes utilizando o Cypress, conforme visto até aqui. Neste primeiro desafio, você deve utilizar apenas a abordagem sem cucumber. 
### Importante:
- o e-mail de cadastro deve ser diferente entre um teste e outro
- você deve utilizar o mochawesome como ferramenta de relatório
- subir o projeto no Github e enviar o link para correção
- adicione GIFs ou imagens de seu projeto executando quando subir para o Github
### Cenários que devem ser implementados:
- Cadastrar um novo usuário
### Fluxo do cenário de "Cadastrar um novo usuário":
- Acessar o site automation practice http://automationpractice.com
- Clicar no botão de Sign in
- Preencher as informações de e-mail (não pode ser repetido)
- Clicar no botão Create an Account
- Preencher as informações do formulário de cadastro
- Clicar no botão Register
- Validar que foi redirecionado para a url correta
- Validar exibição do texto 'Welcome to your account'

## Checklist:
# Markdown
- [x] foo
  - [ ] bar
  - [x] baz
- [ ] bim
# Markdown

- [X] Criar uma nova pasta/diretório com o nome do desafio
- [x] ~~Abrir o pasta criada no Visual Studio Code~~
- [x] ~~Configurar um novo projeto node~~
- [x] ~~Instalar o Cypress no projeto~~
- [x] ~~Abrir o Cypress e gerar arquivos padrão~~
- [x] ~~Configurar arquivo cypress.json com as opções: baseUrl, - experimentalSourceRewriting e watchForFileChanges. Se quiser, pode adicionar o schema também.~~
- [x] ~~Configurar o arquivo support/index para exceções indesejadas~~
- [x] ~~Apagar as specs de exemplo geradas~~
- [x] ~~Criar um novo arquivo de testes~~
- [x] ~~Mapear os elementos necessários para interagir~~
```
// botão de login => [class="login"]
// campo de email de cadastro => input#email_create
// botão cadastro button#SubmitCreate
```
```
// titulo segunda página
// [class="page-subheading"] = YOUR PERSONAL INFORMATION
// Title => input#id_gender1
// First name => input#customer_firstname
// Last name => input#customer_lastname
// Password => input#passwd
// Day => select#days (12  )
// Day => select#months (October )
// Day => select#years (1975  )
// newsletter => input#newsletter
// offers from our partners => input#optin
```
```
// Company => input#company
// Address => input#address1
// Address Line 2 => input#address2
// City = input#city
// State => select#id_state (California)
// Postal Code => input#postcode
// Country => select#id_country (United States)
// Additional information => textarea#other
// Home phone => input#phone
// Mobile phone => input#phone_mobile
// Address alias => input#alias
// Botão Registrar => button#submitAccount
```
- [x] Interagir com os elementos mapeados, navegando pela página para executar o fluxo
- Clicar no botão de Sign in
- Preencher as informações de e-mail (não pode ser repetido)
- Clicar no botão Create an Account
- Preencher as informações do formulário de cadastro
- Clicar no botão Register
- Validar que foi redirecionado para a url correta
- Validar exibição do texto 'Welcome to your account'
[ X ] Instalar e configurar uma biblioteca para geração de dados fictícios
[ X ] Adicionar as asserções para validar que o cadastro foi finalizado corretamente
[ X ] Adicionar os scripts para execução no modo interativo e no modo headless
[ X ] Conferir se o vídeo está sendo gerado corretamente
[ X ] Adicionar as bibliotecas do mochawesome
[ X ] Adicionar as configurações para gerar os arquivos do relatório
[ X ] Adicionar os scripts para geração dos relatórios em html
[ X ] Suba seu projeto no Github

[ ] Configure as actions para executar os testes

[ ] Habilite o GH Pages

[ ] Adicione a action para publicar o relatório do mochawesome

[ X ] Lembre-se, para o resultado aparecer o arquivo do relatório deve ser index.html :)

[ ] Crie uma descrição de seu projeto no Github com imagem ou vídeos da execução, tecnologias, tags e aprendizados