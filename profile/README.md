# Documentação do Projeto

Este repositório contém os principais artefatos de documentação referentes ao projeto, incluindo requisitos de negócio, diagramas de arquitetura, modelo de dados e evidências de qualidade.

## 📖 Apresentação TechChallenge Fase 4

A apresentação do projeto foi realizada no dia 28/07/2025:

SOAT \- TECH CHALLENGE \- FASTFOOD

GRUPO 17 (DISCORD) 62 (FIAP)

Participantes:

| Nome                             | Discord     |
|:---------------------------------|:------------|
| Frederico Teles Costa            | frdCosta    |
| Nathan Cordeiro Ribeiro da Silva | little\_rj1 |
| Gustavo Manocchio                | manocchio   |
| Fernando Marques dos Santos      | slabrx      |

Acessos:

| GitHub \- OrderService | [https://github.com/group-17-fiap-soat/order-fastfood-service](https://github.com/group-17-fiap-soat/order-fastfood-service) |
| :---- | :---- |
| GitHub \- AuthService | [https://github.com/group-17-fiap-soat/auth-fastfood-service](https://github.com/group-17-fiap-soat/auth-fastfood-service) |
| GitHub \- PaymentService | [https://github.com/group-17-fiap-soat/payment-fastfood-service](https://github.com/group-17-fiap-soat/payment-fastfood-service) |
| Github \- Infra | [https://github.com/group-17-fiap-soat/infra](https://github.com/group-17-fiap-soat/infra) |
| Github \- Lambda | [https://github.com/group-17-fiap-soat/lambda](https://github.com/group-17-fiap-soat/lambda) |
| Github \- Database  | [https://github.com/group-17-fiap-soat/database-trf](https://github.com/group-17-fiap-soat/database-trf) |
| Documentação | [https://www.canva.com/design/DAGoOEMoO7I/HZeMQrmzN15N3j6I6ojPbA/view?utm\_content=DAGoOEMoO7I\&utm\_campaign=designshare\&utm\_medium=link2\&utm\_source=uniquelinks\&utlId=hb5019f590b](https://www.canva.com/design/DAGoOEMoO7I/HZeMQrmzN15N3j6I6ojPbA/view?utm_content=DAGoOEMoO7I&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hb5019f590b) |
| Vídeo \- Youtube | [https://youtu.be/BWJbpuCnetI](https://www.youtube.com/watch?v=b7py2u_cs9I) |


## 📌 Requisitos de Negócio

A imagem abaixo consolida os principais requisitos que nortearam o desenvolvimento do projeto:

![Requisitos de Negócio](./1.png)

---

## 🛠️ Diagrama de Baixo Nível (LLD)

Este diagrama apresenta a estrutura detalhada do sistema em nível de componentes e interações:

![LLD - Low Level Design](./2.png)

---

## ☁️ Arquitetura de Infraestrutura (HLD)

Diagrama de alto nível da arquitetura implementada na AWS, contemplando a adoção de banco NoSQL (Redis), containers via ECR e bancos relacionais (RDS) organizados por microserviço:

![HLD - High Level Design](./3.png)

---

## 🧩 Modelo de Dados (DER)

Diagrama Entidade-Relacionamento (DER) dos bancos de dados dos microserviços `order`, `auth` e `payment`, conforme a segmentação da arquitetura orientada a serviços:

![DER - Modelo de Dados](./4.png)

---

## ✅ Qualidade de Código

Evidência do Quality Gate configurado no SonarQube, validando as entregas com no mínimo 80% de code coverage em todos os pipelines:

![Quality Gate SonarQube](./5.png)

---

## 📄 Como contribuir

Sinta-se à vontade para abrir *issues*, sugerir melhorias ou enviar *pull requests*.

## 🧾 Licença

Este projeto está licenciado sob a [MIT License](./LICENSE).
