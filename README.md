# e-commerce
## Objetivo
Desenvolver um software e-commerce que pode ser personalizado estaticamente de forma limitada e possibilite a escalabilidade de funcionalidade de forma que não impacte os demais serviços e que possam ser habilitados e desabilitados de acordo com o cliente(vendedor)

## Padrão arquitetural
### Arquitetura geral do sistema
![image](/docs/e-commerce-arquitetura-geral.png)
### Arquitetura infra
### Arquitetura backend
O padrão arquitetural do backend desenvolvido será microsserviços, por conta da possibilidade de adicionar serviços novos que não impactam nos já existentes além de possibilitar escalabilidade
![image1](/docs/e-commerce-arquitetura-microsservico.png)
A arquitetural interna de cada microserviços convencional, ou seja, microsservicos de funcionalidades funcionais como CRUD(criação, remoção, atualização e leitura de dados) será estruturada em MVC com camadas como inlustrado abaixo:
![image2](/docs/e-commerce-arquitetura-servico-api.png)
As pastas mostradas são os companentes principais, dependendo de cada microsserviço seram criadas outros componentes para apoiar a organização do codigo
### Arquitetura frontend

## Tecnologias
* Backend: Nodejs(Nestjs)
* Frontend: React(Nextjs)
* Banco de dados: Postgres
