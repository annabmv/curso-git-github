# Notas de aula referentes ao Módulo 3 do curso "Git e GitHub" do Bootcamp de Data Analytics.

## **Aula 1**

### **Trabalhando com branchs: O que é uma *branch?***

- São separações de código; permitem que várias pessoas atuem em um mesmo projeto de forma independente.

- A branch inicial de todo projeto é a branch **master**.

- Geralmente, nas empresas são criadas branchs de acordo com o ambiente que esse código será disponibilizado.

  - **Develop** (branch de desenvolvimento).

  - **Homolog** (após as alterações serem validadas, o código vai para a branch de homologação).

  - **Master** (branch principal do projeto; código que fica disponibilizado de forma pública para acesso).

- A equipe cria branchs para separar e desenvolver novas soluções, ou melhorar funcionalidades, de forma simultânea e independente.

## **Aula 2**

### **Trabalhando com branchs: Como criar e alternar para uma *branch* pelo terminal.**

        git checkout -b [nome-da-branch]

> Retorna uma mensagem avisando que já foi alterado o local para a branch criada.


        git branch

> Lista as branchs existentes no repositório.

> A branch que você está é geralmente sinalizada em uma cor diferente (ex: verde).

        git checkout [nome-da-branch]

> Para alternar de branch; indique o nome da branch que quer acessar.

- Todas as modificações realizadas não são aplicadas na branch master.

## **Aula 3**

### **Trabalhando com branchs: Como criar e alternar para uma *branch* pelo GitHub.**

- A nova branch pode ser criada pelo menu "master" na lateral superior esquerda da página.

> Digitar o nome da nova branch > "Create branch: [nome-da-branch] from master.

- É possível deletar branchs diretamente pelo GitHub.

> Ícone "Branches", que fica na lateral superior, ao lado de "master".

## **Aula 4**

### **Trabalhando com branchs: Enviando a *branch* local para o repositório remoto.**

- Realizar o *push* da branch local para o GitHub após realizar o *commit* das alterações realizadas.

        git push --set-upstream origin [nome-da-branch]

> É necessário fazer essa configuração na primeira vez assim como foi realizado com a branch master.

## **Aula 5**

### **Trabalhando com branchs: Fazendo um *merge* local.**

        git pull

> Atualizar o repositório com o remoto.

        git merge [nome-da-branch]

> Mostra exatamente as alterações que foram realizadas com o *merge*.

- Após o *merge* local, realizar o *push* para o repositório remoto.

## **Recursos adicionais:**

- [O que são branches no Git?](https://dev.to/womakerscode/tutorial-git-o-que-sao-branches-ramos-no-git-57pn)