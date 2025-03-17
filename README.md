**MBA em Ciência de Dados**

Disciplina: Data harvesting

Prof: Ms Alex Lima

Aluno: João Paulo Barbosa Amorim Leitão

Matrícula: 2418549

**1. Artefatos**  
- Notebook Python com análise exploratória, limpeza e preparação de dados, além de **aplicação** do uso dos dados para **busca de cursos com comparação de similaridade** disponível ao final do notebook (`analysis.ipynb`).

- Notebook Python com scrapping e persistência de dados, utilizando Requests, BeautifulSoup e Selenium (`Data harvesting - Projeto final.ipynb`).

- Arquivo contendo lista de dependências para executar os dois notebooks (`requirements.txt`).

- Base de dados bruta (`scrapped_datasets/courses.csv`).

- Base de dados limpa (`scrapped_datasets/cleaned_courses.csv`).

A fonte dos dados foi o site da Coursera, sua lista de cursos gratuitos disponível em https://www.coursera.org/courses?query=free&page=1 .


**2 Execução**

1. **Instalar Dependências:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Executar o Notebook de Análise:**
   ```bash
   jupyter notebook analysis.ipynb
   ```

3. **Executar o Notebook de Scraping:**
   ```bash
   jupyter notebook Data\ harvesting\ -\ Projeto\ final.ipynb
   ```


Dessa forma, todos os componentes necessários estejam disponíveis e prontos para execução.ink 

Link para o repositório no Github: https://github.com/joaopaulobarbosa/MBA_data_harvesting

