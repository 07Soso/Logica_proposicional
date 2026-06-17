<h1 align="center">:file_cabinet: Avaliador de proposição com base em lógica proposicional</h1>

Este projeto corresponde ao trabalho final da disciplina **Práticas em Ciência de Dados**, cursada no **1º semestre de 2026**.

A disciplina foi ministrada pelos professores doutores:

- Daniel Roberto Cassar  
- James Moraes de Almeida  
- Leandro Nascimento Lemos  


## :memo: Descrição
Este projeto consiste na implementação de um programa em Python capaz de analisar proposições da lógica proposicional e gerar automaticamente suas respectivas tabelas verdade.
O código realiza a leitura de uma expressão lógica fornecida pelo usuário, identifica as proposições simples presentes, gera todas as possíveis combinações de valores booleanos (True e False) e organiza essas combinações em uma tabela. Em seguida, a expressão é convertida para notação pós-fixa (RPN), permitindo sua avaliação de forma eficiente por meio de uma estrutura de pilha.
Para cada linha da tabela verdade, o programa calcula o valor lógico da proposição e armazena o resultado, possibilitando também a verificação de propriedades como tautologia e contradição.

## 📔 Notebooks e arquivos do projeto:
* `Avaliador_de_proposições.ipynb`: Programa de análise de preposições, geração de tabela verdade e verificação de tautologia e contradição
* `Explicação_detalhada_avaliador_proposições.ipynb`: Este arquivo que documenta, em células fragmentadas, a lógica passo a passo de criação do código, explicando detalhadamente cada parte
* `Avaliador_de_argumentos.ipynb`: Programas de análise de argumentos, verificando sua validade
* `Descrição_versão_inicial_processo_desenvolvimento.ipynb`: Este arquivo apresenta e explica detalhadamente contrução da versão inicial do projeto e os desafios encontrados
* `README.md`: descrição geral do projeto

## Ordem sugerida de leitura dos arquivos:
1. `README.md`
2. `Explicação_detalhada_avaliador_proposições.ipynb`
3. `Avaliador_de_proposições.ipynb`
4. `Avaliador_de_argumentos.ipynb`
5. `Descrição_versão_inicial_processo_desenvolvimento.ipynb`

## :books: Funcionalidades
* <b>Funcionalidade 1</b>: Leitura e interpretação da proposição
  * O programa recebe uma proposição lógica fornecida pelo usuário em formato de string. Em seguida, realiza a separação dos elementos da expressão (letras de proposição, conectivos lógicos e parênteses), preparando os dados para as etapas seguintes de processamento
* <b>Funcionalidade 2</b>: Identificação das letras de proposição
  * A partir da expressão inserida, o código identifica todas as letras de proposição, removendo repetições e organizando-as em uma lista ordenada
* <b>Funcionalidade 3</b>: Geração das combinações de valores lógicos e construção da base da tabela verdade
  * O programa gera todas as possíveis combinações de valores booleanos (True e False) para as letras de proposição identificadas. Cada combinação gerada é distribuída nas respectivas colunas de um dicionário, onde cada chave representa uma proposição
* <b>Funcionalidade 4</b>: Conversão da expressão para notação pós-fixada (RPN)
  * A expressão lógica original é convertida para notação pós-fixada utilizando o método de empilhamento. Essa conversão elimina a necessidade de lidar com parênteses e precedência durante a avaliação, simplificando o processamento
* <b>Funcionalidade 5</b>: Avaliação da expressão lógica (já em RPN)
  * Utilizando a expressão em RPN, o programa avalia o valor lógico da proposição para cada combinação de valores gerada. Essa avaliação é feita com o uso de uma pilha, aplicando os conectivos lógicos conforme necessário
* <b>Funcionalidade 6</b>: Construção da tabela verdade
  * Os resultados obtidos na avaliação são adicionados como uma nova coluna na estrutura de dados, formando a tabela verdade completa da proposição analisada
* <b>Funcionalidade 7</b>: Verificação de tautologia
  * O programa verifica se a proposição é uma tautologia, ou seja, se é intrinsecamente verdadeira (é verdadeira em todas as combinações possíveis). Essa verificação permite classificar a expressão logicamente


## :wrench: Informações técnicas
* Linguagem de programação: `Python 3.13.7`
* Software:  `Visual Studio Code`, `Jupyter Notebook`
* Bibliotecas e Módulos: `pandas`


## :rocket: Rodando o projeto
Para rodar o repositório é necessário clonar o mesmo, dar o seguinte comando para iniciar o projeto:
```
git clone https://github.com/07Soso/projetofinalPCD.git
```

## :soon: Implementação futura
* O que será implementado na próxima sprint?

## :handshake: Colaboradores
* Sophie Silbiger

