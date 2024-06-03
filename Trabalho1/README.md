# ⭕ Jogo da Velha

<div align="center">
<img width="150" height="150" src="https://cdn-icons-png.flaticon.com/512/1865/1865460.png">
</div>

## ℹ️ Informações
- **Autores:** Felipe Freitas, Luiza Plá, Maria Maia, Paola Lopes.
- **Data:** 02/06/2024
- **Linguagem:** Phyton
- **Status:** Concluído
- **Descrição:** Problema do jogo da velha com IA.
- **Link:** https://github.com/DudaWendelMaia/IA.git

## 🎯 Problema
Esta pasta apresenta o desenvolvimento e a implementação de um sistema de Inteligência Artificial (IA) para o clássico jogo da velha em um tabuleiro 3x3. O objetivo principal é construir uma IA capaz de analisar o estado atual do tabuleiro e classificar esse estado em quatro possíveis categorias: 'Tem jogo', 'Jogador X venceu', 'Jogador O venceu' e 'Empate'.

Para alcançar esse objetivo, utilizamos um conjunto de dados disponível publicamente no UCI Machine Learning Repository, que contém instâncias do tabuleiro do jogo da velha. Este conjunto de dados foi analisado e transformado conforme necessário para atender às necessidades do problema.

A solução de IA proposta neste trabalho envolve a implementação e teste de três algoritmos classificadores: k-NN, MLP e árvores de decisão. Cada algoritmo foi treinado e validado usando o mesmo conjunto de dados, permitindo uma comparação justa de seu desempenho. A acurácia foi escolhida como a métrica de avaliação principal para medir o desempenho dos algoritmos.

Além disso, foi desenvolvido um front-end mínimo para o jogo da velha, permitindo a interação entre um jogador humano e uma máquina que joga de forma aleatória. A cada turno, a solução de IA é invocada para determinar o estado do jogo e fornecer feedback ao usuário.

Este relatório documenta em detalhes todas as etapas do processo, desde a análise e preparação dos dados até a implementação e avaliação dos algoritmos de IA. Também são apresentados os resultados obtidos e uma discussão sobre a eficácia da solução proposta.

### Detalhes do Problema
- **Complexidade:** NP-completo devido ao crescimento exponencial das possíveis soluções com o tamanho do tabuleiro.
- **Regras de Ataque:** 
  - Rainhas atacam na mesma linha, coluna ou diagonal.
- **Objetivo:** Encontrar uma solução eficiente para o problema das n-rainhas.

### Estratégia de Solução
A solução utiliza busca e backtracking para posicionar as rainhas de forma não conflituosa no tabuleiro.

## ▶️ Como Executar
Certifique-se de ter tudo instalado. Clone o repositório, compile o código e execute.

1. Clone o repositório:
    ```sh
    git clone https://github.com/DudaWendelMaia/IA.git
    ```

2. Navegue até a pasta do projeto:
    ```sh
    cd "Trabalho1"
    ```

3. Compile o código:
    ```sh
      
    ```

4. Execute o programa:
    ```sh
      
    ```

---

Espero que este trabalho tenha sido útil! ⭐🚀
