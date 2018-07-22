# gulp-initial
Gulp para início de projeto Web

Tutorial para Linux

Instalando o nodejs
$ sudo apt install nodejs

Instalando o npm
$ sudo apt install npm

Instalando o gulp global, para que fique mais facil usar o npm install em um projeto com gulp.
  Primeiro crie um diretorio temporario, que iremos usar para instalar o gulp global.
 $ mkdir tempGulp
 
  Entre no diretorio
 $ cd tempGulp/

  Agora dentro do diretorio, execute o seguinte comando abaixo:
 $ sudo npm install gulp-cli -g
  Logo irá aparecer as dependências sendo instaladas.
 
  Pronto o gulp agora está inatalado em seu sistema globalmnete.
 
  Iremos apagar o diretorio temporario agora.
  Para isso vamos voltar um diretorio antes e usar o seguinte comando:
 $ cd ..
 $ rm -Rf tempGulp/

  Agora no nosso projeto, vamos precisar apenas utilizar o comando:
 $ npm install
  Com isso irá buscar todas as nossas dependências e instalar cada uma.
