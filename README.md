# Teste Desenvolvedor BackendPHP NoFaro 

Seja bem vindo! Obrigado pelo interesse em participar do processo seletivo da Nofaro.
Leia atentamente as instruções abaixo e não hesite em entrar em contato com a gente.

## Objetivo:
Criar uma API que permita a inclusão, listagem e remoção de pets e de atendimentos
realizados.

## Descrição
Um pet possui nome e espécie (cão ou gato). Quando um pet realiza um atendimento são
registradas a data do atendimento e uma descrição. A descrição é um campo de texto utilizado
para informar o que foi realizado no atendimento.

Um exemplo de informação que pode ser montada a partir dos dados da API é: “Em
03/06/2020 o pet Bolinha (cão) ‘recebeu a primeira dose da vacina da gripe’”
Cada pet pode realizar vários atendimentos.

### Inclusão
Ao incluir um pet ou seus atendimentos as seguintes validações devem ser feitas:
1. Nome: obrigatório, com no mínimo 2 caracteres;
1. Espécie: obrigatório, sendo ‘C’ ou ‘G’ representado, respectivamente, cão ou gato;
1. Data do atendimento: obrigatório, com formato Y-m-d;
1. Descrição do atendimento: opcional, campo texto;

### Listagem
A lista de pets deve retornar todas as informações cadastradas de forma paginada.
Deve ser possível filtrar os resultados pelo nome do pet.
O nome poderá ser buscado por strings parciais.

### Remoção
Quando um pet é removido os atendimentos associados ao pet também devem ser removidos.

### Regras
1. Utilizar Laravel;
1. Utilizar MySQL como base de dados;
1. Entregar o resultado através de um sistema de controle de versão (Github, Bitbucket, ...);
1. Ter instruções de como utilizar os recursos da API.

## Entregáveis
Não é preciso desenvolver uma interface gráfica para gerenciar dos dados da API, basta
informar quais endpoints foram criados para listagem, inclusão e remoção de pets e seus
atendimentos. Os endpoints mínimos esperados são: inclusão de pet, remoção de pet, listagem
de pets e inclusão de atendimentos.

### O que será avaliado:
1. Cumprimento dos requisitos apresentados na descrição
1. Organização do código
1. Simplicidade da solução apresentada

Bom teste!
