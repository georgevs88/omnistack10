yarn init -y

yarn add express

yarn add nodemon -D

----------------------

Métodos HTTP: GET, POST, PUT, DELETE

Tipos de parâmetros:
-Query params: req.query (filtros, ordenação, paginação...) - (visível na URL)
-Route params: requesst.params (Identificar um recurso na alteração ou remoção)
-Body params:  request.body (Dados para criação ou alteração de um registro)

------------
mongodb+srv://omnistack:<password>@cluster0-gtqvu.mongodb.net/test?retryWrites=true&w=majority

yarn add mongoose

para verificar a porta do mongo (se proxy esta bloqueando):
http://portquiz.net:27017/

-----------------------------
para chamar api do github
yarn add axios
-----------------------------------------------------------------

FRONTEND

yarn create react-app web
ou
npx create-react-app web

yarn start

REACT:
// Componente: Bloco isolado de HTML, CSS e JS, o qual não interfere no restante da aplicação
// Propriedade: Informações que o componente PAI passa para o componente FILHO
// Estado: Informações mantidas pelo componente (lembrar: imutabilidade)


para acessar o backend, acessar a pasta do mesmo e:
yarn add cors

para fazer as chamadas do backend, na pasta do frontend:
yarn add axios