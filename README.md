**# AED3-TP02**  
**Lista invertida**

Dado o código disponibilizado no dia 07/04 e a classe `ListaInvertida`, estas foram as mudanças feitas:

No arquivo **MenuLivros**:

1. Mexemos no menu para ter dois modos de busca, por ISBN e por título.
2. Chamamos uma nova função `readTexto` criada dentro de `arqLivros` que retorna um array de livros com os termos procurados.
3. Criamos a função `mostrarLivros` para imprimir um array de livros.

No arquivo **ArquivoLivros**:

1. Importamos a classe `ListaInvertida`.
2. Criamos a função `readTexto` que deve pegar os IDs da lista invertida e chamar a função `read(ID)` para concatenar esses livros em um array e retorná-los.
3. Dentro da função `readTexto` o método `read` da Lista invertida é chamado uma vez para cada palavra digitada pelo úsuario e o array resultante é a interceção dos resultados.
4. Na função `create`, acrescentamos uma parte que adiciona cada palavra do título do livro na lista invertida com o respectivo ID.
5. No `delete` usamos o mesmo loop do create, porem dessa vez deletando cada ligação entre o Id do livro e cada uma das palavras do titulo
6. Por fim no `update` usamos a logica do delete depois do create, garantindo que o livro atualizado estará corretamente na lista invertida

**Observações**:
- A busca funciona apenas para títulos de livros.
- O reaproveitamento de espaços vazios do TP1 não está implementado.

**Nossa experiência fazendo**: Conseguimos implementar todos os requisitos e todos estão funcionando corretamente. Não tivemos grandes dificuldades em implementar nenhuma operação em particular, a maior dificuldade foi só com o entendimento da classe lista invertida em si. Depois de testa-la um pouco, implementar as operações foi bastante tranquilo.

**Questionário**
* A inclusão acrescenta os termos a lista invertida

* A alteração modifica a lista removendo os termos antigos e acrescentando os novos 

* A remoção de um livro remove os termos da lista invertida 

* A busca por palavras está implementada e retorna os livros com as palavras pesquisadas no título 

* A busca pode ser feita com mais de uma palavra

* As stop words foram retiradas de todo o processo 

* O que fiz além do que está especificado e colocar as palavras chave na lista invertida com toLowerCase para que letras maiúsculas ou minúsculas não interfiram na pesquisa 

* O trabalho funciona corretamente 

* O trabalho está completo 

* O trabalho não é cópia
