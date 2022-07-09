# Git

###GUI
Grafic User Interface: Interface gráfica do usuário é uum tipo de interface que permite a interação com dispositivos digitais por meio de elementos gráficos.

###CLI
Command-line Interface: Inteface de linha de comando que processa os comandos que serão enviados para um programa na forma de linhas de texto. EX Git Bash.

###Comandos 

**cd(Windows)/cd(Linux)** - change directory: muda para o diretório solicitado.

**dir(Windows)/ls(Linux)** - directory: lista os os diretórios presentes dentro so diretório atual.

**mkdir(Windows)/mkdir(Linux)** - make directory: cria uum diretório.

**del(Windows)/rm(Linux)** - delete: deleta os arquivos do diretório.

**rmdir(Windows)/rm-rf(Linux)** - remove directory: apaga o diretório com todo seu conteúdo.

**git init** - inicia repositório no Git.

**git add** - adiciona alterações no repositório.

**git add (nome do arquivo)** - coloca o arquivo em _Stage_.

**git add** * - Coloca em _Stage_ todos os arquivos que não começam com **.** (ocultos). 

**git add .** - coloca em _Stage_ todos os arquivos, mesmo os que começam com **.** (ocultos).

**git commit** - cria um commit.

**git status** - retorna o status do arquivo.

**git push** - envia o conteúdo no respositório local para o repositório remoto.

**git pull** - Trás o conteúdo do repositório remoto para o repositório local.

**cd ..** - vai para o repositório pai.

**-a** - flag _-a_ permite comando incluindo todos os diretórios, inclusive ocultos.EX: ls -a, git add -a.

**Ctrl+L/ cls** -  limpa a janela de coloca o cursor na primeira linha.



##GitHub

- SHA1
- Objetos fundamentais
- Sistemas distribuídos
- Segurança


#### SHA1 

- _Secure Hash Algorithm_ é um conjunto de funções criptograficas projetadas pela NSA (Agência de Segurança Nacional dos EUA)
- Gere um conjutno identificador de 40 dígitos.
- É uma forma curta de representar um arquivo.

#### Objetos Fundamentais 

**Blobs** - Contém o tipo (_blob_), o tamanho do arquivo, \0, o conteúdo que são os metadados do Git e seu SHA1. É o bloco básico.

**Trees** - Armazena e aponta para _blobs_ diferentes ou outras _trees_. Comtém \0, o nome do arquivo . responsável por montar toda a estrutura de onde estão os arquivos. Seu próprio SHA1 também é alterado caso haja alguma edição em seus metadados (_incluindo os dos seus filhos_).

**Commit** - Aponta para uma _tree_, para um parente (_commit anterior_), autor, mensagem e timestamp. Também possui seu próprio SHA1.

#### Sistemas distribuídos

#### Segurança