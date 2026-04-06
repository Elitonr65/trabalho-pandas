# 💻 Trabalho Prático - Limpeza de Dados com Pandas

## 📌 Descrição

Este projeto tem como objetivo realizar a limpeza e o tratamento de um conjunto de dados utilizando **Python** e a biblioteca **Pandas**, preparando os dados para futuras análises.

---

## 📊 Dataset

O conjunto de dados utilizado contém as seguintes colunas:

* ID
* Duration
* Date
* Pulse
* Maxpulse
* Calories

O dataset possui inconsistências, como:

* Valores nulos
* Datas em formatos incorretos
* Dados inválidos

---

## 🚀 Tecnologias Utilizadas

* Python 🐍
* Pandas 📊
* Google Colab 💻

---

## 🔍 Etapas do Projeto

### 1️⃣ Leitura dos dados

* Importação do arquivo CSV utilizando `pandas.read_csv()`

---

### 2️⃣ Análise inicial

* Visualização com `head()` e `tail()`
* Informações gerais com `info()`

---

### 3️⃣ Tratamento dos dados

✔ Substituição de valores nulos:

* `Calories` → substituído por **0**
* `Date` → tratado adequadamente

✔ Correção de dados inválidos:

* Valor `"20201226"` corrigido para `"2020/12/26"`

✔ Conversão de datas:

* Uso do método `to_datetime()`

✔ Remoção de registros inválidos:

* Linhas com datas inválidas foram removidas

---

## ✅ Resultado Final

Após o tratamento:

* Dataset sem valores inválidos
* Datas no formato correto
* Dados prontos para análise

---

## 📁 Estrutura do Projeto

```
trabalho-pandas/
│
├── dados.csv
├── notebook.ipynb
└── README.md
```

---

## 📌 Como executar

1. Abra o projeto no Google Colab
2. Execute todas as células do notebook
3. Verifique o DataFrame final limpo

---

## 🎯 Conclusão

Este projeto demonstrou como utilizar a biblioteca Pandas para:

* Ler dados externos
* Identificar problemas em datasets
* Realizar limpeza e transformação de dados

---

## 👨‍💻 Autor

Desenvolvido por **Eliton**

---
