Desenvolver os itens abaixo em php utilizando banco de dados mysql, utilizar padrão MVC se tiver conhecimento.
 Tabelas:
    usuario (
        id int, 
        nome varchar(150), 
        cpf varchar(11), 
        email varchar(50), 
        senha varchar(60)
    )
    
    endereco (
        id int, 
        usuario_id int, 
        padrão varchar(1), 
        cep varchar(10), 
        logradouro varchar(100), 
        numero smallint, 
        complemento varchar(150), 
        cidade varchar(150), 
        uf varchar(2)
    )
 
1. Criação de tela de login onde deve ter usuário (email) e senha e faze-lo logar, deve existir um botão para cadastrar novo usuário (nome, email, cpf e senha).
2. Ao logar deve mostrar os dados cadastrados e ter um botão editar e outro excluir. Executar a alteração e exclusão do usuário.
3. Na mesma tela de cadastro com o usuário logado: adicionar, editar ou remover novos endereços e escolher um como padrão. Voltando para a tela principal do usuário, mostrar o endereço padrão e a quandidade de endereços cadastrados.
4. Fazer a validação dos campos utilizando javascript e php.
