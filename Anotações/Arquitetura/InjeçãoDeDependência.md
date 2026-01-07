# Injeção de dependência

## O que é?
- É um padrão de projeto que define como os componentes internos do seu próprio código recebem as dependências de que precisam.

## Ideia central
- Ao invés de uma classe criar as coisas que ela precisa, ela recebe essas coisas prontas.

## Por que usar?
- Testes mais fáceis - Você pode dar versões "falsas" das dependências;
- Código desacoplado - Trocar implementações sem quebrar nada;
- Reutilização - A mesma instância pode ser compartilhada;
- Manutenção - Mudanças de configuração não afetam quem usa.

## Como usar?

## Pergunta que responde:
- Como um objeto dentro do meu código obtém as instâncias de outros objetos dos quais ele depende?

	Uma dependência ocorre quando uma classe precisa de outra ara executar suas tarefas. Basicamente a classe "main" é desaclopada podendo fazer alterações futuras, como por exemplo o banco de dados.