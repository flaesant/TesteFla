# Boids: Simulação de Comportamento de Bando (Flocking)
Este projeto implementa uma simulação de Flocking (comportamento de bando) baseada no algoritmo original de Craig Reynolds (1986). O experimento foi desenvolvido em Python utilizando a biblioteca NumPy para cálculos vetoriais e Matplotlib para a visualização dentro do ambiente Google Colab.

🚀 O Experimento
A simulação demonstra como regras locais simples aplicadas a indivíduos (Boids) podem gerar um comportamento emergente complexo e coordenado em grupo, similar ao movimento de pássaros e cardumes de peixes.

As Três Regras Básicas
O modelo baseia-se em três forças fundamentais que cada boid calcula em relação aos seus vizinhos:

Alinhamento (Alignment): Cada boid tenta voar na mesma direção e velocidade dos seus vizinhos.

Coesão (Cohesion): Cada boid tenta se mover em direção ao centro de massa (posição média) dos seus vizinhos para evitar ficar isolado.

Separação (Separation): Cada boid tenta manter uma distância mínima dos outros para evitar colisões.

🛠️ Tecnologias Utilizadas
Python 3

NumPy: Processamento de matrizes e vetores matemáticos.

Matplotlib: Geração de animações e renderização gráfica.

Google Colab: Ambiente de execução em nuvem.

📋 Como Funciona
O projeto está dividido em duas partes principais:

Boid.py: Contém a classe que define a inteligência do agente, incluindo o sistema de física (posição, velocidade, aceleração) e as funções de comportamento.

Main.py: Configura o ambiente, inicializa a população e gerencia o loop de animação que renderiza o resultado como um vídeo HTML5.

📈 Resultados
A simulação permite observar a transição de um estado de caos inicial (posições e direções aleatórias) para a formação de estruturas dinâmicas organizadas, onde o bando flui de forma orgânica pelo cenário.

Este código e documentação foram produzidos com o auxílio de IA (Gemini 1.5 Flash) para fins educacionais e adaptação técnica ao ambiente Google Colab.
