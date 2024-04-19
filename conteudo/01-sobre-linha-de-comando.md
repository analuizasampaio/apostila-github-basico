[<- Voltar para o início](../README.md)

# Linha de comando

<img src="../imgs/cli/cli.gif" alt="Logo do git" />


## Índice
- [O que é linha de comando ?](#o-que-é-linha-de-comando)
- [Por que é importante ?](#por-que-é-importante-)
- [Comandos básicos do terminal](#comandos-básicos-do-terminal)

### O que é linha de comando ?

É aquela tela preta que aparece nos filmes, normalmente com alguém hackeando algum sistema. Mexer com o terminal assusta um pouco porque ele não é nem um pouco visual. Mas é muito simples mexer nele. Sabe quando a gente arrasta arquivos para uma pasta ou cria uma pasta nova? No terminal você faz tudo isso também, mas sem interface gráfica. A gente insere comandos, e ele executa.

### Por que é importante ?

Na linha de comando você controla melhor o que está rolando com o seu computador - inclusive o versionamento. O git é sempre usado através de linha de comando. (O GitHub tem ferramentas visuais para uso do Git, mas é importante saber se virar pela linha de comando)

### Comandos básicos do terminal

Esses comandos servem para para listar arquivos e navegar entre pastas dentro do computador.

#### Navegação


| Comando | Descrição | Exemplo de Uso |
|---------|-----------|----------------|
| `ls`    | Listagem - Exibe o conteúdo do diretório atual. | `ls` |
| `cd`    | Navegação - Muda o diretório atual. | `cd /caminho/do/diretorio` |
| `pwd`    | Pasta atual - Exibe o caminho atual. | `pwd` |


#### Arquivos/Diretorio(pastas)

| Comando | Descrição | Exemplo de Uso |
|---------|-----------|----------------|
| `touch` | Cria um novo arquivo. | `touch novo_arquivo.txt` |
| `cat`   | Exibe o conteúdo de um arquivo. | `cat arquivo.txt` |
| `cp`    | Copia um arquivo ou diretório. | `cp arquivo.txt destino/` |
| `mv`    | Move um arquivo ou diretório. | `mv arquivo.txt destino/` |
| `rm`    | Remove um arquivo ou diretório. | `rm arquivo.txt` ou `rm -r pasta/` |


#### Outros

| Comando | Descrição | Exemplo de Uso |
|---------|-----------|----------------|
| `help`  | Mostra a ajuda para um comando. | `help cd` ou `help ls` |
| `clear` | Limpa a tela do terminal. | `clear` |
| `echo`  | Exibe uma mensagem na tela ou redireciona para um arquivo. | `echo "Olá, mundo!"` ou `echo "Texto" > arquivo.txt`

Muitos desses comandos serão usados no git, mas para saber os exclusivos do git e github procure [sobre linhas de comando git](/conteudo/03-sobre-linhas-de-comando-git.md)

[<- Conceitos Introdutórios](/conteudo/00-conceitos-introdutorios.md) | [Mais sobre Git ->](/conteudo/02-sobre-git.md)