html2pdf.it
===========
Usando o PhantomJS para gerar pdfs, via webservice. Executando com o node.js.

Veja em ação: [html2pdf.immensa.com.br](http://html2pdf.immensa.com.br/).

Trabalha no Windows e Ubuntu.

No Mac vc precisa instalar:
```
brew install phantomjs
```

Para começar, você precisa clonar o repositório, entrar nele e executar
-----------
```
npm install
```

Rode o webserver
-----------
```
node lib/app.js
```

Rode os testes
-----------
```
npm test
```

Modulos usados no Node.js
----------------
- Rotas, etc. é feito com `express`
- Testes é feito com `mocha`, `chai` e `sinon`, testes ao estilo BDD.
- JSHint é executado no código JavaScript

Versão do Node.js
------------
É necessária a versão 0.10+ do Node.js(Porque vc ja sabe, pode ocorrer erros em uma versão anterior)
