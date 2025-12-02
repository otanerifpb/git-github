# Git e GitHub
Versionamento de um projeto com o Git e repositório com o GitHub

# Config 00 - Principais tutoriais
  * Link 01 - [Como personalizar o Perfil do GitHub](https://www.youtube.com/watch?v=9ygf4hkLVnA)
  * Link 02 - [GitHub para iniciantes](https://www.youtube.com/watch?v=BUGZZaChiYw)
  * Link 03 - [Fazer Clone do GitHub para o PC](https://www.youtube.com/watch?v=w7JF8XSlO2M)
  * Link 04 - [Fazer um Fork de um GitHub para o Meu GitHub](https://www.youtube.com/watch?v=jSFkCqMCuLE)
  * Link 05 - [Enviar um projeto para o GitHub, Master não é mais a pasta principal, agora é "Main"](https://www.youtube.com/watch?v=MdthEusEoy8)

# Config 01 - Instalar o Git no PC
* Passo 01 - Acessar link para baixar o [Git](https://git-scm.com/)
* Passo 02 - Selecionar > Downloads > Click no SO utilizado (Windows)
* Passo 03 - Click na versão do SO > Standalone Installer > Git for Windows/x64 Setup. ou Click here to download
* Passo 04 - Selecionar local para o Download no PC > Salvar
* Passo 05 - Cllick Dir > arquivo do Git-2... na pasta anterior *04* > Execuitar como administrador
* Passo 06 - Instalar o Git > Seguir com "Nest" em todos os passoa > Install > []View Release ... > Finish
* Passo 07 - Testar instalação > cmd > git --help > Enter > vai aparecer todas as informações (branch, commit, ...)

# Congig 02 - Criar uma conta no GitHub
* Passo 01 - Acessar o [GitHub](https://github.com/?locale=pt-br)
* Passo 02 - Click Sing Up > informar um e-mail > Continue
* Passo 03 - Criar uma senha > Continue
* Passo 04 - Criar um username > Continue
* Passo 05 - Receber informações no e-mai > y-sim ou n-não > Continuar
* Passo 06 - Verificar se é Humano > Verificar > Selecionar o que se pede > Create account
* Passo 07 - Ativar a conta > informar o código enviado para o e-mail 
* Passo 08 - Perfil de uso da conta > Quantas pessoas vai usar > Student ou Teacher > Continuar
* Passo 09 - Pesquisa de recusrsos que gostaria de usar no GitHub > Selecionar todos > Continuar
* Passo 10 - Escolher o plano > Free ou Get additional ... > Continue for free

# Config 03 - Criar uma WorkSpace para o Projeto no PC ou usar o cmd ou Power Shell 
## Opção 01 - Criar a WorkSpace do projeto direto no no PC
* Passo 01 - Selecionar a unidade de disco > criar uma WorkSpace > dar o nome "wsnomeprojeto"
* Passo 02 - Colocar um projeto criado, ou criar um a partir desta WorkSpace
## Opção 02 - Criar a WorkSpace do projeto pelo Power Shell/cmd
* Para verificar o conteudo da pasta
```Bash
$ ls ou dir
```
* Nome da WorkSpace para o projeto, ex: wsifpb/wsinove/wspwe1/...
```Bash
$ mkdir WorkSpaceNome
```
* Acesar WorkSpace "wsifpb"
```Bash
$ cd WorkSpaceNome
```

# Config 04 - Criar um repositório no GitHub Renato
* Passo 01 - Abrir o GitHub Renato que foi criado no na #Config 02
* Passo 02 - Selecionr > Repositories > New
* Passo 03 - General > **Repository name:** nome_projeto > **Description:** Descrição do projeto
* Passo 04 - Configuration > **Choose visibility:** [x]Public(Default) []Private > Add README []Off(Default) [x]On (usar README do projeto)
* Passo 05 - > Create repository **a partir de 2020 a breaches padrão é "main" antesn era "master"**

