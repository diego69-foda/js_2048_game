# Jogo 2048

Um jogo 2048 implementado em HTML, CSS e JavaScript puro.

## Como Jogar

1. **Objetivo**: Combine números iguais para chegar ao número 2048!
2. **Controles**:
   - **Teclado**: Use as setas (↑ ↓ ← →) para mover as peças
   - **Mobile**: Deslize o dedo na direção desejada
3. **Regras**:
   - Cada movimento move todas as peças na direção escolhida
   - Peças iguais se combinam quando se tocam
   - Após cada movimento válido, uma nova peça (2 ou 4) aparece
   - O jogo termina quando não há mais movimentos possíveis

## Como Executar

1. Abra o arquivo `src/index.html` em qualquer navegador moderno
2. Clique em "Start" para começar o jogo
3. Use as setas do teclado para jogar

## Funcionalidades

- ✅ Interface responsiva e moderna
- ✅ Suporte para teclado e touch (mobile)
- ✅ Sistema de pontuação
- ✅ Detecção de vitória (2048) e derrota
- ✅ Botão de restart
- ✅ Animações suaves
- ✅ Design fiel ao jogo original

## Estrutura do Projeto

```
src/
├── index.html          # Arquivo principal HTML
├── styles/
│   ├── main.css        # Estilos do jogo
│   └── main.scss       # Versão SCSS (original)
├── scripts/
│   └── main.js         # Lógica do jogo
└── modules/
    └── Game.class.js   # Classe Game (para testes)
```

## Tecnologias Utilizadas

- **HTML5**: Estrutura da página
- **CSS3**: Estilização e layout responsivo
- **JavaScript ES6+**: Lógica do jogo e interações
- **SCSS**: Pré-processador CSS (opcional)

## Desenvolvimento

Para modificar o jogo:

1. **Lógica do jogo**: Edite `scripts/main.js`
2. **Estilos**: Edite `styles/main.css` ou `styles/main.scss`
3. **Estrutura**: Edite `index.html`

## Testes

O projeto inclui uma estrutura para testes unitários. A classe `Game` pode ser testada independentemente da interface.

## Licença

Este projeto é de código aberto e pode ser usado livremente para fins educacionais e pessoais.

