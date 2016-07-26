# What's this?
JavaScript self study notes and usefull resources.

# Reference
* [JavaScript The Right Way](http://jstherightway.org)
* [Javascript Garden](https://bonsaiden.github.io/JavaScript-Garden/)
* [Learn X in Y minutes:Where X=javascript](http://learnxinyminutes.com/docs/javascript/)
* [Learning Advanced JavaScript by John Resig](http://ejohn.org/apps/learn/)
* [the changelog:JavaScript](http://thechangelog.com/tagged/javascript/)
* [CoffeeScript](http://coffeescript.org)
* [h5bp/Front-end-Developer-Interview-Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions)

## Person
* [John Resig](http://ejohn.org)
* [Jeremy Ashkenas](https://github.com/jashkenas)
* [TJ Holowaychuk](https://github.com/tj)
* [Douglas Crockford](http://www.crockford.com)
* [Andrea Giammarchi](http://webreflection.blogspot.jp/)
* [Nicholas C. Zakas](http://www.nczonline.net/)
* [Mark Otto](http://markdotto.com/)
* [Mike Bostock](http://bost.ocks.org/mike/)
* [What Are You Using? on tuts+](http://code.tutsplus.com/articles/what-are-you-using--net-32373)
* [`@fat`](https://github.com/fat)

## Useful
* [scotch.io](https://scotch.io)
* [TUTORIAL REPUBLIC](http://www.tutorialrepublic.com/)

### Tools
* [emmet CheatSheet](http://docs.emmet.io/cheat-sheet/)
* [CODEPEN](http://codepen.io)
* [Fillerati](http://www.fillerati.com)

### Training
[Crash Course on Modern Web Development](http://www.developingandrails.com/2015/01/crash-course-on-modern-web-development.html)

### Project
#### Utility
* [Ramda](http://ramdajs.com/)
* [lodash](https://lodash.com/)
* [underscore](https://github.com/jashkenas/underscore)
* [microjs](http://microjs.com/)
* [D3](http://alignedleft.com/tutorials/d3)

#### Framework
* [AngularJS](https://github.com/angular/angular.js)
* [aurelia](https://github.com/aurelia)
* [Durandal](https://github.com/BlueSpire/Durandal)
* [Riot](https://muut.com/riotjs/)
* [Ember](http://emberjs.com/)
* [React](https://facebook.github.io/react/)
* [Vue.js](http://vuejs.org/)
* [Polymer](https://www.polymer-project.org/)

#### CSS
* [Bootstrap](http://getbootstrap.com/)
* [Foundation](http://foundation.zurb.com/)
* [Responsive CSS Framework Comparison](http://responsive.vermilion.com/compare.php)
* [Myth](http://www.myth.io/)
* [Materialize](http://materializecss.com/)

### ES6, 7, HTML5
* [Babel](https://babeljs.io)
* [google/traceur-compiler](https://github.com/google/traceur-compiler)

* [Understanding ECMAScript 6](https://leanpub.com/understandinges6/read/)
* [Replace CoffeeScript with ES6](https://robots.thoughtbot.com/replace-coffeescript-with-es6)
* [lukehoban/es6features: Overview of ECMAScript 6 features](https://github.com/lukehoban/es6features#readme)
* [ECMAScript compatibility table](http://kangax.github.io/compat-table/es6/)
* [HTML5 ★ BOILERPLATE](https://html5boilerplate.com/)
* [Web Fundamentals by Google](https://developers.google.com/web/fundamentals/?hl=en)
* [HTML5 & Friends](https://developer.cdn.mozilla.net/media/uploads/demos/p/a/paulrouget/html5-dashboard/demo_package/index.html)

## Mailing List
* [A Drip of JavaScript Archive](http://adripofjavascript.com/archive.html)
* [JavaScript Weekly Archives](http://javascriptweekly.com/issues)

## Guidelines
* [Code Guide by @mdo](http://codeguide.co)
* [A JavaScript Quality Guide by @bevacqua](https://github.com/bevacqua/js)
* [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
* [GitHub internal CSS toolkig and guidlines](https://github.com/primer/primer)
* [The definitive front-end performance guide](http://browserdiet.com)
* [The Accessibility Project](http://a11yproject.com)
* [Can I use](http://caniuse.com/)

## Other Resources
### FONT
* [11 Great Icon Fonts for Your Projects](https://scotch.io/bar-talk/11-great-icon-fonts-for-your-projects)
* [Font Awesome](http://fontawesome.io/)
* [Themify Icons](http://themify.me/themify-icons)
* [Foundation Icons](https://scotch.io/bar-talk/11-great-icon-fonts-for-your-projects)
* [Ionicons](http://ionicons.com/)
* [Octicons](https://octicons.github.com/)

### Articles
* [56 Experts reveal 3 beloved front-end development tools](https://psdtowp.net/frontend-development-tools.html)
* [Echo JS](http://www.echojs.com/)
* [A Baseline for Front-End (JS) Developers: 2015](http://rmurphey.com/blog/2015/03/23/a-baseline-for-front-end-developers-2015/)
* [Getting up to JavaScript speed](http://glebbahmutov.com/blog//getting-up-to-javascript-speed/)

### Books
#### JavaScript
* [JSbooks](http://jsbooks.revolunet.com/)
* [JavaScript books by Dr. Gleb Bahmutov PhD](http://glebbahmutov.com/blog/javascript-books/)
* [JavaScript books to take your skills to the next level](http://blog.mediumequalsmessage.com/javascript-books-to-take-your-skills-to-the-next-level)
* [JavaScript Application Design](http://www.bevacqua.io/buildfirst)

#### DOM
* [DOM Enlightenment](http://domenlightenment.com/)

## Phone?
http://phonegap.com

## Undestanding

### Basic Overview

You need to know at least about

* HTML
* DOM
* CSS
* JavaScript

Here is rough scetch what you need to know about above terminologies.
DOM is a short form of Document Object Model.
HTML document is expressed as DOM Tree. In other word, you can think HTML document as collection of DOM element which compose DOM tree.
DOM API provide a programmer the way to manupilate DOM tree dynamically, programatically,
Which means, you can dynamically create/update/delete DOM element.
Dynamically manupilating DOM element is called DOM Programming.
Most common Programming Language used for DOM programming is JavaScript.
You can create DOM element by like `document.createElement('div')`.
What web browser is doing is parse DOM Tree(HTML document in this case), and display to browser's window.
In final phase of rendering DOM tree to browser's window, browser decorates each of DOM element by CSS.

CSS is short form of Cascading Style Sheet. As the word 'Cascading' described, CSS is the set of decoration explained in cascading way.
You can accumulate decoration rule in the direction flow from parent to child.
Child element's decoration is combination of decration in parent and its decendent and itself.

Browser is listening event where user invoke throgh clicking, mouse overing to the each of DOM elemment.
Browser fire the event respectively what happend in DOM.
So typically programmer bind reaction behavior(implemented as function or callback function) to specific event respectively.
Thats is said registering callback function to DOM event listener via DOM API.
What callback wil do typically are..
 - invoke HTTP request with the element user selected and get update from Web server and update DOM tree to refrect computation result done on Server side.
 - change UI element for good userbility.
 - read data from local storage which is used to other event.

The Information send and get in communication with web Server is generally used the format expressed as JSON.
JSON is short form of JavaScript Object Notation.
JSON is well fit specially handling in JavaScript programming.

Thats' all basic what you have to know to dive deep into the world of Web Development.

### Property Lookup
Every object except `null` has a link to another object called its `prototype`.

`Object.prototype` is last resort and it is `undefined`.

o1['foo'] try to retrieve foo propety in o1.
if o1 don'w have foo, it try to find o1.prototype.foo. if 

1. o1['foo']
2. o1.prototype['foo']
3. o1.prototype.prototype['foo']
4. o1.prototype.prototype.prototype['foo']
X. until o1.prototype return 'null'
That's prototype lookup chain!
