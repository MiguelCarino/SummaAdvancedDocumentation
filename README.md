# SummaAdvancedDocumentation
SummaAdvanced is an Argentinian closed source ERP solution with a subisdiary in Mexico. Rendering services for ERP custom development, deployment and maintenance. https://www.quasarglobal.com/
This git tries to tackle on documentation about its four main services.
- **ERP custom development:** How to ask or configure your Summa Advanced instance for custom requirements you may need.
- **ERP deployment:** How to setup your Summa Advanced instance.
- **ERP maintenance:** How to give maintenance to your Summa Advanced instance.
- **ERP troubleshooting:** Most common troubleshooting with your Summa Advanced instance.

# Getting Started with Summa Advanced: 

## Request a demo
You can request a demo at https://www.quasarglobal.com/
## Installation
## Setting up SQL
## Setting up the web server
## Setting up a Summa Advanced instance
### Users
### Business
-Created from scratch:
-Created from another database:
https://stackoverflow.com/questions/3829271/how-can-i-clone-an-sql-server-database-on-the-same-server-in-sql-server-2008-exp
Once copied the database with SQL Server Management Studio, proceed to Run a New Query from SummaAdvmstr database:
### See all current databases
select * from mstrSitios
### Add a new database
insert into mstrSitios(Sitio,Servidor,BaseDatos,Usuario,ClaveUsuario,Licencias,Clave,fechaVencimiento)
VALUES('NameSitio','Server\Database','DatabaseName','username','usernamePassword',0,null,null)
### Add a new database into a site group
insert into mstrGrupoSitios(Grupo,Sitio)
values('GroupName','Site')
### Definitions
## Backup
## Updating a Summa Advanced instance
## Troubleshooting

# Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow [Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general). Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship. Any use of third-party trademarks or logos are subject to those third-party's policies.

# Acknowledgments 

Quasar Argentina benefits from contributions by the open software community. We gratefully acknowledge all contributions made from the broader open source community, in particular:

1) Microsoft SQL Server Management.   

2) 