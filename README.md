 # Api REST e RESTFul

Uma API REST (Representational State Transfer) é uma interface de programação de aplicações (API) que segue os princípios do estilo de arquitetura REST. O REST é um modelo de arquitetura de software que define uma série de requisitos para que as APIs sejam desenvolvidas.

Os princípios do REST são:
- Representação: os recursos são representados por URIs (Uniform Resource Identifiers).
- Estado: o estado de um recurso é representado em sua representação.
- Transferência: as representações de recursos são transferidas entre clientes e servidores usando o protocolo HTTP.
- Interface: a interface de uma API REST deve ser uniforme.
- Cadeia: os recursos podem ser relacionados uns aos outros por meio de URIs.

Uma API RESTful é uma API REST que segue os princípios do REST o mais próximo possível.


## Diferenças entre REST e RESTFul
As principais diferenças entre REST e RESTFul são:

- REST é um modelo de arquitetura, enquanto RESTFul é uma implementação desse modelo.
- RESTFul deve seguir os princípios do REST, como o uso de URIs para representar recursos e o uso do protocolo HTTP para transferir representações de recursos.
- RESTFul geralmente usa formatos de dados padronizados, como JSON ou XML, para representar recursos. Esses formatos de dados são fáceis de entender e processar por diferentes sistemas.

Em outras palavras, uma API RESTful é uma API que segue os princípios do REST e usa o protocolo HTTP de forma consistente.

## HTTP verbs
O protocolo HTTP define uma série de verbos que podem ser usados para realizar diferentes ações em uma API REST.

Os principais verbos HTTP usados em APIs REST são:

- GET: Obter uma representação de um recurso.
- POST: Criar um novo recurso
- PUT: Atualizar um recurso existente.
- DELETE: Excluir um recurso existente.
- PATCH: Aplicar modificações parciais a um recurso.

## HTTP Status Code
O protocolo HTTP define uma série de códigos de status que podem ser usados para indicar o resultado de uma solicitação HTTP.

Os principais códigos de status HTTP usados em APIs REST são:

- 200 OK: A solicitação foi bem-sucedida.
- 400 Bad Request: A solicitação foi mal formada.
- 401 Unauthorized: O cliente não está autorizado a realizar a solicitação.
- 403 Forbidden: O cliente está autorizado a realizar a solicitação, mas não tem permissão para fazê-lo.
- 404 Not Found: O recurso solicitado não foi encontrado.

## Segurança
APIs RESTful devem ser projetadas com segurança em mente, usando mecanismos como autenticação e autorização para proteger os recursos que elas fornecem.

A autenticação é o processo de verificar a identidade de um usuário ou sistema. A autorização é o processo de determinar se um usuário ou sistema tem permissão para acessar um recurso.

Aqui estão alguns exemplos de como a segurança pode ser implementada em APIs RESTful:

- Usar autenticação HTTP básica: Isso é um método simples de autenticação que usa um nome de usuário e uma senha para verificar a identidade de um usuário.
- Usar autenticação OAuth 2.0: Isso é um método mais seguro de autenticação que usa tokens para verificar a identidade de um usuário.
- 
## Autor do resumo
Carlos Frederico - 01285947




