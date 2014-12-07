# Awesome Clojure

- [Awesome products in Clojure](#awesome-products-in-clojure)
  - [LightTable (IDE)](http://www.lighttable.com/)
  - [Nightcode (IDE)](https://nightcode.info/)
  - [Riemann (Monitoring)](http://riemann.io/)
  - [PuppetDB](https://github.com/puppetlabs/puppetdb)
- [Awesome tools in Clojure](#awesome-tools-in-clojure)
  - [Web Framework](#web-framework)
  - [Dependency injection](#dependency-injection)
  - [Package Management](#package-management)
  - [Date and Time](#date-and-time)
  - [GUI](#gui)
  - [Audio](#audio)
  - [HTTP](#http)
  - [Database](#database)
  - [Connection pools](#connection-pools)
  - [Structural Migrations](#structural-migrations)
  - [ORM and SQL generation](#orm-and-sql-generation)
  - [RESTful API](#restful-api)
  - [HTML Manipulation](#html-manipulation)
  - [Data Validation](#data-validation)
  - [Type System](#type-system)
  - [Async processing](#async-processing)
  - [WebSocket](#websocket)
  - [Testing](#testing)
  - [Code Analysis and Linter](#code-analysis-and-linter)
  - [Science and Data Analysis](#science-and-data-analysis)
  - [Computer Vision](#computer-vision)
  - [Literate Programming](#literate-programming)
  - [Miscellaneous](#miscellaneous)
  - [Editor Plugins](#editor-plugins)
  - [Literate Programming](#literate-programming)
  - [Debugging tools](#debugging)
- [Resources](#resources)
  - [Guides](#guides)
  - [Websites](#websites)
  - [Twitter](#twitter)
  - [Misc](#misc)

## Web Framework

*Actually don't search rails/django here, but compose them by yourself*

  * [Web Non-Framework](https://github.com/webnf/webnf)
  * [Luminus](http://www.luminusweb.net/)
  * [Joodo](http://www.joodoweb.com/)
  * [Coils](https://github.com/zubairq/coils)

## Dependency injection

*Managed lifecycle of stateful objects* 

  * [Component](https://github.com/stuartsierra/component)
  * [System](https://github.com/danielsz/system)
  * [Duct](https://github.com/weavejester/duct)
  
## Package management

*Libraries for package and dependency management.*

  * [Leiningen](https://github.com/technomancy/leiningen)

## Date and Time

*Libraries for working with dates and times.*

  * [clj-time](https://github.com/clj-time/clj-time)

## GUI

  * [fx-clj](https://github.com/aaronc/fx-clj)

## Audio

  * [Overtone](http://overtone.github.io/)

## HTTP

*Libraries for working with HTTP.*

  * [clj-http](https://github.com/dakrone/clj-http)
  * [http-kit](http://http-kit.org/)
  * [ring](https://github.com/ring-clojure/ring)

## Database

*Databases and database client libraries*

  * [Datomic](http://www.datomic.com/)
  * [clojure.jdbc](https://github.com/niwibe/clojure.jdbc)
  * [cravendb](https://github.com/robashton/cravendb)
  * [Mongo](http://clojuremongodb.info/)

## Connection pools

*Database connection pools*

  * [hikari-cp](https://github.com/tomekw/hikari-cp)

## Structural Migrations

*Keeps database and others in sync*

  * [Lobos](https://github.com/budu/lobos)
  * [Ragtime](https://github.com/weavejester/ragtime)
  * [Migratus](https://github.com/pjstadig/migratus)
  * [Drift](https://github.com/macourtney/drift)

## Redis

  * [carmine](https://github.com/ptaoussanis/carmine)

## JSON

  * [cheshire](https://github.com/dakrone/cheshire)

## Database Cli

## ORM and SQL generation

*DSL for SQL generaion.*

  * [Korma](http://sqlkorma.com/)
  * [stch-library/sql](https://github.com/stch-library/sql)
  * [sqlingvo](https://github.com/r0man/sqlingvo)
  * [honeysql](https://github.com/jkk/honeysql)

## Security

*Authentication, authorization and other security related libraries.*

  * [Buddy](https://github.com/niwibe/buddy)
  * [Friend](https://github.com/cemerick/friend)
  * [Cylon](https://github.com/juxt/cylon)

## RESTful API

*Libraries for developing RESTful APIs.*

  * [Liberator](http://clojure-liberator.github.io/liberator/)
  * [compojure-api](https://github.com/metosin/compojure-api)

## HTML Manipulation

*Libraries for working with HTML.*

  * [Enlive](https://github.com/cgrand/enlive/wiki)
  * [hiccup](https://github.com/weavejester/hiccup)

## Data Validation

*Libraries for validating data.*

  * [Validateur](http://clojurevalidations.info/)
  * [Prismatic's schema](http://clojurevalidations.info/)
  * [domaintypes](https://github.com/friemen/domaintypes)

## Type System
*Optional type system for Clojure*

  * [core.typed](https://github.com/clojure/core.typed)

## Async processing

  * [core.async](https://github.com/clojure/core.async/)
  * [pulsar](https://github.com/puniverse/pulsar)
  * [lamina](https://github.com/ztellman/lamina)
  * [aleph](https://github.com/ztellman/aleph)

## Monads

  * [cats](https://github.com/niwibe/cats)
  * [algo.monads](https://github.com/clojure/algo.monads)

## WebSocket

  * [Sente](https://github.com/ptaoussanis/sente)

## Testing

  * [Expectations](http://jayfields.com/expectations/)
  * [Midje](https://github.com/marick/Midje)

## Code Analysis and Linter

  * [Slamhound](https://github.com/technomancy/slamhound)
  * [eastwood](https://github.com/jonase/eastwood)
  * [kibit](https://github.com/jonase/kibit)

## Science and Data Analysis

  * [Incanter](https://github.com/incanter/incanter)
  * [Cascalog](http://cascalog.org/)
  * [Onyx](https://github.com/MichaelDrogalis/onyx)

## Computer Vision

  * [clj-tesseract](https://github.com/antoniogarrote/clj-tesseract)
  * [vision](http://nakkaya.com/vision.html)

## Natural Language Processing

  * [clojure-opennlp](https://github.com/dakrone/clojure-opennlp)

## Editor Plugins

  * [CIDER](https://github.com/clojure-emacs/cider)
  * [vim-fireplace](https://github.com/tpope/vim-fireplace)
  * [vim-redl](https://github.com/dgrnbrg/vim-redl)

## Literate Programming

  * [marginalia](https://github.com/gdeer81/marginalia)

## Miscellaneous

 * [clj-tuple](https://github.com/ztellman/clj-tuple)
 * [slingshot](https://github.com/scgilardi/slingshot)

## Debugging

  * [debug-repl](https://github.com/GeorgeJahad/debug-repl)
  * [ritz](https://github.com/pallet/ritz)
  * [redl](https://github.com/dgrnbrg/redl)
  * [limit-break](https://github.com/technomancy/limit-break)
  * [spyscope](https://github.com/dgrnbrg/spyscope)
  * [aprint](https://github.com/razum2um/aprint)
  * [pretty](https://github.com/AvisoNovate/pretty)
  * [prone](https://github.com/magnars/prone)
  * [figwheel](https://github.com/bhauman/lein-figwheel)

## Guides

  * [Clojure Distilled](http://yogthos.github.io/ClojureDistilled.html)
  * [clojure-cookbook](https://github.com/clojure-cookbook/clojure-cookbook)
  * [A Brief Beginner's Guide To Clojure](http://www.unexpected-vortices.com/clojure/brief-beginners-guide/index.html)
  * [Clojure for the Brave and True](http://www.braveclojure.com/)
  * [Clojure from the ground up](http://aphyr.com/tags/Clojure-from-the-ground-up)

## Websites

  * [clojuredocs](http://clojuredocs.org)
  * [crossclj](http://crossclj.info/)
  * [clojure-doc](http://clojure-doc.org/)
  * [Clojure Sphere](http://www.clojuresphere.com/)
  * [Grimoire](http://grimoire.arrdem.com/)
  * [The Clojure Toolbox](http://www.clojure-toolbox.com/)
  * [InstaREPL Online](http://web.clojurerepl.com/)
  * [ZEEF/Clojure](https://clojure.zeef.com/vlad.bokov)

## Twitter

  * [oss_clj](https://twitter.com/oss_clj)

## Misc

  * [koans](https://github.com/functional-koans/clojure-koans)
