# Manual Git/GitHub

## Básico

- *GIT INIT* -> Configurar pasta para o git;

- *GIT STATUS* -> Status dos aruivos;

- *GIT ADD _NOME-ARQUIVO_(OU . PARA TODOS ARQUIVOS DE UMA VEZ SÓ* -> Adiciona arquivo;

- *GIT COMMIT -M "MENSAGEM"* -> Faz o commit dos arquivoas;

- *GIT PUSH* -> Envia os arquivos adicionados anteriormente para o GitHub;

- *GIT REFLOG* -> Mostra as versôes adicionadas.

## avançado

- *GIT BRANCH* -> Mostra os branchs disponíveis;

- *GIT BRANCH _NOME_* -> Cria um branch chamado "nome";

- *GIT CHECKOUT _NOME_* -> Muda para o branch "NOME';

- *GIT MERGE _NOME DA BRANCH_* -> Une a branch "NOME" COM A BRANCH EM USO ATUALMENTE;

- *GIT PULL* -> Traz as atualizaçôes do servidor para a màquina local;

- *GIT CHECKOUT -b _NOME_ _BRANCH REFERÊNCIA_* -> Cria uma nova branch com base em uma já existente;

- *TOUCH .GITIGNORE* -> Definir dentro deste arquivo quais pastas/arquivos que não devem subir para o servidor;

## Mergiar Códigos

1.*GIT PULL NA BRANCH PRINCIPAL*;

2.*GERAR UMA NOVA BRANCH A PARTIR DA PRINCIPAL*;

3.*TRABALHA E CRIAR NOVAS FUNCIONALIDADES NA NOVA BRANCH QUE CRIOU*;

4.*FINALIZAR O TRABALHO NA BRANCH TEMPORÁRIA*

5.*GIT CHECKOUT NA BRANCH PRINCIPAL*;

6.*GIT PULL*;

7.*MERGIAR(UNIR) O CÓDIGO DA BRANCH TEMPORÁRIA COM A BRANCH PRINCIPAL(DEPOIS DE TESTAR)*;

8.*GIT PUSH DA BRANCH PRINCIPAL*
