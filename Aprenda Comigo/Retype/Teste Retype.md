---
order : 993
layout: page
icon : 
tags : [Aprenda Comigo, Retype]
date : 2022-01-10T17:15 # January 10, 2022 at 17:15 (17:15 PM)
color: green
visibility: hidden
#http://localhost:5000/DocProject/aprenda-comigo/retype/teste-retype/
---

# Teste Retype
<p style="text-align: justify;"> Para realizar a instação do Retype, seguiremos os passos abaixo.
Lembrando que o retype usa o GitHub para hospedar os arquivos. Por isso caso não conheça muito bem como o gitHub funciona, sugiro que dê uma pesquisada antes de continuar por aqui.</p>

![](../img/barra.png)

---

## Repositório GitHub
>Bem, o primeiro passo é realizar o login na sua conta do [!button variant="info" corners="pill"  size="xs" text="GitHub"](https://github.com/login).

![Login no GitHub](../img/001.png "Realize seu login")

<br>

Agora, vamos abrir o perfil para acessar nossa lista de repositórios do GitHub:

<br>

### **Passo 01**
>Selecione a opção `Repositórios`:

![Lista de Repositórios](../img/01.png)


<br>

### **Passo 02**
>Clique em `Novo`:

![Novo Repositório](../img/02.png)


<br>

### **Passo 03**
> Agora vamos configurar nosso repositório para que o Retype possa acessá-lo:

![Configuração do Repositório](../img/03.png)

>[!badge variant="danger" corners="pill" text="**A**"] Defina o nome do seu repositório. Se desejar, poderá inserir uma descrição sobre ele; <br>
>[!badge variant="danger" corners="pill" text="**B**"]  Marque este repositório como `Público`;
!!!warning
Caso seu repositório não seja definido como Público o Retype não conseguirá acessá-lo!
!!!

>[!badge variant="danger" corners="pill" text="**C**"]  Adicionar o arquivo _README_ ele será usado como arquivo (página) principal do Retype; <br>
>[!badge variant="danger" corners="pill" text="**D**"]  Por fim, clique em `Criar`.

<br>

### **Passo 04**
>Com o repositório criado, iremos agora copiar o link para realizar a clonagem para nossa máquina local, conforme imagem abaixo:

![Link para Clonagem do Repositório](../img/04.png)
>[!badge variant="danger" corners="pill" text="**A**"]  Clique em `Código`; <br>
>[!badge variant="danger" corners="pill" text="**B**"]  Copie a url disponibilizada.




---

## Instalação do Retype
>Agora iremos usar um terminal para realizar a clonagem do repositório criado.
Aqui, estou usando o `Visual Code`, mas fique a vontade para usar o terminal de sua preferencia.

<br>

### **Passo 01**
>Use o comando abaixo para realizar a clonagem do seu repositório:
`git clone [url do repositório]`

![Realizando Clone do Projeto](../img/05.png)

==- Exemplo
git clone https://github.com/retypeapp/retype.git
==-

!!!success
O resultado deverá ser conforme área destacada em verde.
!!!

<br>
<br>


### **Passo 02**
>Agora acesse a pasta clonada usando o comando `cd nomeRepositorio`;

![Acessando pasta do projeto](../img/06.png)


<br>
<br>



### **Passo 03**
>Execute o comando para instalação do retype: `npm install retypeapp --global`

![Instalando o Retype](../img/07.png)

<br>
<br>


### **Passo 04**

>Para executar o Retype localmente, execute o comando `retype watch`
Acessando a url `localhost:5000/nomeRepositorio` você já poderá visulizar sua página Retype.
 
---

## Hospendando Projeto
>Depois de todos os passos acima, você já pode configurar sua página para ser acessada externamente.
Então você poderá realizar as modificações na sua máquina local e usar uma série de comandos git para atualizar sua página externa.

!!!<span style="color:darkgreen">**Mas por que devo fazer isso?** 🧐 </span>  
A resposta é simples, para que pessoas fora da sua rede de internet possam acessar seu conteúdo. Se não realizar esse passo, apenas você visualizar sua página.
!!!

<br>
<br>


