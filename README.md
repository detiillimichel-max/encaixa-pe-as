# Encaixa Peças – Tetris Colorido

Jogo de encaixar peças feito para celular, sem tela verde! Ideal para crianças e adolescentes.

## Arquivos
- index.html – estrutura
- style.css – visual colorido (nada de verde monocromático)
- script.js – lógica do Tetris
- README.md – este arquivo

## Como usar no celular
1. Baixe os 3 arquivos para a mesma pasta
2. Abra o `index.html` no Chrome ou Safari (IMPORTANTE: não abrir no visualizador do WhatsApp/Telegram)
3. Toque em "Iniciar"
4. Use os botões na parte inferior:
      - ◀ ▶ mover
      - ↻ girar
      - ▼ descer
      - SOLTAR queda rápida
      - SEGURAR guarda peça

Funciona offline. Não precisa instalar nada.

## Se não jogar (tela branca como na sua foto)
É porque abriu no visualizador interno. Faça: Arquivos > Downloads > toque longo > "Abrir com" > Chrome.

## Personalizar
- Cores das peças: em `style.css` nas variáveis --blue, --pink, etc.
- Velocidade inicial: em `script.js`, mude `dropInterval=900` (maior = mais lento)
    - Para crianças pequenas, use 1200
    - Para adolescentes, use 700
- Para iniciar automático, troque no JS `showOverlay('start')` por `startGame()`

Feito com HTML/CSS/JS puro – roda em qualquer celular Android/iPhone.
