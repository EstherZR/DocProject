---
order : 992
icon : 
tags : [Aprenda Comigo, Retype]
date : 2022-06-30
---


# Comandos Git 
<p style="text-align: justify;"> Para realizar a manipulação dos arquivos e fuinalmente publicá-los serão necessários o uso de alguns comandos git. Caso você nunca tenha utilizado o git antes, segue os comandos necessários:</p>

![](../img/barra.png)


## Lista de Comandos
> 1. Verifica alterações Locais: <br>
`git ls-files --modified`

> 2. Adiciona as alterações à lista de envio: <br>
`git add .` ou `git add <nome arquivo>`

> 3. Prepara o commit para o Git.<br>
     <i>Onde a flag -m indica que vamos adicionar uma mensagem para aquele commit</i><br>
     `git commit -m "Ajuste retype ¬¬"`

> 4. Por fim, vamos enviar esse projeto com o seguinte comando: <br>
`git push -u origin main`

> Extra:
  Comando para criar a branch main: <br>
  `git branch -M main`

> 5. Listar todas as branchs existentes
`git branch`

> 6. Criando uma Branch a partir de Outra
`git branch -c branchEspecifica MinhaNovaBrach` <br>

`git checkout MinhaNovaBrach` <br>

`git commit -m "Olha que commit lindo <3"` <br>

`git push -u origin MinhaNovaBrach` <br>

# Merge Entre Branchs
Mude para o branch main usando o comando git checkout e, em seguida, 
faça merge do branch usando o comando git merge junto com o nome do branch.

`git checkout main` <br>
`git merge homolog`