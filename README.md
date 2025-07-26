# Jokenpô Simplificado com Front-end

Este é um projeto simples de jogo de Jokenpô (Pedra, Papel e Tesoura) implementado utilizando apenas tecnologias front-end (HTML, CSS e JavaScript embutido no HTML). O objetivo é demonstrar a lógica básica do jogo e a interação com o usuário através de uma interface web.

## Tecnologias Utilizadas

* **HTML5:** Estrutura e conteúdo da página web.
* **CSS3:** Estilização e layout da interface do usuário.
* **JavaScript:** Lógica do jogo, manipulação do DOM e interação.

## Como Jogar

1.  Abra o arquivo `index.html` em seu navegador.
2.  O jogo consiste em 3 rodadas.
3.  Para cada rodada, clique em um dos botões: "Pedra", "Papel" ou "Tesoura".
4.  O computador fará sua escolha aleatoriamente.
5.  O resultado da rodada (Vitória, Derrota ou Empate) e o placar serão atualizados.
6.  Ao final das 3 rodadas:
    * Se houver um vencedor claro, o jogo terminará com a mensagem de vitória ou derrota.
    * Se houver um empate no placar geral, uma "Rodada extra" será iniciada para desempatar.
7.  Após o término do jogo, um botão "Jogar Novamente" aparecerá para reiniciar.

## Funcionalidades

* **Placar:** Exibe a pontuação atual do Jogador e do Computador.
* **Contador de Rodadas:** Informa a rodada atual do jogo.
* **Escolha do Jogador:** Botões interativos para as opções Pedra, Papel e Tesoura.
* **Escolha do Computador:** Geração aleatória da jogada do computador.
* **Lógica do Jogo:** Determina o vencedor de cada rodada e atualiza o placar.
* **Regras:** Pedra ganha de Tesoura, Papel ganha de Pedra, Tesoura ganha de Papel.
* **Mensagens de Resultado:** Feedback visual para cada rodada (Vitória, Derrota, Empate).
* **Sistema de Rodadas:** Jogo de 3 rodadas com a possibilidade de uma rodada extra em caso de empate geral.
* **Interface Responsiva:** Estilização básica para se adaptar a diferentes tamanhos de tela (max-width).
* **Modal de Fim de Jogo:** Uma janela pop-up exibe o resultado final com os placares e um botão para jogar novamente.

## Estrutura do Projeto

* `index.html`: Contém a estrutura HTML do jogo, incluindo o placar, os botões de jogada, as áreas de exibição de resultados e o JavaScript embutido que controla a lógica do jogo.
* `style.css`: Contém todos os estilos CSS para a apresentação visual do jogo, garantindo uma experiência de usuário agradável.

## Como Rodar o Projeto (Localmente)

1.  Clone este repositório (ou faça o download dos arquivos `index.html` e `style.css`).
2.  Abra o arquivo `index.html` em seu navegador web preferido (Google Chrome, Mozilla Firefox, Microsoft Edge, etc.).

---

**Observação:** O código JavaScript está embutido no arquivo `index.html` para simplificar a demonstração. Para projetos maiores, é recomendável separar o JavaScript em um arquivo `.js` dedicado.
