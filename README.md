🚦 Controle de Semáforo Inteligente

Projeto de Machine Learning usando **Aprendizado por Reforço (Q-Learning)** para otimizar o controle de semáforo com base no fluxo de veículos. O objetivo é reduzir o tempo médio de espera dos carros e melhorar o fluxo em uma interseção simples.


📌 Objetivo
Treinar um agente que aprenda a alternar os sinais de trânsito com base no número de veículos em cada via, utilizando **Q-Learning** para maximizar o número de carros que passam e minimizar o tempo de espera.


🛠️ Tecnologias e Bibliotecas Utilizadas

- Python 3.x  
- NumPy  
- Matplotlib  
- Pandas (opcional)



📘 Algoritmo Utilizado

**Q-Learning**

> Fórmula de atualização:
```python
Q[s][a] = Q[s][a] + alpha * (reward + gamma * max(Q[new_state]) - Q[s][a])

α (alpha): taxa de aprendizado

γ (gamma): fator de desconto

ε (epsilon): taxa de exploração (ε-greedy)
```

🧪 Como Executar o Projeto

# Clone o repositório
git clone https://github.com/WGlyma/Controle-de-semafaro--01633979---Wilamy-gabriel-.git
cd Controle-de-semafaro--01633979---Wilamy-gabriel-

# Instale os requisitos
pip install -r requirements.txt

# Execute o treinamento
python main.py


📊 Resultados Obtidos

✅ Redução do tempo médio de espera

✅ Aumento no número de veículos processados

✅ Evolução da recompensa total ao longo dos episódios


🧠 Dificuldades Encontradas
Definir uma função de recompensa que equilibre bem os fluxos

Ajustar corretamente o valor de epsilon para balancear exploração e exploração

Modelar estados sem que fiquem grandes demais (explosão de estados)
📈 Exemplo de gráfico (substitua pelo seu print real)


✅ Comentários Finais
Este projeto demonstrou como técnicas de aprendizado por reforço podem ser aplicadas a problemas reais. Mesmo em uma simulação simples, foi possível observar o aprendizado do agente e os impactos positivos no desempenho do semáforo.
