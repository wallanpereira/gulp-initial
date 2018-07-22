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
src/  -> Nosso diretório source.
  components/ -> Onde ficara nossos componentes
  fonts/ -> fontes do projetos ( opcional )
  img/ -> Imagens do projeto.
  js/ -> Arquivos .js para o projeto.
  scss/ -> Estilização padrão para o projeto.
gulp.paths.json -> Configuração do caminho para arquivos e diretórios do projeto.
gulpfile.js -> Configurações de cada dependência instalada.
package.json -> Dependências instaladas.
