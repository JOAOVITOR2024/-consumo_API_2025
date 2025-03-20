repositorio criado e commitado 100% no github web, o objetivo do projeto foi criar 4 tipos diferentes de tuplas de arquivos URL em formato json.
arquivos usados: 'https://pokeapi.co/api/v2/pokemon/', 'https://rickandmortyapi.com/api/character/', 'https://swapi.dev/api/people/', 'https://anapioficeandfire.com/api/characters/'.
para rodar o arquivo sera necessario criar um ambiente virtual e instalar a biblioteca requests, com uso do pip.

requisitos de tuplas criadas: (id, name, species) do personagem., (name, [ film(s) ]) do personagem., (name, [ tvSeries ]) do personagem., e outro retornando apenas id e nome.

passos: 1- criação do repositorio "consumo_API_2025"

2- Criar um ambiente virtual e instalar a biblioteca requests, com uso do pip.

3-  Implemente o método extract(self, id) da classe API_Rick_Morty, O método deve:
 3.1 Concatenar o ID à URL base para formar o endpoint correto.
 3.2 Fazer uma requisição GET para obter os dados no formato JSON.
 3.3 Retornar uma tupla contendo (id, name, species) do personagem.
 3.4 Tratar exceções para evitar que o programa quebre caso a API não responda corretamente.
 
4- Implemente o método extract(self, id) da classe API_Star_Wars. O método deve:
 4.1 Concatenar o ID à URL base para formar o endpoint correto.
 4.2 Fazer uma requisição GET para obter os dados no formato JSON.
 4.3 Retornar uma tupla contendo (name, [ film(s) ]) do personagem.
 4.4 Tratar exceções para evitar que o programa quebre caso a API não responda corretamente.
 
5- Implemente o método extract(self, id) da classe API_Ice_and_Fire. O método deve:
 5.1 Concatenar o ID à URL base para formar o endpoint correto.
 5.2 Fazer uma requisição GET para obter os dados no formato JSON.
 5.3 Retornar uma tupla contendo (name, [ tvSeries ]) do personagem.
 5.4 Tratar exceções para evitar que o programa quebre caso a API não responda corretamente.

(OBRIGATÓRIO DAR UM COMMIT DE CRIAÇÃO DE METODO POR VEZ)
