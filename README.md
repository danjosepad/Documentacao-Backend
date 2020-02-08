# Documentacao Backend
Dicas de documentação para o backend usando NodeJS

## Controllers

- Retorno de um JSON
- Nunca chama outro método ou outro Controller

Exemplo de um controller 

```javascript
class ExampleController {

index() { /*Lista usuários*/ }

show() { /*Exibe um usuário*/ }

store() { /*Cria usuário*/ }

update() { /*Atualiza usuário*/ }

delete() { /*Deleta usuário*/ }

}
```

```diff
! Não usar mais do que 5 controllers por entidade, pode usar menos.
```
