# resumoApiREST

# Api REST e RESTFul

API REST (Interface de Programação de Aplicações Representacional por Estado) é uma arquitetura que define um conjunto de princípios para o design de serviços web, utilizando o protocolo HTTP. Ela permite a comunicação entre sistemas de maneira eficiente, utilizando métodos como GET, POST, PUT e DELETE para operar em recursos.

Já o RESTful refere-se à implementação efetiva desses princípios. Uma API RESTful segue as diretrizes do REST, utilizando URIs para ver recursos, métodos HTTP para concretizar operações nesses recursos e retornando representações dos recursos em formatos como JSON ou XML. É uma abordagem flexível e escalável para o desenvolvimento de APIs web.

## Diferenças entre REST e RESTFul

REST e RESTful são nomes que frequentemente andam juntos no contexto do desenvolvimento de serviços web, mas apresentam diferenças leves em suas aplicações.

REST, em sua essência, é uma arquitetura de software que estabelece princípios fundamentais para o design de serviços web. Ele prioriza a identificação de recursos por meio de URIs, a utilização dos métodos HTTP apropriados, o emprego de representações como JSON ou XML, e a abordagem stateless, onde cada requisição do cliente contém todas as informações necessárias.

Por outro lado, RESTful refere-se à implementação prática desses princípios em um serviço web específico. Isso faz com que a criação de URIs significativos que identificam claramente os recursos, o uso correto dos métodos HTTP em conformidade com as ações do serviço, e a escolha adequada de formatos de representação, como JSON ou XML, para transmitir dados.

Ao ter uma abordagem RESTful, os desenvolvedores buscam aplicar os princípios REST de maneira pragmática, adaptando eles a necessidades específicas do serviço em questão. Dessa jeito, a utilização efetiva desses princípios resulta em sistemas web muito bem homogêneos e eficientes.

## HTTP verbs

HTTP verbs, também conhecidos como métodos HTTP, são comandos que indicam a ação a ser realizada em um recurso identificado. Aqui estão alguns dos principais:

1- GET: Recupera dados de um recurso especificado sem alterar o estado do servidor.

2- POST: Envia dados para serem processados a um recurso especificado, muitas vezes usado para criar novos recursos.

3- PUT: Atualiza um recurso identificado ou cria um novo se ele não existir. Substitui completamente o recurso.

4- DELETE: Remove o recurso especificado no URI.

5- PATCH: Aplica modificações parciais a um recurso.

Esses métodos são fundamentais para a comunicação cliente-servidor na arquitetura web, proporcionando operações muito padronizadas para adulterar recursos em servidores através do protocolo HTTP.

## HTTP Status Code

Os códigos de status HTTP são indicadores numéricos retornados por um servidor web para informar sobre o resultado de uma solicitação feita pelo cliente. Alguns códigos comuns incluem:

1- Informational: Indica que a solicitação foi recebida, continuará sendo processada ou que o cliente deve aguardar mais instruções.

2- Success: Indica que a solicitação foi recebida, compreendida e aceita com sucesso. 

3- Redirection: Indica que há a necessidade de realizar ações adicionais para completar a solicitação.

4- Client Error: Indica que ocorreu um erro por parte do cliente. Exemplo error 404 (Not Found) para recurso não encontrado.

5- Server Error: Indica que ocorreu um erro no servidor ao processar a solicitação.

Esses códigos ajudam a diagnosticar e corrigir problemas durante a comunicação entre clientes e servidores web.

---

Autor do resumo: Vinicius Dantas - 01522137
