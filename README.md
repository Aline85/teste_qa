# teste_qa
Teste de QA

Primeiro passo

Instalar o Python 3

Ir para a página https://www.python.org/ , selecionar Downloads no menu.

Click no botão Download Python se caso seu sistema operacional for Windows e baixe o executável. Se caso você utiliza outro sistema operacional, clique no nome do sistema operacional logo abaixo do botão.

Vá para a pasta onde está o arquivo executável e clique duas vezes no arquivo executável.

Selecione o Add Python 3.8 to Path e clique no botão Customize Installation.

Na tela Advanced Options, selecione Install for all users.

No campo Customize install location deixe nesse formato C:\Python38, para instalar no C:.

Clique em install e pronto agora está instalado o python3.

Para verificar que está instalado abra o Prompt de Comando e digite python --version.

Verifique se o pip foi instalado usando esse comando pip --version.

Segundo passo

Instalar Visual Studio Code

Ir para a página https://code.visualstudio.com/

No botão Download for Windows tem uma seta, clique nessa seta.

Clique no link, que é um ícone de seta para baixo do Sistema operacional que você tem na versão Stable.

Vai fazer o download, vá para a pasta onde está instalado o arquivo executável.

Na tela de Selecionar Tarefas Adicionais, selecione Criar um atalho na área de trabalho, Adicione a ação “Abrir com Code” ao menu de contexto de arquivo do Windows Explorer, Adicione a ação “Abrir com Code” ao menu de contexto de diretório do Windows Explorer e Adicione em PATH (disponível após reiniciar).

Clique no botão Install.

Pronto instalado o Visual Studio Code

Agora vamos adicionar umas extensões

No menu da esquerda clique em Extensions, digite python e instale, depois digite robot framework que tem o ícone do robot framework de Tomi Turtiainem e instale.

Como um plus você pode instalar o material icon theme e hyper term theme de Hasse Nasse.

 

 

Terceiro passo

Instalar o Console Emulator somente para o sistema operacional Windows.

Ir para a página cmder.net

Clique no botão Download Full

Abra a pasta onde foi instalado o arquivo zip

Com o botão direito do mouse clique em extrair para “cmder/”

Na pasta clique com botão direito para recortar.

No C: crie uma pasta chamada Tools e cole essa pasta do cmder dentro da pasta Tools.

 

Quarto passo

Instalar Robot Framework

No cmder ou Console Emulator, crie uma pasta c:\projeto\robot

Depois entre na pasta com o comando cd c:\projeto\robot\

Abra o visual studio code e clique em File > Open folder abra a pasta que você criou do robot anteriormente.

Para instalar o robot framework no sistema, vá para o console emulator digite esse comando pip install robotframework

Verificar se o robot está instalado digite esse comando robot --version

Instalar a biblioteca do selenium digite o comando pip install robotframework-seleniumlibrary ou pip install --upgrade robotframework-seleniumlibrary (atualizar a biblioteca)

Para instalação da biblioteca do request para teste de API: pip install -U robotframework-requests

para desinstalar a biblioteca pip uninstall robotframework-requests.

Para verificar o que significa cada comando pip install --help

Fazer o download do chromedriver nessa página https://sites.google.com/a/chromium.org/chromedriver/home

Verifique qual a versão do seu chrome no canto superior direito nos 3 pontinhos selecione ajuda > sobre o google chrome  vai aparecer a versão atualizada parecida com isso O Google Chrome está atualizado Versão 85.0.4183.83 (Versão oficial) 64 bits.

Voltar a página e faça o donwload da versão  Latest stable release: ChromeDriver 85.0.4183.87 que é compatível.

 Clique no arquivo que é compatível com seu sistema operacional, vá para a pasta onde foi o arquivo e extraia ele.

Recorte o arquivo executável e cole na pasta Windows.
