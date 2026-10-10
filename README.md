# 🚆 Dashboard de Levantamento de Banco de Dados — Vias 1 e 2

Dashboard interativo desenvolvido em Python com Streamlit para análise e acompanhamento do levantamento de banco de dados de **CDVs (Circuitos de Via) e Sinais ferroviários** das Vias 1 e 2.

O projeto permite visualizar o preenchimento dos pontos cadastrados, identificar pendências, analisar padrões de escrita e explorar os dados por meio de indicadores, gráficos e tabelas interativas.

## 📊 Funcionalidades

- **Visão geral:** indicadores e gráficos consolidados dos CDVs e sinais.
- **Análise de CDVs:** visualização dos pontos por ativo, função e tipo de local.
- **Análise de sinais:** acompanhamento dos pontos preenchidos e sua distribuição.
- **Qualidade dos dados:** identificação de pendências, registros duplicados e pontos fora dos padrões de escrita definidos.
- **Filtros interativos:** segmentação por via e tipo de local.
- **Exportação de dados:** download dos dados tratados em formato CSV.

## 🛠️ Tecnologias utilizadas

- **Python** — linguagem de programação.
- **Streamlit** — desenvolvimento da interface interativa.
- **Pandas** — leitura, transformação e análise dos dados.
- **Plotly Express** — visualização interativa de dados.
- **OpenPyXL** — leitura de planilhas Excel.

## 📁 Estrutura do projeto

```text
projeto-dashboard/
├── app.py
├── requirements.txt
├── README.md
├── levantamento_BD_CDVs_via_1_e_2.xlsx
└── levantamento_BD_Sinais_via_1_e_2.xlsx
```

## ▶️ Como executar localmente

### 1. Clone o repositório

```bash
git clone <URL_DO_REPOSITORIO>
cd projeto-dashboard
```

### 2. Instale as dependências

```bash
pip install -r requirements.txt
```

### 3. Execute o dashboard

```bash
streamlit run app.py
```

O aplicativo será disponibilizado localmente pelo Streamlit, com o endereço exibido no terminal.

## 📂 Dados de entrada

O dashboard utiliza duas planilhas Excel:

- `levantamento_BD_CDVs_via_1_e_2.xlsx`
- `levantamento_BD_Sinais_via_1_e_2.xlsx`

Os arquivos devem estar na mesma pasta do aplicativo ou ser enviados pela barra lateral da interface.

## 🎯 Objetivo

Facilitar o acompanhamento do levantamento de dados, melhorar a visualização do progresso do preenchimento e apoiar a identificação de inconsistências para revisão.

---

**Projeto desenvolvido com Python e Streamlit.**
