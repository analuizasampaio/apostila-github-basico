[<- Início](../README.md)

# Configurações Mac

## Índice
- [Abrir terminal na pasta desejada](#abrir-terminal-na-pasta-desejada)
- [DS_Store](#DS_Store)

### Abrir terminal na pasta desejada

Para habilitar essa opção é necessário ir nas configurações:

Preferências de sistema(System Preferences) > Teclado(Keyboard) > Atalhos de Teclado(Shortcuts) e ativar as opções:
- [x] Nova aba de terminal na pasta(New Terminal Tab at Folder)
- [x] Novo terminal na pasta(New Terminal at Folder)

- Retirado de: [groovypost](https://www.groovypost.com/howto/open-command-window-terminal-window-specific-folder-windows-mac-linux/)

### DS_Store
O macOS cria um arquivo chamado `.DS_Store` nas pastas, para que ele não entre como arquivo para os projetos no repositório online é necessário fazer essa configuração:

```
git config --global core.excludesfile ~/.gitignore
```

No nosso gitignore já tem configurado para não adicionar esse arquivo no rastreio do git.

- Retirado de: [pine](https://pineco.de/snippets/globally-gitignore-the-ds_store-file/)
