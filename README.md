# dio-desafio-github-eduzz

Language: Portugues Brazil

<h1>Introduação

<p>Este repositorio é primeiro desafio do bootcamp eduzz conduzido pela "DIO"<p>

<p>Objetivo desse desafio era criar o primeiro repositorio no github utilizando o git do meu computador.<p>

<p>Como parte da inciativa, vou colocar abaixo orientações de como subir o seu repositorio utilizando o Ubuntu na versão 20.04, fazendo algumas correções referente a explicação do curso da "Dio"<p>

**Importante: parto do presuposto que você já tenha uma conta no github com o repositorio criado.** <p>

<h2>Instalando o Git (Atualizando)<h2>

Por padrão, o git já vem instalado no Ubuntu, porem em sua versão básica. Então precisamos atualizar ele para a versão mais atual, 2.33 ou superior.

Antes de começar espero que você já tenha criado uma conta no github, nesse passo a passo não iremos abordar como criar lá. 

*Importante antes de começarmos, não use o superadmin, ele ira dar problema em subir o seu repositorio*

Vamos verificar qual versão do git tem no seu computador, com o códiogo abaixo.

Não é necessario sar o git bash no Ubuntu.

**Passo 1** - Abra o terminal no Ubuntu, utilizando o atalho no teclado *Ctrl + Alt + T*. 

Vamos verificar se a versão git do seu computado é a 2.33 ou superior. Caso não sejá, será necessaria atualizala, seguindo os passos abaixo.


**Passo 2** - Digite o código abaixo, para saber qual a versão do seu git.

'''Linux
git --version
'''

Caso a sua versão seja 2.33 ou superior, vá para o passo 8. Se não, continue os com os passos abaixo.

Para atualizar a versão será necessario primeiro desinstalarmos a atual.

**Passo 3** - Digite o código abaixo para desinstalar o git atual. 

'''Linux
sudo apt remove git
'''

Agora, vamos instalar a versão correta, adicionando o repositorio mais atualizado do git.


**Passo 4** - Para adicionar o repositorio mais atualizado do git, digite o código abaixo. 

'''Linux
$ add-apt-repository ppa:git-core/ppa'
'''
Agora é só atualizar os pacotes do computador para que na execução do código seja usado o novo repositorio.

**Passo 5** - Digite o código abaixo para atualizar os pacotes do computador. 

'''Linux
apt update
'''

Agora que esta tudo atualizado vamos instalar o git, será insatalada a verssão mais atual.

*Passo 6* - Digite o codigo abaixo, para instalar o git. 

'''Linux
apt install git
'''

Agora devemos estar com ele atualizado, vamos conferir.


**Passo 7** - Digite o código abaixo, para verificar a versão do git após todos o passos.

'''Linux
apt git --version
'''

Pronto, agora vamos subir o primeiro arquivo no github. Caso a versão ainda não esteja correta sugiro se comunicar comigo nos comentarios.

<h2>Subindo arquivos no Github<h2>

Primeira coisa é decidir, na seu computador, onde você quer colocar o seu arquivo , pode ser em qualquer lugar, porem você precisa primeiro navegar para a pasta.

Tem duas formas, via terminal  ou  via interface com terminal.

Para facilitar, vamos usar um pouco da interface grafica, navegue até a pasta e clique com o botão direito

**Passo 8**- Utilize o botão direito do mouse na pasta onde quer subir o seu primeiro arquivo, e selecione a opção  **Abrir no terminal**.
 

Já com o repositorio criado. Vamos criar incluir novos arquivos no repositorio, já criado
**Passo 9** -  Acesse o seu repositorio no github e clique no botão verde **Code** o copie a opção em Html.

Vamos fazer um clone desse repositorio para subir novos arquivos de forma mais simples. Sem a necessidade de colocar um caminho, pois ele já esta setado.

**Passo 10** - No terminal vamos clonar o repositorio, digite o código abaixo **não o executando**.
'''Linux
git clone 
'''

**Passo 11** - Com o código acima colocado no terminal, de espaço e no teclado **Ctrl +  Shift + V**, para colar o endereço do repositorio, **agora pode executar**.

**Passo 12** -  Agora abra a pasta cloanada e coloque qualquer arquivo novo. Sejá pelo terminal  ou na interface com comando cd. 

**Passo 13** - Adicione esse novo arquivo, utilizando o código abaixo

'''Linux
gi add * 
'''

**Importante lembrar do colocar o espaço entre <em>add<em> e a <em>estrela<em>**

Agora só precisamos fazer o commit para deixar tudo certo e suir

**Passo 14** - Vamos dar comit no nosso arquivo, copie o código abaixo, **não o execute**

'''Linux
git commit -m
'''

**Passo 15** - Coloque entre aspas o texto para identoficar esse novo commit. Agora **execute o programa**. Exemplo abaixo.

'''Linux
git commit -m "Novo texto"
'''

Finalmente, vamos subir ele

**Passo 16** - Digite o codigo para subir a nova versão do código para o github

'''Linux
git push
'''  

**Parabens você subiu o seu primeiro código no github




