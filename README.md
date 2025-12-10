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
ls ou dir
```
* Nome da WorkSpace para o projeto, ex: wsifpb/wsinove/wspwe1/...
```Bash
mkdir WorkSpaceNome
```
* Acesar WorkSpace "wsifpb"
```Bash
cd WorkSpaceNome
```

# Config 04 - Criar um repositório no GitHub Renato
* Passo 01 - Abrir o GitHub Renato que foi criado no na #Config 02
* Passo 02 - Selecionr > Repositories > New
* Passo 03 - General > **Repository name:** nome_projeto > **Description:** Descrição do projeto
* Passo 04 - Configuration > **Choose visibility:** [x]Public(Default) []Private > Add README []Off(Default) [x]On (usar README do projeto)
* Passo 05 - > Create repository **a partir de 2020 a breaches padrão é "main" antesn era "master"**

# Config 05 - Inicialçizar o Git no Projeto
* **Vai criar a linha do tempo do projeto, realizar/repetir este passo sempre que criar uma pasta nova no projeto**
## Opção 01 - Click Dir na pasta do projeto > Git Bash Here __Necessário está na pasta do projeto para abrir um cmd do "Bash"__
* Iniciar o Git
```Bash
$ git init
```
* ...(master) $ Para mudar de "Master" para "Main" no projeto para ter o novo padrão do GitHub
```Bash
git checkout -b main
```
* ...(master) $ Para mudar de "Master" para "Main" no projeto para ter o novo padrão do GitHub
```Bash
git checkout -b main
```
* ...(main) $ Verificar status das pastas do projeto: Verde está no Git, Vermelho está so no PC  
```Bash
git status
```
* ...(main) $ Fechar o Git]
```Bash
exit
```
## Opção 02 - Abrir a pasta do projeto > Click Dir > Mostrar mais opções > Git Bash Here __Abre um cmd__
*Iniciar o Git
```Bash
git init
```
* ...(master) $ Para mudar de "Master" para "Main" no projeto para ter o novo padrão do GitHub 
```Bash
git checkout -b main
```
* ...(main) $ Verificar status dos arquivos: Verde está no GitHub, Vermelho está so no PC
```Bash
git status
```
* ...(main) $ Fechar o Git]
```Bash
exit
```

# Config 06 - Fazer o primeiro commit do Git(PC) >> GitHub(Renato) 
** Usar cmd do Bash na pasta do projeto**
* ...(main) $ Verificar status das pastas do projeto: Verde está no Git, Vermelho está só no Projeto
```Bash
git status
```
* ...(main) $ Adiciona todos as pastas do projeto de uma só vez do Projeto para Git
```Bash
git add .
```
* ...(main) $ Adiciona pastas individuais do Projeto para Git
```Bash
git add ".nomePasta"
```
* ...(main) $ Verificar status dos arquivos: Deve está tudo Verde está no GitHub
```Bash
git status
```
* ...(main) $ De forma resumida, indicar o que foi alterado no Projeto >> o Git
```Bash
git commit -m "Descrever o que foi alterado"
```
* ...(master) $ Conecta o GitHub com o Git, pegar o Link no GitHub, verificar #Config 06
```Bash
git remote add origin https://github.com/otanerifpb/nome_projeto
```
* ...(main) $ Vai mostrar o histórico de comites até o momento, ou seja a linha do tempo
```Bash
git log --oneline
```
* ...(main) $ Upload tudo do Git para o GitHub, pode solicitar user e senha
```Bash
git push origin main
```
** Para ver o código no GitHub basta acessar a pasta e dar um F5 para atualiza.**
	
# Config 07 - Demais Commit, atualizar um projeto do Git >> GitHub
**Usar cmd do Bash na pasta do projeto**
* ...(main) $ Primeiro devemos atualizar do GitHub para o Projeto/Git
```Bash
git pull origin mains
```
* ...(main) $ Verificar status das pastas do projeto: Verde está no Git, Vermelho está só no Projeto
```Bash
git status
```
* ...(main) $ Adiciona todos as pastas do projeto de uma só vez do Projeto para Git	
```Bash
git add .
```
* ...(main) $ Verificar status dos arquivos: Deve está tudo Verde está no GitHub
```Bash
git status
```
* ...(main) $ De forma resumida, indicar o que foi alterado no projeto para o Git
```Bash
git commit -m "Descrever o que foi alterado"
```
* ...(main) $ Vai mostrar o histórico de comites até o momento, ou seja a linha do tempo	  
```Bash
git log --oneline
```
* ...(main) $ Enviar tudo do Git para o GitHub, pode solicitar user e senha
```Bash
git push origin main
```

# Config 08 - Demais Commit, atualizar um projeto do GitHub >> Git
* ...(master) $ Download o que está no GitHub para o Projeto/Git
```Bash
git pull origin main
```
* ...(main) $ Para mudar de "Master" para "Main" no projeto para ter o novo padrão do GitHub
```Bash
git checkout -b main
```
* ...(main) $ Verificar status das pastas do projeto: Verde está no Git, Vermelho está só no Projeto
```Bash
git status
```
* ...(main) $ Atualiza tudo que está indicando em vermelho do Projeto/GitHub >> Git
```Bash
git add .
```
* ...(main) $ Verificar status dos arquivos: Deve está tudo Verde está no Git
```Bash
git status
```
* ...(main) $ Vai mostrar o histórico de comites até o momento, ou seja a linha do tempo
```Bash
 git log --oneline
```

# Config 09 - Baixar um projeto do GitHub Renato para o PC
* Passo 01 - Acessar o Projeto no GitHub Renato
* Passo 02 - Selecionar > Code
* Passo 03 - Escolher > Download ZIP
* Passo 04 - Selecionar o local no PC > Salvar > descompactação do projeto

# Congig 10 - Criar um CLONE de um projeto do GitHub Renato para o PC(Git)
* Link [Criar um Clone do GitHub](https://www.youtube.com/watch?v=w7JF8XSlO2M)
* Acessar a WorkSpace "wsifpb"  
```Bash
 cd nomeWorkSpaceProjeto
```
* Acessar a pasta onde foi instalado o ambiente virtual
```Bash
 cd nomePastaProjeto
```
**Acessar o Projeto no GitHub Reanto > Selecionar > Code > Clone > HTTPS > Copiar o Link "https://github.com/..."**
* Para colar o link >> Ctrl + Shift + v > click em enter
**Pode ser que seja solicitado user e senha**
```Bash
 git clone https://github.com/...
```
* Para verificar se foi baixado do GitHub e testa se o clobe deu certo, listar o que tem na pasta
```Bash
 $ ls
```
* Para acessar o Projeto que foi feito o Clone e agora esta no PC
```Bash
 cd nomeProjeto 
```
* Para verificar o que tem dentro da pasta do Projeto
```Bash
 ls
```

# Config 11 - Criar um FORK de um projeto do GitHub Original para GitHub Renato
* Link [Como criar um FORK do GItHub](https://www.youtube.com/watch?v=jSFkCqMCuLE)
* **FORK: cópia do GitHub Original > GitHub Renato** 
* **CLONE: Cópias no GitHup Reanto > PC, se o CLONE for de uma GitHub Original(terceiro), eu não posso atualizar ou alterar**
* **PUSH: é quando envio as atualizações do meu PC para GitHub Reanto**
* **PULL REQUEST: quando envio as atualizações do GitHub Renato para o GitHub Original**
* Acessar > GitHub Original > Seleciona o projeto > Fork 
* .....Repository name: ------adicionar outro nome se quiser ou permanecer o original
* .....Description: ----------pode informar porque esta realizando o Fork
* .....[x]Copy the main ... --já esta marcado por default
* .....> Create fork  --------neste momento é criado uma cópia de um projeto do GitHub Original para GitHub Meu	

# Config 12 - Atualizar um Projeto do GitHub Renato para GitHub Original
* **Vamos realizar um Pull Request**
* **A atualização do Git para o GitHub Renato pode demorar um pouco para atualizar no servido**
* **Para as atualizações ocorrerem no GitHub Original, é necessário o prorpietário aceitar a atualização**
* > GitHub Renato > Seleciona o projeto > Contribuinte > Open pull request
* Add a title: -----------colocar um titulo que vai identificar o tipo de atualizaçlão
* Add a description: -----descrever o que foi realizado na atualização e explicar com mais detalhes
* > Create pull request --neste momento será enviado as atualizações do GitHub Meu para o GitHub Original
* > GitHub Original > selecionar o Projeto > Pull request
* > Na mensagem de atualização > abrir o código > ver o que foi alterado
* > Marge pull request --neste momento está sendo aceito as atualizações do GitHub Meu no GitHub Original

# Config 13 - README, formatação do texto
* Usar o # Título --------------------------------------Ao usar este caracter, texto tem destaque + uma linha abaixo (equivale h1)
* Usar o ## Subtítulo ----------------------------------Caracter duplo, fica com uma fonte menos + uma linnha depois do texto (equivale h2)
* Usar a 1craze + link + 1craze ------------------------Cria um caixa no link
* Usar as 3craze bash + texto + 3craze -----------------Cria uma caixa com botão "copiar" ex. ```bash comando```
* Usar [Nome da url](http://...) -----------------------Mostra apenas o nome que acessa o link
* Usra o *Texto em Itálico* ou _Texto em Itálico_ ------Deixa o texto itálico
* Usra o **Texto em Negrito** ou __Texto em Negrito__ --Deixa op texto em negrito
* Usra o 1. Item 1 -------------------------------------Lista ordenada
* Usar o * Item 1 --------------------------------------Lista não ordenada
* Usar o ![Texto Alternativo](URL da Imagem) -----------Para usar uma imagem com um link
