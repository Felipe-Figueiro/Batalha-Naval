⚓️ Batalha Naval - Atividade de Lógica de Programação ⚓️
Bem-vindo! Este projeto teve como objetivo por em prática um pouco da Lógica de Programação do meus estudos! 🚀

Este é um jogo clássico de Batalha Naval, desenvolvido em JavaScript para ser jogado diretamente no terminal. O objetivo é testar e aprimorar conceitos fundamentais como arrays, loops, condicionais e manipulação de entrada do usuário.

💡 Como o Código Funciona
O jogo Batalha Naval foi construído com a seguinte lógica:

Configuração do Jogo: O jogador escolhe um nível de dificuldade que define o tamanho do tabuleiro, o número de navios a serem afundados e o total de tentativas.

Criação dos Tabuleiros: O código cria dois tabuleiros, ambos de mesmo tamanho:

tabuleiro: Um tabuleiro "escondido", usado pelo computador para posicionar os navios (representados como "Barco" ou "Mar").

mar: Um tabuleiro visível para o jogador, que mostra apenas os seus tiros (representados por '💥' para acerto e '❌' para erro).

Posicionamento dos Navios: O jogo posiciona os navios aleatoriamente no tabuleiro "escondido", garantindo que não fiquem na mesma posição.

Loop Principal: A partida acontece dentro de um loop while. A cada rodada, o jogador insere as coordenadas de um tiro. O loop continua até que todos os navios sejam encontrados ou as tentativas se esgotem.

Verificação do Tiro: O código verifica se o tiro do jogador acertou a posição de um navio no tabuleiro "escondido".

Fim de Jogo: Ao final da partida, uma mensagem de vitória ou derrota é exibida. O tabuleiro "escondido" é revelado, e o jogador tem a opção de reiniciar o jogo.

🕹️ Como Jogar
Certifique-se de ter o Node.js instalado em sua máquina.

Abra o terminal na pasta do projeto.

Execute o código com o comando:

(Bash)

node nome_do_arquivo.js
O jogo irá pedir que você escolha um nível de dificuldade de 1 a 4.

Em seguida, digite a linha e a coluna do seu tiro para tentar acertar um navio.

Acompanhe o tabuleiro visível para ver o resultado de seus tiros.

No final, você pode escolher se deseja jogar novamente.

🙏 Obrigado por visitar este repositório! Não está muito polido, mas foi eficiente no objetivo de pensar em soluções para alcançar o projeto.
Se tiver sugestões ou dúvidas, ou encontrar erros sinta-se à vontade para entrar em contato! ✨
