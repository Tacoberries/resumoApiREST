# APIs REST e RESTful

As APIs RESTful, oferecem uma interface de programação de aplicações alinhada aos princípios da arquitetura REST (Representational State Transfer). Essa arquitetura, baseada em princípios fundamentais da web, utiliza uma abordagem cliente-servidor e identifica recursos por meio de URLs. A comunicação entre cliente e servidor se dá através de métodos HTTP, como GET, POST, PUT e DELETE. As APIs RESTful são escolhas comuns na construção de serviços web, aplicações móveis e integração de sistemas distribuídos.

## Diferença entre REST e RESTful

Enquanto REST define um conjunto de princípios e restrições arquiteturais, as APIs RESTful são implementações que seguem esses princípios apartir de ferramentas como o uso de métodos HTTP, URLs e transferência de dados entre cliente e servidor.

## HTTP Verbs

Os verbos HTTP indicam as ações a serem realizadas em um recurso.

- **GET:** Obtém informações sobre um recurso.
- **POST:** Submete dados a um recurso específico.
- **HEAD:** Similar ao GET, solicita uma resposta sem o corpo, só o cabeçalho.
- **CONNECT:** Estabelece uma conexão de túnel direto para um servidor.
- **PUT:** Substitui todas as representações atuais do recurso pelo conteúdo enviado.
- **DELETE:** Remove um recurso especificado.
- **OPTIONS:** Descreve as opções de comunicação para o recurso de destino.
- **PATCH:** Aplica modificações parciais a um recurso.
- **TRACE:** Executa um teste de loop-back de mensagem ao longo do caminho para o recurso de destino.

## Códigos de Status HTTP

Os códigos de status de resposta HTTP são indicadores numéricos enviados pelo servidor para informar o resultado de uma solicitação do cliente, agrupados em cinco classes:

1. Respostas Informativas (100 – 199)
2. Respostas Bem-sucedidas (200 – 299)
3. Mensagens de Redirecionamento (300 – 399)
4. Respostas de Erro do Cliente (400 – 499)
5. Respostas de Erro do Servidor (500 – 599)

Exemplos incluem:

- **102 Processing:** O cliente recebeu uma requisição e está processando, mas ainda não tem uma resposta.
- **200 OK:** A requisição foi bem-sucedida.
- **301 Movido Permanentemente:** A URL requisitada foi movida permanetemente. Uma nova URL é fornecida na resposta.
- **404 Not Found:** O recurso solicitado não foi encontrado no servidor.
- **500 Internal Server Error:** Indica um erro interno no servidor ao processar a requisição.

---

**Resumo feito por: João Guilherme Valadares e Souza Arcoverde - 01499788**
