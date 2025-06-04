# 🎲 Trinca da Sorte – Um Jogo de Dados em C#

![.NET](https://img.shields.io/badge/.NET-8.0-blue)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)

Neste projeto, ainda em desenvolvimento, estou colocando em prática os conhecimentos básicos da linguagem **C#**.

---

## 📌 Observações
O projeto foi feito apenas com struct e procedural, sem orientação a objetos, como parte dos estudos iniciais em C#.

O jogo roda no console e utiliza cores, centralização e bordas para uma interface mais amigável

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
```

## 🛠 Requisitos

- [.NET SDK 8.0 ou superior](https://dotnet.microsoft.com/en-us/download)
- [Visual Studio Code](https://code.visualstudio.com/)
- Terminal (Git Bash, CMD, PowerShell ou Terminal do VS Code)

---

## 📥 Como baixar este repositório

1. Abra o terminal e vá até a pasta onde deseja salvar o projeto.
2. Execute:

```bash
git clone https://github.com/seu-usuario/TrincaDaSorte.git
```
3. Entre na pasta do projeto:
```
cd TrincaDaSorte

```
---
## 💻 Como instalar o VS Code

Acesse: https://code.visualstudio.com/

Clique em Download e instale normalmente.
---
## ⚙️ Como instalar o .NET SDK

Acesse: https://dotnet.microsoft.com/download

Baixe o instalador do .NET SDK (não o Runtime) compatível com seu sistema operacional.

Após a instalação, confirme no terminal:
```
dotnet --version
```
Se aparecer a versão (ex: 8.0.100), está tudo certo.

## ▶️ Como rodar o projeto

No terminal, dentro da pasta do projeto, execute:
```
dotnet run
```
Isso irá compilar e iniciar o jogo diretamente no console.

## ✍️ Autor
Lucas Bento
