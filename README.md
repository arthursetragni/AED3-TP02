# AED3-TP02
Lista invertida

Dado o código disponibilizado no dia 07/04 e a classe ListaInvertida, estas foram as mudanças feitas:

No arquivo MenuLivros:

Mexi no menu para ter dois modos de busca, por ISBN e por título.
Criei a função readTexto dentro de arqLivros que retorna um array de livros com os termos procurados.
Criei a função mostrarLivros para imprimir um array de livros.
No arquivo ArquivoLivros:

Importei a classe ListaInvertida.
Criei a função readTexto que deve pegar os IDs da lista invertida e chamar a função read(ID) para concatenar esses livros em um array e retorná-los.
Na função create, acrescentei uma parte que adiciona cada palavra do título do livro na lista invertida com o respectivo ID.
Observações:

A busca na lista invertida é case sensitive, ou seja, procurar por "teste" é diferente de procurar por "Teste".
A busca funciona apenas para títulos de livros.
A busca está restrita a retornar no máximo 20 livros como resultado.
O reaproveitamento de espaços vazios do TP1 não está implementado.
