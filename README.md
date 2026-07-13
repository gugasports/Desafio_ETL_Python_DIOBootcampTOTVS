# Desafio_ETL_Python_DIOBootcampTOTVS
Projeto desenvolvido como parte do desafio da DIO para demonstrar o processo de ETL (Extract, Transform, Load) utilizando Python e Pandas, com geração de mensagens personalizadas para clientes e exportação dos dados processados para um novo arquivo CSV.

## Objetivo

Demonstrar um fluxo completo de processamento de dados:

- **Extract:** leitura de um arquivo CSV contendo informações de clientes.
- **Transform:** geração de mensagens personalizadas para cada cliente.
- **Load:** gravação dos dados processados em um novo arquivo CSV.

---

## Ferramentas utilizadas:

- Python 3 (Colab)
- Pandas

---

## Estrutura do projeto

```
desafio-etl-python-dio/
│
├── data/
│   ├── clientes.csv
│   └── clientes_processados.csv
│
├── src/
│   └── DesafioETL(DIO).ipynb
│
└── README.md
```

---

## Fluxo ETL

### Extract

Leitura do arquivo `clientes.csv`.

**Entrada**

| Nome | Conta | Cartão |
|------|--------|---------|
| Ana Silva | 12345-6 | **** 1234 |
| Carlos Souza | 98765-4 | **** 5678 |

---

### Transform

Durante esta etapa, o sistema cria uma mensagem personalizada para cada cliente.

Exemplo:

```
Olá, Ana! Que seu planejamento financeiro deste mês te aproxime ainda mais dos seus objetivos.
```

---

### Load

Após a transformação, os dados são salvos no arquivo:

```
clientes_processados.csv
```

contendo uma nova coluna chamada **mensagem**.

---

## Resultado

Ao final da execução será gerado um novo arquivo CSV contendo os dados originais acrescidos das mensagens personalizadas.

---

## Aprendizados

Este projeto permitiu praticar conceitos importantes como:

- Manipulação de arquivos CSV
- Utilização da biblioteca Pandas
- Estruturação do processo ETL
- Manipulação de DataFrames
- Geração e exportação de dados

---

## Autor

**Gustavo Mateus**

Especialista em Educação Física, Performance Esportiva e entusiasta de Ciência de Dados e Inteligência Artificial.
