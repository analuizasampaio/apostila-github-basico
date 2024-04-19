### Criando e deletando pastas e arquivos pelo terminal Git Bash

#### a) Crie uma pasta, entre na pasta, crie um arquivo de texto e insira uma frase

#### b) Entre na pasta cria anterior, apague o arquivo, volte uma pasta e apague a pasta

> Erros de digitação e formatação dos comandos no git bash podem acarretar em problemas, lembrem de verificar a grafia caso algum comando dê errado. Para relembrar os comandos é só [voltar ao material sobre comandos no terminal](../../conteudo/01-sobre-linha-de-comando.md)

> Caso o arquivo ou pasta tenha algum erro de digitação ou não exista, também ocorrerão erros. Tentem sempre verificar se estão na pasta correta utilizando `pwd` e se está tentando passar o nome correto dos arquivos e pastas, liste os itens para pegar o nome correto utilizando `ls`.

Você deve ter instalado o Git na sua máquina.
Na Área de Trabalho (Desktop), clique com o botão direito e selecione ***Git Bash here***

Este é o ***Git Bash***. É como um terminal.
Então, executamos ações por meio de instruções de linha de comando.
Seguem abaixo algumas ações básicas para nos habituarmos com o terminal Git Bash.

- `pwd`: *print working directory*, mostra o caminho onde você se encontra
- `ls`: *list*, lista o conteúdo da pasta atual
- `mkdir`: *make a directory*, cria uma nova pasta. Precisa colocar o nome da nova pasta. Ex: `mkdir nomePastaNova`
- `cd`: change directory, entrar em uma pasta. Precisa indicar o nome da pasta que quer entrar. Ex: `cd nomePasta`
- `cd ..`: voltar uma pasta acima
- `echo`: *echo*, eco que cria um arquivo. Precisa indicar o conteúdo e o nome do arquivo. Ex: `echo "oi" > index.html`
- `rm`: *remove*, deleta um arquivo. Precisa indicar o nome do arquivo. Ex: `rm index.html`
- `rm -r` ou `rm --recursive`: deleta uma pasta. Precisa indicar o nome da pasta e deletar recursivamente. Ex: `rm -r nomeDaPasta`
