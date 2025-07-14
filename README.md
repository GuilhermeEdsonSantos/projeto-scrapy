# 📚 Web Scraper – GoodReads

Este projeto é um scraper desenvolvido com **Python** e **Scrapy** que coleta citações, autores e tags do site [GoodReads](https://www.goodreads.com/quotes). Ele realiza a navegação automática por todas as páginas do site, trata os dados coletados e exporta os resultados em formato `.csv`.

# 🔍 Funcionalidades

- Extração de citações de todas as páginas
- Captura do nome do autor e das tags associadas a cada frase
- Tratamento e limpeza de dados textuais
- Paginação automática (navegação entre páginas)
- Exportação dos dados para CSV

## 🛠️ Tecnologias utilizadas

- Python 3
- Scrapy
- XPath
- Manipulação de texto em Python
- Exportação em CSV

## 🚀 Como executar o projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repo.git
   cd nome-do-repo

2.Crie e ative um ambiente virtual (opcional, mas recomendado):

bash

python -m venv venv

venv\Scripts\activate  # Windows

source venv/bin/activate   # Linux/macOS

3.Instale o Scrapy:
bash
pip install scrapy

📌 Observações
O projeto foi criado para fins educacionais, com foco em aprendizado prático de web scraping com Scrapy.
O GoodReads possui termos de uso, e esse scraper deve ser utilizado com responsabilidade, apenas para fins de estudo.

📁 Resultado
O resultado será salvo como citacoes.csv, contendo as colunas: frase, autor e tags.
