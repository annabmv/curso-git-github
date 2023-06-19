# Notas de aula referentes ao Módulo 4 do curso "Git e GitHub" do Bootcamp de Data Analytics.

## **Aula 1**

### **Trabalhando com projetos de outras pessoas: *Fork.***

- No GitHub:

  - Acessar o repositório de interesse; acessar o ícone *"Fork"* no canto superior direito da tela.

  - Uma cópia do repositório será criada na sua conta.

  - Na cópia que foi criada acessar o ícone "*Code"* e copiar o código para criar o acesso/clone local.

## **Aula 2**

### **Trabalhando com projetos de outras pessoas: Mantendo seu projeto atualizado.**

- 2 maneiras:

  - Atualizar diretamente no GitHub:
  
    > Aparece uma mensagem informando que houve alguma atuailzação no repositório principal/base.

      - Selecionar a opção *"Compare"*; conferir as alterações; selecionar *"Create pull request"*. 

  - No terminal:

        git remote add upstream [url-do-repositório]

        git fetch upstream

        git rebase upstream/master

## **Aula 3**

### **Trabalhando com projetos de outras pessoas: Enviando suas alterações.**

- Criar uma *branch* para enviar as suas alterações.

        git checkout -b [nome-da-nova-branch]

- Envio:

        git add .

        git commit -m "[descrição-do-commit]"

        git push 
        (obs: configurar upstream)

> Copiar o link informado com a mensagem *Create a pull request* para o navegador.

## **Aula 4**

### **Trabalhando com projetos de outras pessoas: *Pull request*.**

- Link gerado na aula anterior:

  - Adicionar título e descrição na página da *pull request*.

  - Informar o local (repositório "cópia" > repositório base/master).

- Na configuração da *pull request* você pode informar/adicionar os revisores, o autor e labels (descrever o tipo).

- Quem vai realizar a revisão da pull request pode adicionar comentários ao comparar as alterações e requisitar mudanças.

- Confirmar: *"Merge pull request"*.

## **Recursos adicionais:**

- [fork: Como colarborar com projetos exsitentes?](https://dev.to/womakerscode/tutorial-git-fork-como-colaborar-com-projetos-de-codigo-aberto-1lkm)

- [Copiando um repositório existente.](https://dev.to/womakerscode/tutorial-git-copiando-um-repositorio-existente-git-clone-1bfe)

- [Verificando commits remotos.](https://dev.to/womakerscode/tutorial-git-copiando-um-repositorio-existente-git-clone-1bfe)