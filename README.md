# Uai!Tecas

Esse repositório contém a biblioteca de esquemáticos e footprints utilizados pela equipe Uai!rrior em nossos projetos. A ideia dele é criar um padrão unificado de componentes para evitarmos erros em nossos projetos e diminuir a necessidade de criar novas bibliotecas em todo início de projeto.

## Organização

A nomeclatura e os parâmetros dos componentes seguem um padrão que pode ser observado em *[Schematics/Lib_referencia](Schematics/Lib_referencia.SchLib)*. Além disso, a biblioteca está organizada pelos tipos de componentes listados abaixo:


```
Capacitor
Diodo
Diversos 
Driver
Header
Indutor
Microcontrolador
Mosfet
Pad
Resistor
Voltage Regulator
```

## Utilização

Para utilizar nossa biblioteca, os seguintes passos podem ser seguidos:

1. Baixar a nossa biblioteca, a partir de Code -> Download ZIP ou Clonar nosso repositório, que é uma maneira de ter sempre a nossa biblioteca atualizada. Para isso, pode baixar o GitHub em seu Desktop (<a href="https://git-scm.com/downloads" target="_blank">Download GitHub</a>). Após fazer isso, terá baixado o próprio Git, o terminal Git bash e a interface gráfica Git GUI. Pode ir até uma pasta à sua escolha e abrir o git bash nela (dessa forma, o caminho até ela já terá sido feito), depois pode utilizar o comando:

```
git clone https://github.com/EltUairrior/Uai-Tecas.git
```
Assim que dar o comando, será requisitado seu usuário e senha do GitHub.

2. No nosso caso, utilizamos o software Altium Designer para nossos projetos. Nele, basta abrir a biblioteca (File -> Open Project -> <Pasta onde se encontra a Uai-Tecas>), dar um clique direito sobre ela e ir em "Compile Integrated Library Uai!Tecas.LibPkg". Dessa maneira, vai ter já em mãos a biblioteca pronta para uso em seus esquemáticos e PCB's. Caso não apareça essa opção, vá em Panels, na parte inferior direita, Components, nas três barrinhas ao lado da barra principal de pesquisa da janela que irá aparecer e clique na primeira opção ("File-based Libraries Preferences..."), vá em Installed -> Install e procure onde está a biblioteca. Depois, pode apertar o botão Close e tentar compilar a Uai-Tecas novamente.
  
3. Sempre que a biblioteca sobrer atualizações, pode, através do Git bash, utilizar o comando:
  
```
git pull 
```
Ainda, se preferir, pode também fazer uso do comando:
  
```
  git refresh remote-branch-name
```
  Se divirta utilizando os componentes nos esquemáticos e layouts de seus projetos!

## Contribuindo

Os componentes são limitados aos usados pela equipe, mas caso você encontrem algum erro em nossa biblioteca um Pull Request será muito bem vindo!

