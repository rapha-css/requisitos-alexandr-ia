# Requisitos Funcionais

### O sistema gerencia cadastro e informações de 3 tipos de usuário: Aluno(a), Professor(a) e Bibliotecário(a)
	
+ Informações do(a) Aluno(a):

		* As informações guardadas no sistema, sobre o(a) aluno(a), são: 

			1. Matrícula;
			2. Nome;
			3. Ano cursado no Colégio;
4. E-mail;
5. Senha.
	
	+ Informações do(a) Professor(a):

		* As informações guardadas no sistema, sobre o(a) professor(a) são:

			1. Matrícula;
			2. Nome;
			3. Disciplina;
			4. E-mail;
			5. Senha.

+ Informações do(a) Bibliotecário(a):
	
		* As informações guardadas no sistema, sobre o(a) bibliotecário(a) são:

			1. ID (Identificador Único no sistema);
			2. Nome;
			3. E-mail.

- Todos os cadastros são realizados pelo(a) Bibliotecário(a);
- Todas as informações dos(as) Usuários(as) são guardadas em um banco de dados;
- O(a) Bibliotecário(a) tem acesso à informação de todos os usuários e a permissão de alterá-los quando necessário;
- Os(as) Alunos(as) e Professores(as) terão acesso somente a suas respectivas informações, através da plataforma Web e informando matrícula e senha;
- O(a) Bibliotecário(a) poderão ter acesso ao sistema informando somente o seus  respectivos códigos, na aplicação Desktop.





### Livros

- O sistema gerencia os livros contidos na biblioteca, catalogando-os ou excluindo-os dos registros. 

	+ O(a) Biliotecário(a) cadastra os livros na biblioteca.

	+ Para catalogar os livros o(a) Bibliotecário(a) insere as seguintes informações no sistema:  

	+ Título do livro;
+ Autores do livro;
+ Editora(s) do livro;
+ Gênero do livro.

(Essas informações serão utilizadas na elaboração dos bancos de dados do sistema);


	- Os livros, após cadastrados no sistema, possuirão suas informações parcialmente disponibilizadas aos(às) Alunos(as) e Professores(as), através da plataforma Web, sendo elas:

	+ Se o livro está emprestado ou não;
+ Título do livro;
+ Autores do livro;
+ Editora(s) do livro;
+ Gênero do livro.

- Caso a data de entrega esteja próxima de chegar, será enviado um e-mail para lembrá-lo(a) da devolução do livro.

- Os(as) Alunos(as) poderão colocar até 8 livros na lista de desejo (caso estejam emprestados). E ao fazer isso, serão notificadas quando o livro estiver disponível;

* Esta lista estará disponível apenas ao(à) Bibliotecário(a), na parte Desktop do Sistema.

- Alunos(as) e Professores(as) colocados(as) na Lista Negra (por terem furtado algum livro ou terem causado alguma outra perturbação que venha a prejudicar o sistema de gerenciamento da biblioteca) serão impedidos(as) de acessar o sistema até serem retirados(as) da lista.

- O sistema irá fazer recomendações de leitura aos(às) Usuários(as) baseados nos gêneros lidos recentementes.

- O sistema enviará um e-mail aos(às) Alunos(as) e Professores(as) quando um novo livro for catalogado.