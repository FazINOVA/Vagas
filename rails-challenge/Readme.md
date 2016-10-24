# Rails Challenge

Crie uma landing page com formulário de inscrição para um evento e liste as inscrições em uma página com autenticação.
 
## Desafio

Sua missão é criar uma página de inscrição para o evento "Tour da Bel". Vamos lá, a sua página não pode ser apenas estática, ela precisa de alguma inteligência para que todas inscrições sejam salvas no banco de dados para depois em outra página a gente consiga visualizar, editar e excluir as inscrições. Ela ficará ainda mais legal, se a página for resposiva, ou seja se adaptar para qualquer dispositivo web.

### Layout do Site
O resultado final da página deve ficar de acordo com o mockup abaixo, todas as imagens que você vai precisar para implementar o layout já estão cortadas e anexadas nesse repositório.

![Página de Resultados](resources/mock.png)

## Passos para implementação

### 1. Desenvolver a página de inscrição

Crie um template estático, baseado no layout fornecido, atendendo aos seguintes critérios:

 - utilize o código do arquivo resources/cities.erb para criar o seu dropdown de cidades
 - utilize o código <link href='http://fonts.googleapis.com/css?family=Open+Sans:400,300,700' rel='stylesheet' type='text/css'> para utilizar a fonte open sans no layout
 - a sua página deve ser responsiva ou seja, se adaptar para qualquer dispositivo web, você pode utilizar frameworks como bootstrap para auxiliar na criação da página responsiva
 - faça com que sua página traga uma experiência agradável a qualquer pessoa, independentemente do dispositivo que ela estiver utilizando para ver sua página

### 2. Desenvolver sistema de inscrição

Crie uma sistema para o usuário se inscrerver no evento atendendo aos seguintes critérios:

 - o usuário deve conseguir se inscrever informando a sua "Cidade", "Nome", "Email" e "Telefone".
 - o email de cadastro deve ser único, caso o email já exista o usuário deve ser notificado informando que este email já possui uma inscrição
 - ao efetuar a inscrição o usuário deve ser redirecionado para a página inicial sendo notificado que a inscrição foi feita com sucesso
 
### 3. Área de autenticação

A sua aplicação precisa ter um link na homepage aonde o usuário consiga se cadastrar e efetuar login para uma página interna, obedecendo aos seguintes critérios:

 - ao efetuar o login ou se cadastrar no site, o usuário deve ir para uma página com a lista de todas as inscrições que foram feitas na homepage.
 - a criação e personalização do template dessa página vai ser por sua conta, por tanto seja criativo ;)
 - a lista de inscrição deve permitir que o usuário consiga editar e excluir as inscrições

### 4. Diferancial

Caso seja feita autenticação via facebook para acessar a lista de inscrições interna vai ser considerado um diferencial no teste.

### 5. Wow! Agora temos que fazer deploy! :D

Após a finalização do desafio hospede a sua aplicação no Heroku

### Envio do Desafio
O processo de Pull Request funciona da seguinte maneira:

1. Faça um fork desse repositório (não irá clonar direto!)
2. Crie seu projeto nesse fork.
3. Commits e pushs para o SEU fork.
4. No seu último commit adicione aqui "LINK DA PÁGINA DO SEU PROJETO NO HEROKU".
5. Pela interface do GitHub envie um Pull Request.

*****

### **ATENÇÃO** ###

Não faça PUSH diretamente para ESTE repositório!!!
