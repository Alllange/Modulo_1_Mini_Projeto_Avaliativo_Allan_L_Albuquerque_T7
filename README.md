Mini-Projeto - Análise de Dados com Python T7- Allan Lange Albuquerque 

Link do GIT: 

Sobre o projeto:
Este projeto foi desenvolvido como atividade do curso de Análise de Dados com Python.
O objetivo foi realizar uma análise de uma base de dados de varejo, identificando possíveis problemas nos dados, realizando 
a limpeza da base e utilizando algumas análises estatísticas e gráficos para entender melhor as informações.


Ferramentas utilizadas:
Para desenvolver o projeto foram utilizados:
* Python
*VS Code
*Git
Arquivos:
* CSV
Bibliotecas: 
* Pandas
* Matplotlib
* Datetime


Etapas da execução:
Durante o projeto foram realizadas as seguintes etapas:
* Importação do arquivo `Base Varejo.csv`;
* Verificação da quantidade de registros, colunas e tipos de dados;
* Verificação de valores nulos e registros duplicados;
* Remoção de colunas totalmente vazias;
* Remoção de registros duplicados;
* Tratamento das categorias sem identificação;
* Conversão da coluna de data para o formato `datetime`;
* Cálculo de estatísticas sobre o número de filhos dos clientes;
* Agrupamento dos dados para realizar diferentes análises;
* Criação de gráficos para facilitar a visualização dos resultados;
* Geração de uma nova base com os dados tratados.

Resultados:
A análise dos dados permitiu observar alguns pontos importantes:
* A base original possui 830.000 registros e foram encontrados 96.553 registros duplicados.
* Após a limpeza, a base ficou com 733.447 registros.
* Foram encontradas colunas totalmente vazias, que foram removidas por não serem necessárias para a análise.
* A categoria `#N/D` foi substituída por `SEM CATEGORIA`, facilitando a identificação desses registros.
* A categoria Aliemntos  apresentou a maior quantidade de itens.
* O número de filhos dos clientes varia entre 0 e 4, sendo 0 o valor mais frequente.

ETL e qualidade dos dados:
ETL significa Extração, Transformação e Carregamento dos dados.
Neste projeto, a extração aconteceu na leitura do arquivo CSV. A transformação foi realizada durante a limpeza dos dados, como na remoção das duplicatas, tratamento das categorias e conversão das datas. Por fim, o carregamento aconteceu ao salvar os dados tratados em um novo arquivo chamado `df_limpo.csv`.
A qualidade dos dados é importante porque dados duplicados, vazios ou em formatos incorretos podem prejudicar uma análise. Por isso, antes de analisar os resultados, foi necessário verificar e tratar os problemas encontrados na base.

Gráficos
Foram criados gráficos simples para ajudar na visualização dos dados:
* Quantidade de compras por gênero;
* Quantidade de itens por categoria;
* Quantidade de compras ao longo dos meses;
* Quantidade de clientes por número de filhos;
* Os 10 produtos mais vendidos.

Como executar:
Para executar o projeto:
1. Baixe os arquivos do repositório;
2. Abra a pasta do projeto no VS Code;
3. Certifique-se de que o arquivo `Base Varejo.csv` esteja na mesma pasta do código Python;
4. Execute o arquivo `.py`;
5. Escolha uma das opções disponíveis no menu.
Ao executar o programa, também será criado o arquivo `df_limpo.csv` com os dados tratados.

Arquivos do projeto:
* `Base Varejo.csv` - base original utilizada na análise;
* Arquivo `.py` - código desenvolvido para realizar as análises;
* `df_limpo.csv` - base gerada após o tratamento dos dados;
* `README.md` - documentação do projeto.
