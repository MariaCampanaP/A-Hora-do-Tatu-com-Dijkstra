<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&color=00b362&reversal=false"/>

## ☕︎︎ Projeto - A Hora do Rush (A Hora do Tatu)

Um jogo iterativo que junta o algoritmo de Dijkstra com o famoso jogo hora do rush em uma versão fofa e diferenciada, tendo 3 niveis (facil, medio, medio/dificil) de posições dos tatus, toda vez que um tatu ultrapassa a linha de chegada, o tabuleiro é refeito, mudando seus vertices livres

---

## ☕︎︎ Breve História da Hora do Rush

O jogo **A Hora do Rush** *(Rush Hour)* foi criado em **1996** pelo designer de quebra-cabeças **Nob Yoshigahara**, um dos mais renomados criadores de enigmas do século XX. Lançado pela empresa **ThinkFun**, o jogo rapidamente se tornou um clássico dos puzzles de lógica.
A proposta é simples, mas desafiadora: mover carros e caminhões em um tabuleiro 6x6 até que o carro vermelho consiga sair do congestionamento. Cada desafio possui um arranjo inicial específico e um número limitado de movimentos possíveis, exigindo raciocínio lógico, planejamento e visão espacial.
Ao longo dos anos, *A Hora do Rush* ganhou suas versões digitais, expansões com novos desafios e até edições temátivas. Sua popularidade o consolidou como um dos jogos de lógica mais conhecidos do mundo, frequentemente usado em salas de aula, clubes de matemática e programas de treinamento cognitivo.

---

## ☕︎︎ Para jogar

Aqui estamos disponibilizando os códigos e o jogo também, para jogar, só baixar o arquivo .zip e descompactar, você terá 2 pastas, uma dentro da outra, tire a pasta com o jogo de dentro da outra para que funcione e rode o código main no seu vscode/compilador
**Bibliotecas**: pygame, os e numpy

## ☕︎︎ Como Jogar

1. **Objetivo**: Ultrapassar o tabuleiro usando unicamente o algoritmo
2. **Controles**:
   - Clique em um tatu que esteja com caminho livre (caso contrario ele não vai sair e você perdera 25 pontos)
   - Clique a tecla SPACE para enviar o tatu pelo caminho
3. **Regras**:
   - Não é possivel enviar um tatu preso
   - Não é permitido enviar mais de um tatu por vez
   - Enviar todos os tatus até o final do tabuleiro
4. **Fases**:
   - Nivel 1: dificuldade facil, com 16 tatus
   - Nivel 2: dificuldade media, com 18 tatus
   - Nivel 3: dificuldade media/dificil, com 18 tatus
  
## ☕︎︎ Tecnologias Utilizadas

- **Linguagem**: [Python, pygame]
- **Algoritmo**: Dijkstra implementado do zero
- **Design**: Pixel art

## ☕︎︎ O Algoritmo de Dijkstra

Este jogo implementa visualmente o famoso algoritmo:

1. Inicializa distâncias como infinito
2. Marca o nó inicial (tatu) com distância 0
3. Explora vizinhos atualizando menores distâncias
4. Repete até encontrar o destino (fim do tabuleiro)

## ☕︎︎ Exemplos (Níveis do Jogo)

| Nível Fácil | Nível Médio | Nível Difícil |
|-------------|-------------|---------------|
| ![Nível 1](nivel1.png) | ![Nível 2](nivel2.png) | ![Nível 3](nivel3.png) |

## ☕︎︎ Equipe

**Luna**
- GitHub: [@Luna-Osti]([(https://github.com/Luna-Osti)])
- LinkedIn: [Luna Osti de França](https://www.linkedin.com/in/luna-osti-de-frança-23961b321/)

**Maria Rita**
- GitHub: [@MariaCampanaP]([https://github.com/MariaCampanaP])
- LinkedIn: [Maria Rita Campana Peixoto](https://www.linkedin.com/in/maria-rita-campana/)

**Vallentina**
- GitHub: [@Vallentinanina]([https://github.com/Vallentinanina])
- LinkedIn: [Vallentina Rodrigues Costa Groetaers Sousa](https://www.linkedin.com/in/vallentina-rodrigues-costa-groetaers-sousa-435b85319/)

## ☕︎︎ Como Usar

1. Clone o repositório para o seu computador:

   ```bash
   git clone https://github.com/MariaCampanaP/A-Hora-do-Tatu-com-Dijkstra.git
   ```
   
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&color=00b362&reversal=false&section=footer"/>

