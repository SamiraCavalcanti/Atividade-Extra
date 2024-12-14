
# Deploy de um Projeto Maven no WildFly

## Introdução

Este projeto é um exemplo simples de como criar e fazer o deploy de uma aplicação web usando Maven e WildFly. O projeto foi criado utilizando o archetype `maven-archetype-quickstart-webapp` e inclui uma página HTML básica no `index.jsp`.

## Passo a Passo para Configuração e Deploy

### Criação do Projeto

1. Criei um novo projeto Maven usando o archetype `maven-archetype-quickstart-webapp`:
![Captura de tela de 2024-12-10 15-26-39](https://github.com/user-attachments/assets/6cd823c0-6bb3-4df2-8a09-d63af8742d8e)

   


### Configuração do Ambiente de Desenvolvimento

1. Instalei as extensões **Pack for Java** e **JBoss Tools** no meu IDE.

   
![Captura de tela de 2024-12-11 19-49-16](https://github.com/user-attachments/assets/38a31f48-b737-4d28-ab7e-6b28c5ce7bc2)
![Captura de tela de 2024-12-11 19-45-48](https://github.com/user-attachments/assets/b2e3721d-d7d5-4b2c-8963-64eb0bcbc95c)


3. Na seção de servidores do IDE, utilizei o **JBoss Tools** para criar um novo servidor WildFly.
![Captura de tela de 2024-12-10 15-39-42](https://github.com/user-attachments/assets/f6adb1d6-83d5-4ead-ac98-20d47eb7e1c1)



   

### Deploy da Aplicação

1. Adicionei o servidor WildFly no IDE e configurei-o para fazer o deploy da aplicação.
![Captura de tela de 2024-12-10 15-41-07](https://github.com/user-attachments/assets/45c40612-4525-4313-b19f-0315e42840d2)



3. Fiz o deploy da aplicação no WildFly através do IDE depois de ter gerado o arquivo .war e iniciá-lo.
![Captura de tela de 2024-12-10 15-44-39](https://github.com/user-attachments/assets/fc76f80f-56fb-4109-a2e0-1183a5c15bc7)

![Captura de tela de 2024-12-10 15-46-32](https://github.com/user-attachments/assets/3f6dcf51-dbfe-44d7-80e8-f1b54543e224)

![Captura de tela de 2024-12-10 15-50-15](https://github.com/user-attachments/assets/4908f9d7-1afb-4a20-8152-d293bf7deb80)

![Captura de tela de 2024-12-10 15-54-40](https://github.com/user-attachments/assets/c3452c14-61af-47e5-8748-334ddd2c2f0c)


# Integração Contínua com Jenkins

Este repositório foi configurado com **Integração Contínua (CI)** utilizando o Jenkins ![Jenkins Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/c/cd/Jenkins_logo.svg/800px-Jenkins_logo.svg.png). 

Sempre que há alterações no repositório, o Jenkins automaticamente executa o processo de build, testes e validações, garantindo que o código esteja sempre estável e pronto para produção. O pipeline de CI inclui a execução de testes automatizados e a criação de artefatos de build, otimizando o fluxo de trabalho de desenvolvimento.

## Como funciona:
- O Jenkins monitora o repositório GitHub.
- Quando um novo commit é feito, o pipeline de CI é acionado.
- O Jenkins realiza o build e executa os testes automaticamente.

Com isso, garantimos que o código esteja sempre validado, aumentando a qualidade e a eficiência do desenvolvimento.
![Captura de tela de 2024-12-14 12-26-26](https://github.com/user-attachments/assets/33d2cb22-fd24-4acb-b0e7-8a086a5633f6)
![Captura de tela de 2024-12-14 12-27-13](https://github.com/user-attachments/assets/83024285-2b89-40ac-b64a-533ca5e5b936)
![Captura de tela de 2024-12-14 12-27-46](https://github.com/user-attachments/assets/87782bd3-c51d-444a-ad93-bd7f905b3c2b)









## Tecnologias Utilizadas

![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![WildFly](https://img.shields.io/badge/WildFly-6C757D?style=for-the-badge&logo=wildfly&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=oracle&logoColor=white)
![Jenkins Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/c/cd/Jenkins_logo.svg/800px-Jenkins_logo.svg.png)
