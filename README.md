# Zona Zumbi

Jogo de tiro em primeira pessoa contra ondas de zumbis, feito com [three.js](https://threejs.org/) em um único arquivo HTML.

## Jogar

- **PC (principal):** abra `index.html` no navegador. Se o mouse não travar, rode um servidor local:
  `python -m http.server` e acesse `http://localhost:8000`.
- **Celular:** abra `mobile/index.html` (versão mais simples, com joysticks na tela).

Para publicar de graça: no GitHub, vá em **Settings → Pages**, escolha a branch `main` e a pasta raiz.

## Controles (PC)

| Ação | Tecla |
|---|---|
| Mover | W A S D ou setas |
| Olhar | Mouse |
| Atirar | Botão esquerdo |
| Mirar | Botão direito |
| Trocar de arma | 1 a 7 ou roda do mouse |
| Pegar arma do chão | E |
| Recarregar | R |
| Correr | Shift |
| Pular (e passar por janelas) | Espaço |
| Pausar | Esc |

## O que tem no jogo

- 7 armas: Pistola, Revólver, SMG, AK-47, M4, Escopeta e Sniper (com luneta).
- Zumbis normais, corredores e tanques, em ondas que ficam mais difíceis.
- Zumbis largam kits de vida, munição e armas.
- Casas e lojas com porta e janelas, prédios altos, carros, árvores, pedras e grama.

## Créditos

- Modelos 3D (natureza, armas, carros e zumbi): [Quaternius](https://quaternius.com/), licença CC0.
- Biblioteca gráfica: [three.js](https://threejs.org/) (licença MIT), carregada pela CDN do cdnjs.
- Fonte: Rajdhani (Google Fonts).
