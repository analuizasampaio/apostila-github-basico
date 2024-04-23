### Configurando o Git com seu user.name e user.email

Você deve ter instalado o Git na sua máquina.
Na Área de Trabalho (Desktop), clique com o botão direito e selecione ***Git Bash here***

Comandos para configurar seu usuário no Git:
- `git config --global user.name "Ana Luiza Sampaio"`
- `git config --global user.email "sampaioaanaluiza@gmail.com"`

> Ele pode pedir a sua senha nessa ponto e um erro de autenticação pode aparecer. Fique atenta a [possivel solução](../../conteudo/solucao-erro-autentificacao-gitbash.md)

Para verificar se foi configurado:
- `git config --list`

Para remover usuário:
- `git config --global --unset user.name "Ana Luiza Sampaio"`
- `git config --global --unset user.email "sampaioaanaluiza@gmail.com""`
