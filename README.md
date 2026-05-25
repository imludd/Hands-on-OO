# Hands-on-OO
📚 README - Exercícios de Collections em Java
📌 Sobre a atividade

Esta atividade tem como objetivo praticar o uso das principais Collections do Java, trabalhando com estruturas como:

ArrayList
HashSet
HashMap
Queue

Além disso, a atividade também desenvolve conceitos de:

Programação Orientada a Objetos (POO)
Classes e objetos
Menus interativos
Controle de dados
Manipulação de listas e filas
🧩 Exercícios Desenvolvidos
1️⃣ Lista de Compras com ArrayList
Objetivo

Criar uma lista de compras utilizando ArrayList<String>.

Funcionalidades
Adicionar 5 produtos
Exibir todos os produtos cadastrados
Mostrar a quantidade total de produtos
Conceitos utilizados
ArrayList
Laços de repetição
Métodos .add() e .size()
2️⃣ Média de Notas com ArrayList<Double>
Objetivo

Armazenar notas de alunos e calcular a média da turma.

Funcionalidades
Adicionar 4 notas
Calcular média
Verificar se a média é maior ou igual a 7
Conceitos utilizados
ArrayList<Double>
Operações matemáticas
Estruturas condicionais (if)
3️⃣ Controle de Presença com HashSet
Objetivo

Cadastrar alunos presentes evitando nomes duplicados.

Funcionalidades
Adicionar nomes de alunos
Inserir nomes repetidos
Exibir lista sem repetições
Mostrar quantidade total de presentes
Conceitos utilizados
HashSet
Remoção automática de duplicados
Método .size()
4️⃣ Cadastro de Alunos com HashMap
Objetivo

Gerenciar alunos usando matrícula como chave.

Funcionalidades
Cadastrar matrícula e nome
Buscar aluno pela matrícula
Remover aluno
Listar todos os alunos cadastrados
Conceitos utilizados
HashMap<Integer, String>
Métodos .put(), .get() e .remove()
5️⃣ Fila de Atendimento com Queue
Objetivo

Simular uma fila de clientes.

Funcionalidades
Adicionar 5 clientes
Mostrar próximo atendimento
Atender 2 clientes
Exibir fila atualizada
Conceitos utilizados
Queue
LinkedList
Métodos .add(), .poll() e .peek()
📖 Sistema de Biblioteca
Classe Livro

O sistema possui uma classe chamada Livro com os seguintes atributos:

int codigo;
String titulo;
String autor;
boolean disponivel;
Menu do Sistema
1 - Cadastrar livro
2 - Listar livros
3 - Emprestar livro
4 - Devolver livro
0 - Sair
Regras do Sistema
Um livro só pode ser emprestado se estiver disponível
Ao emprestar, o status muda para indisponível
Ao devolver, o status volta para disponível
Os livros são armazenados em:
ArrayList<Livro>
Conceitos utilizados
Programação Orientada a Objetos
Classes e objetos
ArrayList de objetos
Menus interativos
Manipulação de atributos
🍔 Sistema de Pedidos da Lanchonete
Classe Pedido

O sistema possui uma classe Pedido contendo:

int numeroPedido;
String nomeCliente;
String itemPedido;
double valor;
String status;
Status possíveis
PENDENTE
PREPARANDO
FINALIZADO
Funcionalidades do Sistema
1 - Cadastrar pedido
2 - Listar pedidos
3 - Atualizar status de um pedido
4 - Buscar pedido pelo número
5 - Mostrar valor total dos pedidos
0 - Sair
Coleções sugeridas

Pode ser utilizado:

ArrayList<Pedido>

ou

HashMap<Integer, Pedido>
Conceitos utilizados
Classes e objetos
Menus interativos
Busca de informações
Atualização de dados
Controle de status
Soma de valores
Collections em Java
🛠️ Tecnologias Utilizadas
☕ Java
IDE:
NetBeans

🎯 Objetivo Geral da Atividade

Praticar o desenvolvimento de sistemas utilizando as principais estruturas de coleção do Java, aplicando conceitos fundamentais da programação orientada a objetos e manipulação de dados.

👩‍💻 Autora

Ludmilla Santos
Estudante de Ciência da Computação 🚀
