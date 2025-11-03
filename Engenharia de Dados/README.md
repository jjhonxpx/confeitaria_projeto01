# 🍰 Projeto de Engenharia de Dados – Confeitaria

Este projeto tem como objetivo realizar o **tratamento, padronização e validação de dados de vendas** de uma confeitaria, a partir de uma planilha bruta exportada de um sistema comercial.

---

## 📁 Estrutura da Pasta

📂 confeitaria_engenharia_dados/
│
├── Engenharia_de_Dados_Confeitaria.ipynb # Notebook com o código completo de tratamento
├── Relatorio_Tecnico_Transformacoes.pdf # Relatório técnico descrevendo as etapas aplicadas
└── README.md # Documento explicativo do projeto


---

## 🧾 Descrição do Projeto

O projeto tem como foco a **engenharia e limpeza de dados** do setor de confeitaria, com os seguintes objetivos:

- Revisar a consistência das colunas (Produto, Categoria, Preço Médio, Quantidade Vendida, etc.).
- Remover linhas duplicadas e valores nulos.
- Corrigir inconsistências de formatação (como uso de vírgulas vs. pontos em valores numéricos).
- Garantir tipos de dados adequados (float, int, string).
- Normalizar nomes de categorias e produtos para padronização (ex.: “Salgados”, “SALGADOS”).

---

## 🧰 Tecnologias Utilizadas

- **Python 3**
- **Pandas**
- **NumPy**
- **Jupyter Notebook**

---

## ⚙️ Principais Etapas Realizadas

1. **Leitura e inspeção da planilha original** (`.xlsx`).
2. **Conversão de tipos de dados** (valores numéricos e monetários).
3. **Padronização dos campos** de produto e categoria.
4. **Correções manuais** em nomes com variações de grafia.
5. **Validação de cálculos financeiros** (faturamento e lucro).
6. **Exportação dos resultados** em formatos `.csv` e `.xlsx`.

---

## 📊 Resultados

- Base de dados limpa e pronta para uso em **análises de desempenho, custos e vendas**.
- Redução de inconsistências textuais e numéricas.
- Melhoria na qualidade dos dados para uso em **dashboards e relatórios gerenciais**.
