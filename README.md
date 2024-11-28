Sistema de Gestão de Empréstimos de Livros
Descrição do Projeto
Este projeto é um sistema de gestão de empréstimos de livros desenvolvido para atender às necessidades de uma biblioteca universitária. Atualmente, a biblioteca realiza todo o controle de forma manual, o que gera dificuldades no registro, consulta e monitoramento do acervo e dos empréstimos. Este sistema busca informatizar e otimizar o processo, tornando-o mais eficiente e reduzindo erros.

Objetivo
Fornecer um sistema que permita à biblioteca:

Gerenciar o acervo de livros.
Controlar os empréstimos e devoluções.
Monitorar a disponibilidade dos livros em tempo real.
Implementar uma fila de espera automática para livros indisponíveis.
Enviar alertas para devoluções atrasadas, facilitando o controle.
Principais Funcionalidades
1. Gestão de Livros
Registro de novos livros com detalhes como título, autor, ISBN, ano de publicação e quantidade disponível.
Atualização das informações dos livros.
Exclusão de livros do sistema.
Consulta de livros por título, autor ou ano de publicação.
2. Empréstimo de Livros
Registro de empréstimos com controle de datas de retirada e devolução.
Consulta de disponibilidade de livros por parte dos estudantes.
Gerenciamento de fila de espera para livros emprestados, com notificação automática quando um livro for devolvido.
Envio de alertas para devolução dentro do prazo e notificação de atrasos.
Tecnologias Utilizadas
Backend: Node.js com Firebase (Firestore) para gerenciar os dados.
Firebase Emulator: Para testes locais do Firestore e outros serviços.
Ferramentas Adicionais: Express para rotas e API, Body-Parser para processar requisições.
Fases do Desenvolvimento (Processo RUP)
O projeto foi desenvolvido seguindo as fases do Rational Unified Process (RUP):

Iniciação:

Documento de visão e levantamento de requisitos funcionais e não funcionais.
Planejamento do cronograma e distribuição de tarefas.
Elaboração:

Criação de diagramas de casos de uso.
Desenvolvimento de protótipos das telas principais.
Refinamento dos requisitos.
Construção:

Implementação do sistema completo com funcionalidades CRUD para livros e empréstimos.
Gerenciamento da fila de espera e controle de devoluções.
Testes de unidade e integração.
Transição:

Testes finais e validação do sistema.
Documentação completa (manual do usuário e guia de instalação).

Licença
Este projeto é de uso acadêmico e não possui uma licença oficial. Sinta-se à vontade para estudar e reutilizar partes do código conforme necessário.


Preparação para implantação.
