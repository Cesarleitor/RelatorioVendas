# Relatório de Vendas em Python

Este projeto foi desenvolvido em Python para processar dados de vendas armazenados em um arquivo `.txt` e gerar um relatório com a quantidade vendida e o total arrecadado por produto.

A aplicação lê os dados do arquivo de entrada, organiza as informações em memória, soma as quantidades por produto e calcula automaticamente o valor total de vendas, gerando ao final um novo arquivo de relatório formatado.

## Funcionalidades

- Leitura de dados de vendas a partir de arquivo `.txt`
- Processamento e agrupamento de vendas por produto
- Cálculo da quantidade total vendida
- Cálculo do total arrecadado por produto
- Geração de relatório em arquivo de saída
- Formatação de valores monetários no padrão brasileiro

## Tecnologias utilizadas

- Python 3

## Conceitos praticados

- Leitura e escrita de arquivos
- Dicionários
- Estruturas condicionais
- Estruturas de repetição
- Manipulação de strings
- Conversão de tipos
- Organização e processamento de dados

## Estrutura do projeto

- `main.py` → responsável pelo processamento das vendas e geração do relatório
- `relatorio_vendas.txt` → arquivo de entrada com os dados das vendas
- `saida_relatorio.txt` → arquivo de saída gerado automaticamente pelo programa

## Formato do arquivo de entrada

O arquivo `relatorio_vendas.txt` deve seguir este padrão:

```txt
Pantera M, 10, 999
Pantera P, 7, 599
Pantera PP, 23, 299
Pantera G, 12, 1599
Pantera GG, 4, 2099
Leão M, 10, 1999
Pantera Bebendo Água M, 8, 1299
Cachorro Galgo M, 5, 1199
Cachorro Galgo G, 8, 1599
Leão Caminhando G, 7, 1599
Leão Caminhando GG, 3, 4399
