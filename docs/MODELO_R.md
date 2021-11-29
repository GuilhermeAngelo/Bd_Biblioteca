Chave-primaria: *Italico*(Não encontrei como sublinhar, então resolvi colocar em italico para identificar as chaves primarias)    
Chave-Estrangeira:**Negrito**

Endereco(*Codigo*, Rua, Num)

Biblioteca(*Codigo*, Nome,Site, email, Cod_Endereco)

Usuario(*Codigo*, CPF, Nome, Email, UserName, Senha, Quant_Empres_Ativos, Status_User, **Cod_Endereco, Cod_Biblioteca**)

Mensagem(*Codigo*, UserName

Livro(*ISBN*, Titulo, Autor, Status_Obra, Quantidade, Edicao, Editora, Data_Publicacao, **Cod_Biblioteca, Cod_Categoria**)

Categoria(*Codigo*, Nome)

Funcionario(*Codigo*, Nome,CPF, Salario, Funcao, UserName, Email, Senha, **Cod_Endereco, Cod_Biblioteca**)

Autenticacao(*UserName*, Senha, **Cod_Funcionario, Cod_Usuario**)

Funcionario_Livro(*Codigo*, Cod_Livro, Cod_Funcionario
Usuario_Livro(Codigo, **Cod_usuario, Cod_Livro**, ISBN_Obra, Data_retorno, Status_Emprestimos, Data_Emprestimo)

UsuarioMensagem(*Codigo*, **Cod_Usuario, Cod_Mensagem**)

FuncionarioMensagem(*Codigo*, **Cod_Funcionario, Cod_Mensagem**)

![WhatsApp Image 2021-11-29 at 13 03 29](https://user-images.githubusercontent.com/53875866/143909378-c1655d41-f826-4b6b-a70e-9b5817bace03.jpeg)
