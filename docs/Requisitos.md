# Requisitos

Entidades: Biblioteca, Livro, categoria, Funcionario, Mensagem, Usuário, Autenticação

###### 1 - O sistema deve ser capaz de realizar o cadastro do usuário na biblioteca.
###### 2 - O Usuário possui codigo,cpf,nome,email,endereço,username, senha, status_usuer, qnt_emprest_ativos.
###### 3 - O sistema deve ser capaz de cadastrar as obras(livros).
###### 4 - Um livro tem título,autor,isbn,data_publicação,editora, edição e status_obra, quantidade e categoria.
###### 5 - Os livros são mantidos por 1 ou mais funcionários.
###### 6 - um emprestimo possui cpf,isbn_da_obra,data_emprestimo,data_devolição, status_emp e data de retorno.
###### 7 - O usuario pode  realizar no máximo 3 empréstimos (caso possua 3 emprestimos ativos).
###### 8 - uma categoria possui código e nome.
###### 9 - status_user é ativo ou inativo. 
###### 10 - status_obra é disponível ou indisponível
###### 11 - Para o funcionário manter os livros ele precisa ter uma autenticação no sistema.
###### 12 - A autenticação tem/precisa do username e senha.
###### 13 - O usuário só pode realizar um emprestimo se tiver autenticação no sistema.
###### 14 - o sistema deve ser realizar o cadastro do funcionario(os). A biblioteca tem vários funcionários.
###### 15 - O funcionário possui código, nome, função, salário, Username, email, senha, cpf. 
###### 16 - O funcionário é responsável por manter as obras, os empréstimos e os usuários.
###### 17 - O funcionário recebe/envia mensagem para o usuário informando que o livro foi recebido.Na mensagem(entidade) tem o username de quem enviou e a mensagem.
###### 18 - O usuário também envia/recebe uma mensagem informando que recebeu o livro emprestado.
