# Documentação do Projeto

Este repositório contém os principais artefatos de documentação referentes ao projeto, incluindo requisitos de negócio, diagramas de arquitetura, modelo de dados e evidências de qualidade.

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
