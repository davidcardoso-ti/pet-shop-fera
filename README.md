@brief Informações gerais sobre o projeto.

Projeto 3 da disciplina IMD0030 LP1, ministrada pelo Prof. Silvio Sampaio no curso BTI da UFRN.

Programa
--

Pet Fera

Objetivo
--

- O objetivo deste trabalho é customizar o programa de cadastro de animais para a loja de animais silvestres **Pet Fera**.
- Principais melhorias:
	- Uso do conteiner 'map' da STL
	- Uso de biblioteca dinâmica
	- Implementação do programa secundário Exportar
	- Tratamento de exceções

Um pouco sobre o funcionamento da Pet Fera
--

- **Pet Fera** é uma loja que comercializa animais silvestres com os devidos cuidados e autorizações do
Instituto Brasileiro do Meio Ambiente e dos Recursos Naturais Renováveis (IBAMA). Para garantir
a saúde e o bem-estar dos animais sob sua tutela, a **Pet Fera** mantém uma equipe de profissionais
capacitados, incluindo um grupo de veterinários e tratadores. Assim, para cada animal são
atribuídos um veterinário e um tratador que juntos garantirão a saúde e o bem-estar dele.

Opções do menu principal do programa Pet Fera (build/petfera/petfera.exe)
--

- (0) Sair
- (1) Pesquisar funcionário
- (2) Pesquisar animal
- (3) Excluir funcionário pelo ID
- (4) Excluir animal pelo ID
- (5) Cadastro de funcionário
- (6) Cadastro rápido de animal

Opções do programa secundário Exportar (build/petfera/exportar.exe)
--

- Este programa não pede entrada de dados durante a execução. Porém, aceita parametros via linha de comando:
	- -c <classe> 			=> filtra por classe de animal (opcional)
	- -t <tratador> 		=> filtra por tratador (opcional)
	- -v <veterinario> 		=> filtra por veterinario (opcional)
	- <arquivo_exportacao> 	=> arquivo usado para salvar o resultado (obrigatório)

Informações adicionais
--

- Link do relatório: https://goo.gl/7DPME2
