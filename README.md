# webdev16

Web development in 2016. Where we are (approximately), and how we got here
(approximately). It can be tough to get started in web dev since there are so
many things going on at the moment. New JavaScript standard, quick emergence of
new frameworks and libraries, multiple strategies for achieving the same thing,
popularization of containers through Docker, service and web workers, asm.js and
(soon!) WASM, GraphQL, the list goes on. It is *very* exciting times - so much
spurious activity sparking within the cylinder of the engines of technology
powering the Internet. Improvements in these underlying technologies - ease of
use, setup, and deployment, access to more powerful technologies, modern
database systems built with concurrency and scale in mind, more powerful API
designs, are the items which will power the next generation of services built
off the Internet, having impact in scientific research, novel marketplaces,
social connectivity, the transgression of evolution from a biological substrate
into a technological one..

## Challenges

- learn Node
  * [The Art of Node](https://github.com/maxogden/art-of-node)
  * understand async control flow with callbacks, promises, generators
  * [cb-promises-generators](https://medium.com/@rdsubhas/es6-from-callbacks-to-promises-to-generators-87f1c0cd8f2e#.5qhu279mz)
  * events
  * streams
  * modules
- learn React
  * [getting started](https://facebook.github.io/react/docs/getting-started.html)
  * props, state, lifecylce methods
  * with ES6 classes
- [ToDo](http://todomvc.com/) app backed by
  * MongoDB
  * PostgreSQL
- learn redux
  * Egghead videos
  * [Full stack redux](http://teropa.info/blog/2015/09/10/full-stack-redux-tutorial.html)
  * Todo example
  * async actions with redux-thunk
  * async with redux-sagas
- webpack
- gulp
- bonuses
  * layer GraphQL on top of PostgreSQL

If you want to use koa, understand *generators*:
- [ES6 Generators](https://davidwalsh.name/es6-generators)
- [Analysis of Generators and other Async Patterns in Node](https://spion.github.io/posts/analysis-generators-and-other-async-patterns-node.html)

## App Types

- basic HTML, CSS, JS (jQuery probably)
- serverside rendering with templates like Jade, Handlebars
- JSON API powering a SPA (single page application)
- react isomorphic - mix of serverside render that becomes SPA on client

## Timeline

Web dev proceeded roughly as follows:

- the old days: `index.html`s sprinkled among a folder structure. no JS or CSS
  yet. Routing defined by folder structure.
- then PHP: *PHP Hypertext Preprocessor*. (see: recursive backronym). Paired with
  something like Apache (then later nginx), uses a similar folder based structure,
  except now HTML is generated on the webserver on a per-user-per-request basis
  allowing for more complex behaviour.
- early JS days: back when CSS3 was just a dream and you used DOM hover events
  to trigger style updates on nav bar tab hovers. jQuery comes out as a solution
  to common tasks requiring cross-browser compatible code.
- Ruby on Rails gains popularity. "the new PHP". Now applications can be structured
  with the model, view, controller paradigm. (This can be done with PHP too but
  originally PHP was like folder-based HTML but with preprocessing)
- around this time, front end development is also picking up, the web is on its
  way to becoming the forefront of UX and UI. CSS3 is now standard, CSS
  preprocessors like LESS and SASS come out, JS is seeing more usage for things
  like validating forms clientside, image carousels, handling click events - the
  type of things you would "sprinkle jQuery" on top of a serverside rendered
  page (with Ruby or PHP or otherwise) to add interactivity. At this point,
  "page navigation" is largely still server or file based. Experimentation with
  building larger applications with jQuery start, projects like Backbone and
  Angular come out
- V8 and Node.js. npm. SPAs and the MEAN stack.
- grunt, Yeoman, gulp
- React, webpack

2004

- Nov
  * [rails][rails]

2008

- Nov
  * [jasmine][jasmine]

2009

- June
  * [express][express]
- Sep
  * [npm][npm]
  * [requirejs][requirejs]
- Oct
  * [mustache][mustache]
  * [underscore][underscore]
  * [lodash][lodash]

2010

- Jan
  * [angular][angular]
- March
  * [sinonjs][sinonjs]
  * [three.js][three.js]
- July
  * [knockout][knockout]
  * [handlebars][handlebars]
- Sep
  * [browserify][browserify]
  * [d3][d3]
- Nov
  * [jshint][jshint]
- Dec
  * [chai][chai]
  * [phantomjs][phantomjs]

2011

- Sep
  * [backbone][backbone]
  * [grunt][grunt]
- Oct
  * [karma][karma]
- Aug
  * [mocha][mocha]
- Nov
  * [meteor][meteor]
- April
  * [ember][ember]

2012

- Feb
  * [bacon][bacon]
- March
  * [webpack][webpack]
- April
  * [yeoman][yeoman]
- Sep
  * [bower][bower]
  * [Rxjs][Rxjs]

2013

- Jan
  * [protractor][protractor]
- May
  * [react][react]
  * [systemjs][systemjs]
- June
  * [gulp][gulp]
  * [eslint][eslint]
- Aug
  * [koa][koa]
- Sep
  * [bluebird][bluebird]

2014

- Jan
  * [Highland][Highland]
- May
  * [Immutable.js][Immutablejs]
- July
  * [vue][vue]

2015

- Jan.
  * [react-native][react-native]
- May
  * [rollup][rollup]

[angular]: https://angularjs.org/
[backbone]: http://backbonejs.org/
[bacon]: https://baconjs.github.io/
[bower]: http://bower.io/
[browserify]: http://browserify.org/
[bluebird]: http://bluebirdjs.com/
[chai]: http://chaijs.com/
[d3]: https://d3js.org/
[ember]: http://www.emberjs.com/
[eslint]: http://eslint.org/
[express]: http://expressjs.com/
[grunt]: http://gruntjs.com/
[gulp]: http://gulpjs.com/
[handlebars]: http://handlebarsjs.com/
[Highland]: http://highlandjs.org/
[Immutablejs]: http://facebook.github.io/immutable-js/
[jasmine]: http://jasmine.github.io/
[jshint]: http://jshint.com/
[karma]: http://karma-runner.github.io/
[koa]: http://koajs.com/
[knockout]: http://knockoutjs.com/
[lodash]: https://lodash.com/
[meteor]: https://www.meteor.com/
[mocha]: http://mochajs.org/
[mustache]: http://mustache.github.com/
[npm]: http://www.npmjs.com/
[phantomjs]: http://phantomjs.org/
[protractor]: http://www.protractortest.org/
[rails]: http://rubyonrails.org/
[react]: https://facebook.github.io/react/
[react-native]: http://facebook.github.io/react-native/
[requirejs]: http://requirejs.org/
[rollup]: http://rollupjs.org/
[Rxjs]: http://reactivex.io/
[sinonjs]: http://sinonjs.org/
[systemjs]: https://github.com/systemjs/systemjs
[three.js]: http://threejs.org/
[underscore]: http://underscorejs.org/
[vue]: http://vuejs.org/
[webpack]: https://webpack.github.io/
[yeoman]: http://yeoman.io/

## JavaScript

- [awesome-javascript](https://github.com/sorrycc/awesome-javascript)

## Web Workers

- [Web Workers: I like the way you work it](http://nolanlawson.github.io/webperf-2016-03/#/)
  * "Every line of frontend JS you've ever written has (momentarily) stopped your page from working."
  * From [http://nolanlawson.github.io/webperf-2016-03/#/19](http://nolanlawson.github.io/webperf-2016-03/#/19):


## Databases

- [PouchDB](https://pouchdb.com/)
- [node-postgres](https://github.com/brianc/node-postgres)
- [mongoose](http://mongoosejs.com/) and [MongoDB](https://www.mongodb.com)
- [CockroachDB](https://www.cockroachlabs.com/)
- [redis](http://redis.io/)
