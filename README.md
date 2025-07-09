
# 🕹️ Plataforma 2D com PGZero

Este é um jogo de plataforma 2D desenvolvido com **PGZero**, voltado para fins educativos. O projeto segue todos os requisitos de um teste técnico, com foco em movimentação, colisão, animações e organização por classes.

---

## 🎮 Como jogar

- Use **setas direcionais** para mover o herói.
- Pule entre plataformas usando **w** ou **seta direcional para cima**, evite inimigos e alcance o **portal final** para vencer.
- Se perder toda a vida, a tela de *Game Over* será exibida.
- O menu inicial permite iniciar, parar música ou sair do jogo.

---

## ✅ Funcionalidades implementadas

- [x] **Menu inicial interativo** com botões funcionais (Play, Música, Sair)
- [x] **Animação de idle e caminhada** para herói
- [x] **Classes separadas** para Player, Plataforma, Inimigo, Coração e Portal
- [x] **Sistema de pulo e gravidade**
- [x] **Plataformas com colisão**
- [x] **Inimigos animados com detecção de colisão**
- [x] **Coração coletável para recuperar vida**
- [x] **Portal de vitória com transição de tela**
- [x] **Tela de vitória e tela de derrota com retorno automático ao menu**
- [x] **Sistema de pausa (Pause/Play) com tecla `P`**
- [x] **Sons de clique, pulo e dano**

---

## 📁 Organização do código

- `main.py`: código principal com as telas, atualizações e lógica geral
- `images/`: pasta com imagens dos personagens, inimigos, corações, fundo e plataformas
- `sons/`: efeitos sonoros do jogo (pulo, dano, clique, música de fundo)

---

## 🧰 Tecnologias utilizadas

- [PGZero](https://pygame-zero.readthedocs.io/en/stable/)
- Python 3.11+
- Biblioteca `pygame.Rect` para colisões (permitido pelo regulamento)

---

## 🚫 Restrições atendidas

- ❌ Sem uso direto de `pygame.draw`, `Surface`, ou `pygame.display`
- ✅ Uso permitido de `pygame.Rect` apenas para colisão
- ✅ Todo o desenho e som é feito via recursos do PGZero

---
