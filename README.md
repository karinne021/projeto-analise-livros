# Análise de Dados sobre Livros

## Objetivo do Projeto
Este projeto foi desenvolvido com o propósito de estudar e praticar técnicas de análise de dados utilizando Python. O foco principal é explorar informações relacionadas a livros, incluindo suas avaliações, número de páginas, gêneros e datas de publicação.

## Bibliotecas Necessárias
Para executar o notebook, as seguintes bibliotecas são necessárias:

- **pandas**: Para manipulação e análise de dados.
- **numpy**: Para operações matemáticas e tratamento de arrays.
- **matplotlib**: Para visualizações básicas de dados.
- **seaborn**: Para criar gráficos mais elaborados e esteticamente agradáveis.

Certifique-se de instalá-las utilizando o gerenciador de pacotes `pip`, caso ainda não estejam no ambiente:

```bash
pip install pandas numpy matplotlib seaborn
```

## Como Rodar o Notebook
1. Clone este repositório ou baixe os arquivos diretamente.
2. Certifique-se de ter o Python instalado (versão 3.7 ou superior é recomendada) e configure um ambiente virtual, se preferir.
3. Abra o notebook (`projeto_livros.ipynb`) em um ambiente compatível, como:
   - [Jupyter Notebook](https://jupyter.org/install)
   - [VSCode](https://code.visualstudio.com/) com a extensão Python.
4. Execute as células do notebook em sequência para reproduzir os resultados.

## Descrição do Dataset
O DataFrame utilizado neste projeto foi baixado do Kaggle e contém informações sobre livros. 
Para acessar o dataset original, utilize o link: [Best Books Ever Dataset](https://www.kaggle.com/datasets/pooriamst/best-books-ever-dataset?resource=download).


### Descrição dos Campos:
- **bookId**: Identificador do livro no Goodreads.
- **title**: Título do livro.
- **series**: Nome da série.
- **author**: Autor do livro.
- **rating**: Avaliação global no Goodreads.
- **description**: Descrição do livro.
- **language**: Idioma do livro.
- **ISBN**: ISBN do livro.
- **genres**: Gêneros do livro.
- **characters**: Personagens principais.
- **bookFormat**: Tipo de encadernação.
- **edition**: Tipo de edição (ex. Edição de Aniversário).
- **pages**: Número de páginas.
- **publisher**: Editora.
- **publishDate**: Data de publicação.
- **firstPublishDate**: Data de publicação da primeira edição.
- **awards**: Lista de prêmios.
- **numRatings**: Número total de avaliações.
- **ratingsByStars**: Número de avaliações por estrela.
- **likedPercent**: Percentual de avaliações acima de 2 estrelas (como no Goodreads).
- **setting**: Ambiente da história.
- **coverImg**: URL da imagem da capa.
- **bbeScore**: Pontuação na lista Best Books Ever.
- **bbeVotes**: Número de votos na lista Best Books Ever.
- **price**: Preço do livro (extraído do Iberlibro).


## Resultados
Durante a análise, foram obtidos insights importantes, como:

- A relação entre o número de páginas e as avaliações dos livros.
- A distribuição dos livros por gênero, identificando o mais popular.
- A evolução das publicações ao longo dos anos, destacando tendências em determinados períodos.
- A identificação de valores ausentes e filtragem para análises mais específicas, como publicações sem gênero associado ou em intervalos de tempo definidos.

As visualizações criadas (gráficos de barras, histogramas, gráficos de dispersão, entre outros) foram úteis para entender os padrões e responder às perguntas de negócio formuladas ao longo do projeto.

## Conclusão
Este projeto destacou a importância de técnicas básicas de análise e visualização de dados para extrair informações relevantes. Ele serve como uma base para estudos futuros, onde podem ser aplicados modelos mais complexos de aprendizado de máquina e análise preditiva.

Sinta-se à vontade para contribuir ou entrar em contato caso tenha dúvidas ou sugestões!
