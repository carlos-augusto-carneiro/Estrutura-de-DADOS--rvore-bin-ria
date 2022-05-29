# Estrutura-de-DADOS-arvore-binaria

O adicionar em uma árvore de busca binária sempre vai iniciar colocando o menor a esquerda e o maior a direita.


Caso a raiz seja igual a NULL, será adicionada nela primeira antes dos outros


Vamos ver como funciona o adcionar usando essa árvore.
Nesse caso vemos que o ponteiro aux percorre toda a árvore até o 4.

Imaginamos que queremos adicionar o número 5, o aux vai sair da raiz se pergutando, N é maior que 8?, caso o N fosse maior que 8 iria para direita, mas como o
N=5 ele vai perguntar, N é menor que 8?, como é ele vai para esquerda e chega ao 3, e vai fazer a mesma  pergunta, N é menor que 3, nesse caso não é então ele 
vai para a direita e encontra o 4 e vai fazer a pergunta de novo, N é menor que 4?, nesse caso não então ele vai pra direita, como aux->dir = NULL, então o número
5 vai ficar no lugarl do NULL

![image04](https://user-images.githubusercontent.com/91989796/170873308-01e67ad9-c107-4bc1-8789-999493ac43d2.gif)
