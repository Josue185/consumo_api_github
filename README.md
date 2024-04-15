# Consumo de api do github

Projeto de Consumo da API do GitHub
Objetivo do Projeto:
O projeto tem como objetivo utilizar a API do GitHub para extrair dados detalhados sobre usuários, seus repositórios, atividades de commit, estrelas, forks, e mais. Essas informações podem ser usadas para análises estatísticas, monitoramento de tendências de desenvolvimento, ou simplesmente para coletar dados específicos de projetos ou desenvolvedores.

Tecnologias Usadas:

Python: Linguagem de programação principal para scripting e manipulação de dados.
Requests: Biblioteca Python para fazer requisições HTTP de maneira simples e intuitiva.
Pandas: Biblioteca Python para análise e manipulação de dados, utilizada para organizar os dados coletados em um formato tabular e facilitar a análise.
Jupyter Notebook: Ambiente interativo que permite a combinação de código executável, texto explicativo e visualizações gráficas.
Funcionalidades:

Extração de Dados: O sistema faz requisições à API do GitHub para obter dados JSON, que são processados e transformados em DataFrames com a ajuda do Pandas.
Análise de Dados: Após a coleta, os dados podem ser analisados para identificar padrões, como os repositórios mais populares, os mais ativos ou tendências de contribuições.
Visualização de Dados: Os dados são visualizados usando bibliotecas Python como Matplotlib ou Seaborn, proporcionando insights visuais sobre as informações coletadas.
Fluxo do Projeto:

Autenticação na API: Utiliza-se tokens de acesso para autenticar na API do GitHub para fazer requisições.
Requisições de Dados: Scripts Python utilizam a biblioteca Requests para fazer chamadas à API e coletar dados em formato JSON.
Processamento de Dados: Os dados JSON são convertidos em DataFrames do Pandas para facilitar a manipulação e análise.
Visualização: Os dados processados são exibidos graficamente para oferecer interpretações visuais e fáceis de entender.
Aplicações Potenciais:
Este projeto pode ser utilizado por desenvolvedores para monitorar sua própria atividade ou a de suas organizações, por gerentes de projeto para manter uma visão geral do progresso dos trabalhos, ou por analistas de dados interessados em tendências no mundo do desenvolvimento de software.

![Screenshot 2024-04-15 16 07 11](https://github.com/Josue185/consumo_api_github/assets/92592495/03639e0c-db49-49dc-9d84-4452349eeeab)
![Screenshot 2024-04-15 16 06 03](https://github.com/Josue185/consumo_api_github/assets/92592495/b72e9eb3-1455-464b-8405-3dcf706e3e63)
