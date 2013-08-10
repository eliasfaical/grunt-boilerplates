# Grunt Boilerplate LESS

Com as dependências do boilerplate instaladas e as informaçòes do seu `package.json` modificadas, basta executar uma tarefa para ver o Grunt em ação.


## Visão Geral

| Plugin | O que faz? | Mais Informações |
|--------|------------|------------------|
| grunt-contrib-uglify | Minifica seus arquivos | [https://npmjs.org/package/grunt-contrib-uglify](https://npmjs.org/package/grunt-contrib-uglify) |
| grunt-contrib-concat | Concatena seus arquivos | [https://npmjs.org/package/grunt-contrib-concat](https://npmjs.org/package/grunt-contrib-concat) |
| grunt-contrib-watch | Observa as mudanças dos seus arquivos | [https://npmjs.org/package/grunt-contrib-watch](https://npmjs.org/package/grunt-contrib-watch) |
| grunt-contrib-less | Compila os arquivos LESS para CSS | [https://npmjs.org/package/grunt-contrib-less](https://npmjs.org/package/grunt-contrib-less) |
| grunt-contrib-jshint | Faz a validação dos seus scripts (linting) | [https://npmjs.org/package/grunt-contrib-jshint](https://npmjs.org/package/grunt-contrib-jshint) |
| grunt-contrib-imagemin | Otimiza as suas imagens | [https://npmjs.org/package/grunt-contrib-imagemin](https://npmjs.org/package/grunt-contrib-imagemin) |
| matchdep | Filtrar dependências pelo nome | [https://npmjs.org/package/matchdep](https://npmjs.org/package/matchdep) |
| grunt-ftp-deploy | Realiza deploy via FTP | [https://npmjs.org/package/grunt-deploy](https://npmjs.org/package/grunt-deploy) |
| grunt-notify | Exibe notificações das tarefas | [https://npmjs.org/package/grunt-notify](https://npmjs.org/package/grunt-notify) |


## Tarefas Disponíveis

***Importante: todas estas tarefas deverão ser executadas no diretório raiz do seu projeto***

### Tarefa de Construção

>**Execute com:** grunt w

>**O que esta tarefa faz?**

>- Observa as mudanças de todos os seus arquivos (livereload opcional)
>- Compila e concatena todos os arquivos *.less para CSS
>- Minifica (e concatena) seus arquivos `*.js`
>- Executa a validação dos seus scripts

### Tarefa de Otimização

>**Execute com:** grunt o

>**O que esta tarefa faz?**

>- Fará uma otimização das suas imagens


### Deploy via FTP

>**Execute com:** grunt d

>**O que esta tarefa faz?**

>- Envia os arquivos para o server definido via FTP