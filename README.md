**# AED3-TP02**  
**Lista invertida**

Dado o código disponibilizado no dia 07/04 e a classe `ListaInvertida`, estas foram as mudanças feitas:

No arquivo **MenuLivros**:

1. Mexi no menu para ter dois modos de busca, por ISBN e por título.
2. Chamei uma nova função `readTexto` criada dentro de `arqLivros` que retorna um array de livros com os termos procurados.
3. Criei a função `mostrarLivros` para imprimir um array de livros.

No arquivo **ArquivoLivros**:

1. Importei a classe `ListaInvertida`.
2. Criei a função `readTexto` que deve pegar os IDs da lista invertida e chamar a função `read(ID)` para concatenar esses livros em um array e retorná-los.
3. Dentro da função `readTexto` o método `read` da Lista invertida é chamado uma vez para cada palavra digitada pelo úsuario e o array resultante é a interceção dos resultados.
4. Na função `create`, acrescentei uma parte que adiciona cada palavra do título do livro na lista invertida com o respectivo ID.
5. No `delete` usei o mesmo loop do create, porem dessa vez deletando cada ligação entre o Id do livro e cada uma das palavras do titulo
6. Por fim no `update` usei a logica do delete depois do create, garantindo que o livro atualizado estará corretamente na lista invertida

**Observações**:
- A busca na lista invertida é case sensitive, ou seja, procurar por "teste" é diferente de procurar por "Teste".
- A busca funciona apenas para títulos de livros.
- A busca está restrita a retornar no máximo 20 livros como resultado.
- O reaproveitamento de espaços vazios do TP1 não está implementado.
