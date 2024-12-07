# Desafio de Game - Detona Ralph

Durante este projeto diversos conceitos foram demonstrados, entre eles a estruturação de um projeto de jogo e sua importância para o andamento do projeto, incluindo organização de código e arquivos, facilitando possível mudanças e adições ao projeto em momentos futuros, como criar uma página HTML para ser a base do jogo, além de como a estilizar fazendo o uso de CSS.

Por fim, aprendemos o básico sobre como criar uma engine para jogos e seu funcionamento. 

Além disso tudo, é claro foram apresentadas claro diversas dicas e sugestões de boas práticas.

# Diferenciais de meu projeto com o projeto base
## Ao clicar em um local onde não tem inimigo (Detona Ralph) a quantidade de vidas diminui em 1.
Além disso, quando a quantidade de vidas chega a 0 acontece o Game Over.

## Adicionados mais efeitos sonoros 
### Quando Ralph se move há um efeito sonoro para avisar o jogador que ele está em uma nova posição ou que sua hitbox foi restaurada. 
Às vezes o número sorteado para a posição dele é o mesmo que ele já está, portanto ele permanece no mesmo quadrado quando já é possível clicar nele novamente, o soundcue evita que o jogador perca pontos por ele ficar na mesma posição. <br>
OBS: Por questões de evitar spam sonoro, o navegador evita que o som saia a não ser que clique na tela antes, portanto até o jogador clicar e conseguir pontos ou errar, o soundcue de movimento nao irá tocar.

### Foi adicionado mais um efeito sonoro ao clicar em um quadrado em branco e perder uma vida.

## Dificuldade incremental, a cada 20s Ralph se move mais rápido.
Por conta disso a quantidade de vidas foi aumentada para 10, para evitar um game over prematuro.
OBS: Não sei dizer o motivo, mas a diferença na velocadade do jogo só é notável ao chegar em valores abaixo de 500ms, antes desse ponto é como se nada mudasse.

# Créditos: Este projeto foi desenvolvido seguindo o projeto Criando um Jogo do Detona Ralph com Javascript da DIO.
