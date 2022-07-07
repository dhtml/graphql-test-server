$ npm install

$ npm start
The server is running in 9000 port, so we can test the application using GraphiQL tool. Open the browser and enter the URL http://localhost:9000/graphiql. Type the following query in the editor −

{
test
}
The response from the server is given below −

{
"data": {
"test": "Test Success, GraphQL server is running !!"
}
}


Read more about this here - https://www.tutorialspoint.com/graphql/graphql_environment_setup.htm
