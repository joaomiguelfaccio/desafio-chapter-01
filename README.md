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
- Consolidar os aprendizados do **_Chapter 1_**
- Adicionar mais um projeto em seu portfólio
- Preparar você para desafios técnicos de processos seletivos com Cypress
### Enunciado do Desafio (Instruções):
Utilizando o site automation practice, criar um novo projeto (do zero) e configurar o projeto para implementar testes utilizando o Cypress, conforme visto até aqui. Neste primeiro desafio, você deve utilizar apenas a abordagem sem cucumber. 
### Importante:
- o e-mail de cadastro deve ser diferente entre um teste e outro
- você deve utilizar o mochawesome como ferramenta de relatório
- subir o projeto no Github e enviar o link para correção
- adicione GIFs ou imagens de seu projeto executando quando subir para o Github
## Cenários que devem ser implementados:
- Cadastrar um novo usuário
### Fluxo do cenário de "Cadastrado de um novo usuário":
- Acessar o site automation practice http://automationpractice.com
- Clicar no botão de Sign in
- Preencher as informações de e-mail (não pode ser repetido)
- Clicar no botão Create an Account
- Preencher as informações do formulário de cadastro
- Clicar no botão Register
- Validar que foi redirecionado para a url correta
- Validar exibição do texto 'Welcome to your account'

## Checklist:
- [X] ~~Criar uma nova pasta/diretório com o nome do desafio~~
- [x] ~~Abrir o pasta criada no Visual Studio Code~~
- [x] ~~Configurar um novo projeto node~~
- [x] ~~Instalar o Cypress no projeto~~
- [x] ~~Abrir o Cypress e gerar arquivos padrão~~
- [x] ~~Configurar arquivo cypress.json com as opções: baseUrl, - experimentalSourceRewriting e watchForFileChanges. Se quiser, pode adicionar o schema também.~~
- [x] ~~Configurar o arquivo support/index para exceções indesejadas~~
- [x] ~~Apagar as specs de exemplo geradas~~
- [x] ~~Criar um novo arquivo de testes~~
- [x] ~~Mapear os elementos necessários para interagir~~
> Elementos da Página inicial
```
- botão de login => [class="login"]
```
> Elementos da Página de Autenticação
```
- campo de email de cadastro => input#email_create
- botão cadastro => button#SubmitCreate
```
> Elementos da Página de Criação do usuário - informações pessoais
```
- Texto da seção => [class="page-subheading"] = "YOUR PERSONAL INFORMATION"
- Title => input#id_gender1
- First name => input#customer_firstname
- Last name => input#customer_lastname
- Password => input#passwd
- Date of Birth (dia) => select#days (12)
- Date of Birth (mês) => select#months (October)
- Date of Birth (ano) => select#years (1975)
- Newsletter => input#newsletter
- Offers from our partners => input#optin
```
> Elementos da Página de Criação do usuário - endereço
```
- Company => input#company
- Address => input#address1
- Address Line 2 => input#address2
- City = input#city
- State => select#id_state (California)
- Postal Code => input#postcode
- Country => select#id_country (United States)
- Additional information => textarea#other
- Home phone => input#phone
- Mobile phone => input#phone_mobile
- Address alias => input#alias
- Botão Registrar => button#submitAccount
```
- [x] ~~Interagir com os elementos mapeados, navegando pela página para executar o fluxo~~
> Fluxo de cadastro
```
- Clicar no botão de Sign in
- Preencher as informações de e-mail (não pode ser repetido)
- Clicar no botão Create an Account
- Preencher as informações do formulário de cadastro
- Clicar no botão Register
- Validar que foi redirecionado para a url correta
- Validar exibição do texto 'Welcome to your account'
```
- [x] ~~Instalar e configurar uma biblioteca para geração de dados fictícios~~
- [x] ~~Adicionar as asserções para validar que o cadastro foi finalizado corretamente~~
- [x] ~~Adicionar os scripts para execução no modo interativo e no modo headless~~
- [x] ~~Conferir se o vídeo está sendo gerado corretamente~~
- [x] ~~Adicionar as bibliotecas do mochawesome~~
- [x] ~~Adicionar as configurações para gerar os arquivos do relatório~~
- [x] ~~Adicionar os scripts para geração dos relatórios em html~~
- [x] ~~Suba seu projeto no Github~~
- [x] Configure as actions para executar os testes
- [x] Habilite o GH Pages
- [ ] Adicione a action para publicar o relatório do mochawesome
- [x] ~~Lembre-se, para o resultado aparecer o arquivo do relatório deve ser index.html :)~~
- [x] ~~Crie uma descrição de seu projeto no Github com imagem ou vídeos da execução, tecnologias, tags e aprendizados~~

## Exemplo de screenshots e vídeos
![exemplo_failed](https://user-images.githubusercontent.com/68667256/124394146-78098780-dcd4-11eb-93ed-86c82afb509d.png)
https://user-images.githubusercontent.com/68667256/124394218-d2a2e380-dcd4-11eb-9cee-1fd33dd3fbc2.mp4
