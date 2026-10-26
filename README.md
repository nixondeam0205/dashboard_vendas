# Dashboard de Vendas com Python e Streamlit

Este foi um dos projetos que desenvolvi durante meus estudos de Data Science na Alura. A ideia foi colocar em prática o que estava aprendendo sobre Python, análise de dados e visualização, construindo um dashboard que pudesse ser acessado diretamente pelo navegador.

## Acesse o projeto

- **Dashboard:** [Visualizar aplicação](https://nixondeam-dashboard-vendas-alura.streamlit.app/Dados_brutos)
- **Código-fonte:** [Repositório no GitHub](https://github.com/nixondeam0205/dashboard_vendas)

## Sobre o projeto

O dashboard utiliza dados de vendas para apresentar informações de forma visual e permitir que o usuário explore os resultados com filtros.

Durante o desenvolvimento, trabalhei com a obtenção dos dados por API, a manipulação com Pandas e a criação de gráficos interativos. Também desenvolvi uma página para consultar os dados brutos e selecionar quais colunas devem ser exibidas.

## O que é possível explorar

- Receita total e quantidade de vendas.
- Receita por estado e categoria de produto.
- Distribuição geográfica das vendas.
- Evolução mensal da receita e do volume de vendas.
- Comparação entre vendedores e estados.
- Dados brutos com filtros por produto, categoria, preço, frete, período, vendedor, local da compra, avaliação, pagamento e parcelas.

## Tecnologias utilizadas

- **Python:** desenvolvimento da aplicação.
- **Pandas:** manipulação, agrupamento e análise dos dados.
- **Requests:** consulta à API que fornece os dados.
- **Plotly Express:** criação dos gráficos interativos.
- **Streamlit:** construção e publicação do dashboard.

## Como executar o projeto

É necessário ter Python e Git instalados, além de conexão com a internet para consultar a API.

Clone o repositório:

```bash
git clone https://github.com/nixondeam0205/dashboard_vendas.git
cd dashboard_vendas
```

Crie um ambiente virtual:

```bash
python -m venv venv
```

No Windows, ative o ambiente:

```powershell
.\venv\Scripts\Activate.ps1
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

Execute o dashboard:

```bash
streamlit run Dashboard.py
```

## Fonte dos dados

Os dados são consultados pela API [labdados.com/produtos](https://labdados.com/produtos).

Como a aplicação depende desse serviço externo, o funcionamento do dashboard também depende da disponibilidade da API.

## O que aprendi

Esse projeto me ajudou a entender melhor como diferentes ferramentas podem trabalhar juntas em uma aplicação de análise de dados.

Pratiquei o consumo de APIs, a manipulação de dados com Pandas, a construção de gráficos e filtros interativos e a publicação de uma aplicação web. Também precisei resolver problemas durante o desenvolvimento, o que fez parte importante do aprendizado.

Pretendo continuar evoluindo o projeto à medida que aprofundar meus conhecimentos em análise de dados e Python.

## Sobre mim

Sou formado em Direito e estou direcionando meus estudos para a área de tecnologia, com foco em Data Science e análise de dados. Tenho estudado Python, Pandas e visualização de dados, buscando desenvolver projetos práticos para consolidar meus conhecimentos.

- **GitHub:** [nixondeam0205](https://github.com/nixondeam0205)
- **LinkedIn:** [Nixon Deam Cavalcanti](https://www.linkedin.com/in/nixon-deam-cavalcanti/)

---

*Projeto educacional desenvolvido durante meus estudos na Alura.*
