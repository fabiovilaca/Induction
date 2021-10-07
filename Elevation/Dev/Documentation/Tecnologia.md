# Tecnologia

A arquitetura base de uma aplicação Elevation é [client/server](https://en.wikipedia.org/wiki/Client%E2%80%93server_model), thin client com um application server, o Web server que executa o Web site da aplicação. Esse Web site é alojado no [Microsoft Azure](https://azure.microsoft.com/en-us/).

Utilizam-se tecnologias Web de última geração como o [Angular JS](https://angularjs.org/) para controlar os componentes de cliente, que executam em qualquer browser e em qualquer dispositivo (porque a tecnologia de apresentação é [HTML5](https://www.w3schools.com/html/default.asp)).

As views da aplicação são [ASP.NET MVC](https://dotnet.microsoft.com/apps/aspnet/mvc).

Existem duas camadas de serviços, uma interna, usada pela aplicação, própria da sua lógica de interação, e uma pública, via [Web API](https://en.wikipedia.org/wiki/Web_API) para integração de sistemas externos.

A lógica de negócio principal é implementada pelos business managers.

A camada de dados é gerida pela [Entity Framework](https://docs.microsoft.com/en-us/ef/) com um reposítório [SQL Azure](https://azure.microsoft.com/en-us/products/azure-sql/database/).

  
![alt text](https://github.com/fabiovilaca/Elevation/blob/master/Induction/assets/media/architecture.techs.png)