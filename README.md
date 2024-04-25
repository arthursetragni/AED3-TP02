# AED3-TP02
Lista invertida

Dado o codigo disponibilizado no dia 07/04 e a classe ListaInvertida, essas foram as mudanças feitas:

No arquivo MenuLivros

1) mexi no menu para ter dois jeitos de busca, por isbn e por titulo
2) Criei a funcao readTexto dentro de arqLivros que vai retornar um array de livros com os termos procurados
3)Criei a funcao mostrarLivros para imprimir um array de livros


No arquivo ArquivoLivros

1)importei a classe listaInvertida
2)criei a funcao readTexto que deve pegar os IDs da lista invertida, e chamar a funcao read(ID) para ir concatenando esses livros em um array e retorna-los
3) Na função create, acrecentei uma parte que adiciona cada paralvra do titulo do livro na lista invertida com o respectivo ID

Observações
A busca na lista invertida esta case sensitive, logo procurar por "teste" é diferente de procurar por "Teste".
A busca funciona apenas para titulos de livros.
A busca esta restringida para pegar no maximo 20 livros como resultado.
O reaproveitamento de espaços vazios do TP1 não esta implementado.
