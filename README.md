# Mineração de Lances de Futebol

Este projeto tem como objetivo identificar sequências de lances em partidas de futebol que levam a finalizações, utilizando técnicas de mineração de padrões frequentes.

## 📌 Sobre o Projeto
O futebol é um esporte dinâmico e estratégico, onde pequenos padrões de jogadas podem impactar significativamente o resultado de uma partida. Utilizando dados detalhados do StatsBomb Open Data, este projeto busca analisar sequências de eventos dentro do jogo para identificar padrões que resultam em chutes ao gol.

A metodologia aplicada envolve a conversão dos eventos da partida em transações sequenciais e a utilização de algoritmo de mineração de padrões Prefixspan para extrair insights relevantes.

## 🗂 Estrutura do Repositório
- **README.md**: Este arquivo de documentação.
- **requirements.txt**: Arquivos e bibliotecas necessários para o projeto.
- **data/**: Diretório para armazenar os dados.
  - **processado.json**: Base de dados processada
- **notebooks/**: Diretório contendo notebooks para análise.
  - **exploracao.ipynb**: Análise inicial do dataset.
  - **mineracao.ipynb**: Mineração de padrões sequenciais.
- **.gitignore**: Arquivos a serem ignorados pelo Git.

## 🏗 Etapas do Projeto
1. **Entendimento dos Dados:** Exploração inicial do dataset para compreender sua estrutura e granularidade.
2. **Preparação dos Dados:** Transformação dos eventos de jogo em sequências que representam jogadas completas que terminam com uma finalização.
3. **Mineração de Padrões:** Aplicação de algoritmos de mineração para encontrar sequências frequentes de ações.
4. **Análise:** Interpretação dos padrões encontrados e visualização dos resultados.

## 📊 Fonte dos Dados
Os dados utilizados no projeto são provenientes do [StatsBomb Open Data](https://github.com/statsbomb/open-data), uma base de dados pública contendo informações detalhadas sobre eventos em partidas de futebol e várias outras informações.
