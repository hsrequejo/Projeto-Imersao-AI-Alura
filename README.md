# Projeto-Imersao-AI-Alura

# Descrição
Projeto da Imersão AI Alura.

Serve para conversar com um dataframe pandas pelo pandas AI usando o Gemini como modelo llm

Pode pedir estatíscas, agrupar, fazer gráficos, o que você quiser

**Exemplo de prompt**: *Qual os 5 carros japoneses mais pesados de 1980?*

# Vantagens

1. Usa o Pandas AI para salvar e analisar o banco de dados, ou seja, não gasta tokens com os dados e podemos colocar dados com milhares de linhas e colunas, usando o poder do pandas.

2. Usa o Gemini para gerar a ponte entre o llm e criar a query para o pandas.

3. LLMs são ruins com números, mas como usamos o LLM apenas para gerar a query e os cálculos são feitos pelo Pandas, temos cálculos confiáveis.

4. Podemos pedir para plotar gráficos, escolhendo variéveis e tipos de gráficoi usando apenas linguagem natural.
