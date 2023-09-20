# Meu_Portfolio

Projeto guiado elaborado no final do módulo de React.js do curso de Front End da <img src="src/assets/reprograma-fundos-claros.png" alt="logo reprograma" width="200"> , cujo objetivo era criar um site - portfólio pessoal.

## Índice:

  - [APRESENTAÇÃO](#Apresentação)

     - [Quem é Flaviana?](###Quem-É-Flaviana-?)

     - [Contatos](###Contatos)
     
   - [DESCRIÇÃO DO PROJETO](#Descrição-Do-Projeto)

      - [Contexto](##Contexto)
    
      - [Estrutura do Projeto](##Estrutura-Do-Projeto)
    
      - [TECNOLOGIAS UTILIZADAS](##Tecnologias-Utilizadas)
     
   - [PASSO A PASSO UTILIZADO](#Passo-A-Passo-Utilizado)

   - [FUNCIONALIDADES IMPLEMENTADAS](#Funcionalidades-Implementadas)

   - [IMPLEMENTAÇÕES FUTURAS](#Implementações-Futuras)

   - [COMO RODAR O PROJETO](##Como-Rodar-O-Projeto)

   - [CONFIRA O RESULTADO](###Confira-O-Resultado)

     
# APRESENTAÇÃO
### Quem é Flaviana?

![image](https://github.com/FlavianaFXT/ProjetoFinal-reprograma/assets/113718720/1e13d5e7-b1b4-4701-a689-ec293ec77ea1)


Flaviana Ferraz é uma sertaneja de Pernambuco morando no sertão da Paraiba, formada em Gestão Ambiental e Mestre em Recursos Hídricos, após mais de 10 anos de formada, aos 34 anos, decidiu fazer transição de carreira. Hoje, empreendedora e aluna {reprograma} trilhando os caminhos do Desenvolvimento FrontEnd.

### Contatos

- [E-mail](flaviferraz@yahoo.com.br)
- [LinkedIn](https://www.linkedin.com/in/flaviana-ferraz-frontend)
- [GitHub](https://github.com/flavianafxt)


# DESCRIÇÃO DO PROJETO

## Contexto

O objetivo desse projeto era elaborar um Portfólio pessoal utilizando o React.js.

![image](https://github.com/FlavianaFXT/Meu_Portfolio/assets/113718720/0bfe407d-0fa2-4d8f-a508-91a89e88591c)


## O site contem 4 páginas:

* Home
![image](https://github.com/FlavianaFXT/Meu_Portfolio/assets/113718720/1006de23-bf3a-4bb1-ae00-b8752eac4886)

* Sobre
 ![image](https://github.com/FlavianaFXT/Meu_Portfolio/assets/113718720/1d2595fe-cc74-4cb4-9fb1-3875d4a95c10)

  ![image](https://github.com/FlavianaFXT/Meu_Portfolio/assets/113718720/0d3b2087-56c8-45d9-ad91-0e6be502508f)

* Portfólio
  ![image](https://github.com/FlavianaFXT/Meu_Portfolio/assets/113718720/4326a2a3-7416-4b91-93ae-d60a7672dbb2)

![image](https://github.com/FlavianaFXT/Meu_Portfolio/assets/113718720/3940d720-0d48-44e1-8c4d-121bd046e187)

![image](https://github.com/FlavianaFXT/Meu_Portfolio/assets/113718720/23c1aba6-7a63-45b0-a4f3-bf2fe959bf24)

* Contato
  ![image](https://github.com/FlavianaFXT/Meu_Portfolio/assets/113718720/3dae43a1-25d9-4b36-a52a-2a0b602a2114)

![image](https://github.com/FlavianaFXT/Meu_Portfolio/assets/113718720/c5b63afc-e916-40ab-ab40-d5df0e2375f3)


Foi utilizada ainda a estrutura de componentes para compor partes das páginas com maior facilidade.

## Estrutura do projeto

![image](https://github.com/FlavianaFXT/Meu_Portfolio/assets/113718720/3d41ce66-aa76-4b0a-bbad-cb288d9a877c)  

![image](https://github.com/FlavianaFXT/Meu_Portfolio/assets/113718720/73844913-23c0-47d4-885f-800e84ff096e)

![image](https://github.com/FlavianaFXT/Meu_Portfolio/assets/113718720/933834f4-7267-4ede-99bd-af3db0e9cb10)


## TECNOLOGIAS UTILIZADAS

| Ferramenta | Descrição |
| --- | --- |
| `ReactJS` | framework web|
| `Vite` | gerador de projeto de front-end|
| `npm` | gerenciador de pacotes|
| `Firebase` | Ferramenta realtime database para gravar as mensagens de contato|
| `Module CSS` | Ferramenta para ter mais produtividade ao estilizar a aplicação|
| `react-icons` | Dependência com icones no reactjs|
| `React router dom` | Dependência para criar rotas no reactjs|
| `Git` | Gerenciador de vercionamento|
| `Github` | Hospedagem do código fonte integrado com gerenciador de versionamento|
| `Vercel` | Hospedagem para a aplicação, fiz o deploy integrado com o github|
  

# PASSO A PASSO UTILIZADO

1️⃣ Criação de repositorio no github e clone na maquina em que trabalhei no projeto através do Git Bash
2️⃣ Start do projeto na maquina utilizando o VS Code e seu terminal, atraves dos comandos de iniciação vite e node
 
  ```bash
  npm create vite@latest nome-projeto -- --template react
  ```
   ```bash
  cd nome-projeto
   ```
  ```bash
    npm i
  ```
  ```bash
     npm run dev
  ```
  
3️⃣ Exclusão de arquivos do projeto que não faremos uso e inserção de algum elemento em App.jsx para ver se o projeto está funcionando
4️⃣Instalação do react-router-dom para criação do arquivo Router e possibilitar a navegação do Menu e para outras páginas componentes do site
   ```bash
   npm i react-router-dom@6
   ``` 
5️⃣ Criação do Router para o menu de navegação.
6️⃣ Criação dos componentes que se repetem 
7️⃣ Criação de componentes e de conteúdo de cada página principal, assim como suas estilizações. Nessa fase, foi utilizado o react-icons, o qual foi instalado pelo terminal utilizando o comando:
   ```bash
   npm i react-icons
   ```
  
8️⃣ Criação e integração do firebase com variaveis de ambiente na página Contato
 ```bash
 npm i firebase
```
  
9️⃣ Adicionar todas as modificações a cada etapa e subir no GitHub
 ```bash
 git add .
 ```
 ```bash
 git commit -m "comentario"
```
 ```bash
 git push
```

1️⃣ 0️⃣ Deploy do projeto no Vercel


# FUNCIONALIDADES IMPLEMENTADAS

✔️ Utilização do Router para navegação entre páginas

✔️ Integração com o firebase para criação de banco de dados para o recebimento das mensagens enviadas via página Contato

✔️ Componentização para desenvolvimento mais rápido das páginas e elementos das páginas

✔️ Estilização com o CSS modulado

✔️ Responsividade

# IMPLEMENTAÇÕES FUTURAS

- [ ] Acessibilidade


## COMO RODAR O PROJETO

Para rodar esse projeto em sua máquina, siga os passos a seguir:

1️⃣ Realize o fork desse repositorio

2️⃣ Clone na sua máquina

3️⃣ Entre no diretório do repositorio clonado e as dependências do projeto, com o comando:
```bash
                                           npm install ou npm i
```

4️⃣ Por fim rode o projeto:
```bash
                           npm run dev
```

O navegador será aberto automaticamente usando a porta localhost:3000 
  
### CONFIRA O RESULTADO: https://meu-portfolio-lvu6upayj-flavianafxt.vercel.app/


  


