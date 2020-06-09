<h1 align="center" style="border-bottom: none">
    <b>
        XgeneCloud<br>
        Instant REST & GraphQL APIs on any Database
    </b>
</h1>

<div align="center">
 
[![Build Status](https://travis-ci.org/dwyl/esta.svg?branch=master)](https://travis-ci.com/github/xgenecloud/xgenecloud) 
[![Node version](https://badgen.net/npm/node/next)](http://nodejs.org/download/)
[![License](https://badgen.net/npm/license/xc-core)]()<!--![Discord](https://img.shields.io/discord/661905455894888490)
![Stack Exchange monthly questions](https://img.shields.io/stackexchange/stackoverflow/qm/xgenecloud)
--> [![Twitter](https://img.shields.io/twitter/url/https/twitter.com/XgeneCloud.svg?style=social&label=Follow%20%40XgeneCloud)](https://twitter.com/xgenecloud)

</div>

<p align="center">
    <a href="http://www.xgenecloud.com"><b>Website</b></a> •
    <a href="https://xgenecloud.com/docs/"><b>Documentation</b></a> • 
    <a href="https://xgenecloud.com/#subscribe-to-newsletter"><b>Newsletter</b></a> • 
    <a href="https://discord.gg/5RgZmkW"><b>Discord</b></a> • 
    <a href="https://twitter.com/xgenecloud"><b>Twitter</b></a> • 
    <a href="https://xgenecloud.com/download"><b>Download App</b></a> 
</p>  

<br>

# Supported Databases
- MySQL, PostgresSQL, MSSQL, SQLite, MariaDb

# Usage

Install CLI
<pre>
$ <b>npm install -g xc-cli</b>
</pre>

Install & Open GUI (Built in Database & API Client)
<pre>
<b>$ xc app.install</b>
<b>$ xc app.open</b>
</pre>

Auto generate REST/GraphQL APIs from new or existing database schema 
<pre>
<b>$ xc new project-name</b>
</pre>

Help
<pre>
<b>$ xc man</b>
</pre>

<p>
    <br/><br/>
</p>

## Demo 1 : Generate REST APIs on existing MySQL Database
<p align="center">
    <img src="/static/demo/cli/chinook-rest-example.gif" width="85%">
    <br/><br/><br/><br/>
</p>

## Demo 2 : GUI for Database Design and Scaffolding APIs
<p align="center">
<img  loading="lazy" src="/static/demo/gui/gui-api-scaffolding.mov.gif"/>
<br/><br/><br/><br/>
</p>

## Demo 3 : Generate GraphQL APIs on existing MySQL Database
<p align="center">
    <img src="/static/demo/cli/chinook-graphql-example.gif" width="85%">
    <br/><br/><br/><br/>
</p>


# What is XgeneCloud ?
XgeneCloud consists of **Three** simple & amazing products :
- **An Instant API Framework** that can generate REST & GraphQL on any database 
- **A GUI based fully-featured Database & API Client**
  - GUI DB Client enables - Point & Click schema design & schema migrations. 
  - GUI API Client to debug APIs.
- **A Hybrid Serverless Framework**!
  - All APIs generated can be depoyed as Serverless Functions on any Cloud Platform! 
  - This is without changing any change to source code generated.

## A Simple Overview
<br>
<img  loading="lazy" src="/static/cloud/venndiagram.png"/>
<br>

## A Detailed Overview
<img  loading="lazy" src="/static/diagrams/cloudOverview.png"/>

<br>

# Table Of Contents
- [**Setup**](https://docs.xgenecloud.com/en/v0.5/getting-started/install)
  - [Install](https://docs.xgenecloud.com/en/v0.5/getting-started/install#install-cli)
  - [Generating APIs for first time](https://docs.xgenecloud.com/en/v0.5/getting-started/install#generate-apis)
- [**Architecture**](https://docs.xgenecloud.com/en/v0.5/architecture/Components)
  - [Components](https://docs.xgenecloud.com/en/v0.5/architecture/Components)
  - [REST APIs](https://docs.xgenecloud.com/en/v0.5/architecture/rest-router-service-model)
    - [Router Service Model](https://docs.xgenecloud.com/en/v0.5/architecture/rest-router-service-model)
    - [Request Lifecycle](https://docs.xgenecloud.com/en/v0.5/architecture/rest-request-lifecycle)
  - [GraphQL APIs](https://docs.xgenecloud.com/en/v0.5/architecture/graphql-router-service-model)
    - [Resolver Service Model](https://docs.xgenecloud.com/en/v0.5/architecture/graphql-router-service-model)
    - [Request Lifecycle](https://docs.xgenecloud.com/en/v0.5/architecture/graphql-request-lifecycle)
- [**REST APIs Framework**](https://docs.xgenecloud.com/en/v0.5/architecture/graphql-request-lifecycle)
  - [APIs Generated](https://docs.xgenecloud.com/en/v0.5/architecture/graphql-request-lifecycle)
  - [Authentication](https://docs.xgenecloud.com/en/v0.5/rest-apis/rest-authentication)
  - [ACL](https://docs.xgenecloud.com/en/v0.5/rest-apis/rest-acl)
  - [Middleware](https://docs.xgenecloud.com/en/v0.5/rest-apis/rest-middleware)
  - [Swagger Documentation (autogenerated)](https://docs.xgenecloud.com/en/v0.5/rest-apis/rest-swagger)
- [**GraphQL API Framework**](https://docs.xgenecloud.com/en/v0.5/graphql-apis/graphql-apis-generated)
  - [Authentication](https://docs.xgenecloud.com/en/v0.5/graphql-apis/graphql-authentication)
  - [ACL](https://docs.xgenecloud.com/en/v0.5/graphql-apis/graphql-acl)
  - [Middleware](https://docs.xgenecloud.com/en/v0.5/graphql-apis/graphql-middleware)
  - [GraphQL Schema Generation & Stitching](http://localhost:3000/en/v0.5/graphql-apis/graphql-schema-stitching)
- [**Database**](https://docs.xgenecloud.com/en/v0.5/database/database-modelling)
  - [Database Modelling](https://docs.xgenecloud.com/en/v0.5/database/database-modelling)
  - [Schema Migrations](https://docs.xgenecloud.com/en/v0.5/database/database-migrations)
  - [Validations](https://docs.xgenecloud.com/en/v0.5/database/database-model-validation)
  - [Hooks for write operations](https://docs.xgenecloud.com/en/v0.5/database/database-model-hooks)
- [**Hybrid Serverless API Framework**](https://docs.xgenecloud.com/en/v0.5/deploy/serverless/serverless-aws)
  - [AWS Lambda](https://docs.xgenecloud.com/en/v0.5/deploy/serverless/serverless-aws)
  - [GCP Cloud Functions](https://docs.xgenecloud.com/en/v0.5/deploy/serverless/serverless-gcp)
  - [Azure Function App](https://docs.xgenecloud.com/en/v0.5/deploy/serverless/serverless-azure)
  - [Alibaba/Aliyun Function Compute](https://docs.xgenecloud.com/en/v0.5/deploy/serverless/serverless-alibaba)
  - [Vercel / Zeit Now](https://docs.xgenecloud.com/en/v0.5/deploy/serverless/serverless-vercel)
- [**API Client**](https://docs.xgenecloud.com/en/v0.5/desktop-app/api-client)
  - [Debug APIs](https://docs.xgenecloud.com/en/v0.5/desktop-app/api-client#api-collection)
  - [Test Performance of APIs](https://docs.xgenecloud.com/en/v0.5/desktop-app/api-client#performance-testing)
- [**CLI**](https://docs.xgenecloud.com/en/v0.5/cli/using-man-pages)
  - [Using man pages](https://docs.xgenecloud.com/en/v0.5/cli/using-man-pages) 
    - [man](https://docs.xgenecloud.com/en/v0.5/cli/using-man-pages)
  - [API Generation](https://docs.xgenecloud.com/en/v0.5/cli/api-generation/) 
    - [new](https://docs.xgenecloud.com/en/v0.5/cli/api-generation/#project-creation)
    - [gen.apis.rest](https://docs.xgenecloud.com/en/v0.5/cli/api-generation/#rest-api-generation)    
    - [gen.apis.graphql](https://docs.xgenecloud.com/en/v0.5/cli/api-generation/#graph-api-generation)
  - [Module Generation](https://docs.xgenecloud.com/en/v0.5/cli/module-generation/) 
    - [gen.module](https://docs.xgenecloud.com/en/v0.5/cli/module-generation/)    
  - [Database Schema Migrations](https://docs.xgenecloud.com/en/v0.5/cli/db-migrations) 
    - [db.migrate.list](https://docs.xgenecloud.com/en/v0.5/cli/db-migrations/#list)
    - [db.migrate.create](https://docs.xgenecloud.com/en/v0.5/cli/db-migrations/#create)
    - [db.migrate.up](https://docs.xgenecloud.com/en/v0.5/cli/db-migrations/#up)    
    - [db.migrate.down](https://docs.xgenecloud.com/en/v0.5/cli/db-migrations/#down)        
    - [db.migrate.sync](https://docs.xgenecloud.com/en/v0.5/cli/db-migrations/#sync)        
  - [Access Control Lists (ACL)](https://docs.xgenecloud.com/en/v0.5/cli/acl/) 
    - [permissions.set](https://docs.xgenecloud.com/en/v0.5/cli/acl/#permission-set)
    - [permissions.get](https://docs.xgenecloud.com/en/v0.5/cli/acl/#permission-get)
    - [permissions.user.add](https://docs.xgenecloud.com/en/v0.5/cli/acl/#role-add)    
    - [permissions.user.rename](https://docs.xgenecloud.com/en/v0.5/cli/acl/#role-rename)        
    - [permissions.user.delete](https://docs.xgenecloud.com/en/v0.5/cli/acl/#role-delete)        
  - [Component](https://docs.xgenecloud.com/en/v0.5/cli/component/) 
    - [components.add](https://docs.xgenecloud.com/en/v0.5/cli/component/)
  
# All Demos : Instant APIs on other SQL databases

| Database  | REST APIs Demo                 | GraphQL APIs Demo                  |
|-----------|--------------------------------|------------------------------------- 
| MySql     | [using CLI](#generating-rest-apis-for-mysql-database-using-cli) / [using GUI](#generating-rest-apis-for-mysql-database-using-gui)  |                 [using CLI](#generating-graphql-apis-for-mysql-database-using-cli) / [using GUI](#generating-graphql-apis-for-mysql-database-using-gui)                   |
| Postgres  | [using CLI](#generating-rest-apis-for-postgres-database-using-cli) / [using GUI](#generating-rest-apis-for-postgres-database-using-gui)  |              [using CLI](#generating-graphql-apis-for-postgres-database-using-cli) / [using GUI](#generating-graphql-apis-for-postgres-database-using-gui)                      |
| MsSql     | [using CLI](#generating-rest-apis-for-mssql-database-using-cli) / [using GUI](#generating-rest-apis-for-mssql-database-using-gui)               |             [using CLI](#generating-graphql-apis-for-mssql-database-using-cli) / [using GUI](#generating-graphql-apis-for-mssql-database-using-gui)                         |
| Sqlite3   | [using CLI](#generating-rest-apis-for-sqlite-database-using-cli) / [using GUI](#generating-rest-apis-for-sqlite-database-using-gui)               |             [using CLI](#generating-graphql-apis-for-sqlite-database-using-cli) / [using GUI](#generating-graphql-apis-for-sqlite-database-using-gui)                         |
| MariaDb   | [using CLI](#generating-rest-apis-for-mysql-database-using-cli) / [using GUI](#generating-rest-apis-for-mysql-database-using-gui)               |                [using CLI](#generating-graphql-apis-for-mysql-database-using-cli) / [using GUI](#generating-graphql-apis-for-mysql-database-using-gui)                    |
| Multiple Databases   | [using CLI](#generating-rest-apis-for-multiple-databases-using-cli) / [using GUI](#generating-rest-apis-for-multiple-databases-using-gui)               |                [using CLI](#generating-graphql-apis-for-multiple-databases-using-cli) / [using GUI](#generating-graphql-apis-for-multiple-databases-using-gui)                    |
| Scaffolding for a Table   | [using CLI](#code-scaffolding-for-a-table-cli) / [using GUI](#code-scaffolding-for-a-table)               |                [using CLI](#code-scaffolding-for-a-table-gql-cli) / [using GUI](#code-scaffolding-for-a-table-gql)                    |
| ACL   |  [Click here](#graphql-acl)| [Click here](#rest-acl) | 
| Auto Documentation   |  [Click here](#swagger)| | 


# Feature Demos : Others

| Feature                          | Links                          |
|----------------------------------|-------------------------------- 
| Setup                            | [Click here](#setup) | 
| API Client History             | [Click here](#api-client-history) | 
| API Client Collections         | [Click here](#api-client-collections) | 
| API Performance Test         | [Click here](#api-performance-test) | 
| Database Client Design         | [Click here](#database-client-design) | 
| Database Client Migrations     | [Click here](#database-client-migrations) |  
| Smart Terminal                   | [Click here](#smart-terminal) | 
| Themes : Dark                    | [Click here](#themes--dark) | 
| Themes : Colors                  | [Click here](#themes--colors) | 
| Themes : Custom Colors           | [Click here](#themes--custom-colors) | 
| Multi Environment project        | [Click here](#multi-environment-project) | 


# Youtube PlayLists

| Playlist | Link |
|---------------|------|
| Instant Rest APIs | [Click here](https://www.youtube.com/watch?v=gEU-QvmwSKQ&list=PLhQvP2JTFbRi3SUBIsac37V6SITSMK0rk) |
| Instant GraphQL APIs | [Click here](https://www.youtube.com/watch?v=8LGJKUW9hhU&list=PLhQvP2JTFbRhwVE_-yJQiY32iHOP9zBJ4&index=2&t=0s) |
| Database Client - Desktop App | [Click here](https://www.youtube.com/watch?v=ETEEcY4mmEg&list=PLhQvP2JTFbRi70kd_odHHJVpawZr9wXNY&index=2&t=0s) |
| Smart Terminal | [Click here](https://www.youtube.com/watch?v=nVn3oe4oAuc&list=PLhQvP2JTFbRhj550ia3pPU_oryHacE7fE&index=2&t=0s) |
| Themes | [Click here](https://www.youtube.com/watch?v=5vqqW_nG_OY&list=PLhQvP2JTFbRii2eIXEzAeWUBWiYO189Cu&index=2&t=0s) |


# Serverless Platforms Supported
| Cloud Platform | Serverless    | Serverless Containers     |
|--------------|---------------|------------------------------------- 
| AWS       | [<img src="/static/cloud/aws-lambda-1.svg" height="24"> Lambda](#aws-lambda-deployment) | <img src="/static/cloud/fargate.png" height="24"> Fargate |
| GCP  | [<img src="/static/cloud/cloud-function.png" height="24"> Cloud Function](#gcp-cloud-function) | <img src="/static/cloud/cloud-run.png" height="24"> Cloud Run |
| Azure    | [<img src="/static/cloud/azure-function.png" height="24"> Function App](#azure-function-app) | <img src="/static/cloud/azure-function.png" height="24"> Function App Container |
| Zeit    | [<img src="/static/cloud/zeit-now.jpg" height="24"> Now](#zeit-now) | |
| Alibaba | [<img src="/static/cloud/alibaba.png" height="24"> Function Compute](#alibaba-function-compute) | <img src="/static/cloud/alibaba-ask.png" height="24"> Alibaba Serverless Kubernetes |



[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating REST APIs for MySQL Database Using CLI

<p align="center">
<img  loading="lazy" src="/static/demo/cli/mysql-rest-magento.gif"/>
</p>

[Asciinema](https://asciinema.org/a/KNkZqQ8g6wWMByLUqsR6W0hcr?t=10&speed=2)


[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating REST APIs for MySQL Database Using GUI
  
  <p align="center">
<img loading="lazy" src="/static/demo/gui/mysql-rest.gif"/>
</p>  

[Youtube](https://www.youtube.com/watch?v=gEU-QvmwSKQ)

[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating REST APIs for Postgres Database Using CLI

<p align="center">
<img  loading="lazy" src="/static/demo/cli/pg-rest.gif"/>
</p>

[Asciinema](https://asciinema.org/a/o57c945IEBFYeLZ0l606U3m7G?t=10&speed=2)



[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating REST APIs for Postgres Database Using GUI

<p align="center">
<img  loading="lazy" src="/static/demo/gui/pg-rest.gif"/>
</p>

[Youtube](https://www.youtube.com/watch?v=H_ghRwhh6js)

[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating REST APIs for MSSQL Database Using CLI

<p align="center">
<img  loading="lazy" src="/static/demo/cli/mssql-rest.gif"/>
</p>

[Asciinema](https://asciinema.org/a/38UyO54GpQXpsXdfoDviraN9U?t=11&speed=2)


[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating REST APIs for MSSQL Database Using GUI

<p align="center">
<img  loading="lazy" src="/static/demo/gui/mssql-rest.gif"/>
</p>

[Youtube](https://www.youtube.com/watch?v=Vyd9_93UfXs)

[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating REST APIs for SQLite Database Using CLI

Coming Soon...

[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating REST APIs for SQLite Database Using GUI

<p align="center">
<img  loading="lazy" src="/static/demo/gui/sqlite-rest.gif"/>
</p>

[Youtube](https://www.youtube.com/watch?v=R3SiJQPVVcQ)

[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating REST APIs for Multiple Databases Using GUI

<p align="center">
<img  loading="lazy" src="/static/demo/gui/gui-multi-chinook-rest.gif"/>
</p>

[Youtube](https://youtu.be/TXYhp5TlkNo)

[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Scaffolding for a Table

<p align="center">
<img  loading="lazy" src="/static/demo/gui/gui-api-scaffolding.mov.gif"/>
</p>

[Youtube](https://youtu.be/m5fD8dDOkww)

[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Scaffolding for a Table : CLI

<p align="center">
<img  loading="lazy" src="/static/demo/cli/cli-api-scaffolding-rest.mov.gif"/>
</p>

[Youtube](https://youtu.be/HGk4FkhuxZs)


[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating REST APIs for Multiple Databases Using CLI

<p align="center">
<img  loading="lazy" src="/static/demo/cli/multi-db-demo.gif"/>
</p>

[Youtube](https://youtu.be/TXYhp5TlkNo)


[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating GraphQL APIs for MySQL Database Using CLI

<p align="center">
<img  loading="lazy" src="/static/demo/cli/mysql-graphql.gif"/>
</p>

[Asciinema](https://asciinema.org/a/nuDgAWrY2Trs6to6E2SaZw8yA?t=11&speed=2)



[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating GraphQL APIs for MySQL Database Using GUI

<p align="center">
<img  loading="lazy" src="/static/demo/gui/mysql-graphql.mov.gif"/>
</p>

[Youtube](https://www.youtube.com/watch?v=8LGJKUW9hhU)

[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating GraphQL APIs for Postgres Database Using CLI

<p align="center">
<img  loading="lazy" src="/static/demo/cli/pg-graphql.gif"/>
</p>

[Asciinema](https://asciinema.org/a/K1RrH2ixbrbDuTUkXdUGKF41u?t=12&speed=2)

[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating GraphQL APIs for Postgres Database Using GUI

<p align="center">
<img  loading="lazy" src="/static/demo/gui/pg-graphql.gif"/>
</p>

[Youtube](https://www.youtube.com/watch?v=QEq3Mjbeelg)


[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating GraphQL APIs for MSSQL Database Using CLI

<p align="center">
<img  loading="lazy" src="/static/demo/cli/mssql-graphql.gif"/>
</p>

[Asciinema](https://asciinema.org/a/HBT8Zn6wxRUneQZxYEjSsVUYE?t=18&speed=2)

[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating GraphQL APIs for MSSQL Database Using GUI

<p align="center">
<img  loading="lazy" src="/static/demo/gui/mssql-graphql.gif"/>
</p>

[Youtube](https://www.youtube.com/watch?v=qaLIpXe1gb0)

[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating GraphQL APIs for SQLite Database Using CLI

Coming Soon...

[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating GraphQL APIs for SQLite Database Using GUI

<p align="center">
<img  loading="lazy" src="/static/demo/gui/sqlite-graphql.gif"/>
</p>

[Youtube](https://www.youtube.com/watch?v=DmP5_Rsib_4)


[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating GraphQL APIs for Multiple Databases Using GUI

Coming soon...

[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Generating GraphQL APIs for Multiple Databases Using CLI

Coming soon...

[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Scaffolding for a Table : GQL

<p align="center">
<img  loading="lazy" src="/static/demo/gui/gui-api-scaffolding-gql.mov.gif"/>
</p>

[Youtube](https://youtu.be/KbeGpETI1vs)

[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Scaffolding for a Table : GQL CLI

<p align="center">
<img  loading="lazy" src="/static/demo/cli/cli-api-scaffolding-graphql.mov.gif"/>
</p>

[Youtube](https://youtu.be/HGk4FkhuxZs)

[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### GraphQL : ACL

<p align="center">
<img  loading="lazy" src="/static/demo/security/gui-acl-graphql.mov.gif"/>
</p>

[Youtube](https://youtu.be/YegtwHyUhaM)

[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### REST : ACL

<p align="center">
<img  loading="lazy" src="/static/demo/security/gui-acl-rest.mov.gif"/>
</p>

[Youtube](https://youtu.be/AwbxwZjjN-8)



[⤴️](#all-demos--instant-apis-on-other-sql-databases)
### Swagger

<p align="center">
<img  loading="lazy" src="/static/demo/swagger/swagger.png"/>
</p>

[Youtube](https://www.youtube.com/watch?v=1unQAEGDz8U&feature=youtu.be)

[⤴️](#feature-demos--others)
### Setup

<p align="center">
<img  loading="lazy" src="/static/demo/setup/setup.gif"/>
</p>

[Asciinema](https://asciinema.org/a/bJIzrdLhzg82sY8S9ztaLLZhX&speed=2)


[⤴️](#feature-demos--others)
### API Client History  


<p align="center">
<img  loading="lazy" src="/static/demo/client-api/api-client-history-demo.mov.gif"/>
</p>

[Youtube](https://www.youtube.com/watch?v=A2yFGh2Mqok)

[⤴️](#feature-demos--others)

### API Client Collections  

<p align="center">
<img  loading="lazy" src="/static/demo/client-api/api-collection-demo.mov.gif"/>
</p>

[Youtube](https://www.youtube.com/watch?v=EIadg-Z1oTc)

[⤴️](#feature-demos--others)

### API Performance Test  

<p align="center">
<img  loading="lazy" src="/static/demo/gui/http-perf.gif"/>
</p>

[Youtube](https://www.youtube.com/watch?v=znTQyUZUcSQ)

[⤴️](#feature-demos--others)
### Database Client Design  

<p align="center">
<img  loading="lazy" src="/static/demo/client-db/schema-design-demo.mov.gif"/>
</p>

[Youtube](https://www.youtube.com/watch?v=ETEEcY4mmEg)

[⤴️](#feature-demos--others)
### Database Client Migrations  

<p align="center">
<img  loading="lazy" src="/static/demo/client-db/schema-design-demo.mov.gif"/>
</p>

[Youtube](https://www.youtube.com/watch?v=IKvraKy0S90)

[⤴️](#feature-demos--others)
### Smart Terminal    

<p align="center">
<img  loading="lazy" src="/static/demo/smart-terminal/smart-terminal-demo.mov.gif"/>
</p>

[Youtube](https://www.youtube.com/watch?v=nVn3oe4oAuc)


[⤴️](#feature-demos--others)
### Themes : Dark    

<p align="center">
<img  loading="lazy" src="/static/demo/themes/dark-theme-demo.mov.gif"/>
</p>


[Youtube](https://www.youtube.com/watch?v=5vqqW_nG_OY)


[⤴️](#feature-demos--others)
### Themes : Colors    

<p align="center">
<img  loading="lazy" src="/static/demo/themes/theme-colors-demo.mov.gif"/>
</p>

[Youtube](https://www.youtube.com/watch?v=f1VocvAO3oE)

[⤴️](#feature-demos--others)
### Themes : Custom Colors    

<p align="center">
<img  loading="lazy" src="/static/demo/themes/theme-color.gif"/>
</p>

[Youtube](https://youtu.be/NFs0rOvhgbQ)

[⤴️](#feature-demos--others)
### Multi Environment project   

<p align="center">
<img  loading="lazy" src="/static/demo/gui/gui-multi-env.gif"/>
</p>

[Youtube](https://youtu.be/Y-v_4KnK1Jo)


# Serverless Deployment



[⤴️](#serverless-platforms-supported) 

## AWS Lambda Deployment

- Open `server/config/default.config.js` and set `aws.lambda` to true and change other cloud serverless platform values as `false`.
- Install AWS cli & authenticate

    Refer : https://docs.aws.amazon.com/cli/index.html
    
- Open `serverless.yml` file and do  the  necessary changes.
- `npm run aws:lambda`


[⤴️](#serverless-platforms-supported)

## Azure Function App

- Install Azure cli and login.
- `npm install -g azure-functions-core-tools`
- `npm run azure:deploy`


[⤴️](#serverless-platforms-supported)

## GCP Cloud Function


- Install Google Cloud cli and authenticate.
- `npm run gcp:fn`



[⤴️](#serverless-platforms-supported)

## Zeit Now


- Install Zeit now library and authenticate using email.
- Add `production` environment in `config.xc.json`
 
    ```
    "envs": {
        "production": {
          "db": [
            {
              "client": "mysql",
              "connection": {
                "host": "localhost",
                "port": "3306",
                "user": "root",
                "password": "password",
                "database": "sakila"
              },
              "meta": {
                "tableName": "_evolutions",
                "dbAlias": "primary"
              }
            }
          ],
          "api" : {}
        }
      },
    ```
- `npm run zeit:now`

  

[⤴️](#serverless-platforms-supported)

## Alibaba Function Compute 

- Install `fun` cli tool `npm install @alicloud/fun -g`
- Setup alibaba account configuration in cli using `fun config` ( https://www.alibabacloud.com/help/doc-detail/64204.htm )
- Run 
    - `npm run ali:fn:compute`
    - or `fun deploy`





    