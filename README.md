# Api Rest Star Wars

	Projeto inicial para aprendizagem de Java e Rest Api's. 

### Objetivo
	
	Criar uma api rest com a relação de planetas de star wars.

### Requisitos da Api

- Inserir um planeta do universo Star Wars
- Listar todos os planetas inseridos
- ter um update para o nome do planeta
- deletar um planeta dado um id
- utilizar a swapi dev api https://swapi.dev/ para criar um método que receba o nome de um planeta e retorne quantas vezes esse planeta apareceu em filmes (caso não encontre o planeta, tratar esse erro)

### Requisitos do planeta a ser inserido

- id
- nome
- clima
- terreno
- número de aparições em filmes

### Observações

 1. Seria interessante que, ao se inserir um planeta, ele faça uma busca e já insira, caso exista na base, o seu número de aparições em filmes.

 2. Seria também interessante que a api tenha uma certa cobertura de testes e que seus endpoints sejam documentados (Swagger).

 3. A gestão de dependências deve ser através de gradle ou maven

 4. O mais importante: O projeto deve utilizar TDD e ter uma boa cobertura de testes.

### Como rodar e testar a aplicação *(TODO)*.
