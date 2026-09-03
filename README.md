# 🎮 Steam Analytics

Análise exploratória do catálogo de jogos da Steam, desenvolvida em Python e organizada em perguntas de negócio sobre preço, popularidade, avaliações, gêneros e DLCs.

## Objetivo

Transformar dados brutos do Steam Games Dataset em informações úteis sobre o mercado de jogos, combinando limpeza, engenharia de atributos, visualizações e interpretação dos resultados.

## Perguntas analisadas

- Qual é o preço mediano por gênero?
- Como os jogos gratuitos e pagos se distribuem?
- Quais gêneros dominam o catálogo?
- Existe relação entre preço e aprovação dos usuários?
- Como a quantidade de DLCs se relaciona com a satisfação?
- Qual é o perfil dos jogos com alta aprovação?

## Principais resultados

- Jogos gratuitos têm presença relevante no catálogo.
- Entre os jogos pagos, preço médio e mediano podem diferir devido a valores extremos.
- Preços menores apresentam, em alguns grupos, aprovação ligeiramente superior.
- Uma quantidade elevada de DLCs não implica maior satisfação.
- Jogos bem avaliados conseguem sustentar preços medianos mais altos.

> Os resultados dependem do recorte e da versão do dataset utilizados no notebook.

## Tecnologias

- Python
- pandas e NumPy
- Matplotlib e Seaborn
- Jupyter Notebook
- kagglehub

## Arquivos

```text
.
├── atividade_steam.ipynb
├── Steam Analysis Deck _standalone_.html
└── README.md
```

- `atividade_steam.ipynb`: preparação, análise e visualizações.
- `Steam Analysis Deck _standalone_.html`: apresentação navegável dos resultados.

## Como executar

1. Clone este repositório:

```bash
git clone https://github.com/arthurbueno150-create/Steam_Analytics.git
cd Steam_Analytics
```

2. Instale as dependências:

```bash
pip install pandas numpy matplotlib seaborn kagglehub jupyter
```

3. Abra o notebook:

```bash
jupyter notebook atividade_steam.ipynb
```

O `kagglehub` poderá solicitar autenticação para baixar o dataset.

## Demonstração

A apresentação HTML pode ser baixada e aberta no navegador. O repositório também utiliza GitHub Pages quando a publicação está habilitada.

## Autor

Arthur Bueno de Morais Oliveira

Projeto acadêmico da disciplina de Ciência de Dados.
