# node-cli
Exemplo de uma CLI em Node para procurar arquivos em uma pasta.

## Cli em NodeJS : 

- yarn 
- Babel 
- Gulp 
- webpack 


## Instalação
Para instalar localmente e poder usar o comando no terminal, use o comando:

`npm link`

O comando `search-files` vai estar disponível no terminal. Você pode usar o comando passando o nome do arquivo que deseja procurar no diretório atual:

`search-files .json`

Neste exemplo, listaria todos os arquivos com a extensão `.json`.

## Editando o comando
Você pode editar livremente o arquivo `bin/search-files-cli` para mudar o comportamento do comando sem precisar rodar o comando `npm link` novamente. Qualquer alteração feita nesse arquivo já irá refletir no comando `search-files`.

