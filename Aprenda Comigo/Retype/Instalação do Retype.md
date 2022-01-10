---
order : 993
icon : 
tags : [Aprenda Comigo, Retype]
date : 2022-01-10
---

# Instalando o Retype?
<p style="text-align: justify;"> Para realizar a instação do Retype, seguiremos os passos abaixo.
Lembrando que o retype usa o GitHub para hospedar os arquivos. Por isso caso não conheça muito bem como o gitHub funciona, sugiro que dê uma pesquisada antes de continuar por aqui.</p>

![](../img/barra.png)

---

## Repositório GitHub
Bem, o primeiro passo é realizar o login na sua conta do [!button variant="info" corners="pill"  size="xs" text="GitHub"](https://github.com/login).

![Login no GitHub](../img/001.png "Realize seu login")

<br>

Agora, vamos abrir o perfil para acessar nossa lista de repositórios do GitHub:

<br>

### **Passo 01**

![Lista de Repositórios](../img/01.png)
1. Selecione a opção "Repositórios"

<br>

### **Passo 02**

![Novo Repositório](../img/02.png)
2. Clique em `Novo`.

<br>

### **Passo 03**
![Configuração do Repositório](../img/03.png)
3. Defina o nome do seu repositório. Se desejar, poderá inserir uma descrição sobre ele; <br>
4. Marque este repositório como `Público`;
!!!warning
Caso seu repositório não seja definido como Público o Retype não conseguirá acessá-lo!
!!!

5. Adicionar o arquivo _README_ ele será usado como arquivo (página) principal do Retype;

6. Por fim, clique em `Criar`.

<br>

### **Passo 04**
Com o repositório criado, iremos agora copiar o link para realizar a clonagem para nossa máquina local, conforme imagem abaixo:

![Link para Clonagem do Repositório](../img/04.png)
7. Clique em `Código`; <br>
8. Copie a url disponibilizada.




---

## Instalação do Retype
Agora iremos usar um terminal para realizar a clonagem do repositório criado.
Aqui, estou usando o `Visual Code`, mas fique a vontade para usar o terminal de sua preferencia.

<br>

### **Passo 01**
Use o comando abaixo para realizar a clonagem do seu repositório:
`git clone [url do repositório]`
![](../img/05.png)
==- Exemplo
git clone https://github.com/EstherZR/DocProject.git
==-

!!!success
O resultado deverá ser conforme área circulada em verde.
!!!

<br>
<br>


### **Passo 02**
Agora acesse a pasta clonada usando o comando `cd nomeRepositorio`;
![](../img/06.png)


<br>
<br>



### **Passo 03**
Execute o comando para instalação do retype: `npm install retypeapp --global`
![](../img/07.png)

<br>
<br>


### **Passo 04**
Para executar o Retype localmente, execute o comando `retype watch`

Acessando a url `localhost: 5000/nomeRepositorio` você já poderá visulizar sua página Retype.
 

<br>
<br>


