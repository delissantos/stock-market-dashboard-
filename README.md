# 📈 Dashboard de Cotações de Ações

## 📌 Sobre o projeto

Este projeto consiste em uma aplicação web desenvolvida em **Python** utilizando **Streamlit** para visualizar o histórico de preços de ações negociadas na bolsa de valores.

A aplicação permite que o usuário informe o ticker de uma ação (por exemplo, `AAPL`, `PETR4.SA` ou `VALE3.SA`) e visualize um gráfico interativo com os preços de fechamento obtidos através da biblioteca **Yahoo Finance (yfinance)**.

O projeto foi desenvolvido como atividade da disciplina de **Estatística**, aplicando conceitos de manipulação e visualização de dados.

---

## 🚀 Funcionalidades

* Consulta de ações por ticker
* Coleta automática de dados financeiros utilizando a API do Yahoo Finance
* Visualização do histórico de preços
* Gráfico interativo desenvolvido com Plotly
* Interface simples e intuitiva utilizando Streamlit

---

## 🛠️ Tecnologias utilizadas

* Python
* Streamlit
* yfinance
* Plotly

---

## 📂 Estrutura do projeto

```text
Estatistica/
│
├── app.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Instalação

Clone o repositório:

```bash
git clone https://github.com/delissantos/Estatistica.git
```

Entre na pasta do projeto:

```bash
cd Estatistica
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

---

## ▶️ Como executar

Execute o aplicativo com:

```bash
streamlit run app.py
```

Após iniciar, o navegador abrirá automaticamente a aplicação.

---

## 💡 Exemplos de tickers

| Empresa       | Ticker   |
| ------------- | -------- |
| Apple         | AAPL     |
| Microsoft     | MSFT     |
| Tesla         | TSLA     |
| Petrobras     | PETR4.SA |
| Vale          | VALE3.SA |
| Itaú Unibanco | ITUB4.SA |

---

## 📊 Exemplo de utilização

1. Execute a aplicação.
2. Digite o ticker desejado.
3. Aguarde o carregamento dos dados.
4. Visualize o gráfico interativo com o histórico dos preços de fechamento da ação.

---

## 📚 Objetivo acadêmico

Este projeto teve como objetivo aplicar conceitos de estatística, análise de dados e visualização gráfica utilizando dados reais do mercado financeiro, além de explorar bibliotecas amplamente utilizadas no ecossistema Python para Ciência de Dados.

---

## 👩‍💻 Autora

**Délis Santos**

GitHub: https://github.com/delissantos
