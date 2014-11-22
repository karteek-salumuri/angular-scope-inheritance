# Teste 1

### Código sem a sintaxe `controllerAs`

**Resultado**: Você pode ver [aqui](http://ericdouglas.github.io/angular-scope-inheritance/src/01-test/index.html) que se usarmos a sintaxe `controller`, o filho recebe o valor digitado no escopo do pai. **Isso não é algo bom!**

No momento que você muda a  entrada do *filho*, a conexão entre as variáveis `title` é desfeita.