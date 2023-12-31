# CRUD de dados de vendas
- Projeto Final do Módulo 2 do curso Vem Ser Tech ADA + iFood

# Apresentação Projeto
<p style='text-align: justify;'> Esse projeto é uma aplicação em Python que permite fazer diversas manipulações de registros. O programa utiliza um menu interativo o qual permite que o usuário realize operações, como adicionar, remover e editar registros, realizar leitura e filtragem de dados, gerar estatística, exportar dados para JSON e visualizar regra de negócio.</p>  

 ## Grupo B:

- Adriely
- Amanda Rodrigues
- Daniel Poleti 
- Leticia Santos
- Lorrany 
- Ricardo

# Funcionalidades do Projeto

<p style='text-align: justify;'>O sistema possui 31 funções que estão distribuidas para formatação, validação, formação de listas e suas funções principais que são as seguintes:</p>  

1. **Menu Principal:**
    - <p style='text-align: justify;'>Apresenta as opções para o usuário, como editar, remover e adicionar informações.</p> 

2. **Regra de negócio:**
    - <p style='text-align: justify;'>Realiza o agrupamento dos clientes através dos valores de ticket médio de cada um;</p> 
    - <p style='text-align: justify;'>Separa os clientes em dois grupos, sendo o grupo A aqueles com perfil acima do ticket médio e o grupo B abaixo do ticket médio.</p>

3. **Estatística:**
    - <p style='text-align: justify;'>Calcula o ticket médio que é um indicador usado para avaliar o gasto médio dos clientes e utilizado para as outras estatísticas;<>
    - <p style='text-align: justify;'>Outras estatísticas são os dados de vendas por gênero, vendas por grupo, vendas por categoria, vendas por método de pagamento e itens mais vendidos.</p>  

4. **Filtro:**
    - <p style='text-align: justify;'>Função que realiza os filtros de acordo com os parâmetros de entrada passados;</p>
    - <p style='text-align: justify;'>Esses filtros podem ser por idade, gênero, item, categoria, preço, método de pagamento ou quantidade de compras.</p>

# Fluxograma 

![Fluxograma](Flowchart.jpg)
Referência: [Fluxograma do Script](https://miro.com/app/board/uXjVNNQHetw=/?moveToViewport=-5856,-879,7669,3565&embedId=44500891566)

<p style='text-align: justify;'>Na abertura do código, é solitado ao cliente qual tipo de arquivo ele deseja importar(csv, json), então é apresentada uma lista de arquivos numerados com o nome de cada um. 
Se o arquivo está com linguagem em Inglês, ele solicita se quer o arquivo traduzido ou não, a partir daí  destina-se à um segundo Menu:</p>

![menu 2023-11-23 at 16.00.41.jpeg](https://github.com/Grupo-B-Turma-2-Ada-VemSerTech/Projeto_Mod02_Ada_VemSerTech/blob/e447a83228a85b68faa8474515645ef28a19e4f2/menu%202023-11-23%20at%2016.00.41.jpeg)

<p style='text-align: justify;'>Há várias opções, para que o usuário tome frente de sua escolha.
A partir disso o código é trabalhado em 31 funções, que também fazem parte deste fluxograma, onde, podemos citar alguns exemplos:</p>

- <p style='text-align: justify;'>Usuário pode inserir registros no arquivo selecionado;</p>
- <p style='text-align: justify;'>Caso haja algum erro no registro, pode ser feita uma edição;</p>
- <p style='text-align: justify;'>Pode simplesmente ler os dados sem que haja uma exportação;</p>
- <p style='text-align: justify;'>Ou até mesmo exportar um arquivo, depois de edita-lo ou inserir registros;</p>
- <p style='text-align: justify;'>Na opção de Estatística é trabalhado com opções relevantes para decisões;</p>
- <p style='text-align: justify;'>Em Mostrar regra de negócio, realiza o cálculo do ticket médio e agrupa os clientes em dois grupos;</p> 
- <p style='text-align: justify;'>Ainda em Regra de Negócio separa os clientes em dois grupos, sendo o grupo A aqueles com perfil acima do ticket médio e o grupo B abaixo do ticket médio que também é trabalhado em Estatítica.</p>

<p style='text-align: justify;'>Todo o Fluxo do processo de chamada de funções está descrito na imagem do Fluxograma, mostrando a saída, entrada de cada detalhe do Projeto.</p>

# Requisitos
- Python 3.8+

 ## Arquivos
- `Projeto_grupoB.ipynb`
- `shopping_trends.csv` (opcional)
- `vendas_dados.json` (opcional)
- `vendas_dados_traduzidos.json` (opcional)

 **obs.:** Os arquivos precisam estar no mesmo diretório

 > Os dados de entradas podem ser verificado no link a seguir: [Fonte dos dados](https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset)


# Instalação
## Pacotes
- ``os``
- ``translate``
- ``json``
- ``csv``
- ``langdetect``


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

<p style='text-align: justify;'>Nesse projeto, os alunos tiveram oportunidade de aplicar os seguintes conceitos de programação:</p>

- **JSON:** <p style='text-align: justify;'>Utilizado para maipulações de dados. Para adicionar, editar ou remover dados desse tipo de arquivo.</p>

- **Arquivo CSV:** <p style='text-align: justify;'>Arquivo com os dados originais. Foi utilizado para gerar o JSON.</p>

- **Try/except:** <p style='text-align: justify;'>Utilizado para fazer a validação de dados numéricos.</p>

- **Função anônima(lambda):** <p style='text-align: justify;'>Criadas para gerar as funções de filtro e estatística do projeto.</p>

- **Filter:** <p style='text-align: justify;'>Utilizado para filtrar informações do arquivo JSON.</p>

<p style='text-align: justify;'>O projeto auxiliou na consolidação dos conceitos aprendidos em sala de aula. Além de exapandir o conhecimento nas funcionalidades da linguagem Python e tratamentos de arquivos como CSV e JSON.</p>

