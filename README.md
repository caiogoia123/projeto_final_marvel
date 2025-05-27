## Visão Geral
Este repositório contém um projeto colaborativo focado na extração, tratamento, armazenamento e análise de dados provenientes da API oficial da Marvel Comics. O objetivo principal é aplicar e demonstrar conhecimentos práticos em Python, manipulação de APIs, e técnicas de banco de dados e visualização de dados para gerar insights sobre o vasto universo da Marvel, incluindo personagens, quadrinhos, séries e eventos.

## Pré-requisitos Essenciais
Python: Versão 3.7 ou superior.

Ambiente Jupyter: Jupyter Notebook ou JupyterLab para executar o arquivo .ipynb.

Chaves da API da Marvel: É indispensável possuir uma chave pública e uma chave privada válidas, obtidas no Portal de  [Desenvolvedores da Marvel](https://developer.marvel.com/account)

Bibliotecas Python:

- requests
- pandas
- numpy
- matplotlib
- seaborn
- jupyterlab (ou notebook)
- google-colab (esta é específica se você estiver executando o notebook no ambiente Google Colab para gerenciar as chaves da API através do userdata).

## Como executar o projeto

- Primeiro, execute git clone ou baixe o repositório projeto_final_marvel

```sh
git clone <https://github.com/caiogoia123/projeto_final_marvel.git>
```

- Execute o projeto no ambiente Google Colab caso não queira baixar as dependências
- O notebook está configurado para usar o userdata do Google Colab. Adapte conforme seu ambiente
- Extraia o banco do zip "marvel_characters_teste.zip" e faça upload dele no Colab caso não queira criar o banco novamente

## Resultados esperados

- Saídas de texto e tabelas diretamente no notebook.
- Geração de gráficos visualizando os insights.
- -Criação/atualização do arquivo de banco de dados banco_marvel.db no diretório do projeto.

# Motivação:
Este projeto permite aplicar conhecimentos de Python, APIs e armazenamento de 
dados em um cenário prático, simulando desafios do mercado.
