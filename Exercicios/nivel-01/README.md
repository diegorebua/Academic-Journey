# Nível 1: Fácil (Manipulação de Arrays e Objetos)

Neste nível você praticará métodos funcionais de Array (`map`, `filter`, `reduce`, `find`) para transformar e manipular estruturas de dados.

---

### Exercício 1.1: Filtragem de Usuários Ativos
**Objetivo:** Dada uma lista de usuários, crie a função `obterUsuariosAtivos(usuarios)` que retorne apenas os usuários onde `ativo === true` e `idade >= 18`.

**Entrada:**
```javascript
const usuarios = [
  { id: 1, nome: "Alice", ativo: true, idade: 22 },
  { id: 2, nome: "Bob", ativo: false, idade: 25 },
  { id: 3, nome: "Carlos", ativo: true, idade: 17 }
];
```

**Saída Esperada:**
```javascript
[{ id: 1, nome: "Alice", ativo: true, idade: 22 }]
```

---

### Exercício 1.2: Cálculo de Total do Carrinho
**Objetivo:** Crie uma função `calcularTotalCarrinho(itens)` que utilize `reduce` para calcular o valor total de uma lista de compras, levando em consideração a quantidade e o preço unitário de cada item.

**Entrada:**
```javascript
const carrinho = [
  { produto: "Notebook", preco: 3000, quantidade: 1 },
  { produto: "Mouse", preco: 100, quantidade: 2 },
  { produto: "Teclado", preco: 200, quantidade: 1 }
];
```

**Saída Esperada:**
```javascript
3400
```

---

### Exercício 1.3: Agrupamento por Categoria
**Objetivo:** Crie uma função `agruparPorCategoria(produtos)` que receba um array de produtos e retorne um objeto cujas chaves sejam as categorias e os valores sejam arrays dos produtos correspondentes.

**Saída Esperada:**
```javascript
{
  eletronicos: ["Notebook", "Mouse"],
  livros: ["Clean Code"]
}
```
