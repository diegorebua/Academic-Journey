# 🎯 TypeScript — Iniciante

**Total de exercícios neste nível:** 30

## 📝 Lista de Exercícios

- [01_tipos_basicos](./01_tipos_basicos): Declare variáveis com tipos primitivos (string, number, boolean, null, undefined) e entenda as diferenças.
- [02_interfaces_basicas](./02_interfaces_basicas): Crie interfaces para modelar Livro, Autor e Editora. Instancie objetos e valide os tipos.
- [03_type_alias](./03_type_alias): Use type alias para criar tipos customizados. Compare com interfaces e entenda quando usar cada um.
- [04_arrays_tuplas](./04_arrays_tuplas): Declare arrays tipados e tuplas. Crie uma função que retorna uma tupla [erro, resultado].
- [05_enums](./05_enums): Crie Enums para representar os Status de um Pedido (PENDENTE, PROCESSANDO, ENVIADO, ENTREGUE, CANCELADO).
- [06_funcoes_tipadas](./06_funcoes_tipadas): Tipar parâmetros, retornos e funções de callback. Implemente sobrecarga de funções.
- [07_union_intersection](./07_union_intersection): Use Union Types (A | B) e Intersection Types (A & B) para representar dados flexíveis.
- [08_optional_chaining](./08_optional_chaining): Demonstre o uso de optional chaining (?.) e nullish coalescing (??) com TypeScript.
- [09_type_assertions](./09_type_assertions): Use as e satisfies para realizar asserções de tipo de forma segura.
- [10_literal_types](./10_literal_types): Crie Literal Types para representar direções ('norte' | 'sul' | 'leste' | 'oeste').
- [11_readonly_const](./11_readonly_const): Aplique readonly em interfaces e const assertions em objetos para criar dados imutáveis.
- [12_funcoes_genericas_simples](./12_funcoes_genericas_simples): Crie funções genéricas simples: identidade, primeiro elemento de array, last.
- [13_narrowing](./13_narrowing): Pratique type narrowing com typeof, instanceof, in e discriminated unions.
- [14_classe_basica](./14_classe_basica): Crie uma classe Pessoa com propriedades tipadas, construtor, getters/setters e métodos.
- [15_heranca_ts](./15_heranca_ts): Implemente herança entre classes Animal → Cachorro, Gato com métodos abstratos.
- [16_interfaces_classes](./16_interfaces_classes): Implemente interfaces em classes concretas. Crie uma interface Forma com área() e perímetro().
- [17_modificadores_acesso](./17_modificadores_acesso): Demonstre public, private, protected e readonly em uma classe BankAccount.
- [18_decorators_simples](./18_decorators_simples): Crie um decorator simples de log que registra chamadas de método com timestamp.
- [19_tipos_utilitarios_basicos](./19_tipos_utilitarios_basicos): Pratique Partial<T>, Required<T>, Readonly<T> e Record<K, V> em exemplos reais.
- [20_refatorar_js_para_ts](./20_refatorar_js_para_ts): Pegue um arquivo JavaScript existente e refatore-o completamente para TypeScript tipado.
- [21_namespace](./21_namespace): Organize código em Namespaces TypeScript. Entenda as diferenças com módulos ES6.
- [22_generics_constraints](./22_generics_constraints): Use constraints em genéricos: <T extends object>, <T extends keyof U>.
- [23_mapped_types_basicos](./23_mapped_types_basicos): Crie Mapped Types simples: MyReadonly<T>, MyPartial<T>, MyRequired<T>.
- [24_template_literal_types](./24_template_literal_types): Use Template Literal Types para criar tipos de rotas de API: '/users/${string}'.
- [25_conditional_types_basicos](./25_conditional_types_basicos): Escreva Conditional Types simples: IsString<T>, IsArray<T>.
- [26_index_signatures](./26_index_signatures): Use Index Signatures para representar dicionários e mapeamentos dinâmicos.
- [27_funcao_overload](./27_funcao_overload): Implemente uma função parse que aceita string ou Uint8Array com sobrecarga de tipo.
- [28_discriminated_union](./28_discriminated_union): Modele os estados de uma requisição HTTP usando Discriminated Unions.
- [29_never_type](./29_never_type): Demonstre o uso do tipo never em exhaustive checks e funções que nunca retornam.
- [30_tsconfig_explorar](./30_tsconfig_explorar): Explore as opções do tsconfig.json: strict, esModuleInterop, paths, baseUrl e incremental.
