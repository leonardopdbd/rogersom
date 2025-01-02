# Roger´som Geradores

Site de apresentação da empresa.

## Funcionalidades

- Apresentação
- Contato

## Tecnologias Utilizadas

- [XAMPP](https://www.apachefriends.org/)
- PHP
- MySQL
- HTML/CSS
- Javascript

## Como Usar o Site

## 1. - Pré-requisitos
 - Instale o XAMPP (ou qualquer outro servidor que suporte PHP e MySQL).
 - Tenha o phpMyAdmin para gerenciar o banco de dados.

## 2. - Configuração do Ambiente
- Copie os arquivos do projeto para a pasta htdocs do XAMPP.
Exemplo: C:\xampp\htdocs\rogersom.
Inicie o XAMPP:
Ative o servidor Apache e o MySQL no painel do XAMPP.

## 3. Configuração do Banco de Dados

1. Acesse o phpMyAdmin em http://localhost/phpmyadmin.
2. Crie um banco de dados chamado meu_banco_de_dados (ou qualquer outro nome que preferir).
3. Importe o arquivo database.sql (incluso no projeto) para criar as tabelas necessárias.
4. Configure a conexão com o banco de dados no arquivo process_form.php


## 4. Utilizando o Site
Acesse o site em http://localhost/meu-projeto/contato.html.
Preencha o formulário com os seguintes campos:
Nome
E-mail
Mensagem
Clique no botão Enviar:
Os dados serão salvos no banco de dados.
Um e-mail será enviado para o administrador com a mensagem.

## 5. Verificando os Dados
No Banco de Dados:

Acesse http://localhost/phpmyadmin.
Encontre a tabela contatos no banco de dados configurado.
Visualize as mensagens enviadas.
