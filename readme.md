## Plugin de Dados 

O Plugin de Dados - é uma ferramenta que permite acessar e manipular dados por meio de APIs externas. Ele possui funcionalidades para adicionar conexões com APIs, autenticação, rotas de consulta, models para os dados e endpoints criados.

### API

Responsável por adicionar conexões com APIs externas. Por meio dela, é possível configurar os endpoints das APIs e defini-los como conexões. Essas conexões podem ser utilizadas posteriormente para realizar consultas e manipular os dados dessas APIs.

### AUTH

O módulo de autenticação do Plugin de Dados - oferece recursos para garantir a segurança das informações. É possível implementar autenticação em endpoints específicos ou em todas as rotas do plugin. Isso permite que os usuários sejam autenticados antes de acessar os dados e recursos disponíveis.

### ENDPOINTS

Os endpoints são as rotas disponíveis no Plugin de Dados. Eles permitem realizar consultas e manipular os dados das APIs externas. Alguns exemplos de endpoints que podem ser adicionados são: buscar um recurso específico, obter uma lista de recursos, criar, atualizar ou excluir um recurso.

### MODELS

Os models são os objetos que representam os dados que serão manipulados pelo Plugin de Dados. Eles definem a estrutura dos dados que serão acessados, permitindo que sejam realizadas operações como criação, leitura, atualização e exclusão desses dados.

### ROUTES

As routes são as rotas do Plugin de Dados que correspondem aos endpoints disponíveis. Elas são configuradas no sistema e definem as ações que podem ser executadas em cada endpoint. É possível adicionar rotas para buscar, criar, atualizar ou excluir recursos específicos.

### Comandos

Para ativar o ambiente virtual do Plugin de Dados, utilize o seguinte comando:

```
source env/bin/activate
```

### Comandos Docker

Para executar o Plugin de Dados com o Docker, são necessários os seguintes comandos:

```
docker compose build
```

```
docker compose up
```