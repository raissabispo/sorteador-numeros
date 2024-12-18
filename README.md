# Sorteador de Números Aleatórios

Este é um projeto simples desenvolvido em JavaScript para realizar o sorteio de números aleatórios com base em parâmetros definidos pelo usuário. O projeto inclui funcionalidades para reiniciar os campos e alterar o status do botão de reinício.

## Funcionalidades

Sorteio de Números Aleatórios:

- Permite ao usuário definir a quantidade de números a serem sorteados.

- Define o intervalo do sorteio por meio dos campos "De" e "Até".

- Garante que os números sorteados sejam únicos.

## Validação de Entrada:

- Verifica se o valor do campo "De" é menor que o do campo "Até".

- Exibição dos Resultados:

- Mostra os números sorteados em uma área dedicada na página.

- Reinício dos Campos:

- Limpa os campos de entrada e redefine o status do botão de reinício.

## Estrutura do Projeto

## Funções Principais

- sortear():
Realiza o sorteio de números aleatórios com base nos parâmetros fornecidos pelo usuário.

- obterNumeroAleatorio(min, max):
Gera um número aleatório dentro de um intervalo definido.

- alterarStatusBotao():
Altera o status do botão de reinício entre habilitado e desabilitado.

- reiniciar():
Limpa os campos de entrada e redefine o estado da interface para o padrão.

## Estrutura de Arquivos

- index.html:
Contém a estrutura da interface do usuário.

- style.css:
Define os estilos visuais para o projeto.

- script.js:
Contém toda a lógica do sorteio e manipulação da interface.

## Como Usar

- Insira o número desejado para os campos:

- Quantidade: Quantidade de números a serem sorteados.

- De: Valor inicial do intervalo.

- Até: Valor final do intervalo.

- Clique no botão de sorteio para gerar os números.

- Os números sorteados serão exibidos na tela.

- Para realizar um novo sorteio, clique no botão de reinício e insira novos valores.
