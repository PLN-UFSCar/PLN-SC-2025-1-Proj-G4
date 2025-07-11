## Sobre o Projeto 🛠️ 
Este projeto foi desenvolvido como parte da disciplina de Processamento de Linguagem Natural (PLN) da UFSCar, com foco na análise de sentimentos de textos utilizando diferentes técnicas de aprendizado de máquina e processamento de linguagem natural.

## Objetivos 🎯
- Implementar e comparar diferentes abordagens para análise de sentimentos em um dataset de avaliações de livros de diversos gêneros feitas na Amazon Brasil

## Estrutura do Projeto 📁
O projeto está organizado em um notebook Jupyter (`Projeto_PLN.ipynb`) que contém:
- **Pré-processamento**: Limpeza e preparação dos dados textuais
- **Naive Bayes**: Implementação do classificador Naive Bayes para análise de sentimentos
- **SVM com TF-IDF**: Máquina de Vetores de Suporte utilizando vetorização TF-IDF
- **Oplexicon**: Análise de sentimentos baseada no léxico Oplexicon
- **Wordnet Affect BR**: Utilização do léxico Wordnet Affect para português brasileiro
- **Sentilex**: Aplicação do léxico Sentilex para classificação de sentimentos
- **LIWC**: Análise utilizando o dicionário LIWC (Linguistic Inquiry and Word Count)
- **Affect PT-BR**: Implementação com o léxico Affect PT-BR
- **BERTimbau**: Modelo de linguagem BERT treinado para português brasileiro

## Tecnologias Utilizadas 💻
- **Python**: Linguagem principal do projeto
- **Pandas**: Manipulação e análise de dados
- **NumPy**: Computação numérica
- **Scikit-learn**: Algoritmos de aprendizado de máquina
- **NLTK/spaCy**: Processamento de linguagem natural
- **Transformers**: Biblioteca para modelos de linguagem pré-treinados
- **Matplotlib/Seaborn**: Visualização de dados
- **Jupyter Notebook**: Ambiente de desenvolvimento

## Dataset 📊
O projeto utiliza o dataset disponível em:
**https://github.com/larifeliciana/books-reviews-portuguese/tree/master**

Este dataset contém resenhas de livros coletadas em português, adequadas para análise de sentimentos. As características específicas dos dados e sua estrutura estão documentadas no próprio notebook.
