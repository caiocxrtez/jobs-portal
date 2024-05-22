========= Instruções do Projeto ==========

A estrutura do projeto é simples: "system" é o projeto, "home" é a aplicação principal. Neste projeto, 
você não precisará criar um módulo novo, apenas utilizar o "HOME" para criar modelos e funcionalidades.



Tarefas a serem realizadas:

########## 1 - Criar 3 views:

*Login
*Logout
*Create_account

Essas views devem incluir funcionalidades de autenticação. Os formulários já estão incluídos nos templates, 
então você precisará configurá-los para autenticar os usuários. Após o login, 
você deverá retornar uma resposta JSON informando que a autenticação foi bem-sucedida. Por favor, usar functions views. 

########## 2 - Configurar mensagens para os templates:

*Enviar mensagens para os templates nas páginas de login e registro.
*Informar ao usuário se a conta que está sendo criada já existe ou não.
*Informar erros como senha fraca ou campos inválidos diretamente no template.

########## 3 - implementar Ajax:

*Utilizar Ajax para fazer a transição de mensagens, trazendo-as do servidor de forma dinâmica, sem necessidade de atualizar a página.

########## 4 - Estender o User do Django:

*Criar um modelo de usuário personalizado.
*Assim que o usuário se registrar, ele deverá ter automaticamente um perfil.
*Os campos do perfil podem ser simples, como nome, telefone e endereço.


ATENÇÃO: 

Incluir Scripts dentro da própria página na tag <script> MY SCRIPT </script>