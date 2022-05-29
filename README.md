# Estrutura-de-DADOS-arvore-binaria

O adicionar em uma árvore de busca binária sempre vai iniciar colocando o menor a esquerda e o maior a direita.


Caso a raiz seja igual a NULL, será adicionada nela primeira antes dos outros


Vamos ver como funciona o adcionar usando essa árvore.
Nesse caso vemos que o ponteiro aux percorre toda a árvore até o 4.



![image04](https://user-images.githubusercontent.com/91989796/170873308-01e67ad9-c107-4bc1-8789-999493ac43d2.gif)


Imaginamos que queremos adicionar um número(N), o aux vai sair da raiz se pergutando, N é maior que 8?, caso o N fosse maior que 8 iria para direita, caso fosse
menor que 8 iria para a direita.

suponhamos que iriamos adicionar o número 5, N=5, ele vai perguntar, N é menor que 8?, como N é menor que 8, 5 < 8, então ele vai para esquerda e chega ao 3, e vai fazer a mesma  pergunta, N é menor que 3, nesse caso N não é menor que 3, 5 > 3, então ele vai para a direita e encontra o 4 e vai fazer a pergunta de novo, N é menor que 4?, nesse caso N não é menor que 4, 5 > 4, então ele vai pra direita, como a direita do 4 não tem nada dizemos que ele ta apontando para NULL, então o número 5 vai ficar no lugar do NULL.

Por fim ficaria assim a árvore.


![adicionado 5](https://user-images.githubusercontent.com/91989796/170874902-6eec83ad-9b08-4e85-9d22-71593e1247e1.png)
