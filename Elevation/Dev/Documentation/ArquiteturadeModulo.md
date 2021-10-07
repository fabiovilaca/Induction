# Arquitetura de um Módulo

O diagrama seguinte apresenta uma visão sumarizada da arquitetura de cada módulo da aplicação.

![alt text](https://github.com/fabiovilaca/Elevation/blob/master/Induction/assets/media/architecture.module.png)

Um módulo divide-se em 2 layers físicos:

   - Os componentes cliente (que executam no browser).
   - Os componentes servidor (que executam no servidor Web).

Esses componentes estão divididos em 4 layers lógicos:

   - Presentation – componentes que lidam com o UI da aplicação.
   - Services – serviços aplicacionais públicos (API) e internos.
   - Domain – componentes que implementam a lógica de negócio.
   - Data – componentes que lidam com a persistência dos dados.
 

O cliente Elevation comunica com o servidor através de uma API interna JavaScript/REST que acede aos serviços do respetivo módulo.

Aplicações externas (de parceiros) comunicarão com o sistema através de uma Web API.

A integração entre módulos é realizada através de application services (uma espécie de versão da Web API com funcionalidades adaptadas à integração).