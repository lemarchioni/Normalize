# Normalize CSS
 
## O que é?

A ideia de existir o Normalize CSS é a mesma que do Reset CSS, mas ele possui algumas diferenças importantes na hora de usar.

O principal objetivo do Normalize é deixar consistente a estilização padrão entre os navegadores. Algumas estilizações padrões dos browsers que são úteis para o desenvolvimento de páginas são mantidas, alguns bugs comuns entre os navegadores são corrigidos, algumas melhorias de usabilidade e também todo o código do Normalize é comentado e com uma documentação sobre as modificações.

## Diferenças entre Reset CSS e Normalize:

* O `reset.css` limpa `TODOS` os padrões dos navegadores. Portanto, é muito agressivo, enquanto o Normalize ainda mantém padrões que são úteis;

* Normalize corrige alguns bugs que existem nas estilizações padrões dos navegadores;

* Normalize corrige alguns bugs que existem nas estilizações padrões dos navegadores;

* Este é modular. O código todo é separado por seções específicas, então você pode procurar por mudanças de forma mais direta;

* Possui uma documentação detalhada sobre o uso e justificativas das mudanças feitas por ele.

## Como utilizá-lo?

Da mesma forma que o Reset CSS, o Normalize é uma folha de estilos que deve ser importado antes de qualquer estilização no projeto. É importante "limpar" primeiro o projeto antes de começar a desenvolver.

## Linkando...

Em seu arquivo `.html`, dentro da tag `<head>`, utilize a tag `<link>`, para chamar o arquivo em que estará o seu normalize CSS, como no exemplo:

`<link rel="stylesheet" href="normalize.css">`

Com o normalize CSS adicionado ao projeto, os demais estilos do layout podem ser aplicados sem prejuízo.

Espero que esse conteúdo seja útil de alguma forma!

<img src="https://raw.githubusercontent.com/leovargasdev/leovargasdev/master/.github/image.png" width="300">