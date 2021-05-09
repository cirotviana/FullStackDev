





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





#  Javascript 

* [Código limpo Javascript](https://github.com/ryanmcdermott/clean-code-javascript) Princícios de engenharia de software, livro do renomado autor Robert C. Martin's chamado código limpo, adaptado para JavaScript. It's a guide to producing [readable, reusable, and refactorable](https://github.com/ryanmcdermott/3rs-of-software-architecture)  software in JavaScript.

## Entrevista
* [Guia para entrevistas](https://github.com/yangshun/tech-interview-handbook)
  


## Links

* [Best Of JavaScript](https://bestofjs.org/) - reúne as últimas tendências sobre projetos de código aberto relacionados a Node.js e a plataforma web: JavaScript, é claro (cliente e servidor), mas também HTML, CSS ... 