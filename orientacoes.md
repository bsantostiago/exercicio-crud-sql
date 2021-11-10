# Exercícios CRUD SQL

Usando o banco de dados do exercício anterior e as tabelas de clientes e contas, faça as seguintes operações SQL:

1. Insira na tabela clientes 3 clientes fictícios com nome, sobrenome, email, tipo (pessoa física) e endereço.

2. Insira na tabela clientes 2 clientes fictícios com nome, sobrenome, email, tipo (pessoa jurídica) e endereço.

3. Insira na tabela contas, 5 contas com código da conta, data de abertura, tipo (Poupança ou Corrente) e cliente_id. ATENÇÃO: o campo cliente_id deve ser associado ao id dos clientes cadastrados na tabela clientes conforme a seguir:

	- 2 clientes pessoa física devem ter conta do tipo corrente.
	- 1 cliente pessoa física deve ter conta do tipo poupança.
	- 2 clientes pessoa jurídica devem ter conta do tipo corrente
	
4. Faça 1 consulta SQL que traga os dados dos clientes que são pessoa física ordernados pelo nome.

5. Faça 1 consulta SQL que traga os dados dos clientes que são pessoa jurídica ordernados pelo nome.

6. Faça 1 consulta SQL que traga o nome, tipo e e-mail dos clientes junto com a informação de qual tipo de conta possuem ordenados pelo tipo de conta em ordem decrescente.

7. Altere o e-mail de somente um cliente.

8. Apague um dos clientes que é pessoa jurídica.