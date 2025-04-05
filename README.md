# 🤖 Robô Trader com Inteligência Artificial

Este projeto é um modelo de **IA desenvolvido em Python** com o objetivo de simular decisões de compra e venda de ações na bolsa de valores. Ele utiliza **Q-Learning**, uma técnica de Aprendizado por Reforço, para aprender a operar com base em experiências de mercado simuladas.

---

## 🧠 Objetivo

Criar um agente inteligente capaz de aprender estratégias de investimento a partir de um saldo inicial, operando **ações da Apple (AAPL)** com dados históricos. Ao final dos ciclos de treinamento, o robô deve:

- Decidir quando comprar, vender ou manter ações;
- Maximizar o lucro ao longo do tempo;
- Exibir o resultado final com base nas decisões tomadas.

---

## 🚀 Tecnologias Utilizadas

- **Python 3.12+**
- **Pandas** – manipulação de dados
- **NumPy** – operações matemáticas
- **Plotly** – gráficos interativos e Candlestick
- **Dash** *(opcional)* – para visualização web

---

## 📈 Como Funciona

1. O modelo lê os dados históricos da ação AAPL (`dataset.csv`);
2. Ele executa ações em episódios simulados, aprendendo com recompensas (lucros ou prejuízos);
3. A Tabela Q é atualizada dinamicamente a cada episódio;
4. Ao final, o agente executa as ações com base na política aprendida e calcula o lucro final.

---

## 📊 Exemplo de Saída

🔧 Definindo os Hiperparâmetros do Q-Learning... 
📈 Configurando o Ambiente de Negociação... 
✅ Treinamento Concluído! 
📌 Execução Finalizada! 
🪙 Número final de ações: 2 💰 Preço final da ação: 154.12 
📈 Lucro final obtido: R$ 147.50 🤖 Obrigado por usar o Robô Trading!

---

## ▶️ Como Rodar

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/robo-trading-ia.git

# Acesse a pasta
cd robo-trading-ia

# Instale as dependências
pip install pandas numpy plotly dash

# Execute o script principal
python main.py
