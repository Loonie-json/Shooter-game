# 💥 BLOCK SHOT

<p align="center">
  <img src="https://img.shields.io/badge/Language-HTML5%20%2F%20CSS3%20%2F%20JS-accent?style=for-the-badge&labelColor=1a1a1e&color=c8f53a" alt="Tech Stack">
  <img src="https://img.shields.io/badge/Genre-Bullet%20Hell%20%2F%20-blue?style=for-the-badge&labelColor=1a1a1e&color=3ab4f5" alt="Gênero">
  <img src="https://img.shields.io/badge/Waves-15%20Max-red?style=for-the-badge&labelColor=1a1a1e&color=f53a3a" alt="Ondas">
</p>

> **BLOCOS SHOT** é um jogo de tiro *arcade-survival* minimalista e frenético rodando nativamente no navegador. Enfrente hordas de blocos inimigos, suba de nível, melhore seus atributos e tente sobreviver até a Wave 10 para derrotar o Vazio.

---

## ⚡ Funcionalidades Principais

* **🕹️ Engine Pura (Vanilla):** Desenvolvido sem frameworks ou bibliotecas externas. Apenas manipulação de DOM de alta performance e `requestAnimationFrame`.
* **📊 Elementos de RPG:** Sistema de XP, subida de nível automática, ganho de Vida Máxima e escalonamento de Dano (ATK).
* **👾 Bestiário Variado:** * `▲ Makako` e `▶ Gnomo` (Velozes/Perseguidores)
    * `◆ Bruto` (Tanque com muita vida)
    * `✦ Gandalf` (Atirador à distância)
* **💀 Bossfights Épicas:** * **Wave 5:** `🌀 VORTEX` (Gera um campo gravitacional que puxa o jogador e dispara em espiral).
    * **Wave 10:** `🌌 VOID` (Teleporta aleatoriamente e lança padrões massivos de *Bullet Hell*, 50/50 se não morrer por azar talvez passe).
    * **Wave 15:** `RONALDO`(Avanços mortais e uma Salva brutal de misseis, esquive ate o fim).

---

## 🎮 Como Jogar (Controles)

A arena usa controles clássicos de jogos de PC:

| Comando | Tecla | Ação |
| :---: | :---: | :--- |
| <kbd>W</kbd> <kbd>A</kbd> <kbd>S</kbd> <kbd>D</kbd> | Setas ou Letras | Movimenta o Bloco (`YOU`) pela arena |
| <kbd>Espaço</kbd> ou <kbd>J</kbd> | Barra de Espaço / J | Dispara um projétil no inimigo mais próximo |
| <kbd>Shift</kbd> | Shift Esquerdo | Executa um **Dash** rápido (Garante invencibilidade temporária) |

---

## 🛠️ Detalhes Técnicos

O projeto demonstra conceitos sólidos de lógica de desenvolvimento de jogos:
* **Game Loop:** Controlado via tempo delta (`dt`) garantindo que a velocidade do jogo seja consistente independentemente da taxa de atualização do monitor.
* **Aparência:** Identidade visual moderna baseada em variáveis CSS (`:root`), usando as fontes *Syne* e *DM Mono* via Google Fonts.
* **Sistema de Log:** Feed em tempo real no canto inferior esquerdo mostrando eventos de combate e spawn.

---

## 🚀 Como Executar o Projeto

link da pagina do jogo:
https://loonie-json.github.io/Shooter-game/

Como o jogo foi feito em uma única página web estruturada, executá-lo é extremamente simples:

1. Faça o clone do repositório ou baixe o arquivo HTML:
   ```bash
   git clone https://github.com/Loonie-json/Shooter-game
   cd Shooter-game
   ```
2. Use:
   ```bash
   python -m http.server 8000
   ```
   ou use o live server do seu ambiente de codigo.
