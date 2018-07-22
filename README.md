# gulp-initial
Gulp para início de projeto Web

Tutorial para Linux

Instalando o nodejs
$ sudo apt install nodejs

Instalando o npm
$ sudo apt install npm

Instalando o gulp global, para que fique mais facil usar o npm install em um projeto com gulp.
  Primeiro crie um diretório temporario, que iremos usar para instalar o gulp global.
 $ mkdir tempGulp
 
  Entre no diretorio
 $ cd tempGulp/

  Agora dentro do diretório, execute o seguinte comando abaixo:
 $ sudo npm install gulp-cli -g
  Logo irá aparecer as dependências sendo instaladas.
 
  Pronto o gulp agora está inatalado em seu sistema globalmnete.
 
  Iremos apagar o diretório temporario agora.
  Para isso vamos voltar um diretório antes e usar o seguinte comando:
 $ cd ..
 $ rm -Rf tempGulp/

  Agora no nosso projeto, vamos precisar apenas utilizar o comando:
 $ npm install
  Com isso irá buscar todas as nossas dependências e instalar cada uma.


===== ESTRUTURA DO PROJETO =====
<p>
src/  -> Nosso diretório source.<br>
  &nbsp;&nbsp;components/ -> Onde ficara nossos componentes<br>
  &nbsp;&nbsp;fonts/ -> fontes do projetos ( opcional )<br>
  &nbsp;&nbsp;img/ -> Imagens do projeto.<br>
  &nbsp;&nbsp;js/ -> Arquivos .js para o projeto.<br>
  &nbsp;&nbsp;scss/ -> Estilização padrão para o projeto.<br>
gulp.paths.json -> Configuração do caminho para arquivos e diretórios do projeto.<br>
gulpfile.js -> Configurações de cada dependência instalada.<br>
package.json -> Dependências instaladas.<br>
 </p>
