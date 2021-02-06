# HTTP

> ## Sucesso

1. x Request com verbo http válido (post)
2. x Passar nos headers o content type JSON
3. x Chamar request com body correto
4. x Ok - 200 e resposta com dados
5. x No content - 204 e resposta sem dados

> ## Erros

1. x Bad request - 400
2. x Unauthorized - 401
3. x Forbidden - 403
4. Not found - 404
5. x Internal server error - 500

> ## Exceção - Status code diferente dos citados acima

1. x Internal server error - 500

> ## Exceção - Http request deu alguma exceção

1. x Internal server error - 500

> ## Exceção - Verbo http inválido

1. x Internal server error - 500
