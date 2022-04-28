# projeto de git e github

## instalação do git

Comandos para configurar o git após a instalação:

```bash
git config --global user.name "<seu_nome>"
git config --global user.email "<seu_email>"
git init #inicializa uma pasta com o git
git add "<nome_do_arquivo>" #adiciona os arquivos para serem versionados
git comit -m "<sua_mensagem>" #cria uma nova versão do código
git branch -M "main" #altera o nome da branch para main

caso abra o vi/vim se não usar o -m com a mensagem no git commit:
-apertar a tecla i
-digitar a mensagem
-apertar a tecla ESC
:wq
git remote add origin "<link_do_projeto_no_github>"
```

## Comandos básicos para enviar/trazer código entre o remoto e o local
```bash
git push origin main #envia do local para o remoto
git pull origin main #traz do remoto para o local
```

## Logo do git
![Git](imagens/iconegit.png)

## Páginas

[Scrum](scrum.md)

[KANBAN](kanban.md)

[Comandos básicos de Git](comandos_b%C3%A1sicos.md)

## Fontes

Documentação da linguagem [Markdown](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

Texto legal
Texto vindo do github!
