# 🎲 Trinca da Sorte – Um Jogo de Dados em C#

![.NET](https://img.shields.io/badge/.NET-6.0-blue)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)

Neste projeto, ainda em desenvolvimento, estou colocando em prática os conhecimentos básicos da linguagem **C#**.

---

## 🎮 Sobre o Jogo

**Trinca da Sorte** é um jogo simples e divertido onde o jogador desafia a máquina em uma corrida até **100 pontos**, utilizando lançamentos de dados. Tudo acontece no console, de forma animada e interativa.

---

## 🧠 Como o Programa Funciona

- Utiliza números aleatórios (`Random.Next(1, 7)`) para simular o lançamento dos dados.
- Os dados são exibidos **um por um**, com pequenas pausas para simular a rolagem.
- Após cada jogada, o programa calcula a pontuação da rodada com base nas regras abaixo.
- Os placares do jogador e da máquina são atualizados e exibidos a cada rodada.
- O jogo é executado inteiramente em **modo console**, sem interface gráfica.

---

## 📦 Regras de Pontuação

| Regra               | Descrição                              | Pontos              |
|---------------------|----------------------------------------|---------------------|
| 🎲 Soma dos dados   | Soma simples dos 3 dados               | Soma normal         |
| 🟰 Dois dados iguais | Ex: 3, 3, 5                            | +2 pontos           |
| 🟰🟰 Três dados iguais | Ex: 4, 4, 4                            | +4 pontos           |
| ❌ Soma total < 5    | Ex: 1 + 2 + 1 = 4                      | -3 pontos (mínimo 0)|
| 🎯 Vitória           | Primeiro a atingir 100 pontos vence   |                     |

> 💡 Os bônus e penalidades são aplicados **após** a soma normal dos dados.

---

## ✅ Exemplo de Rodada

```plaintext
[Jogador] Pressione ENTER para lançar os dados...

🎲 Dado 1: 4
🎲 Dado 2: 4
🎲 Dado 3: 1

Soma: 9 + Bônus: 2 → Total da rodada: 11 pontos
Pontuação acumulada do jogador: 28 pontos

Agora é a vez da máquina...

🎲 Dado 1: 6
🎲 Dado 2: 6
🎲 Dado 3: 6

Soma: 18 + Bônus: 4 → Total da rodada: 22 pontos
Pontuação acumulada da máquina: 34 pontos

