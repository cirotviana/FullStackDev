


# All DEV
* [Lista de coisas que todo programador deveria conhecer](https://github.com/mtdvio/every-programmer-should-know)


#   Back-End

##  Design API

[Guia para Projeto de API HTTP](https://github.com/Gutem/http-api-design/) -  guia fundamental para construção de uma API

  ### Conteúdo

* [Fundamentos](#fundamentos)
  *  [Separe as Responsabilidades](#separe-as-responsabilidades)
  *  [Exija Conexões Seguras](#exija-conexões-seguras)
  *  [Exija Versionamento no Cabeçalho Accepts](#exija-versionamento-no-cabeçalho-accepts)
  *  [Suporte ETags para Cacheamento](#suporte-etags-para-cacheamento)
  *  [Forneça Request-Ids para Introspecção](#forneça-request-ids-para-introspecção)
  *  [Divida Respostas Longas Entre Requisições com Ranges](#divida-respostas-longas-entre-requisições-com-ranges)
* [Requisições](#requisições)
  *  [Aceite JSON serializado no corpo das requisições](#aceite-json-serializado-no-corpo-das-requisições)
  *  [Use formatos de rotas consistentes](#use-formatos-de-rotas-consistentes)
    *  [Rotas e atributos em letras minúsculas](#rotas-e-atributos-em-letras-minúsculas)
    *  [Suporte referência com atributos que não sejam ID por conveniência](#suporte-referência-com-atributos-que-não-sejam-id-por-conveniência)
    *  [Minimize a profundidade da rota](#minimize-a-profundidade-da-rota)
* [Respostas](#respostas)
  *  [Retorne o código de estado apropriado](#retorne-o-código-de-estado-apropriado)
  *  [Prover recursos completos quando disponível](#prover-recursos-completos-quando-disponível)
  *  [Prover os (UU)IDs dos recursos](#prover-os-uuids-dos-recursos)
  *  [Prover timestamps padrões](#prover-timestamps-padrões)
  *  [Use horários UTC em formato ISO8601](#use-horários-utc-em-formato-iso8601)
  *  [Aninhe as relações de chaves estrangeiras](#aninhe-as-relações-de-chaves-estrangeiras)
  *  [Gere erros estruturados](#gere-erros-estruturados)
  *  [Mostre o estado limite de requisições](#mostre-o-estado-limite-de-requisições)
  *  [Manter o JSON minificado em todas as respostas](#manter-o-json-minificado-em-todas-as-respostas)
* [Artefatos](#artefatos)
  *  [Prover um esquema JSON processável](#prover-um-esquema-json-processável)
  *  [Prover documentação para leitura](#prover-documentação-para-leitura)
  *  [Prover exemplos executáveis](#prover-exemplos-executáveis)
  *  [Descreva a estabilidade](#descreva-a-estabilidade)

# Front End

* [Front-End Checklist](https://github.com/thedaviddias/Front-End-Checklist)  The Front-End Checklist is an exhaustive list of all elements you need to have / to test before launching your website / HTML page to production.



## Entrevista
* [Guia para entrevistas](https://github.com/yangshun/tech-interview-handbook)

#  Javascript 

* [33 conceitos](https://github.com/tiagoboeing/33-js-concepts) que todo desenvolvedor JS deve conhecer

* [Código limpo Javascript](https://github.com/ryanmcdermott/clean-code-javascript) Princícios de engenharia de software, livro do renomado autor Robert C. Martin's chamado código limpo, adaptado para JavaScript. It's a guide to producing [readable, reusable, and refactorable](https://github.com/ryanmcdermott/3rs-of-software-architecture)  software in JavaScript.

Recommended Node.js Libraries
-----------------------------

- [Nodemon](https://github.com/remy/nodemon) - Automatically restart Node.js server on code changes.
- [geoip-lite](https://github.com/bluesmoon/node-geoip) - Geolocation coordinates from IP address.
- [Filesize.js](http://filesizejs.com/) - Pretty file sizes, e.g. `filesize(265318); // "265.32 kB"`.
- [Numeral.js](http://numeraljs.com) - Library for formatting and manipulating numbers.
- [Node Inspector](https://github.com/node-inspector/node-inspector) - Node.js debugger based on Chrome Developer Tools.
- [node-taglib](https://github.com/nikhilm/node-taglib) - Library for reading the meta-data of several popular audio formats.
- [sharp](https://github.com/lovell/sharp) - Node.js module for resizing JPEG, PNG, WebP and TIFF images.

## Advanced

* [How JavaScript Works](https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf)

* [V8 Engine - Used by node.js](https://v8.dev/docs/)

# How to write optimized JavaScript
* **Order of object properties**: always instantiate your object properties in the same order so that hidden classes, and subsequently optimized code, can be shared.

* **Dynamic properties**: adding properties to an object after instantiation will force a hidden class change and slow down any methods that were optimized for the previous hidden class. Instead, assign all of an object’s properties in its constructor.
* **Methods:** code that executes the same method repeatedly will run faster than code that executes many different methods only once (due to inline caching).
* **Arrays**: avoid sparse arrays where keys are not incremental numbers. Sparse arrays which don’t have every element inside them are a hash table. Elements in such arrays are more expensive to access. Also, try to avoid pre-allocating large arrays. It’s better to grow as you go. Finally, don’t delete elements in arrays. It makes the keys sparse.
* **Tagged values**: V8 represents objects and numbers with 32 bits. It uses a bit to know if it is an object (flag = 1) or an integer (flag = 0) called SMI (SMall Integer) because of its 31 bits. Then, if a numeric value is bigger than 31 bits, V8 will box the number, turning it into a double and creating a new object to put the number inside. Try to use 31 bit signed numbers whenever possible to avoid the expensive boxing operation into a JS object.
  


## Links

* [Best Of JavaScript](https://bestofjs.org/) - reúne as últimas tendências sobre projetos de código aberto relacionados a Node.js e a plataforma web: JavaScript, é claro (cliente e servidor), mas também HTML, CSS ... 