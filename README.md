
# Biblioteca Pandas - Python

### Estudos da biblioteca Pandas

A biblioteca pandas pode ser considerada a mais importante dentro do mundo da análise de dados para o Python. É a ferramenta principal para construção de estrutura, manipulação e limpeza de dados, sendo também utilizada com bibliotecas de processamento numérico e construção de gráficos.


## Lendo arquivo de dados

- Existem muitas funções nativas para ler seus dados, normalmente iniciando por pd.read_[extensão]


CSV
```bash
df = pd.read_csv('caminho_arquivo.csv', sep='separador')
df = pd.read_csv ('vendas_202005.csv', set = ';')
```

EXCEL
```bash
df = pd.read_excel('caminho_arquivo.xlsx', sheet_name='guia')
df = pd.read_excel ('vendas_202005.xlsx', sheet_name = 'Jan')

```



## Autores

- [@medium](https://medium.com/tech-grupozap/introdu%C3%A7%C3%A3o-a-biblioteca-pandas-89fa8ed4fa38)

