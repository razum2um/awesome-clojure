# Awesome Clojure [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

- [Awesome products in Clojure](#awesome-products-in-clojure)
  - [LightTable (IDE)](http://lighttable.com/)
  - [Nightcode (IDE)](https://sekao.net/nightcode/)
  - [Maria.cloud (Online IDE for beginners)](https://www.maria.cloud/)
  - [Riemann (Monitoring)](http://riemann.io/)
  - [Precursor (Online prototyping tool)](https://precursorapp.com/)
  - [Puppet Server](https://github.com/puppetlabs/puppet-server)
  - [PuppetDB](https://github.com/puppetlabs/puppetdb)
  - [Metabase](https://github.com/metabase/metabase)
  - [Metabase Datomic](https://github.com/lambdaisland/metabase-datomic)
  - [CircleCI](https://circleci.com/)
  - [asciinema](https://asciinema.org/)
  - [Avi (vim rewrite)](https://github.com/maitria/avi)
  - [Liquid (Text Editor)](https://github.com/mogenslund/liquid)
  - [Nightlight (Text Editor)](https://github.com/oakes/Nightlight)
  - [Clojupyter](https://github.com/clojupyter/clojupyter)
  - [meins](https://github.com/matthiasn/meins)
  - [Jepsen](https://github.com/jepsen-io/jepsen)
  - [Braid](https://github.com/braidchat/braid): a team-chat app with a novel UI that leads to better conversations
  - [Atea](https://github.com/pkamenarsky/atea): a minimalistic menu bar time tracker for MacOS
  - [Accelerated Text](https://github.com/tokenmill/accelerated-text): a natural language generation environment (backend: Clojure, frontend: JS)
- [Languages written with Clojure](#languages-written-with-clojure)
  - [jank](https://github.com/jeaye/jank)
  - [lux](https://github.com/LuxLang/lux)
  - [mal](https://github.com/kanaka/mal/tree/master/clojure)
  - [scheje](https://github.com/turbopape/scheje)
  - [eden](https://github.com/benzap/eden)
- [Awesome tools in Clojure](#awesome-tools-in-clojure)
  - [Advanced datastructures](#advanced-datastructures)
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
  - [GraphQL API](#graphql-api)
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
  - [Text Processing](#text-processing)
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
  - [Terminal UI](#terminal-ui)
  - [Graphviz](#graphviz)

- [Resources](#resources)
  - [Guides](#guides)
  - [Video tutorials](#video-tutorials)
  - [Websites](#websites)
  - [Twitter](#twitter)
  - [Exercises](#exercises)

## Advanced datastructures

  * [Persistent AVL trees](https://github.com/clojure/data.avl): persistent sorted maps and sets with log-time rank queries
  * [Finger Tree](https://github.com/clojure/data.finger-tree): double-list, counted-double-list, counted-sorted-set
  * [Hitchhiker Tree](https://github.com/datacrypt-project/hitchhiker-tree): create fast, snapshottable, massively scalable databases
  * [Hierarchical set](https://github.com/llasram/hier-set)
  * [Ordered](https://github.com/amalloy/ordered): ordered sets and maps
  * [Lazy Map](https://github.com/Malabarba/lazy-map-clojure): whose values are only calculated when accessed
  * [Duratom](https://github.com/jimpil/duratom), [enduro](https://github.com/alandipert/enduro), [perdure](https://github.com/pesterhazy/perdure): atoms persisted on disk
  * [Durable Queue](https://github.com/Factual/durable-queue): queue persisted on disk
  * [bifurcan](https://github.com/lacuna/bifurcan): linear map/set/list (stores entries contiguously in memory), ;writtern in java, but test suite (read: usage examples) [in clojure](https://github.com/lacuna/bifurcan/blob/master/test/bifurcan)
  
## Web Framework

*Actually don't search rails/django here, but compose them by yourself*
  * [Compojure](https://github.com/weavejester/compojure)
  * [Compojure-api](https://github.com/metosin/compojure-api)
  * [Web Non-Framework](https://github.com/webnf/webnf)
  * [Luminus](http://www.luminusweb.net/)
  * [Joodo](https://github.com/slagyr/joodoweb)
  * [Coils](https://github.com/l4u/coils)
  * [Duct](https://github.com/weavejester/duct)
  * [Pedestal](https://github.com/pedestal/pedestal)
  * [Datsys](https://github.com/metasoarous/datsys)
  * [yada](https://github.com/juxt/yada)
  * [Hoplon](http://hoplon.io/)
  * [Fulcro](https://github.com/fulcrologic/fulcro)
  * [Coast](http://coastonclojure.com/)
  * [Reitit](https://github.com/metosin/reitit)
  * [Tadam](https://www.tadam-framework.dev/)

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
  * [clojurephant](https://github.com/clojurephant/clojurephant) (Gradle plugin)
  * [shadow-cljs](https://github.com/thheller/shadow-cljs) (Clojurescript)

## Version Control Management

*Code utilities for interacting with VCS software*

  * [lucid.git](http://docs.caudate.me/lucidity/lucid-git.html)

## Date and Time

*Libraries for working with dates and times.*

  * [clj-time](https://github.com/clj-time/clj-time)
  * [clojure.java-time](https://github.com/dm3/clojure.java-time) - Java 8 Date-Time API
  * [timewords](https://github.com/tokenmill/timewords)

## GUI

  * [fx-clj](https://github.com/aaronc/fx-clj)
  * [seesaw](https://github.com/daveray/seesaw)
  * [trikl](https://github.com/lambdaisland/trikl)

## Audio

  * [Overtone](http://overtone.github.io/)
  * [Alda](https://github.com/alda-lang/alda)

## HTTP

*Libraries for working with HTTP.*

  * [clj-http](https://github.com/dakrone/clj-http)
  * [http-kit](http://www.http-kit.org/)
  * [ring](https://github.com/ring-clojure/ring)
  * [kvlt](https://github.com/nervous-systems/kvlt)
  * [aleph](https://github.com/ztellman/aleph)

## Database

*Databases and database client libraries*

  * [Datomic](http://www.datomic.com/)
  * [Datahike](https://github.com/replikativ/datahike)
  * [Datascript](https://github.com/tonsky/datascript)
  * [Cassandra](https://github.com/mpenet/alia)
  * [clojure.jdbc](https://github.com/funcool/clojure.jdbc)
  * [cravendb](https://github.com/robashton/cravendb)
  * [Mongo](http://clojuremongodb.info/)
  * [Monglorious](https://baumandm.github.io/monglorious/)
  * [RethinkDB](https://github.com/apa512/clj-rethinkdb)
  * [Revise (RethinkDB)](https://github.com/bitemyapp/revise)
  * [Spandex (ElasticSearch)](https://github.com/mpenet/spandex)
  * [Elastisch](http://clojureelasticsearch.info/)
  * [Neo4j](http://clojureneo4j.info/)
  * [Aerospike](https://github.com/AppsFlyer/aerospike-clj)

## Connection pools

*Database connection pools*

  * [hikari-cp](https://github.com/tomekw/hikari-cp)
  * [metabase/connection-pool](https://github.com/metabase/connection-pool)

## Structural Migrations

*Keeps database and others in sync*

  * [Lobos](https://github.com/budu/lobos)
  * [Ragtime](https://github.com/weavejester/ragtime)
  * [Joplin](https://github.com/juxt/joplin)
  * [Migratus](https://github.com/yogthos/migratus)
  * [Drift](https://github.com/macourtney/drift)

## Redis

  * [carmine](https://github.com/ptaoussanis/carmine)
  * [celtuce](https://github.com/lerouxrgd/celtuce)

## JSON

  * [cheshire](https://github.com/dakrone/cheshire)
  * [jsonista](https://github.com/metosin/jsonista)

## Database Cli

## ORM and SQL generation

*DSL for SQL generation.*
  * [Walkable](https://github.com/walkable-server/walkable)
  * [Korma](https://github.com/korma/Korma)
  * [Specql](https://github.com/tatut/specql/)
  * [stch-library/sql](https://github.com/stch-library/sql)
  * [sqlingvo](https://github.com/r0man/sqlingvo)
  * [sqlium](https://github.com/TheLadders/sqlium/)
  * [honeysql](https://github.com/jkk/honeysql)
  * [Toucan](https://github.com/metabase/toucan)

## Security

*Authentication, authorization and other security related libraries.*

  * [Buddy](https://github.com/funcool/buddy)
  * [caesium](https://github.com/lvh/caesium) (libsodium bindings)
  * [Friend](https://github.com/cemerick/friend)
  * [bolt](https://github.com/juxt/bolt)

## RESTful API

*Libraries for developing RESTful APIs.*

  * [Liberator](http://clojure-liberator.github.io/liberator/)
  * [Compojure-api](https://github.com/metosin/compojure-api)
  * [Friboo](https://github.com/zalando/friboo)
  * [yada](https://github.com/juxt/yada)
  * [router](https://github.com/darkleaf/router)
  * [reitit](https://github.com/metosin/reitit)

## GraphQL API

*Libraries for developing GraphQL APIs.*

  * [Lacinia](https://lacinia.readthedocs.io/en/latest/)

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
  * [struct](https://github.com/funcool/struct)

## Type System
*Optional type system for Clojure*

  * [core.typed](https://github.com/clojure/core.typed)

## Pattern Matching

  * [core.match](https://github.com/clojure/core.match)
  * [Verbal-Exprejon](https://github.com/GuillaumeBadi/Verbal-Exprejon)
  * [defun](https://github.com/killme2008/defun)
  * [cats.match](https://github.com/zalando/cats.match)
  * [Akar](https://github.com/missingfaktor/akar)
  * [Meander](https://github.com/noprompt/meander)

## Async processing

  * [core.async](https://github.com/clojure/core.async/)
  * [pulsar](https://github.com/puniverse/pulsar)
  * [manifold](https://github.com/ztellman/manifold)

## Monads

  * [cats](https://github.com/funcool/cats)
  * [algo.monads](https://github.com/clojure/algo.monads)
  * [Fluokitten](https://github.com/uncomplicate/fluokitten)

## WebSocket

  * [Chord](https://github.com/jarohen/chord)
  * [Sente](https://github.com/ptaoussanis/sente)
  * [aleph](https://github.com/ztellman/aleph)

## Testing

  * [Expectations](https://github.com/clojure-expectations/expectations)
  * [Midje](https://github.com/marick/Midje)
  * [lucid.unit](http://docs.caudate.me/lucidity/lucid-unit.html)
  * [test-doubles](https://github.com/GreenPowerMonitor/test-doubles) 
  * [kaocha](https://github.com/lambdaisland/kaocha)

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
  * [clj-kondo](https://github.com/borkdude/clj-kondo)

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
  * [Bayadera - Bayesian Data Analysis on the GPU](https://github.com/uncomplicate/bayadera)
  * [ClojureCUDA](https://github.com/uncomplicate/clojurecuda)
  * [Neanderthal - fast matrix and linear algebra](https://github.com/uncomplicate/neanderthal)
  * [ClojureCL - parallel computations with OpenCL](https://github.com/uncomplicate/clojurecl)
  * [Loom - graph library for Clojure](https://github.com/aysylu/loom)

## Machine Learning

  * [clj-ml](https://github.com/antoniogarrote/clj-ml)
  * [cortex](https://github.com/originrose/cortex)
  * [clj-bigml](https://github.com/bigmlcom/clj-bigml)
  * [Clatern](https://github.com/rinuboney/clatern)
  * [Deeplearning4j](https://github.com/deeplearning4j/deeplearning4j)
  * [Enclog](https://github.com/jimpil/enclog)
  * [Infer](https://github.com/aria42/infer)
  * [k9](https://github.com/gigasquid/k9)
  * [lambda-ml](https://github.com/cloudkj/lambda-ml)
  * [Statistiker](https://github.com/clojurewerkz/statistiker)
  * [Synaptic](https://github.com/japonophile/synaptic)
  * [clojure-tensorflow](https://github.com/kieranbrowne/clojure-tensorflow)
  * [dl4clj (deeplearning4j to clojure)](https://github.com/yetanalytics/dl4clj)
  * [Anglican](https://probprog.github.io/anglican/)

## Computer Vision

  * [clj-tesseract](https://github.com/antoniogarrote/clj-tesseract)
  * [vision](http://nakkaya.com/vision.html)

## Text Processing

  * [clojure-opennlp](https://github.com/dakrone/clojure-opennlp)
  * [postagga](https://github.com/turbopape/postagga)
  * [beagle](https://github.com/tokenmill/beagle)

## Parsing

  * [Instaparse](https://github.com/Engelberg/instaparse)
  * [kern](https://github.com/blancas/kern)
  * [duckling](https://github.com/wit-ai/duckling)
  * [buran](https://github.com/alekseysotnikov/buran) - RSS/Atom feed consumer and producer
  
## Exceptions and Error Handling
  * [Ex](https://github.com/mpenet/ex)
  * [Perseverance](https://github.com/grammarly/perseverance)
  * [Dire](https://github.com/MichaelDrogalis/dire)
  
## Reflection
*Libraries for improved code reflection and object introspection

  * [hara.reflect](docs.caudate.me/hara/hara-reflect.html)
  * [lucid.mind](http://docs.caudate.me/lucidity/lucid-mind.html)
  * [lucid.query](http://docs.caudate.me/lucidity/lucid-query.html)

## Rule-based Programming
  * [Clara Rules](https://github.com/cerner/clara-rules)
  * [Arete](https://github.com/yipeeio/arete)

## Editor Plugins

  * [Calva (VSCode)](https://github.com/BetterThanTomorrow/calva)
  * [CIDER (Emacs)](https://github.com/clojure-emacs/cider)
  * [smartparens (Emacs)](https://github.com/Fuco1/smartparens)
  * [rainbow-delimiters (Emacs)](https://github.com/Fanael/rainbow-delimiters)
  * [aggressive-indent (Emacs)](https://github.com/Malabarba/aggressive-indent-mode)
  * [vim-cljfmt (Vim)](https://github.com/venantius/vim-cljfmt)
  * [vim-eastwood (Vim)](https://github.com/venantius/vim-eastwood)
  * [vim-fireplace (Vim)](https://github.com/tpope/vim-fireplace)
  * [vim-redl (Vim)](https://github.com/dgrnbrg/vim-redl)
  * [vim-leiningen (Vim)](https://github.com/tpope/vim-salve)
  * [rainbow_parentheses.vim (Vim)](https://github.com/junegunn/rainbow_parentheses.vim)
  * [vim-iced (Vim)](https://github.com/liquidz/vim-iced)
  * [Cursive (IntelliJ)](https://cursive-ide.com/)
  * [Parinfer (multiple editors)](http://shaunlebron.github.io/parinfer/)
  * [Bracket Pair Colorizer (VSCode)](https://github.com/kristoft/awesome-clojure.git)

## Documentation

*Utilities and libraries for (non-LP) code and project documentation*

 * [lucid.publish](http://docs.caudate.me/lucidity/lucid-publish.html)

## Literate Programming

  * [marginalia](https://github.com/gdeer81/marginalia)
  * [klipse](https://github.com/viebel/klipse)

## Archives and Compression

  * [swindon (java.util.zip wrapper)](https://github.com/AeroNotix/swindon)

## Miscellaneous

 * [potemkin](https://github.com/ztellman/potemkin) - reexport vars in another ns / act like a clojure map
 * [clj-tuple](https://github.com/ztellman/clj-tuple)
 * [slingshot](https://github.com/scgilardi/slingshot)
 * [lucid.system](http://docs.caudate.me/lucidity/lucid-system.html)
 * [virgil](https://github.com/ztellman/virgil)
 * [javastar](https://github.com/tailrecursion/javastar)
 * [riddley](https://github.com/ztellman/riddley)
 * [kezban](https://github.com/ertugrulcetin/kezban)

## Debugging

  * [tools.trace](https://github.com/clojure/tools.trace)
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
  * [mate-clj](https://github.com/AppsFlyer/mate-clj)

## CI

  * [lambdacd](https://github.com/flosell/lambdacd)
  
## Project Management
  
  * [milestones](https://github.com/turbopape/milestones)

## Terminal UI

  * [clojure-lanterna](https://sjl.bitbucket.io/clojure-lanterna/)
  * [triki](https://github.com/lambdaisland/trikl)
  * [zaffre](https://github.com/aaron-santos/zaffre)
  * [closh](https://github.com/dundalek/closh)
  
## Graphviz

  * [zipper-viz](https://github.com/lambdaisland/zipper-viz)
  * [dorothy](https://github.com/daveray/dorothy)
  * [viz.cljc](https://github.com/jebberjeb/viz.cljc)
  * [fsmviz](https://github.com/jebberjeb/fsmviz)
  * [rhizome](https://github.com/ztellman/rhizome)

## Guides

  * [The Clojure Style Guide](https://github.com/bbatsov/clojure-style-guide)
  * [Clojure Distilled](http://yogthos.github.io/ClojureDistilled.html)
  * [clojure-cookbook](https://github.com/clojure-cookbook/clojure-cookbook)
  * [A Brief Beginner's Guide To Clojure](http://www.unexpected-vortices.com/clojure/brief-beginners-guide/index.html)
  * [Clojure for the Brave and True](http://www.braveclojure.com/)
  * [Clojure from the ground up](https://aphyr.com/tags/Clojure-from-the-ground-up)
  * [Error message catalog](https://github.com/yogthos/clojure-error-message-catalog)
  * [Clojure by Example](https://kimh.github.io/clojure-by-example/)

## Video tutorials

### YouTube

  * [Misophistful's channel](https://www.youtube.com/user/Misophistful/videos): Understand concepts such as list comprehension, threading macros, generative testing, destructuring, core.match and introductions to Light Table, Datomic and Game development with Clojure
  * [Fred Overflow's channel](https://www.youtube.com/channel/UC9m7D4XKPJqTPCLSBym3BCg/search?query=Clojure): Introductions to Functional programming and TDD with Clojure
  * [Clojure Pills screencast](https://www.youtube.com/channel/UCH0CkLvbv6yEyrUnw9qujpQ/videos): Introduction to Clojure one function at a time
  * [Data persistance with Postgres, Clojure and JDBC](https://www.youtube.com/channel/UCrwwOZ4h2FQhAdTMfjyQfQA/playlists)
  * [Clojure Tutorials by Timothy Baldridge](https://www.youtube.com/channel/UC6yONKYeoE2P3bsahDtsimg/videos): More advanced videos on core.async, tranducers, transients, logic programming and a "Function of the day" series.

## Websites

  * [Clojure](http://clojure.org/)
  * [Clojure Slack](http://clojurians.net/)
  * [clojuredocs](http://clojuredocs.org)
  * [crossclj](https://crossclj.info/)
  * [clojure-doc](http://clojure-doc.org/)
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
  * [Codewars](https://www.codewars.com/kata/search/clojure)
