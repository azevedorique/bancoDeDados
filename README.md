# bancoDeDados
atividade de banco de dados 

ALUNO : Henrique Guerra Gonçalves de Azevedo

Modelo Escolhido : Sistema de Gerenciamento de Biblioteca 

Entidades implementadas: 

Livro,
Autor,
Editora,
Usuário,
Empréstimo,
Categoria.

as entidades editora e categoria foram adicionadas pensando em um sistema real de banco de dados
para esse modelo, onde seria muito mais simples buscar um livro no banco de dados sabendo a editora
que o publicou e a categoria a qual ele pertence.

Foram implementados os seguintes relacionamentos: 

Um Livro pode ter um ou mais autores, da mesma forma que um autor pode escrever vários livros.

O livro é publicado por uma editora, e uma editora pode publicar vários livros.

Um livro participa de um empréstimo realizado pelo usuário, que pode pegar emprestado um ou mais livros.

Um livro pode ou não estar disponível para empréstimo.

Um livro pode pertencer a uma ou mais categorias.

Também foi feita uma especialização-generalização na entidade usuário, que se subdivide em funcionário e membro. O funcionário terá
como atributos o cargo que ocupa, o seu salário, a data em que foi contratado e o seu horário de trabalho. Já o membro possuirá os atributos
data de cadrasto e histórico de empréstimos. Tanto funcionário quanto membro possuem o atributo chave ID, representando a sua identificação.




