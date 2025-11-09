Exercício 3 — Locomoção em Ambiente VR

Autora: Lara Costa
Unidade Curricular: Interação em Ambientes Virtuais


- Objetivo

Desenvolver um ambiente de Realidade Virtual (VR) que permita ao utilizador mover-se através de teletransporte, com a utilização do componente Blink Controls do A-Frame.
O objetivo é criar um ambiente com obstáculos que incentive a exploração através da locomoção virtual.


- Descrição da Implementação

O ambiente 3D recria uma sala virtual com chão, teto, paredes e iluminação ambiente.
No centro da sala existe uma área com água sem piso sólido, simulada por uma caixa translúcida azul.

O utilizador inicia numa plataforma sólida, podendo teletransportar-se entre diferentes plataformas até chegar ao outro lado, desviando-se dos obstáculos posicionados ao longo do caminho.

A locomoção é feita através de teletransporte, Blink, utilizando os controladores do headset VR.


- Componentes Principais

  - Blink Controls: Implementa o sistema de teletransporte, permitindo que o utilizador se mova dentro do ambiente.
  - Plataformas: Representam as áreas seguras onde o utilizador pode aterrar.
  - Água: Uma zona translúcida que simula um obstáculo.
  - Iluminação e Estrutura: Paredes, teto e luz ambiente criam uma sensação de imersão espacial.


- Interação

  - O utilizador controla a locomoção com os controladores do headset VR.
  - O ponto de destino é indicado visualmente antes de confirmar o teletransporte.
  - Todas as áreas, fora da água, são acessíveis por teletransporte.


- Tecnologias Utilizadas

  - A-Frame 
  - HTML5 / JavaScript
  - Componente Blink Controls


- Como Executar

1. Abrir o link no navegador com suporte a WebXR (como Chrome ou Firefox Reality).
2. Colocar o headset VR e utilizar os controladores para teletransportar-se entre as plataformas.
3. Explorar o ambiente, movendo-se de uma extremidade à outra da sala.


- Link para a experiência VR: https://lmarques1304.github.io/exercicio3-vr/