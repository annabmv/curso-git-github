# Notas de aula referentes ao Módulo 2 do curso "Git e GitHub" do Bootcamp de Data Analytics.

## **Aula 1**

### **Criando um repositório local:**

Passo 1: Criar o diretório local.


        mkdir [nome-da-pasta]

Passo 2: Acessar a pasta do diretório criado.

        cd [nome-da-pasta]

Passo 3: Verificar as configurações do Git.

        git config --list

> Verificar se o email e username são os mesmo do GitHub.

Passo 4: Inicializar o diretório.

        git init

Passo 5: Criar os primeiros arquivos.

- Ex: "notasdeaula.md"

Obs: No curso foi utilizado o VS Code.

## **Aula 2**

### **Conectando seu repositório local com o GitHub:**

Passo 1:

> Acessar sua conta no GiHub > "New repository" > definir o nome do novo repositório > adicionar descrição (curta e objetiva) > selecionar "Public" (repositório público) > "Create repository"

Passo 2:

> No GitHub: "...or create a new repository on the command line"

        git remote add origin [caminho-para-o-repositorio]

> Colar o comando no terminal do VS Code (*exemplo passado no curso*).

Passo 3:

        git remote -v

> Verificar origem remota.

## **Aula 3**

### **Clonando um repositório já existente**

Passo 1:

        mkdir [nome-do-repositorio]

> Criar o repositório de interesse.

        cd [nome-do-repositorio]

> Acessar o repositório criado.

Passo 2:

- Copiar, no GitHub, o link HTTPS referente ao repositório que será clonado.

Passo 3:

        git clone [link-HTTPS]

> Clonar o repositório do GitHub na pasta que foi criada.

## **Aula 4**

### **Comandos mais utilizados: *git status***

        git status

> Verificar o status dos arquivos e pastas dentro do nosso repositório.

- Esse comando mostra se houve alterações (pasta e/ou arquivo), porém não mostra quais foram as alterações realizadas.

## **Aula 5**

### **Comandos mais utilizados: *git add***

        git add .

> Adiciona todos os arquivos para a esteira de commit.

        git add [nome do arquivo]

> Adiciona um arquivo específico.

## **Aula 6**

### **Comandos mais utilizados: *git commit*** 

        git commit -m [descrição do commit]

> Registro das alterações realizadas (quais modificações, quem e quando).

- No GitHub todos os *commits* realizados ficam registrados.

- Existe um código único para cada *commit*.
