[<- Voltar para o início](../README.md)

# Github 

## Índice
- [Disponibilizar o projeto para o mundo](#disponibilizar-o-projeto-para-o-mundo)
- [Github](#github)
- [Diferenaça entre git e github](#diferença-entre-git-e-github)
- [Branchs](#branchramificação)

### Disponibilizar o projeto para o mundo

O git nos ajuda a versionar nossos arquivos localmente, porém para podermos trabalhar em equipe e manter nossos arquivos seguros precisamos disponibilizar nosso projeto online, e para isso existem as hospedagens de repositórios, sites que são capazes de manter a lógica de versionamento do git:

<img src="../imgs/github/hospedagem.png" alt="Logo de 3 hospedagens disponíveis: github, gitlab e bitbucket" />
Esses são exemplos das principais hospedagens de repositórios disponíveis: Github, Gitlab e Bitbucket.

Nesse curso utilizaremos o github.

### Github
#### O que é?

GitHub é uma plataforma de hospedagem de código-fonte com controle de versão usando o Git. Ele permite que programadores ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo. É a partir dele que hospedaremos nosso repositório local para um online. É uma espécie de rede social muito utilizada principalmente por desenvolvedores para divulgação de seus trabalhos ou para que outros programadores contribuam com projetos.

Resumidamente: Você trabalha na sua máquina e salva versões do seu código no GitHub, e também pode baixar cópias do código que está hospedado GitHub para a sua máquina.
GitHub é amplamente utilizado por programadores para divulgação de seus trabalhos ou para que outros programadores contribuam com projetos.

Vamos nos cadastrar para conseguirmos subir nossos códigos para um repositório online.

Após o cadastro configuraremos nosso usuário no gitbash para definir a autoria das nossas modificações:
Para adicionar usuário:
```
git config --global user.name "Seu nome"
git config --global user.email “email@gmail.com” 
```

```
git config --list
```

Para remover usuário:
```
git config --global --unset user.name "Seu nome"
git config --global --unset user.email “email@gmail.com” 
```

#### Por que é importante?
- Portfólio - É um site seguro para guardar e mostrar seus projetos. Não é incomum as empresas pedirem apenas seu GitHub antes de uma entrevista de emprego.
- Organização - Permite que todo mundo trabalhe no mesmo projeto (seja um projeto da sua empresa ou um Open Source).
- Ferramentas - Porque oferece funcionalidades extras ao git, como interface visual, documentação, bug tracking, feature requests, pull requests, etc.
- Versatilidade: Você pode guardar qualquer tipo de arquivo no git/Github, não necessariamente código. Por exemplo, essa aula que estamos vendo. O Github utiliza uma linguagem chamada Markdown, que permite criar listas, links, ancôras, adicionar imagens, vídeos, gifs...

### Diferença entre git e github
> A diferença entre git e github é que o git é só uma ferramenta para versionar projetos, enquanto o github é o site no qual você colocará esses projetos versionados. uma analogia válida seria que o git é seu pincel e tintas enquanto o github é um museu.
- [Fonte: Ratamero](http://www.ratamero.com/blog/git-e-github-parte-1-o-que-sao-e-como-usar/)

#### Vamos praticar?
- [ ] [Exercicio 2](/exercicios/02-exercicio-git-config/exercicio2.md)
- [ ] [Exercicio 3](/exercicios/03-exercicio-local-remoto/exercicio3.md)
- [ ] [Exercicio 4](/exercicios/04-exercicio-clone/exercicio4.md)
- [ ] [Exercicio 5](/exercicios/05-exercicio-pull/exercicio5.md)

### Branch(ramificação)
![img.png](/imgs/git-flow.png)
#### O que são Branches?
Branches são versões alternativas de um repositório de código. Cada branch representa uma linha de desenvolvimento independente, permitindo que várias pessoas trabalhem em diferentes partes do código simultaneamente sem interferir no trabalho umas das outras.

#### Por que usar Branches?
- Isolamento de Funcionalidades: Permite desenvolver novas funcionalidades ou corrigir bugs em um ambiente isolado, sem afetar o código principal.
- Colaboração: Facilita o trabalho em equipe, pois cada membro pode ter sua própria branch para trabalhar em suas tarefas.
- Experimentação: Possibilita testar novas ideias ou implementações sem comprometer o código principal.
- Controle de Qualidade: Ajuda na revisão e aprovação de alterações antes de mesclá-las ao código principal (branch master ou main).

#### Vamos praticar?
- [ ] [Exercicio 6](/exercicios/06-exercicio-branchs/exercicio6.md)

[+ sobre branches](https://www.atlassian.com/br/git/tutorials/using-branches#:~:text=O%20comando%20git%20branch%20tamb%C3%A9m,%C3%A0%20configura%C3%A7%C3%A3o%20do%20reposit%C3%B3rio%20local.&text=Este%20comando%20vai%20enviar%20uma,experiment%20para%20o%20reposit%C3%B3rio%20remoto%20.)


[<- Sobre linha de comando](./03-sobre-linhas-de-comando-git.md) | [Sobre fork ->](./05-sobre-fork.md)
