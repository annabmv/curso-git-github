# Notas de aula referentes ao Módulo 1 do curso "Git e GitHub" do Bootcamp de Data Analytics.

## **Aula 1**

### **Instalação**

O download é realizado no próprio site do Git (verificar a opção correta dependendo do seu sistema operacional):

- <https://git-scm.com/downloads>

Windows:

- No momento da instalação verificar se a opção de instalar o Git Bash está selecionada.

- Git Bash é uma aplicação que emula um terminal Unix. No caso do Windows, por exemplo, pode ser que alguns comandos do Git funcionem apenas no Git Bash.

### **Configuração**

- Após a instalação, executar o seguinte comando no terminal:

        git --version

## **Aula 2**

### **Criar uma conta no GitHub**

Configurando sua conta no computador:

        git config --global user.name [seu-username]

        git config --global user.email [seu-email] 

- Substitua o que está entre [ ] pelos da sua conta no GitHub.

Para conferir:

      git config --list

- No final das informações apresentadas você pode verificar as informações de email e username que estão configurados.

## **Aula 3**

### **Versionamento**

- O versionamento de software é um processo de controle de versões.

- Permite saber quando e quais mudanças foram realizadas, acompanhando as mudanças aplicadas no software.

- O Git controla esse histórico de versões de um mesmo código atribuindo uma "numeração" referente ao estado daquele código em determinado momento que foi salvo.

## **Aula 4**

### **Repositório**

- É uma pasta onde armazenamos o projeto, dentro de um repositório os projetos podem se dividir em módulos e outras divisões específicas para cada objetivo.

- Todo repositório tem um arquivo *.git*, este arquivo indica que este repositório é "rastreável" para o Git.

## **Aula 5**

### **Commit**

- É um conjunto de alterações no código. Toda vez que você desejar salvar/registrar as alterações no seu projeto, você "comita" essas alterações.

- Um commit tem as alterações que são realizadas nele e uma mensagem descritiva, além de informações sobre o autor, data, etc.

- **Change (Diff)**: o Git mantém o controle de versão rastreando as alterações e diferenças entre as versões dos arquivos "cadastrados" nele.

- O que o Git entende por alteração de um arquivo:
    - Criação, renomeação ou exclusão de arquivos.
    - Inserção ou exclusão de uma linha em um arquivo (uma linha modificada é uma inserção e uma exclusão).

## **Aula 6**

### **Branch**

- São separações de código, permitindo que várias pessoas atuem em um mesmo projeto de maneira independente e paralela.

- Branch inicial: **master**
    - Nas empresas geralmente criamos branchs de acordo com o ambiente que esse código será disponibilizado;

- *Develop*: ambiente para uso em tempo de desenvolvimento.

- *Homolog*: Após as alterações serem validadas em ambiente de desenvolvimento.

- *Master*: É a branch principal do nosso projeto.

## **Aula 7**

### **Merge**

- Consiste em unir duas branchs, sendo geralmente realizado para juntar alterações de branchs em que pessoas estavam atuando de forma paralela.

## **Aula 8**

### **Clone**

- Transferir o repositório que está no GitHub para nossa máquina local; gerar uma cópia.

- Permite que tenhamos acesso ao repositório localmente, podendo realizar alterações e enviá-las para o GitHub.

## **Aula 9**

### **Pull**

- Com o comando *git pull* podemos atualizar o nosso repositório local.
    - É realizado um *merge* entro o repositório remoto (GitHub) com o local, de forma que a gente mantenha o conteúdo atualizado para evitar conflitos no momento de envio de futuras alterações.

## **Aula 10**

### **Push**

- O comando *git push* realiza o envio de nossas alterações locais para o repositório remoto (GitHub).
    - Dessa forma, o repositório remoto está atualizado com a versão local.

## **Aula 11**

### **Fork**

- Semelhante ao clone, porém só ocorre na interface gráfica do GitHub.

- O repositório não é baixado automaticamente para o seu computador, você terá uma cópia dele na sua conta do GitHub.

- Permite que você faça *pull-requests* para contribuir com o conteúdo no repositório principal.

## **Aula 12**

### **Pull request**

- Depois de realizar o *fork* no repositório de interesse podemos resolver *issues* e realizar *pull requests* para enviar soluções para erros e adicionar novos conteúdos.

- A pessoa dona do repositório principal avalia a sua *pull request* e, se estiver tudo ok, será feito o *merge* nesse repositório.

## **Materiais complementares**

- Instalação, configuração e inicialização do Git no Windows: [acesse aqui](https://dev.to/womakerscode/tutorial-instalando-configurando-e-inicializando-o-git-no-windows-57cj)

- Instalação do GitHub Desktop para Windows: [acesse aqui](https://dev.to/womakerscode/instalacao-do-github-desktop-para-windows-2nhp)

- Guia e comandos básicos para iniciantes: [acesse aqui](https://dev.to/womakerscode/git-e-github-guia-rapido-e-comandos-basicos-para-iniciantes-4ile)