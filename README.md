# Desafio de Projeto sobre Git/GitHub da DIO 

## O que é GIT?
- O ***Git*** é um sistema de controle de versão distribuído e amplamente adotado, nele você pode criar e editar arquivos. Sempre quando alguém disponibiliza sua parte do projeto no Git, ele gerencia as alterações feitas e guarda um histórico.
-  Seu criador principal é ***Linus Torvalds***.
- Ele é um software que o design dele é voltado para outro tipo de programa. Ele é um ***CLI (Comand Line Interface)***, que é diferente ***GUI (Graphic User Interface)***, ou seja, ele não tem uma interface gráfica, a forma de usar o Git é por ***linha de comando***.

## O que é GitHub?

- ***GitHub*** é uma plataforma para gerenciar seu código e criar um ambiente de colaboração entre desenvolvedores, que utiliza o Git com sistema de controle.

- Por mais que seja utilizado majoritariamente por desenvolvedores, o GitHub vem atraindo outras equipes que querem se beneficiar com o sistema de controle de versão.

## Como funciona o GIT?
- O Git usa o SHA, um algoritmo de encriptação que gera um conjunto de caracteres identificador de 40 dígitos para identificar os arquivos de forma segura e rápida.
- A sigla **SHA** significa Secure Hash Algorithm (Algoritmo de Hash Seguro), é um conjunto de funções hash criptográficas projetadas pela NSA (Agência de Segurança Nacional dos EUA).

## Comandos básicos do GIT:

### **Git config**
- Configura o nome do autor e endereço de email que serão utilizados nos seus commits.

    ``
    git config --global user.name "Nome"
    ``

    ``
    git config --global user.email seuemail@email.com
    ``

### **Git init**
- Comando utilizado para criar o repositório do seu projeto.

    ``
    git init <nome do repositório>
    ``

### **Git clone**
- Cria uma cópia de um repositório remoto para seu computador.

    ``
    git clone <url do repositório>
    ``

### **Git add**
- Adiciona um arquivo específico para a fila de commit do GIT.

    ``
    git add <nome do arquivo>
    ``
- Adiciona todos os arquivos para serem incluídos no commit.

    ``
    git add .
    ``

    ou

    ``
    git add *
    ``
### **Git status**
- Mostra as alterações do seu projeto ou os arquivos que precisam ser incluídos no commit.

    ``
    git status
    ``

### **Git commit**
- Cria um commit com mensagem.

    ``
    git push <nome remoto> <branch>
    ``

### **Git push**
- Envia as alterações feitas para o servidor remoto.

    ``
    git push <nome remoto> <branch>
    ``


