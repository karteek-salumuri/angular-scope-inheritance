# Test 1

### Code without `controllerAs` Syntax

**Result**: You can see [here](http://ericdouglas.github.io/angular-scope-inheritance/src/01-test/index.html) that if you use just the `controller` syntax, the child receive the values typed in the parent scope. **This is not good**!

In the moment that you change the child input, the connection between the two `title` variables is lost.