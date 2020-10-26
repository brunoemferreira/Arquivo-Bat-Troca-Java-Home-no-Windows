<h2 align="center">
    <img alt="Logo Java Bat" width="200px" title="#LogoJavaBat" src="./assets/batjava.png" />
</h2>

<h2 align="center">Troca Java Home</h2>

## 💻 Sobre o Arquivo

Este é um arquivo que foi desenvolvido para máquinas Windows que possuem várias versões do Java instaladas, ele tem a função de quando executado trocar a versão do java que está na Variável de Ambiente JAVA_HOME da sua máquina para a versão que está informada no arquivo.

## Entendendo o Arquivo
Atenção : Abaixo estou exemplificando utilizando a versão do java 14, verifique quais versões do java voce possui instaladas e faça um arquivo bat desse para cada versão passando seus caminhos respectivamente e sempre que for utilizar uma versão execute o bat da versão escolhida. 

Ex de Nome do arquivo : TrocaJavaHome_v14.bat

````bash

REM O Comando @echo off ele Faz com que o prompt fique oculto durante toda execução
@echo off

REM A linha abaixo seta o caminho informado para a variável de ambiemte JAVA_HOME
set JAVA_HOME=C:\Program Files\Java\jdk-14.0.1

REM A linha abaixo adiciona JAVA_HOME ao path
set Path=%JAVA_HOME%\bin;%Path%

REM Dá uma mensagem que a versão informada no path está ativa
echo Java 14 ativo.

````

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
- S.O ser Windows
- [Git](https://git-scm.com)
- As versões do Java de sua preferência. Baixe aqui [Java](https://www.java.com/pt-BR/download/)
- Editor de Código/Texto de sua preferência. Eu uso o [VSCode](https://code.visualstudio.com/)


### 🎲 Rodando o Arquivo

```bash
# Clone este repositório
$ git clone https://github.com/brunoemferreira/Arquivo-Bat-Troca-Java-Home-no-Windows.git

# Abra o arquivo com o Editor de sua preferência faça as alterações conforme sua versão do Java, salve e é só executar :) 
```

## 😯 Como contribuir para o projeto

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`
> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](https://github.com/firstcontributions/first-contributions)


## 📝 Licença

Este Arquivo esta sobe a licença MIT.

Feito com ❤️ por Bruno Eduardo 👋🏽 [Entre em contato!](https://www.linkedin.com/in/brunoemf/)

