# Workshop Vuejs 

1. Um pouco da história do [Vuejs](https://br.vuejs.org/)
   1. Sobre complexidade inerente e instrumental
2. Instância do Vuejs
   1. Sobre o objeto `data`
      1. Tem todos os dados da instancia
      2. Tudo que é referenciado no HTML deve ser inicializado aqui
   2. Objeto `computed`
      1. A intenção é retornar dados manipulados
      2. Por que usar isso? Por questões de peformance. Ele vai ficar em um cache 
   3. Objeto `methods`
      1. São simplesmente os métodos que conhecemos
      2. `cadastrar`, `alterar`, `excluir`, ...
   4. `props` são valores que vem no component pai
   5. Objeto `watch`
   6. `computed` VS `watch`
      1. `watch` reage a mudanças de outros dados
      2. `computed` transforma dados e deixa em um cache
   7. Sobre *Single File Component - SFC*
      1. `template`, `script` e `style`
      2. Separação de responsabilidades clara
      3. Estilo CSS só servem para a aquele componente
      4. Cada componente tem o seu comportamento próprio
3. Exemplos
   1. Componentes
   2. [vue-router](https://br.vuejs.org/v2/guide/routing.html)
      1. Roteamento
      2. Oficialmente suportado
      3. Existe uma outra biblioteca chamada de [Page.js](http://visionmedia.github.io/page.js/)
   3. Consumir recursos `http`
      1. axios
      2. vue-resource
   4. [Vuex](https://vuex.vuejs.org/ptbr/)
      1. Gerenciador de estado
      2. Baseado no Flux
4. Outros pontos
   1. PWA
   2. Desenvolvimento mobile
      1. [Quasar](https://quasar.dev/) (híbrido)
      2. [Nativescript](https://www.nativescript.org/) (Nativo)
      3. [Weex](https://weex.apache.org/) (Nativo)
   3. [Nuxt.js](https://nuxtjs.org/) - Renderização no servidor
   4. [Suporte ao Typescript](https://br.vuejs.org/v2/guide/typescript.html)
5. Por que eu gosto do Vuejs (também gosto do Angular)
   1. Simplicidade sensacional e sem muita cerimônia (Complexidade instrumental)
   2. [Documentação](https://br.vuejs.org/v2/guide/) bem completa, na minha opinião
   3. Mais simples que outros frameworks
   4. De uso incremental
   5. Tem um [CLI](https://cli.vuejs.org/)
6. Conclusão

## Referências

1. https://braziljs.org/artigos/no-mar-de-libs-e-frameworks-conhecendo-o-vue-js-parte-ii/
2. https://blog.codecasts.com.br/por-que-vue-js-e-nao-react-d5b58c09d193
3. https://medium.com/emanuelg-blog/descomplicando-os-single-file-components-do-vue-js-2df16724baab
4. https://insights.stackoverflow.com/trends?tags=vue.js%2Cangular%2Creactjs
