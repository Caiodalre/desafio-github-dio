# Comandos Git

Este arquivo reúne os principais comandos Git estudados durante o desafio.

## Configuração inicial

Antes de começar a usar o Git, é importante configurar o nome e o e-mail do usuário.

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@email.com"
```

## Criar um repositório Git

```bash
git init
```

O comando `git init` inicia um novo repositório Git dentro da pasta atual.

## Verificar o status dos arquivos

```bash
git status
```

O comando `git status` mostra quais arquivos foram modificados, adicionados ou ainda não estão sendo rastreados pelo Git.

## Adicionar arquivos à área de preparação

```bash
git add .
```

O comando `git add .` adiciona todos os arquivos modificados para a área de preparação.

## Criar um commit

```bash
git commit -m "mensagem do commit"
```

O commit registra oficialmente uma versão do projeto no histórico do Git.

## Renomear a branch principal

```bash
git branch -M main
```

Esse comando define o nome da branch principal como `main`.

## Conectar o repositório local ao GitHub

```bash
git remote add origin URL_DO_REPOSITORIO
```

Esse comando conecta o repositório local ao repositório remoto no GitHub.

## Enviar alterações para o GitHub

```bash
git push -u origin main
```

Esse comando envia os commits locais para o GitHub.

## Clonar um repositório

```bash
git clone URL_DO_REPOSITORIO
```

Esse comando cria uma cópia de um repositório existente no computador.

## Ver histórico de commits

```bash
git log
```

Esse comando exibe o histórico de commits realizados no projeto.

## Criar uma nova branch

```bash
git checkout -b nome-da-branch
```

Esse comando cria uma nova branch e já muda para ela.

## Trocar de branch

```bash
git checkout nome-da-branch
```

Esse comando muda para uma branch existente.

## Listar branches

```bash
git branch
```

Esse comando lista as branches existentes no repositório.

## Enviar uma branch para o GitHub

```bash
git push -u origin nome-da-branch
```

Esse comando envia uma branch local para o repositório remoto.

## Atualizar o repositório local

```bash
git pull
```

Esse comando baixa as atualizações do repositório remoto para o repositório local.
