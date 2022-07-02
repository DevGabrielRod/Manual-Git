# Manual Git/GitHub

## Básico

- ```git init``` -> Configurar pasta para o git;

- ```git status``` -> Status dos aruivos;

- ```git add ``` _NOME-ARQUIVO_(OU . PARA TODOS ARQUIVOS DE UMA VEZ SÓ* -> Adiciona arquivo;

- ```git commit -m``` "MENSAGEM"* -> Faz o commit dos arquivoas;

- ```git push``` -> Envia os arquivos adicionados anteriormente para o GitHub;

- ```git reflog``` -> Mostra as versôes adicionadas.

## avançado

- ```git branch``` -> Mostra os branchs disponíveis;

- ```git branch```* _NOME_* -> Cria um branch chamado "nome";

- ```git checkou``` *_NOME_* -> Muda para o branch "NOME';

- ```git merge``` _NOME DA BRANCH_* -> Une a branch "NOME" COM A BRANCH EM USO ATUALMENTE;

- ```git pull``` -> Traz as atualizaçôes do servidor para a màquina local;

- ```git checkou -b``` _NOME_ _BRANCH REFERÊNCIA_* -> Cria uma nova branch com base em uma já existente;

- ```touch .ignore``` -> Definir dentro deste arquivo quais pastas/arquivos que não devem subir para o servidor;

## Mergiar Códigos

1.*```git pull``` NA BRANCH PRINCIPAL*;

2.*GERAR UMA NOVA BRANCH A PARTIR DA PRINCIPAL*;

3.*TRABALHA E CRIAR NOVAS FUNCIONALIDADES NA NOVA BRANCH QUE CRIOU*;

4.*FINALIZAR O TRABALHO NA BRANCH TEMPORÁRIA*

5.*```git checkout``` NA BRANCH PRINCIPAL*;

6.```git pull```;

7.*MERGIAR(UNIR) O CÓDIGO DA BRANCH TEMPORÁRIA COM A BRANCH PRINCIPAL(DEPOIS DE TESTAR)*;

8.*GIT PUSH DA BRANCH PRINCIPAL*
