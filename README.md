# 📊 Análise de Engajamento no Instagram com Python

## 📌 Sobre o projeto

Este projeto tem como objetivo analisar o desempenho de publicações no Instagram, buscando identificar quais características estão associadas a um maior número de curtidas e comentários.

Desenvolvido como parte do curso **Ciência de Dados Impressionador, da Hashtag Treinamentos**, o projeto utiliza Python para explorar dados de publicações e investigar padrões relacionados ao formato do conteúdo, à presença de pessoas e à realização de campanhas.

A proposta é demonstrar como a análise exploratória de dados pode transformar informações brutas em insights úteis para apoiar decisões de conteúdo e marketing digital.

## 🎯 Objetivos

- Explorar e compreender a estrutura da base de dados.
- Tratar valores ausentes e preparar os dados para análise.
- Analisar a distribuição de curtidas e comentários.
- Comparar o desempenho dos diferentes formatos de publicação.
- Investigar a relação entre a presença de pessoas, campanhas e o desempenho das publicações.
- Identificar padrões e apresentar conclusões a partir dos dados.

## 🛠️ Tecnologias e ferramentas

| Ferramenta | Aplicação |
|---|---|
| Python | Linguagem utilizada na análise |
| Pandas | Manipulação, tratamento e análise de dados |
| Matplotlib | Criação de visualizações |
| Jupyter Notebook | Desenvolvimento e documentação do projeto |
| Excel | Fonte dos dados analisados |

## 🔎 Etapas do projeto

**1. Importação e exploração dos dados**

- Carregamento da base em Excel utilizando Pandas.
- Inspeção das primeiras e últimas linhas, dimensões e tipos de dados.
- Verificação da estrutura e das informações disponíveis.

**2. Limpeza e preparação dos dados**

- Remoção da coluna de visualizações, conforme a proposta do exercício.
- Identificação e tratamento de valores ausentes na coluna de carrossel.
- Preparação dos dados para as análises seguintes.

**3. Análise exploratória de dados (EDA)**

- Estatística descritiva das variáveis numéricas.
- Análise da distribuição de curtidas e comentários ao longo do tempo.
- Identificação das publicações com maior e menor número de curtidas.

**4. Análise comparativa**

- Comparação das médias de curtidas e comentários por tipo de publicação.
- Análise considerando a presença de pessoas nas publicações.
- Investigação do desempenho de publicações associadas a campanhas.
- Avaliação do uso de carrossel nas publicações do tipo Foto.
- Análise combinada das características para investigar possíveis padrões.

## 💡 Principais insights

A análise exploratória identificou alguns padrões relevantes na base estudada:

- **Presença de pessoas:** publicações com pessoas apresentaram médias de curtidas superiores às publicações sem pessoas.
- **Campanhas:** publicações associadas a campanhas apresentaram resultados médios superiores em diferentes comparações.
- **Combinação de características:** as publicações com pessoas e campanhas apresentaram a maior média de curtidas entre os grupos analisados.
- **Formato do conteúdo:** o desempenho variou conforme o contexto da publicação, indicando que o formato, isoladamente, não explica todos os resultados.
- **Carrossel:** nesta análise inicial, o uso de carrossel não apresentou uma vantagem clara em relação às fotos sem carrossel.

### 📈 Um olhar além dos números

Um dos principais aprendizados foi perceber que analisar apenas a média geral de curtidas e comentários não é suficiente para compreender o desempenho das publicações.

Ao segmentar os dados por diferentes características, foi possível identificar padrões que não eram evidentes na análise inicial, reforçando a importância de explorar os dados sob diferentes perspectivas.

## 📊 Resultados e visualizações

As visualizações desenvolvidas no notebook permitem explorar a evolução das curtidas e dos comentários, além de comparar o desempenho das publicações conforme suas características.

Os resultados podem ajudar a formular hipóteses sobre quais estratégias de conteúdo merecem ser investigadas em análises futuras.

Curtidas x Data:
<img width="1182" height="679" alt="curtidasXdata" src="https://github.com/user-attachments/assets/e37e42ca-f831-40e2-a45e-e0d6ffd87696" />

Comentários x Data:
<img width="1165" height="679" alt="cometarios x data" src="https://github.com/user-attachments/assets/89c14f0d-9de4-4cea-8433-5836460f6d24" />

Curtidas e Comentários x Data:
<img width="1182" height="679" alt="curtidas e comentarios x data" src="https://github.com/user-attachments/assets/8e283077-c1be-45e1-84e3-3e221869aa8c" />

Engajamento por tipo:
<img width="925" height="417" alt="engajamento_por_tipo" src="https://github.com/user-attachments/assets/1274530b-50c6-4083-9164-d444279d2345" />

Engajamento por campanha: 
<img width="921" height="313" alt="engajamento_por_campanha" src="https://github.com/user-attachments/assets/1c553c37-d8fd-4b33-adbf-0e56e0be03ae" />


## ⚠️ Limitações da análise

- Os resultados se referem exclusivamente à base de dados disponibilizada para o exercício.
- As médias podem ser influenciadas por publicações com desempenho excepcional.
- As associações identificadas não comprovam relações de causa e efeito.
- A base não fornece informações suficientes para calcular uma taxa de engajamento baseada em alcance ou número de seguidores.
- Os insights devem ser interpretados considerando o tamanho e as características da amostra.

## ▶️ Como executar o projeto

**Pré-requisitos:** Python e Jupyter Notebook.

**1. Instale as bibliotecas necessárias:**

```bash
pip install pandas matplotlib openpyxl jupyter
```

**2. Disponibilize o arquivo Excel** no mesmo diretório do notebook, utilizando o nome esperado no código.

**3. Abra o arquivo `Analise_engajamento_instagram.ipynb`** no Jupyter Notebook.

**4. Execute as células em ordem** para reproduzir as etapas de exploração, análise e visualização dos dados.

> Observação: a reprodução completa depende da disponibilidade do arquivo Excel original utilizado no exercício.

## 📁 Estrutura do projeto

```text
analise-engajamento-instagram/
│
├── README.md
├── Analise_engajamento_instagram.ipynb
└── 08. Analisando o engajamento no Instagram.xlsx
```

A planilha deve ser incluída no repositório somente se houver autorização para sua redistribuição. Caso contrário, ela deverá ser obtida separadamente por um canal autorizado.

## 📚 Contexto educacional

Este projeto foi desenvolvido para fins de aprendizado, como parte do curso **Ciência de Dados Impressionador — Hashtag Treinamentos**, com foco na aplicação prática de conceitos de análise exploratória de dados utilizando Python.

## 👨‍💻 Autor

Projeto de estudo desenvolvido como parte da minha jornada de aprendizado em Ciência de Dados, com interesse em análise de dados, visualização e geração de insights para apoiar decisões de negócio.

**Área:** Ciência de Dados | Análise de Dados | Marketing Analytics
