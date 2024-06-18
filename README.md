# helloworld
Meu primeiro Script Shell

Antes de mais nada para poder criar script executáveis e preciso “elevar” o nível de usuário para poder executar o mesmo, neste caso tenha acesso do usuário “root”, com ele pode realizar tudo em seu sistema, então nunca se esqueça:

“Com grandes poderes, vem grandes responsabilidades” (Tio Ben)

Passo 1: Crie um arquivo vazio chamado “HelloWorld” no terminal.
Podemos criar um arquivo vazio usando os seguintes comandos:

$ touch HelloWorld.sh

Onde:
touch: É usado para criar um arquivo vazio.
HelloWorld.sh: HelloWorld é um arquivo com extensão .sh do arquivo executável do shell unix.

Passo 2: Abra o arquivo.
Aqui abriremos nosso arquivo criado, utilizando os seguintes comandos:

$ nano HelloWorld.sh

Onde:
nano: É usado para abrir arquivos em um editor de texto (ou seja, GNU nano)
O editor está aberto, escreva o seguinte código em um editor de texto:

#!/bin/sh
# Este é um programa bash para exibir Hello World.
echo " Hello World "

Onde:
#! : É conhecido como shebang.
/bin/sh: É o caminho executável do shell do sistema.
#: É usado para escrever comentários.
echo: É usado para exibir texto na tela.

Etapa 3: dê permissão para executar o script.
Escreva o comando para dar permissão de execução:

$ chmod +x HelloWorld.sh

Onde:
chmod +x: É usado para tornar o arquivo executável.

Etapa 4: execute o script.
Finalmente execute o script com o comando:

$ ./Helloworld.sh  

Saída:
Hello World
