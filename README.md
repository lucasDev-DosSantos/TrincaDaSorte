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

---
🚀 Como Clonar e Rodar o Projeto
1. Faça o fork no GitHub
Acesse o repositório original.

Clique em Fork para copiar para sua conta.

2. Clone o repositório
Abra o terminal e digite:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/Trinca-da-Sorte.git
cd Trinca-da-Sorte
Substitua seu-usuario pelo nome da sua conta no GitHub.

3. Instale o Visual Studio Code
Baixe e instale o VS Code em: https://code.visualstudio.com

4. Instale o .NET SDK
Você precisa do .NET SDK instalado: https://dotnet.microsoft.com/download

Verifique se está instalado com:

bash
Copiar
Editar
dotnet --version
5. Abra o projeto no VS Code
Se você tiver o comando code configurado:

bash
Copiar
Editar
code .
Se não funcionar, abra o VS Code manualmente e vá em File > Open Folder....

6. Execute o projeto
Dentro da pasta do projeto, digite:

bash
Copiar
Editar
dotnet run
💡 Dicas com Git
bash
Copiar
Editar
git add .
git commit -m "Minha alteração"
git push
📬 Contribuição
Este projeto faz parte do meu processo de aprendizado. Se você tiver dicas, sugestões ou quiser colaborar, fique à vontade para abrir uma issue ou enviar um pull request.

yaml
Copiar
Editar

---

Se quiser, posso também te ajudar a criar uma logo simples pro projeto ou até gerar um gif animado simulando a jogada no console pra colocar no README. Quer algo disso?
