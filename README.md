# Awesome Clojure [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

- [Awesome products in Clojure](#awesome-products-in-clojure)
  - [LightTable (IDE)](http://lighttable.com/)
  - [Nightcode (IDE)](https://sekao.net/nightcode/)
  - [Riemann (Monitoring)](http://riemann.io/)
  - [Puppet Server](https://github.com/puppetlabs/puppet-server)
  - [PuppetDB](https://github.com/puppetlabs/puppetdb)
  - [Metabase](https://github.com/metabase/metabase)
  - [Avi (vim rewrite)](https://github.com/maitria/avi)
  - [Liquid (Text Editor)](https://github.com/mogenslund/liquid)
  - [Clojupyter](https://github.com/clojupyter/clojupyter)
  - [Meo](https://github.com/matthiasn/meo)
- [Languages written with Clojure](#languages-written-with-clojure)
  - [jank](https://github.com/jeaye/jank)
  - [lux](https://github.com/LuxLang/lux)
  - [mal](https://github.com/kanaka/mal/tree/master/clojure)
  - [scheje](https://github.com/turbopape/scheje)
- [Awesome tools in Clojure](#awesome-tools-in-clojure)
  - [Web Framework](#web-framework)
  - [Dependency injection](#dependency-injection)
  - [Build Automation and Package management](#build-automation-and-package-management)
  - [Version Control Management](#version-control-management)
  - [Date and Time](#date-and-time)
  - [GUI](#gui)
  - [Audio](#audio)
  - [HTTP](#http)
  - [Database](#database)
  - [Connection pools](#connection-pools)
  - [Structural Migrations](#structural-migrations)
  - [Redis](#redis)
  - [JSON](#json)
  - [ORM and SQL generation](#orm-and-sql-generation)
  - [Security](#security)
  - [RESTful API](#restful-api)
  - [Emails](#emails)
  - [HTML Manipulation](#html-manipulation)
  - [Data Validation](#data-validation)
  - [Type System](#type-system)
  - [Pattern Matching](#pattern-matching)
  - [Async processing](#async-processing)
  - [Monads](#monads)
  - [WebSocket](#websocket)
  - [Testing](#testing)
  - [Webdriver automation](#webdriver-automation)
  - [Code Analysis and Linter](#code-analysis-and-linter)
  - [Science and Data Analysis](#science-and-data-analysis)
  - [Machine Learning](#machine-learning)
  - [Computer Vision](#computer-vision)
  - [Natural Language Processing](#natural-language-processing)
  - [Parsing](#parsing)
  - [Reflection](#reflection)
  - [Editor Plugins](#editor-plugins)
  - [Documentation](#documentation)
  - [Literate Programming](#literate-programming)
  - [Archives and Compression](#archives-and-compression)
  - [Miscellaneous](#miscellaneous)
  - [Debugging tools](#debugging)
  - [CI](#ci)
  - [Project Management](#project-management)

- [Resources](#resources)
  - [Guides](#guides)
  - [Websites](#websites)
  - [Twitter](#twitter)
  - [Exercises](#exercises)


## Web Framework

*Actually don't search rails/django here, but compose them by yourself*
  * [Compojure](https://github.com/weavejester/compojure)
  * [Web Non-Framework](https://github.com/webnf/webnf)
  * [Luminus](http://www.luminusweb.net/)
  * [Joodo](https://github.com/slagyr/joodoweb)
  * [Coils](https://github.com/zubairq/AppShare)
  * [Duct](https://github.com/weavejester/duct)
  * [Pedestal](https://github.com/pedestal/pedestal)
  * [Datsys](https://github.com/metasoarous/datsys)
  * [yada](https://github.com/juxt/yada)
  * [Hoplon](http://hoplon.io/)
  * [Fulcro](https://github.com/fulcrologic/fulcro)
  * [Coast](http://coastonclojure.com/)

## Dependency injection

*Managed lifecycle of stateful objects*

  * [Component](https://github.com/stuartsierra/component)
  * [System](https://github.com/danielsz/system)
  * [mount](https://github.com/tolitius/mount)
  * [Integrant](https://github.com/weavejester/integrant)

## Build Automation and Package management

*Libraries for project build automation and package/dependency management.*

  * [Leiningen](https://github.com/technomancy/leiningen)
  * [Boot](https://github.com/boot-clj/boot)
  * [lucid.distribute](http://docs.caudate.me/lucidity/lucid-distribute.html)
  * [lucid.package](http://docs.caudate.me/lucidity/lucid-package.html)

## Version Control Management

*Code utilities for interacting with VCS software*

  * [lucid.git](http://docs.caudate.me/lucidity/lucid-git.html)

## Date and Time

*Libraries for working with dates and times.*

  * [clj-time](https://github.com/clj-time/clj-time)

## GUI

  * [fx-clj](https://github.com/aaronc/fx-clj)
  * [seesaw](https://github.com/daveray/seesaw)

## Audio

  * [Overtone](http://overtone.github.io/)
  * [Alda](https://github.com/alda-lang/alda)

## HTTP

*Libraries for working with HTTP.*

  * [clj-http](https://github.com/dakrone/clj-http)
  * [http-kit](http://www.http-kit.org/)
  * [ring](https://github.com/ring-clojure/ring)
  * [kvlt](https://github.com/nervous-systems/kvlt)

## Database

*Databases and database client libraries*

  * [Datomic](http://www.datomic.com/)
  * [clojure.jdbc](https://github.com/funcool/clojure.jdbc)
  * [cravendb](https://github.com/robashton/cravendb)
  * [Mongo](http://clojuremongodb.info/)
  * [Monglorious](https://baumandm.github.io/monglorious/)
  * [RethinkDB](https://github.com/apa512/clj-rethinkdb)
  * [ElasticSearch](http://clojureelasticsearch.info/)
  * [Neo4j](http://clojureneo4j.info/)

## Connection pools

*Database connection pools*

  * [hikari-cp](https://github.com/tomekw/hikari-cp)

## Structural Migrations

*Keeps database and others in sync*

  * [Lobos](https://github.com/budu/lobos)
  * [Ragtime](https://github.com/weavejester/ragtime)
  * [Joplin](https://github.com/juxt/joplin)
  * [Migratus](https://github.com/yogthos/migratus)
  * [Drift](https://github.com/macourtney/drift)

## Redis

  * [carmine](https://github.com/ptaoussanis/carmine)

## JSON

  * [cheshire](https://github.com/dakrone/cheshire)

## Database Cli

## ORM and SQL generation

*DSL for SQL generation.*

  * [Korma](http://sqlkorma.com/)
  * [stch-library/sql](https://github.com/stch-library/sql)
  * [sqlingvo](https://github.com/r0man/sqlingvo)
  * [honeysql](https://github.com/jkk/honeysql)
  * [Toucan](https://github.com/metabase/toucan)

## Security

*Authentication, authorization and other security related libraries.*

  * [Buddy](https://github.com/funcool/buddy)
  * [Friend](https://github.com/cemerick/friend)
  * [bolt](https://github.com/juxt/bolt)

## RESTful API

*Libraries for developing RESTful APIs.*

  * [Liberator](http://clojure-liberator.github.io/liberator/)
  * [compojure-api](https://github.com/metosin/compojure-api)
  * [Friboo](https://github.com/zalando/friboo)
  * [yada](https://github.com/juxt/yada)
  * [router](https://github.com/darkleaf/router)

## Emails

  * [postal](https://github.com/drewr/postal)

## HTML Manipulation

*Libraries for working with HTML.*

  * [Enlive](https://github.com/cgrand/enlive/wiki)
  * [hiccup](https://github.com/weavejester/hiccup)
  * [clostache](https://github.com/fhd/clostache)
  * [selmer](https://github.com/yogthos/Selmer)

## Data Validation

*Libraries for validating data.*

  * [Validateur](http://clojurevalidations.info/)
  * [Prismatic's schema](https://github.com/plumatic/schema)
  * [domaintypes](https://github.com/friemen/domaintypes)
  * [Bouncer](https://github.com/leonardoborges/bouncer)
  * [clova](https://github.com/markwoodhall/clova)
  * [Orchestra](https://github.com/jeaye/orchestra)

## Type System
*Optional type system for Clojure*

  * [core.typed](https://github.com/clojure/core.typed)

## Pattern Matching

  * [core.match](https://github.com/clojure/core.match)
  * [Verbal-Exprejon](https://github.com/GuillaumeBadi/Verbal-Exprejon)
  * [defun](https://github.com/killme2008/defun)
  * [cats.match](https://github.com/zalando/cats.match)
  * [Akar](https://github.com/missingfaktor/akar)

## Async processing

  * [core.async](https://github.com/clojure/core.async/)
  * [pulsar](https://github.com/puniverse/pulsar)
  * [lamina](https://github.com/ztellman/lamina)
  * [aleph](https://github.com/ztellman/aleph)

## Monads

  * [cats](https://github.com/funcool/cats)
  * [algo.monads](https://github.com/clojure/algo.monads)

## WebSocket

  * [Chord](https://github.com/jarohen/chord)
  * [Sente](https://github.com/ptaoussanis/sente)

## Testing

  * [Expectations](http://jayfields.com/expectations/)
  * [Midje](https://github.com/marick/Midje)
  * [lucid.unit](http://docs.caudate.me/lucidity/lucid-unit.html)

## Webdriver automation

  * [Etaoin](https://github.com/igrishaev/etaoin)

## Code Analysis and Linter

  * [Slamhound](https://github.com/technomancy/slamhound)
  * [eastwood](https://github.com/jonase/eastwood)
  * [kibit](https://github.com/jonase/kibit)
  * [lucid.query](http://docs.caudate.me/lucidity/lucid-query.html)
  * [yagni](https://github.com/venantius/yagni)
  * [lein-bikeshed](https://github.com/dakrone/lein-bikeshed)
  * [spectrum](https://github.com/arohner/spectrum)
  * [cloverage](https://github.com/cloverage/cloverage)

## Science and Data Analysis

*Libraries, extended REPLs, and other tools for scientific and statistical data
anylysis and visualization.*

  * [Incanter](https://github.com/incanter/incanter)
  * [Cascalog](http://cascalog.org/)
  * [Onyx](https://github.com/onyx-platform/onyx)
  * [sparklling](https://github.com/gorillalabs/sparkling)
  * [flambo](https://github.com/yieldbot/flambo)
  * [Neanderthal](https://github.com/uncomplicate/neanderthal)
  * [lucid.graph](http://docs.caudate.me/lucidity/lucid-graph.html)
  * [Streaming Histograms](https://github.com/bigmlcom/histogram)
  * [Gorilla REPL](http://gorilla-repl.org/)  

## Machine Learning

  * [clj-ml](https://github.com/antoniogarrote/clj-ml)
  * [cortex](https://github.com/thinktopic/cortex)
  * [clj-bigml](https://github.com/bigmlcom/clj-bigml)
  * [Clatern](https://github.com/rinuboney/clatern)
  * [Deeplearning4j](https://github.com/deeplearning4j/deeplearning4j)
  * [Enclog](https://github.com/jimpil/enclog)
  * [Infer](https://github.com/aria42/infer)
  * [k9](https://github.com/gigasquid/k9)
  * [lambda-ml](https://github.com/cloudkj/lambda-ml)
  * [Statistiker](https://github.com/clojurewerkz/statistiker)
  * [Synaptic](https://github.com/japonophile/synaptic)

## Computer Vision

  * [clj-tesseract](https://github.com/antoniogarrote/clj-tesseract)
  * [vision](http://nakkaya.com/vision.html)

## Natural Language Processing

  * [clojure-opennlp](https://github.com/dakrone/clojure-opennlp)
  * [postagga](https://github.com/turbopape/postagga)

## Parsing

  * [Instaparse](https://github.com/Engelberg/instaparse)
  * [kern](https://github.com/blancas/kern)
  * [duckling](https://github.com/wit-ai/duckling)
  
## Exceptions and Error Handling
  * [Perseverance](https://github.com/grammarly/perseverance)
  * [Dire](https://github.com/MichaelDrogalis/dire)
  
## Reflection
*Libraries for improved code reflection and object introspection

  * [hara.reflect](docs.caudate.me/hara/hara-reflect.html)
  * [lucid.mind](http://docs.caudate.me/lucidity/lucid-mind.html)
  * [lucid.query](http://docs.caudate.me/lucidity/lucid-query.html)

## Editor Plugins

  * [CIDER (Emacs)](https://github.com/clojure-emacs/cider)
  * [smartparens (Emacs)](https://github.com/Fuco1/smartparens)
  * [rainbow-delimiters (Emacs)](https://github.com/Fanael/rainbow-delimiters)
  * [aggressive-indent (Emacs)](https://github.com/Malabarba/aggressive-indent-mode)
  * [vim-fireplace (Vim)](https://github.com/tpope/vim-fireplace)
  * [vim-redl (Vim)](https://github.com/dgrnbrg/vim-redl)
  * [vim-leiningen (Vim)](https://github.com/tpope/vim-salve)
  * [rainbow_parentheses.vim (Vim)](https://github.com/junegunn/rainbow_parentheses.vim)
  * [Cursive (IntelliJ)](https://cursive-ide.com/)
  * [Parinfer (multiple editors)](http://shaunlebron.github.io/parinfer/)

## Documentation

*Utilities and libraries for (non-LP) code and project documentation*

 * [lucid.publish](http://docs.caudate.me/lucidity/lucid-publish.html)

## Literate Programming

  * [marginalia](https://github.com/gdeer81/marginalia)
  * [klipse](https://github.com/viebel/klipse)

## Archives and Compression

  * [swindon (java.util.zip wrapper)](https://github.com/AeroNotix/swindon)

## Miscellaneous

 * [clj-tuple](https://github.com/ztellman/clj-tuple)
 * [slingshot](https://github.com/scgilardi/slingshot)
 * [lucid.system](http://docs.caudate.me/lucidity/lucid-system.html)

## Debugging

  * [debugger](https://github.com/razum2um/clj-debugger)
  * [debug-repl](https://github.com/GeorgeJahad/debug-repl)
  * [ritz](https://github.com/pallet/ritz)
  * [redl](https://github.com/dgrnbrg/redl)
  * [limit-break](https://github.com/technomancy/limit-break)
  * [spyscope](https://github.com/dgrnbrg/spyscope)
  * [aprint](https://github.com/razum2um/aprint)
  * [packed-printer](https://github.com/cgrand/packed-printer)
  * [pretty](https://github.com/AvisoNovate/pretty)
  * [prone](https://github.com/magnars/prone)
  * [figwheel](https://github.com/bhauman/lein-figwheel)
  * [ultra](https://github.com/venantius/ultra)

## CI

  * [lambdacd](https://github.com/flosell/lambdacd)

## Guides

  * [The Clojure Style Guide](https://github.com/bbatsov/clojure-style-guide)
  * [Clojure Distilled](http://yogthos.github.io/ClojureDistilled.html)
  * [clojure-cookbook](https://github.com/clojure-cookbook/clojure-cookbook)
  * [A Brief Beginner's Guide To Clojure](http://www.unexpected-vortices.com/clojure/brief-beginners-guide/index.html)
  * [Clojure for the Brave and True](http://www.braveclojure.com/)
  * [Clojure from the ground up](https://aphyr.com/tags/Clojure-from-the-ground-up)
  * [Clojure by Example](https://kimh.github.io/clojure-by-example/)

## Websites

  * [Clojure](http://clojure.org/)
  * [Clojure Slack](http://clojurians.net/)
  * [clojuredocs](http://clojuredocs.org)
  * [crossclj](https://crossclj.info/)
  * [clojure-doc](http://clojure-doc.org/)
  * [Grimoire](http://conj.io/)
  * [The Clojure Toolbox](http://www.clojure-toolbox.com/)
  * [InstaREPL Online](http://web.clojurerepl.com/)
  * [ZEEF/Clojure](https://clojure.zeef.com/vlad.bokov)
  * [Try Clojure](http://www.tryclj.com/)

## Twitter

  * [oss_clj](https://twitter.com/oss_clj)

## Exercises

  * [Clojure Koans](http://clojurekoans.com)
  * [Wonderland Clojure Katas](https://github.com/gigasquid/wonderland-clojure-katas)
  * [Clojure Katas](http://clojurekatas.org)
  * [4clojure](http://www.4clojure.com/)
  * [exercism.io](http://exercism.io/languages/clojure)
  * [Clojurecademy](https://clojurecademy.com)

## Project Management
  
  * [milestones](https://github.com/turbopape/milestones)
