# LojasAluraStore
Este projeto realiza uma análise completa de dados das quatro lojas virtuais da Alura Store com o objetivo de ajudar o proprietário, Sr. João, a decidir qual delas possui o pior desempenho e deve ser vendida. Usando Python, Pandas e Matplotlib, o trabalho explora informações reais de faturamento, categorias de produtos, avaliações, custos...
# 📊 Análise de Dados – Alura Store

Este projeto faz parte do curso **"Praticando Python para Data Science: Challenge Alura Store"** da Alura.  
O objetivo é auxiliar o Sr. João, dono de quatro lojas virtuais, a identificar qual delas apresenta o pior desempenho e deve ser vendida para gerar capital para um novo negócio.

---

## ✅ 🎯 Propósito da Análise

A análise tem como finalidade responder à pergunta:

➡️ **Qual das quatro lojas tem o pior desempenho geral e deve ser vendida?**

Para isso, avaliamos métricas essenciais:

- Faturamento total
- Categorias mais vendidas
- Avaliação média dos clientes
- Produtos mais e menos vendidos
- Custo médio de frete
- Gráficos comparativos utilizando Matplotlib

Com esses dados, conseguimos determinar qual loja apresenta menor potencial de lucro e crescimento.

---

## 📁 Estrutura do Projeto

📦 AluraStore-Analise
┣ 📂 dados
┃ ┣ loja_1.csv
┃ ┣ loja_2.csv
┃ ┣ loja_3.csv
┃ ┗ loja_4.csv
┣ 📜 AluraStore_Analise.ipynb
┗ 📜 README.md


✅ **dados/** → contém os arquivos CSV das quatro lojas  
✅ **notebook.ipynb** → onde foram realizadas todas as análises, gráficos e conclusão  
✅ **README.md** → explicação do projeto

---

## 📈 Exemplos de Gráficos e Insights Obtidos

### ✅ Faturamento Total
Gráfico que compara o faturamento das quatro lojas.  
➡ **Insight:** A Loja 4 possui o menor faturamento total.

### ✅ Avaliação Média dos Clientes
Mostra a satisfação do cliente em cada loja.  
➡ As notas são semelhantes, mas a Loja 4 não se destaca.

### ✅ Vendas por Categoria
Exibe quais categorias são mais lucrativas em cada loja.  
➡ As outras lojas têm categorias fortes; a Loja 4 tem baixo volume em vários produtos.

### 🧾 Conclusão Principal
📌 **A Loja 4 foi identificada como a de pior desempenho** e é a recomendação de venda.

---

## ▶️ Como Executar o Notebook

1. Faça o download dos arquivos do projeto.
2. Abra o Google Colab ou Jupyter Notebook.
3. Importe o notebook `AluraStore_Analise.ipynb`
4. Certifique-se de que os arquivos CSV estão na mesma pasta do notebook.
5. Execute as células na ordem.

### 📌 Instalação de bibliotecas (caso necessário)
```python
!pip install pandas matplotlib

✅ Tecnologias Utilizadas

Python 3

Pandas

Matplotlib

Google Colab / Jupyter Notebook

✍️ Autor

Desenvolvido como parte do curso da Alura.
Analista de Dados: Priscila S.
