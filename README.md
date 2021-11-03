# Breeders Tools em ReactJS :rocket:

Este teste foi criada usando [ReactJS](https://pt-br.reactjs.org/).

## Setup :gear:

# Como começar a desenvolver :clipboard:

1. Antes de começar, tenha certeza que seu ambiente está pronto para o desenvolvimento.
2. Clone esse repositório usando o comando `git clone < project-url.git >`.
3. Instale as dependências do projeto usando `yarn`.
4. Use o comando `yarn start` para iniciar um servidor local.

## Boas práticas :thumbsup:

### GIT

#### Nomeando as branches

As branches de desenvolvimento devem ser criadas a partir da branch dev, fazendo o checkout com o comando`git checkout dev`.

1. Caso a branch seja de uma nova feature, crie com o nome `feature/branch-name` com o comando `git checkout -b feature/branch-name`.
2. Caso a branch seja de uma correção, crie com o nome `fix/branch-name` com o comando `git checkout -b fix/branch-name`.
3. Caso a branch seja de uma release, crie com o nome `release/branch-name` com o comando `git checkout -b release/branch-name`.

> Lembre-se de criar o nome das branches em inglês, usando o padrão do ES6, com o nome em minúsculas e separados por hífen.

#### Padrão de commits

Os commits no Git podem ser feito em português e descrevendo bem o que as ações presentes nesse commit. Lembre-se de fazer commits ao menos uma vez ao dia. Você também pode fazer vários commits para separar bem o que está entrando no repositório. Imaginando um commit de correção do texto de um botão, você poderia usar o comando `git commit -m "Corrigindo retorno login"` e o comando `git push` para enviar o código e o commit para o repositório.

Você também pode fazer commits com código 'quebrado' no repositório, lembrando de adicionar as iniciais de `Work In Progress` no início da mensagem do commit, por exemplo: `git commit -m "[WIP] Corrigindo retorno login"`.
