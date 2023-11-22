# CRUD de dados de vendas
- Projeto Final do Módulo 2 do curso Vem Ser Tech ADA + iFood

# Apresentação Pojeto
Esse projeto é uma plicação em Python que permite fazer diversas manipulações de registros. O programa utiliza um menu interativo o qual permite que o usuário realize operações, como adicionar, remover e editar registros, realizar leitura e filtragem de dados, gerar estatística, exportar dados para JSON e visualizar regra de negócio.

 ## Grupo B:

- Adriely
- Amanda Rodrigues de Souza
- Daniel Poleti 
- Leticia 
- Lorrany 
- Ricardo

# Descrição
![Fluxograma do Script](https://miro.com/app/board/uXjVNNQHetw=/?moveToViewport=-5856,-879,7669,3565&embedId=44500891566)
![Fluxograma](Flowchart.jpg)

[Fonte dos dados](https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset)
# Requisitos
- Python 3.8+
 ## Arquivos
- `Projeto_grupoB.ipynb`
- `shopping_trends.csv` (opcional)
- `vendas_dados.json` (opcional)
- `vendas_dados_traduzidos.json` (opcional)
 **obs.:** Os arquivos precisam estar no mesmo diretório
# Instalação
## Pacotes
`pip install langdetect`

`pip install translate`

# Análises estatísticas
## Regra de Negócios
Ticket Médio:
$$T_{m} = \frac{\sum{V_{vendas}}}{n_{vendas}}$$
Onde $V_{vendas}$ representa o valor de venda realizada e $n_{vendas}$ é a quantidade de vendas realizadas.

Os clientes foram categorizados de acordo com o Ticket Médio:
- Grupo A: Clientes com valores de compras acima do Ticket Médio
- Grupo B: Clientes com valores de compras abaixo do Ticket Médio


## Estatísticas
- Porcentagem de vendas por Gênero;
- Porcentagem de vendas por Grupo (Ticket Médio);
- Porcentagem de vendas por Categoria;
- Porcentagem de vendas por Item;
- Porcentagem de vendas por Método de Pagamento.

# Conclusão do Projeto com os Conceitos Principais Aplicados

Nesse projeto, os alunos tiveram oportunidade de aplicar os seguintes conceitos de programação:
- **JSON:** Utilizado para maipulações de dados. Para adicionar, editar ou remover dados desse tipo de arquivo.

- **Arquivo CSV:** Arquivo com os dados originais. Foi utilizado para gerar o JSON.

- **try/except:** Utilizado para fazer a validação de dados numéricos.

- **Função anônima(lambda):** Criadas para gerar as funções de filtro e estatística do projeto.

- **filter:** Utilizado para filtrar informações do arquivo JSON.

O projeto auxiliou na consolidação dos conceitos aprendidos em sala de aula. Além de exapandir o conhecimento nas funcionalidades da linguagem Python e tratamentos de arquivos como CSV e JSON.

