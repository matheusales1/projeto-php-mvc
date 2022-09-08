Criando a pagina de login e colocando as <?=$base;?>, sempre colocar a url base do seu site em todos os links.

As informações do formaluario de login sao enviados para o signinAction e de lá é pego as informações do banco de dados e faz com que o usuario entre no site ou volte para o login.

criei a function verifyLogin para verificar os logins e coloquei mensagens de erro caso o usuario erre a senha ou email.