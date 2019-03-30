# Awesome Go
## Command Line
### Standard CLI

*Libraries for building standard or basic Command Line applications.*

* [argparse](https://github.com/akamensky/argparse) - Command line argument parser inspired by Python's argparse module.
* [argv](https://github.com/cosiner/argv) - Go library to split command line string as arguments array using the bash syntax.
* [cli](https://github.com/mkideal/cli) - Feature-rich and easy to use command-line package based on golang struct tags.
* [cli](https://github.com/teris-io/cli) - Simple and complete API for building command line interfaces in Go.
* [cli-init](https://github.com/tcnksm/gcli) - The easy way to start building Golang command line applications.
* [climax](http://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command.
* [cobra](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions.
* [commandeer](https://github.com/jaffee/commandeer) - Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags.
* [complete](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion.
* [docopt.go](https://github.com/docopt/docopt.go) - Command-line arguments parser that will make you smile.
* [env](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs.
* [flag](https://github.com/cosiner/flag) - Simple but powerful command line option parsing library for Go supporting subcommand.
* [flaggy](https://github.com/integrii/flaggy) - A robust and idiomatic flags package with excellent subcommand support.
* [flagvar](https://github.com/sgreben/flagvar) - A collection of flag argument types for Go's standard `flag` package.
* [go-arg](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go.
* [go-commander](https://github.com/yitsushi/go-commander) - Go library to simplify CLI workflow.
* [go-flags](https://github.com/jessevdk/go-flags) - go command line option parser.
* [go-getoptions](https://github.com/DavidGamba/go-getoptions) - Go option parser inspired on the flexibility of Perl’s GetOpt::Long.
* [gocmd](https://github.com/devfacet/gocmd) - Go library for building command line applications.
* [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - cli application framework with auto configuration and dependency injection.
* [kingpin](https://github.com/alecthomas/kingpin) - Command line and flag parser supporting sub commands.
* [liner](https://github.com/peterh/liner) - Go readline-like library for command-line interfaces.
* [mitchellh/cli](https://github.com/mitchellh/cli) - Go library for implementing command-line interfaces.
* [mow.cli](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation.
* [pflag](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags.
* [readline](https://github.com/chzyer/readline) - Pure golang implementation that provides most features in GNU-Readline under MIT license.
* [sand](https://github.com/Zaba505/sand) - Simple API for creating interpreters and so much more.
* [sflags](https://github.com/octago/sflags) - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries.
* [strumt](https://github.com/antham/strumt) - Library to create prompt chain.
* [ukautz/clif](https://github.com/ukautz/clif) - Small command line interface framework.
* [urfave/cli](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli).
* [wlog](https://github.com/dixonwille/wlog) - Simple logging interface that supports cross-platform color and concurrency.
* [wmenu](https://github.com/dixonwille/wmenu) - Easy to use menu structure for cli applications that prompts users to make choices.

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

* [asciigraph](https://github.com/guptarohit/asciigraph) - Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies.
* [aurora](https://github.com/logrusorgru/aurora) - ANSI terminal colors that supports fmt.Printf/Sprintf.
* [cfmt](https://github.com/mingrammer/cfmt) - Contextual fmt inspired by bootstrap color classes.
* [chalk](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output.
* [color](https://github.com/fatih/color) - Versatile package for colored terminal output.
* [colourize](https://github.com/TreyBastian/colourize) - Go library for ANSI colour text in terminals.
* [ctc](https://github.com/wzshiming/ctc) - The non-invasive cross-platform terminal color library does not need to modify the Print method.
* [go-ataman](https://github.com/workanator/go-ataman) - Go library for rendering ANSI colored text templates in terminals.
* [go-colorable](https://github.com/mattn/go-colorable) - Colorable writer for windows.
* [go-colortext](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals.
* [go-isatty](https://github.com/mattn/go-isatty) - isatty for golang.
* [go-prompt](https://github.com/c-bata/go-prompt) - Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit).
* [gocui](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces.
* [gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text.
* [gookit/color](https://github.com/gookit/color) - Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows.
* [mpb](https://github.com/vbauerster/mpb) - Multi progress bar for terminal applications.
* [progressbar](https://github.com/schollz/progressbar) - Basic thread-safe progress bar that works in every OS.
* [simpletable](https://github.com/alexeyco/simpletable) - Simple tables in terminal with Go.
* [tabby](https://github.com/cheynewallace/tabby) - A tiny library for super simple Golang tables.
* [tabular](https://github.com/InVisionApp/tabular) - Print ASCII tables from command line utilities without the need to pass large sets of data to the API.
* [termbox-go](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces.
* [termdash](https://github.com/mum4k/termdash) - Go terminal dashboard based on **termbox-go** and inspired by [termui](https://github.com/gizak/termui).
* [termtables](https://github.com/apcera/termtables) - Go port of the Ruby library [terminal-tables](https://github.com/tj/terminal-table) for simple ASCII table generation as well as providing markdown and HTML output.
* [termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib).
* [uilive](https://github.com/gosuri/uilive) - Library for updating terminal output in realtime.
* [uiprogress](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications.
* [uitable](https://github.com/gosuri/uitable) - Library to improve readability in terminal apps using tabular data.

## Configuration

*Libraries for configuration parsing.*

* [config](https://github.com/olebedev/config) - JSON or YAML configuration wrapper with environment variables and flags parsing.
* [configure](https://github.com/paked/configure) - Provides configuration through multiple sources, including JSON, flags and environment variables.
* [confita](https://github.com/heetch/confita) - Load configuration in cascade from multiple backends into a struct.
* [conflate](https://github.com/the4thamigo-uk/conflate) - Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema.
* [env](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults).
* [envcfg](https://github.com/tomazk/envcfg) - Un-marshaling environment variables to Go structs.
* [envconf](https://github.com/ian-kent/envconf) - Configuration from environment.
* [envconfig](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables.
* [envh](https://github.com/antham/envh) - Helpers to manage environment variables.
* [gcfg](https://github.com/go-gcfg/gcfg) - read INI-style configuration files into Go structs; supports user-defined types and subsections.
* [go-up](https://github.com/ufoscout/go-up) - A simple configuration library with recursive placeholders resolution and no magic.
* [goConfig](https://github.com/crgimenes/goConfig) - Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file.
* [godotenv](https://github.com/joho/godotenv) - Go port of Ruby's dotenv library (Loads environment variables from `.env`).
* [gofigure](https://github.com/ian-kent/gofigure) - Go application configuration made easy.
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - Modular JSON configuration. Keep you config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization.
* [gookit/config](https://github.com/gookit/config) - application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge.
* [hjson](https://github.com/hjson/hjson-go) - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments.
* [ingo](https://github.com/schachmat/ingo) - Flags persisted in an ini-like config file.
* [ini](https://github.com/go-ini/ini) - Go package to read and write INI files.
* [joshbetz/config](https://github.com/joshbetz/config) - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP.
* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) - Go library for managing configuration data from environment variables.
* [mini](https://github.com/sasbury/mini) - Golang package for parsing ini-style configuration files.
* [sprbox](https://github.com/oblq/sprbox) - Build-environment aware toolbox factory and agnostic config parser (YAML, TOML, JSON and Environment vars).
* [store](https://github.com/tucnak/store) - Lightweight configuration manager for Go.
* [viper](https://github.com/spf13/viper) - Go configuration with fangs.
* [xdg](https://github.com/OpenPeeDeeP/xdg) - Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html).

## CSS Preprocessors

*Libraries for preprocessing CSS files.*

* [gcss](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor.
* [go-libsass](https://github.com/wellington/go-libsass) - Go wrapper to the 100% Sass compatible libsass project.

## Data Structures

*Generic datastructures and algorithms in Go.*
* [algorithms](https://github.com/shady831213/algorithms) - Algorithms and data structures.CLRS study.
* [binpacker](https://github.com/zhuangsirui/binpacker) - Binary packer and unpacker helps user build custom binary stream.
* [bit](https://github.com/yourbasic/bit) - Golang set data structure with bonus bit-twiddling functions.
* [bitset](https://github.com/willf/bitset) - Go package implementing bitsets.
* [bloom](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go.
* [bloom](https://github.com/yourbasic/bloom) - Golang Bloom filter implementation.
* [boomfilters](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams.
* [concurrent-writer](https://github.com/free/concurrent-writer) - Highly concurrent drop-in replacement for `bufio.Writer`.
* [conjungo](https://github.com/InVisionApp/conjungo) - A small, powerful and flexible merge library.
* [count-min-log](https://github.com/seiflotfy/count-min-log) - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory).
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go.
* [deque](https://github.com/edwingeng/deque) - A highly optimized double-ended queue.
* [deque](https://github.com/gammazero/deque) - Fast ring-buffer deque (double-ended queue).
* [encoding](https://github.com/zhenjl/encoding) - Integer Compression Libraries for Go.
* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - Go implementation of Adaptive Radix Tree.
* [go-datastructures](https://github.com/Workiva/go-datastructures) - Collection of useful, performant, and thread-safe data structures.
* [go-ef](https://github.com/amallia/go-ef) - A Go implementation of the Elias-Fano encoding.
* [go-geoindex](https://github.com/hailocab/go-geoindex) - In-memory geo index.
* [go-mcache](https://github.com/OrlovEvgeny/go-mcache) - Fast in-memory key:value store/cache library. Pointer caches.
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) - Region quadtrees with efficient point location and neighbour finding.
* [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) - Concurrent FIFO queue.
* [gods](https://github.com/emirpasic/gods) - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc.
* [golang-set](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go.
* [goset](https://github.com/zoumo/goset) - A useful Set collection implementation for Go.
* [goskiplist](https://github.com/ryszard/goskiplist) - Skip list implementation in Go.
* [gota](https://github.com/kniren/gota) - Implementation of dataframes, series, and data wrangling methods for Go.
* [hide](https://github.com/emvi/hide) - ID type with marshalling to/from hash to prevent sending IDs to clients.
* [hilbert](https://github.com/google/hilbert) - Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves.
* [hyperloglog](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.
* [levenshtein](https://github.com/agext/levenshtein) - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.
* [levenshtein](https://github.com/agnivade/levenshtein) - Implementation to calculate levenshtein distance in Go.
* [mafsa](https://github.com/smartystreets/mafsa) - MA-FSA implementation with Minimal Perfect Hashing.
* [merkletree](https://github.com/cbergoon/merkletree) - Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures.
* [mspm](https://github.com/BlackRabbitt/mspm) - Multi-String Pattern Matching Algorithm for information retrieval.
* [null](https://github.com/emvi/null) - Nullable Go types that can be marshalled/unmarshalled to/from JSON.
* [pipeline](https://github.com/hyfather/pipeline) - An implementation of pipelines with fan-in and fan-out.
* [ring](https://github.com/TheTannerRyan/ring) - Go implementation of a high performance, thread safe bloom filter.
* [roaring](https://github.com/RoaringBitmap/roaring) - Go package implementing compressed bitsets.
* [set](https://github.com/StudioSol/set) - Simple set data structure implementation in Go using LinkedHashMap.
* [skiplist](https://github.com/MauriceGit/skiplist) - Very fast Go Skiplist implementation.
* [skiplist](https://github.com/gansidui/skiplist) - Skiplist implementation in Go.
* [timedmap](https://github.com/zekroTJA/timedmap) - Map with expiring key-value pairs.
* [trie](https://github.com/derekparker/trie) - Trie implementation in Go.
* [ttlcache](https://github.com/diegobernardes/ttlcache) - In-memory LRU string-interface{} map with expiration for golang.
* [willf/bloom](https://github.com/willf/bloom) - Go package implementing Bloom filters.

## Database

*Databases implemented in Go.*

* [badger](https://github.com/dgraph-io/badger) - Fast key-value store in Go.
* [BigCache](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data.
* [bolt](https://github.com/boltdb/bolt) - Low-level key/value database for Go.
* [buntdb](https://github.com/tidwall/buntdb) - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support.
* [cache2go](https://github.com/muesli/cache2go) - In-memory key:value cache which supports automatic invalidation based on timeouts.
* [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) - BigCache with clustering support and individual item expiration.
* [cockroach](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore.
* [couchcache](https://github.com/codingsince1985/couchcache) - RESTful caching micro-service backed by Couchbase server.
* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) - CovenantSQL is a SQL database on blockchain.
* [dgraph](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database.
* [diskv](https://github.com/peterbourgon/diskv) - Home-grown disk-backed key-value store.
* [eliasdb](https://github.com/krotik/eliasdb) - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language.
* [fastcache](https://github.com/VictoriaMetrics/fastcache) - fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead.
* [GCache](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC.
* [go-cache](https://github.com/pmylund/go-cache) - In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.
* [goleveldb](https://github.com/syndtr/goleveldb) - Implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in Go.
* [gorocksdb](https://github.com/kapitan-k/gorocksdb) - Gorocksdb is a wrapper for [RocksDB](https://rocksdb.org) written in Go.
* [groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
* [influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics.
* [ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB.
* [levigo](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB.
* [moss](https://github.com/couchbase/moss) - Moss is a simple LSM key-value storage engine written in 100% Go.
* [nutsdb](https://github.com/xujiajun/nutsdb) - Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as  list, set, sorted set.
* [piladb](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures.
* [prometheus](https://github.com/prometheus/prometheus) - Monitoring system and time series database.
* [pudge](https://github.com/recoilme/pudge) - Fast and simple  key/value store written using Go's standard library.
* [rqlite](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite.
* [Scribble](https://github.com/nanobox-io/golang-scribble) - Tiny flat file JSON store.
* [slowpoke](https://github.com/recoilme/slowpoke) - Key-value store with persistence.
* [tempdb](https://github.com/rafaeljesus/tempdb) - Key-value store for temporary items.
* [tidb](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1.
* [tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang.
* [Vasto](https://github.com/chrislusf/vasto) - A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption.

*Database tools.*

* [chproxy](https://github.com/Vertamedia/chproxy) - HTTP proxy for ClickHouse database.
* [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) - Collects small insterts and sends big requests to ClickHouse servers.
* [dbbench](https://github.com/sj14/dbbench) - Database benchmarking tool with support for several databases and scripts.
* [go-mysql](https://github.com/siddontang/go-mysql) - Go toolset to handle MySQL protocol and replication.
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - Sync your MySQL data into Elasticsearch automatically.
* [kingshard](https://github.com/flike/kingshard) - kingshard is a high performance proxy for MySQL powered by Golang.
* [myreplication](https://github.com/2tvenom/myreplication) - MySql binary log replication listener. Supports statement and row based replication.
* [octillery](https://github.com/knocknote/octillery) - Go package for sharding databases ( Supports every ORM or raw SQL ).
* [orchestrator](https://github.com/github/orchestrator) - MySQL replication topology manager & visualizer.
* [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser.
* [prep](https://github.com/hexdigest/prep) - Use prepared SQL statements without changing your code.
* [pREST](https://github.com/nuveo/prest) - Serve a RESTful API from any PostgreSQL database.
* [rwdb](https://github.com/andizzle/rwdb) - rwdb provides read replica capability for multiple database servers setup.
* [vitess](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.

*SQL query builder, libraries for building and using SQL.*

* [Dotsql](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use them with ease.
* [gendry](https://github.com/didi/gendry) - Non-invasive SQL builder and powerful data binder.
* [godbal](https://github.com/xujiajun/godbal) - Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily.
* [goqu](https://github.com/doug-martin/goqu) - Idiomatic SQL builder and query library.
* [igor](https://github.com/galeone/igor) - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax.
* [ormlite](https://github.com/pupizoid/ormlite) - Lightweight package containing some ORM-like features and helpers for sqlite databases.
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities.
* [scaneo](https://github.com/variadico/scaneo) - Generate Go code to convert database rows into arbitrary structs.
* [sqrl](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance.
* [Squalus](https://gitlab.com/qosenergy/squalus) - Thin layer over the Go SQL package that makes it easier to perform queries.
* [Squirrel](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries.
* [xo](https://github.com/knq/xo) - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.

## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
    * [avatica](https://github.com/apache/calcite-avatica-go) - Apache Avatica/Phoenix SQL driver for database/sql.
    * [bgc](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery for go.
    * [firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go.
    * [go-adodb](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that uses database/sql.
    * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver for Go.
    * [go-oci8](https://github.com/mattn/go-oci8) - Oracle driver for go that uses database/sql.
    * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - MySQL driver for Go.
    * [go-sqlite3](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that uses database/sql.
    * [gofreetds](https://github.com/minus5/gofreetds) - Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org).
    * [goracle](https://github.com/go-goracle/goracle) - Oracle driver for Go, using the ODPI-C driver.
    * [pgx](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql.
    * [pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql.

* NoSQL Databases
    * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language.
    * [arangolite](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB.
    * [asc](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go.
    * [dynago](https://github.com/underarmour/dynago) - Dynago is a principle of least surprise client for DynamoDB.
    * [forestdb](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB.
    * [go-couchbase](https://github.com/couchbase/go-couchbase) - Couchbase client in Go.
    * [go-couchdb](https://github.com/fjl/go-couchdb) - Yet another CouchDB HTTP API wrapper for Go.
    * [go-pilosa](https://github.com/pilosa/go-pilosa) - Go client library for Pilosa.
    * [go-rejson](https://github.com/nitishm/go-rejson) - Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease.
    * [gocb](https://github.com/couchbase/gocb) - Official Couchbase Go SDK.
    * [gocql](http://gocql.github.io) - Go language driver for Apache Cassandra.
    * [godscache](https://github.com/defcronyke/godscache) - A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached.
    * [gomemcache](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language.
    * [gorethink](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB.
    * [goriak](https://github.com/zegl/goriak) - Go language driver for Riak KV.
    * [mgo](https://github.com/globalsign/mgo) - MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.
    * [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - Official MongoDB driver for the Go language.
    * [neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang.
    * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - Neo4j REST Client in golang.
    * [neoism](https://github.com/jmcvetta/neoism) - Neo4j client for Golang.
    * [redigo](https://github.com/gomodule/redigo) - Redigo is a Go client for the Redis database.
    * [redis](https://github.com/go-redis/redis) - Redis client for Golang.
    * [redis](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services.
    * [xredis](https://github.com/shomali11/xredis) - Typesafe, customizable, clean & easy to use Redis client.

* Search and Analytic Databases.
    * [bleve](https://github.com/blevesearch/bleve) - Modern text indexing library for go.
    * [elastic](https://github.com/olivere/elastic) - Elasticsearch client for Go.
    * [elasticsql](https://github.com/cch123/elasticsql) - Convert sql to elasticsearch dsl in Go.
    * [elastigo](https://github.com/mattbaird/elastigo) - Elasticsearch client library.
    * [goes](https://github.com/OwnLocal/goes) - Library to interact with Elasticsearch.
    * [riot](https://github.com/go-ego/riot) - Go Open Source, Distributed, Simple and efficient Search Engine.
    * [skizze](https://github.com/seiflotfy/skizze) - probabilistic data-structures service and storage.

* Multiple Backends.
    * [cachego](https://github.com/fabiorphp/cachego) - Golang Cache component for multiple drivers.
    * [cayley](https://github.com/google/cayley) - Graph database with support for multiple backends.
    * [dsc](https://github.com/viant/dsc) - Datastore connectivity for SQL, NoSQL, structured files.
    * [gokv](https://github.com/philippgille/gokv) - Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more)

## Distributed Systems

*Packages that help with building Distributed Systems.*

* [celeriac](https://github.com/svcavallar/celeriac.v1) - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go.
* [consistent](https://github.com/buraksezer/consistent) - Consistent hashing with bounded loads.
* [digota](https://github.com/digota/digota) - grpc ecommerce microservice.
* [doublejump](https://github.com/edwingeng/doublejump) - A revamped Google's jump consistent hash.
* [drmaa](https://github.com/dgruber/drmaa) - Job submission library for cluster schedulers based on the DRMAA standard.
* [dynamolock](https://cirello.io/dynamolock) - DynamoDB-backed distributed locking implementation.
* [dynatomic](https://github.com/tylfin/dynatomic) - A library for using DynamoDB as an atomic counter.
* [emitter-io](https://github.com/emitter-io/emitter) - High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love.
* [flowgraph](https://github.com/vectaport/flowgraph) - flow-based programming package.
* [gleam](https://github.com/chrislusf/gleam) - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed.
* [glow](https://github.com/chrislusf/glow) - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go.
* [go-health](https://github.com/InVisionApp/go-health) - Library for enabling asynchronous dependency health checks in your service.
* [go-jump](https://github.com/dgryski/go-jump) - Port of Google's "Jump" Consistent Hash function.
* [go-kit](https://github.com/go-kit/kit) - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc.
* [gorpc](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load.
* [grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC.
* [hprose](https://github.com/hprose/hprose-golang) - Very newbility RPC Library, support 25+ languages now.
* [jaeger](https://github.com/jaegertracing/jaeger) - A distributed tracing system.
* [jsonrpc](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0.
* [jsonrpc](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP client implementation.
* [KrakenD](https://github.com/devopsfaith/krakend) - Ultra performant API Gateway framework with middlewares.
* [micro](https://github.com/micro/micro) - Pluggable microservice toolkit and distributed systems platform.
* [NATS](https://github.com/nats-io/gnatsd) - Lightweight, high performance messaging system for microservices, IoT, and cloud native systems.
* [outboxer](https://github.com/italolelis/outboxer) - Outboxer is a go library that implements the outbox pattern.
* [pglock](https://cirello.io/pglock) - PostgreSQL-backed distributed locking implementation.
* [raft](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp.
* [raft](https://github.com/coreos/etcd/tree/master/raft) - Go implementation of the Raft consensus protocol, by CoreOS.
* [redis-lock](https://github.com/bsm/redis-lock) - Simplified distributed locking implementation using Redis.
* [ringpop-go](https://github.com/uber/ringpop-go) - Scalable, fault-tolerant application-layer sharding for Go applications.
* [rpcx](https://github.com/smallnest/rpcx) - Distributed pluggable RPC service framework like alibaba Dubbo.
* [sleuth](https://github.com/ursiform/sleuth) - Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq)).
* [tendermint](https://github.com/tendermint/tendermint) - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols.
* [torrent](https://github.com/anacrolix/torrent) - BitTorrent client package.
    * [dht](https://godoc.org/github.com/anacrolix/dht) - BitTorrent Kademlia DHT implementation.
    * [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - Video streaming torrent client.

## Error Handling

*Libraries for handling errors.*

* [errors](https://github.com/pkg/errors) - Package that provides simple error handling primitives.
* [errorx](https://github.com/joomcode/errorx) - A feature rich error package with stack traces, composition of errors and more.
* [go-multierror](https://github.com/hashicorp/go-multierror) - Go (golang) package for representing a list of errors as a single error.
* [tracerr](https://github.com/ztrue/tracerr) - Golang errors with stack trace and source fragments.
* [werr](https://github.com/txgruppi/werr) - Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called.

## Files

*Libraries for  handling files and file systems.*

* [afero](https://github.com/spf13/afero) - FileSystem Abstraction System for Go.
* [go-csv-tag](https://github.com/artonge/go-csv-tag) - Load csv file using tag.
* [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) - Copy files for humans.
* [go-gtfs](https://github.com/artonge/go-gtfs) - Load gtfs files in go.
* [notify](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal.
* [opc](https://github.com/qmuntal/opc) - Load Open Packaging Conventions (OPC) files for Go.
* [pdfcpu](https://github.com/hhrutter/pdfcpu) - PDF processor.
* [skywalker](https://github.com/dixonwille/skywalker) - Package to allow one to concurrently go through a filesystem with ease.
* [tarfs](https://github.com/posener/tarfs) - Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files.
* [vfs](https://github.com/C2FO/vfs) - A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS.


## Functional

*Packages to support functional programming in Go.*

* [fpGo](https://github.com/TeaEntityLab/fpGo) - Monad, Functional Programming features for Golang.
* [fuego](https://github.com/seborama/fuego) - Functional Experiment in Go.
* [go-underscore](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities.


## Generation and Generics

*Tools to enhance the language with features like generics via code generation.*

* [efaceconv](https://github.com/t0pep0/efaceconv) - Code generation tool for high performance conversion from interface{} to immutable type without allocations.
* [gen](https://github.com/clipperhouse/gen) - Code generation tool for ‘generics’-like functionality.
* [go-enum](https://github.com/abice/go-enum) - Code generation for enums from code comments.
* [go-linq](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go.
* [goderive](https://github.com/awalterschulze/goderive) - Derives functions from input types.
* [gotype](https://github.com/wzshiming/gotype) - Golang source code parsing, usage like reflect package.
* [GoWrap](https://github.com/hexdigest/gowrap) - Generate decorators for Go interfaces using simple templates.
* [interfaces](https://github.com/rjeczalik/interfaces) - Command line tool for generating interface definitions.
* [jennifer](https://github.com/dave/jennifer) - Generate arbitrary Go code without templates.
* [pkgreflect](https://github.com/ungerik/pkgreflect) - Go preprocessor for package scoped reflection.

## Goroutines

*Tools for managing and working with Goroutines.*

* [ants](https://github.com/panjf2000/ants) - A high-performance goroutine pool for golang.
* [artifex](https://github.com/borderstech/artifex) - Simple in-memory job queue for Golang using worker-based dispatching.
* [async](https://github.com/studiosol/async) - A safe way to execute functions asynchronously, recovering them in case of panic.
* [breaker](https://github.com/kamilsk/breaker) - 🚧 Flexible mechanism to make your code breakable.
* [cyclicbarrier](https://github.com/marusama/cyclicbarrier) - CyclicBarrier for golang.
* [go-floc](https://github.com/workanator/go-floc) - Orchestrate goroutines with ease.
* [go-flow](https://github.com/kamildrazkiewicz/go-flow) - Control goroutines execution order.
* [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) - Manage a pool of goroutines using this lightweight library with a simple API.
* [go-trylock](https://github.com/subchen/go-trylock) - TryLock support on read-write lock for Golang.
* [GoSlaves](https://github.com/themester/GoSlaves) - Simple and Asynchronous Goroutine pool library.
* [goworker](https://github.com/benmanns/goworker) - goworker is a Go-based background worker.
* [gpool](https://github.com/Sherifabdlnaby/gpool) - manages a resizeable pool of context-aware goroutines to bound concurrency.
* [grpool](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool.
* [oversight](https://cirello.io/oversight) - Oversight is a complete implementation of the Erlang supervision trees.
* [parallel-fn](https://github.com/rafaeljesus/parallel-fn) - Run functions in parallel.
* [pool](https://github.com/go-playground/pool) - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation.
* [semaphore](https://github.com/kamilsk/semaphore) - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context.
* [semaphore](https://github.com/marusama/semaphore) - Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations).
* [stl](https://github.com/ssgreg/stl) - Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism.
* [threadpool](https://github.com/shettyh/threadpool) - Golang threadpool implementation.
* [tunny](https://github.com/Jeffail/tunny) - Goroutine pool for golang.
* [worker-pool](https://github.com/vardius/worker-pool) - goworker is a Go simple async worker pool.
* [workerpool](https://github.com/gammazero/workerpool) - Goroutine pool that limits the concurrency of task execution, not the number of tasks queued.

## GUI

*Libraries for building GUI Applications.*

*Toolkits*

* [app](https://github.com/murlokswarm/app) - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress.
* [fyne](https://github.com/fyne-io/fyne) - Cross platform native GUIs designed for Go, rendered using EFL. Supports: Linux, macOS, Windows.
* [go-astilectron](https://github.com/asticode/go-astilectron) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron).
* [go-gtk](http://mattn.github.io/go-gtk/) - Go bindings for GTK.
* [go-sciter](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform.
* [gotk3](https://github.com/gotk3/gotk3) - Go bindings for GTK3.
* [gowd](https://github.com/dtylman/gowd) - Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform.
* [qt](https://github.com/therecipe/qt) - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi).
* [ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go. Cross platform.
* [walk](https://github.com/lxn/walk) - Windows application library kit for Go.
* [webview](https://github.com/zserge/webview) - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux).

*Interaction*

* [gosx-notifier](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go.
* [robotgo](https://github.com/go-vgo/robotgo) - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other.
* [systray](https://github.com/getlantern/systray) - Cross platform Go library to place an icon and menu in the notification area.
* [trayhost](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system's taskbar.


## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

See [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list.

## Images

*Libraries for manipulating images.*

* [bild](https://github.com/anthonynsimon/bild) - Collection of image processing algorithms in pure Go.
* [bimg](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips.
* [cameron](https://github.com/aofei/cameron) - An avatar generator for Go.
* [geopattern](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string.
* [gg](https://github.com/fogleman/gg) - 2D rendering in pure Go.
* [gift](https://github.com/disintegration/gift) - Package of image processing filters.
* [go-cairo](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library.
* [go-gd](https://github.com/bolknote/go-gd) - Go binding for GD library.
* [go-nude](https://github.com/koyachi/go-nude) - Nudity detection with Go.
* [go-opencv](https://github.com/lazywei/go-opencv) - Go bindings for OpenCV.
* [go-webcolors](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go.
* [gocv](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 3.3+.
* [goimagehash](https://github.com/corona10/goimagehash) - Go Perceptual image hashing package.
* [govatar](https://github.com/o1egl/govatar) - Library and CMD tool for generating funny avatars.
* [image2ascii](https://github.com/qeesung/image2ascii) - Convert image to ASCII.
* [imagick](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API.
* [imaginary](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing.
* [imaging](https://github.com/disintegration/imaging) - Simple Go image processing package.
* [img](https://github.com/hawx/img) - Selection of image manipulation tools.
* [ln](https://github.com/fogleman/ln) - 3D line art rendering in Go.
* [mergi](https://github.com/noelyahan/mergi) - Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate).
* [mort](https://github.com/aldor007/mort) - Storage and image processing server written in Go.
* [mpo](https://github.com/donatj/mpo) - Decoder and conversion tool for MPO 3D Photos.
* [picfit](https://github.com/thoas/picfit) - An image resizing server written in Go.
* [pt](https://github.com/fogleman/pt) - Path tracing engine written in Go.
* [resize](https://github.com/nfnt/resize) - Image resizing for Go with common interpolation methods.
* [rez](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD.
* [smartcrop](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes.
* [steganography](https://github.com/auyer/steganography) - Pure Go Library for LSB steganography.
* [stegify](https://github.com/DimitarPetrov/stegify) - Go tool for LSB steganography, capable of hiding any file within an image.
* [svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation.
* [tga](https://github.com/ftrvxmtrx/tga) - Package tga is a TARGA image format decoder/encoder.

## Job Scheduler

*Libraries for scheduling jobs.*

* [clockwerk](http://github.com/onatm/clockwerk) - Go package to schedule periodic jobs using a simple, fluent syntax.
* [clockwork](https://github.com/whiteShtef/clockwork) - Simple and intuitive job scheduling library in Go.
* [go-cron](https://github.com/rk/go-cron) - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons.
* [gron](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly.
* [JobRunner](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in.
* [jobs](https://github.com/albrow/jobs) - Persistent and flexible background jobs library.
* [leprechaun](https://github.com/kilgaloon/leprechaun) - Job scheduler that supports webhooks, crons and classic scheduling.
* [scheduler](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy.

## JSON

*Libraries for working with JSON.*

* [gjo](https://github.com/skanehira/gjo) - Small utility to create JSON objects.
* [GJSON](https://github.com/tidwall/gjson) - Get a JSON value with one line of code.
* [go-respond](https://github.com/nicklaw5/go-respond) - Go package for handling common HTTP JSON responses.
* [gojq](https://github.com/elgs/gojq) - JSON query in Golang.
* [gojson](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON.
* [JayDiff](https://github.com/yazgazan/jaydiff) - JSON diff utility written in Go.
* [JSON-to-Go](https://mholt.github.io/json-to-go/) - Convert JSON to Go struct.
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference.
* [jsonf](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON.
* [jsongo](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects.
* [jsonhal](https://github.com/RichardKnop/jsonhal) - Simple Go package to make custom structs marshal into HAL compatible JSON responses.
* [kazaam](https://github.com/Qntfy/kazaam) - API for arbitrary transformation of JSON documents.
* [mp](https://github.com/sanbornm/mp) - Simple cli email parser. It currently takes stdin and outputs JSON.

## Logging

*Libraries for generating and working with log files.*

* [distillog](https://github.com/amoghe/distillog) - distilled levelled logging (think of it as stdlib + log levels).
* [glg](https://github.com/kpango/glg) - glg is simple and fast leveled logging library for Go.
* [glo](https://github.com/lajosbencz/glo) - PHP Monolog inspired logging facility with identical severity levels.
* [glog](https://github.com/golang/glog) - Leveled execution logs for Go.
* [go-cronowriter](https://github.com/utahta/go-cronowriter) - Simple writer that rotate log files automatically based on current date and time, like cronolog.
* [go-log](https://github.com/subchen/go-log) - Simple and configurable Logging in Go, with level, formatters and writers.
* [go-log](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers.
* [go-log](https://github.com/ian-kent/go-log) - Log4j implementation in Go.
* [go-logger](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers.
* [gologger](https://github.com/sadlil/gologger) - Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch.
* [gomol](https://github.com/aphistic/gomol) - Multiple-output, structured logging for Go with extensible logging outputs.
* [gone/log](https://github.com/One-com/gone/tree/master/log) - Fast, extendable, full-featured, std-lib source compatible log library.
* [journald](https://github.com/ssgreg/journald) - Go implementation of systemd Journal's native API for logging.
* [log](https://github.com/apex/log) - Structured logging package for Go.
* [log](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go.
* [log](https://github.com/teris-io/log) - Structured log interface for Go cleanly separates logging facade from its implementation.
* [log-voyage](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang.
* [log15](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go.
* [logdump](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging.
* [logex](https://github.com/chzyer/logex) - Golang log lib, supports tracking and level, wrap by standard log lib.
* [logger](https://github.com/azer/logger) - Minimalistic logging library for Go.
* [logmatic](https://github.com/borderstech/logmatic) - Colorized logger for Golang with dynamic log level configuration.
* [logo](https://github.com/mbndr/logo) - Golang logger to different configurable writers.
* [logrus](https://github.com/Sirupsen/logrus) - Structured logger for Go.
* [logrusly](https://github.com/sebest/logrusly) - [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/).
* [logutils](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger.
* [logxi](https://github.com/mgutz/logxi) - 12-factor app logger that is fast and makes you happy.
* [lumberjack](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser.
* [mlog](https://github.com/jbrodriguez/mlog) - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output.
* [onelog](https://github.com/francoispqt/onelog) - Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenario. Also, it is one of the logger with the lowest allocation.
* [ozzo-log](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail).
* [seelog](https://github.com/cihub/seelog) - Logging functionality with flexible dispatching, filtering, and formatting.
* [spew](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging.
* [stdlog](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.
* [tail](https://github.com/hpcloud/tail) - Go package striving to emulate the features of the BSD tail program.
* [xlog](https://github.com/xfxdev/xlog) - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format.
* [xlog](https://github.com/rs/xlog) - Structured logger for `net/context` aware HTTP handlers with flexible dispatching.
* [zap](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go.
* [zerolog](https://github.com/rs/zerolog) - Zero-allocation JSON logger.


## Miscellaneous

### Dependency Injection
*Libraries for working with dependency injection.*

* [alice](https://github.com/magic003/alice) - Additive dependency injection container for Golang.
* [dig](https://github.com/uber-go/dig) - A reflection based dependency injection toolkit for Go.
* [fx](https://github.com/uber-go/fx) - A dependency injection based application framework for Go (built on top of dig).
* [wire](https://github.com/Fs02/wire) - Strict Runtime Dependency Injection for Golang.

### Strings
*Libraries for working with strings.*
* [strutil](https://github.com/ozgio/strutil) - String utilities.
* [xstrings](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages.

*These libraries were placed here because none of the other categories seemed to fit.*

* [anagent](https://github.com/mudler/anagent) - Minimalistic, pluggable Golang evloop/timer handler with dependency-injection.
* [antch](https://github.com/antchfx/antch) - A fast, powerful and extensible web crawling & scraping framework.
* [archiver](https://github.com/mholt/archiver) - Library and command for making and extracting .zip and .tar.gz archives.
* [autoflags](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields.
* [avgRating](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation.
* [banner](https://github.com/dimiro1/banner) - Add beautiful banners into your Go applications.
* [base64Captcha](https://github.com/mojocn/base64Captcha) - Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha.
* [battery](https://github.com/distatus/battery) - Cross-platform, normalized battery information library.
* [bitio](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go.
* [browscap_go](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](http://browscap.org/).
* [captcha](https://github.com/steambap/captcha) - Package captcha provides an easy to use, unopinionated API for captcha generation.
* [conv](https://github.com/cstockton/go-conv) - Package conv provides fast and intuitive conversions across Go types.
* [datacounter](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter.
* [ffmt](https://github.com/go-ffmt/ffmt) - Beautify data display for Humans.
* [ghorg](https://github.com/gabrie30/ghorg) - Clone all repos from a GitHub org into a single directory.
* [go-commons-pool](https://github.com/jolestar/go-commons-pool) - Generic object pool for Golang.
* [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.
* [go-resiliency](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang.
* [go-unarr](https://github.com/gen2brain/go-unarr) - Decompression library for RAR, TAR, ZIP and 7z archives.
* [gofakeit](https://github.com/brianvoe/gofakeit) - Random data generator written in go.
* [gommit](https://github.com/antham/gommit) - Analyze git commit messages to ensure they follow defined patterns.
* [gopsutil](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc).
* [gosh](https://github.com/osamingo/gosh) - Provide Go Statistics Handler, Struct, Measure Method.
* [gosms](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS.
* [gountries](https://github.com/pariz/gountries) - Package that exposes country and subdivision data.
* [health](https://github.com/dimiro1/health) - Easy to use, extensible health check library.
* [healthcheck](https://github.com/etherlabsio/healthcheck) - An opinionated and concurrent health-check HTTP handler for RESTful services.
* [hostutils](https://github.com/Wing924/hostutils) - A golang library for packing and unpacking FQDNs list.
* [indigo](https://github.com/osamingo/indigo) - Distributed unique ID generator of using Sonyflake and encoded by Base58.
* [lk](https://github.com/hyperboloide/lk) - A simple licensing library for golang.
* [llvm](https://github.com/llir/llvm) - Library for interacting with LLVM IR in pure Go.
* [morse](https://github.com/alwindoss/morse) - Library to convert to and from morse code.
* [pdfgen](https://github.com/hyperboloide/pdfgen) - HTTP service to generate PDF from Json requests.
* [persian](https://github.com/mavihq/persian) - Some utilities for Persian language in go.
* [sandid](https://github.com/aofei/sandid) - Every grain of sand on earth has its own ID.
* [shellwords](https://github.com/Wing924/shellwords) - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell.
* [shortid](https://github.com/teris-io/shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs.
* [stats](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc...
* [turtle](https://github.com/hackebrot/turtle) - Emojis for Go.
* [url-shortener](https://github.com/pantrif/url-shortener) - A modern, powerful, and robust URL shortener microservice with mysql support.
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and output handling.
* [xdg](https://github.com/rkoesters/xdg) - FreeDesktop.org (xdg) Specs implemented in Go.
* [xkg](https://github.com/go-xkg/xkg) - X Keyboard Grabber.


## Networking

*Libraries for working with various layers of the network.*

* [arp](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826.
* [buffstreams](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy.
* [canopus](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252).
* [cidranger](https://github.com/yl2chen/cidranger) - Fast IP to CIDR lookup for Go.
* [dhcp6](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315.
* [dns](https://github.com/miekg/dns) - Go library for working with DNS.
* [ether](https://github.com/songgao/ether) - Cross-platform Go package for sending and receiving ethernet frames.
* [ethernet](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags.
* [fasthttp](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http.
* [fortio](https://github.com/fortio/fortio) - Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC.
* [ftp](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959).
* [gmqtt](https://github.com/DrmagicE/gmqtt) - Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1.
* [gNxI](https://github.com/google/gnxi) - A collection of tools for Network Management that use the gNMI and gNOI protocols.
* [go-getter](https://github.com/hashicorp/go-getter) - Go library for downloading files or directories from various sources using a URL.
* [go-stun](https://github.com/ccding/go-stun) - Go implementation of the STUN client (RFC 3489 and RFC 5389).
* [gobgp](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language.
* [golibwireshark](https://github.com/sunwxg/golibwireshark) - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data.
* [gopacket](https://github.com/google/gopacket) - Go library for packet processing with libpcap bindings.
* [gopcap](https://github.com/akrennmair/gopcap) - Go wrapper for libpcap.
* [goshark](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet.
* [gosnmp](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions.
* [gotcp](https://github.com/gansidui/gotcp) - Go package for quickly writing tcp applications.
* [grab](https://github.com/cavaliercoder/grab) - Go package for managing file downloads.
* [graval](https://github.com/koofr/graval) - Experimental FTP server framework.
* [HTTPLab](https://github.com/gchaincl/httplab) - HTTPLabs let you inspect HTTP requests and forge responses.
* [jazigo](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple network devices.
* [kcp-go](https://github.com/xtaci/kcp-go) - KCP - Fast and Reliable ARQ Protocol.
* [kcptun](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol.
* [lhttp](https://github.com/fanux/lhttp) - Powerful websocket framework, build your IM server more easily.
* [linkio](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces.
* [llb](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response.
* [mdns](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang.
* [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
* [NFF-Go](https://github.com/intel-go/nff-go) - Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF).
* [packet](https://github.com/aerogo/packet) - Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed.
* [peerdiscovery](https://github.com/schollz/peerdiscovery) - Pure Go library for cross-platform local peer discovery using UDP multicast.
* [portproxy](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it.
* [publicip](https://github.com/polera/publicip) - Package publicip returns your public facing IPv4 address (internet egress).
* [quic-go](https://github.com/lucas-clemente/quic-go) - An implementation of the QUIC protocol in pure Go.
* [raw](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface.
* [sftp](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt.
* [ssh](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh).
* [sslb](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance.
* [stun](https://github.com/go-rtc/stun) - Go implementation of RFC 5389 STUN protocol.
* [tcp_server](https://github.com/firstrow/tcp_server) - Go library for building tcp servers faster.
* [tspool](https://github.com/two/tspool) - A TCP Library use worker pool to improve performance and protect your server.
* [utp](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation.
* [water](https://github.com/songgao/water) - Simple TUN/TAP library.
* [webrtc](https://github.com/pions/webrtc) - A pure Go implementation of the WebRTC API.
* [winrm](https://github.com/masterzen/winrm) - Go WinRM client to remotely execute commands on Windows machines.
* [xtcp](https://github.com/xfxdev/xtcp) - TCP Server Framework with simultaneous full duplex communication,graceful shutdown,custom protocol.

### HTTP Clients

*Libraries for making HTTP requests.*

* [gentleman](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library.
* [goreq](https://github.com/smallnest/goreq) - Enhanced simplified HTTP client based on gorequest.
* [grequests](https://github.com/levigross/grequests) - A Go "clone" of the great and famous Requests library.
* [heimdall](https://github.com/gojektech/heimdall) - An enchanced http client with retry and hystrix capabilities.
* [pester](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency.
* [rq](https://github.com/ddo/rq) - A nicer interface for golang stdlib HTTP client.
* [sling](https://github.com/dghubble/sling) - Sling is a Go HTTP client library for creating and sending API requests.

## OpenGL

*Libraries for using OpenGL in Go.*

* [gl](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow).
* [glfw](https://github.com/go-gl/glfw) - Go bindings for GLFW 3.
* [goxjs/gl](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android).
* [goxjs/glfw](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events.
* [mathgl](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM.

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [beego orm](https://github.com/astaxie/beego/tree/master/orm) - Powerful orm framework for go. Support: pq/mysql/sqlite3.
* [go-pg](https://github.com/go-pg/pg) - PostgreSQL ORM with focus on PostgreSQL specific features and performance.
* [go-queryset](https://github.com/jirfag/go-queryset) - 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM.
* [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) - A flexible and powerful SQL string builder library plus a zero-config ORM.
* [go-store](https://github.com/gosuri/go-store) - Simple and fast Redis backed key-value store library for Go.
* [gomodel](https://github.com/cosiner/gomodel) - Lightweight, fast, orm-like library helps interactive with database.
* [GORM](https://github.com/jinzhu/gorm) - The fantastic ORM library for Golang, aims to be developer friendly.
* [gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go.
* [grimoire](https://github.com/Fs02/grimoire) - Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3).
* [lore](https://github.com/abrahambotros/lore) - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go.
* [Marlow](https://github.com/dadleyy/marlow) - Generated ORM from project structs for compile time safety assurances.
* [pop/soda](https://github.com/gobuffalo/pop) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* [QBS](https://github.com/coocood/qbs) - Stands for Query By Struct. A Go ORM.
* [reform](https://github.com/go-reform/reform) - Better ORM for Go, based on non-empty interfaces and code generation.
* [SQLBoiler](https://github.com/volatiletech/sqlboiler) - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema.
* [upper.io/db](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers.
* [Xorm](https://github.com/go-xorm/xorm) - Simple and powerful ORM for Go.
* [Zoom](https://github.com/albrow/zoom) - Blazing-fast datastore and querying engine built on Redis.

## Resource Embedding

* [esc](https://github.com/mjibson/esc) - Embeds files into Go programs and provides http.FileSystem interfaces to them.
* [fileb0x](https://github.com/UnnoTed/fileb0x) - Simple tool to embed files in go with focus on "customization" and ease to use.
* [go-embed](https://github.com/pyros2097/go-embed) - Generates go code to embed resource files into your library or executable.
* [go-resources](https://github.com/omeid/go-resources) - Unfancy resources embedding with Go.
* [go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as html,js,css,images and templates very easy.
* [packr](https://github.com/gobuffalo/packr) - The simple and easy way to embed static files into Go binaries.
* [statics](https://github.com/go-playground/statics) - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks.
* [statik](https://github.com/rakyll/statik) - Embeds static files into a Go executable.
* [templify](https://github.com/wlbr/templify) - Embed external template files into Go code to create single file binaries.
* [vfsgen](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem.

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* [chart](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types.
* [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) - Dataframes for Go for machine-learning and statistics (similar to pandas).
* [evaler](https://github.com/soniah/evaler) - Simple floating point arithmetic expression evaluator.
* [ewma](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages.
* [geom](https://github.com/skelterjohn/geom) - 2D geometry for golang.
* [go-dsp](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go.
* [go-fn](https://github.com/ematvey/go-fn) - Mathematical functions written in Go language, that are not covered by math pkg.
* [go-gt](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language.
* [gocomplex](https://github.com/varver/gocomplex) - Complex number library for the Go programming language.
* [goent](https://github.com/kzahedi/goent) - GO Implementation of Entropy Measures.
* [gohistogram](https://github.com/VividCortex/gohistogram) - Approximate histograms for data streams.
* [gonum](https://github.com/gonum/gonum) - Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more.
* [gonum/plot](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go.
* [goraph](https://github.com/gyuho/goraph) - Pure Go graph theory library(data structure, algorith visualization).
* [gosl](https://github.com/cpmech/gosl) - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more.
* [GoStats](https://github.com/OGFris/GoStats) - GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions.
* [graph](https://github.com/yourbasic/graph) - Library of basic graph algorithms.
* [ode](https://github.com/ChristopherRabotin/ode) - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions.
* [orb](https://github.com/paulmach/orb) - 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support.
* [pagerank](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go.
* [piecewiselinear](https://github.com/sgreben/piecewiselinear) - Tiny linear interpolation library.
* [PiHex](https://github.com/claygod/PiHex) - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi.
* [rootfinding](https://github.com/khezen/rootfinding) - root-finding algorithms library for finding roots of quadratic functions.
* [sparse](https://github.com/james-bowman/sparse) - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries.
* [stats](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library.
* [streamtools](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data.
* [TextRank](https://github.com/DavidBelicza/TextRank) - TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support.
* [triangolatte](https://github.com/tchayen/triangolatte) - 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs.


## Serialization

*Libraries and tools for binary serialization.*

* [asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER and DER encoding library for golang.
* [bambam](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go.
* [bel](https://github.com/32leaves/bel) - Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC.
* [colfer](https://github.com/pascaldekloe/colfer) - Code generation for the Colfer binary format.
* [csvutil](https://github.com/jszwec/csvutil) - High Performance, idiomatic CSV record encoding and decoding to native Go structures.
* [fwencoder](https://github.com/o1egl/fwencoder) - Fixed width file parser (encoding and decoding library) for Go.
* [go-capnproto](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go.
* [go-codec](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support.
* [gogoprotobuf](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets.
* [goprotobuf](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers.
* [jsoniter](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json".
* [mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures.
* [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions.
* [structomap](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures.


## Text Processing

*Libraries for parsing and manipulating texts.*

* Specific Formats
    * [align](https://github.com/Guitarbum722/align) - A general purpose application that aligns text.
    * [allot](https://github.com/sbstjn/allot) - Placeholder and wildcard text parsing for CLI tools and bots.
    * [bbConvert](https://github.com/CalebQ42/bbConvert) - Converts bbCode to HTML that allows you to add support for custom bbCode tags.
    * [blackfriday](https://github.com/russross/blackfriday) - Markdown processor in Go.
    * [bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer.
    * [colly](https://github.com/asciimoo/colly) - Fast and Elegant Scraping Framework for Gophers.
    * [commonregex](https://github.com/mingrammer/commonregex) - A collection of common regular expressions for Go.
    * [dataflowkit](https://github.com/slotix/dataflowkit) - Web scraping Framework to turn websites into structured data.
    * [did](https://github.com/ockam-network/did) - DID (Decentralized Identifiers) Parser and Stringer in Go.
    * [doi](https://github.com/hscells/doi) - Document object identifier (doi) parser in Go.
    * [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) - Editorconfig file parser and manipulator for Go.
    * [enca](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](http://cihar.com/software/enca/).
    * [encdec](https://github.com/mickep76/encdec) - Package provides a generic interface to encoders and decodersa.
    * [genex](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings.
    * [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links.
    * [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) - Fixed-width text formatting (encoder/decoder with reflection).
    * [go-humanize](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format.
    * [go-nmea](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language.
    * [go-runewidth](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string.
    * [go-slugify](https://github.com/mozillazg/go-slugify) - Make pretty slug with multiple languages support.
    * [go-vcard](https://github.com/emersion/go-vcard) - Parse and format vCard.
    * [go-zero-width](https://github.com/trubitsyn/go-zero-width) - Zero-width character detection and removal for Go.
    * [gofeed](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go.
    * [gographviz](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language.
    * [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) - Format bytes to string.
    * [gonameparts](https://github.com/polera/gonameparts) - Parses human names into individual name parts.
    * [goq](https://github.com/andrewstuart/goq) - Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery).
    * [GoQuery](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language.
    * [goregen](https://github.com/zach-klippenstein/goregen) - Library for generating random strings from regular expressions.
    * [gotext](https://github.com/leonelquinteros/gotext) - GNU gettext utilities for Go.
    * [guesslanguage](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text.
    * [htmlquery](https://github.com/antchfx/htmlquery) - An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression.
    * [inject](https://github.com/facebookgo/inject) - Package inject provides a reflect based injector.
    * [mxj](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages.
    * [sdp](https://github.com/gortc/sdp) - SDP: Session Description Protocol [[RFC 4566](https://tools.ietf.org/html/rfc4566)].
    * [sh](https://github.com/mvdan/sh) - Shell parser and formatter.
    * [slug](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support.
    * [Slugify](https://github.com/avelino/slugify) - Go slugify application that handles string.
    * [syndfeed](https://github.com/zhengchun/syndfeed) - A syndication feed for Atom 1.0 and RSS 2.0.
    * [toml](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection).
* Utility
    * [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) - A sanitization-based swear filter for Go.
    * [gotabulate](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go.
    * [kace](https://github.com/codemodus/kace) - Common case conversions covering common initialisms.
    * [parseargs-go](https://github.com/nproc/parseargs-go) - string argument parser that understands quotes and backslashes.
    * [parth](https://github.com/codemodus/parth) - URL path segmentation parsing.
    * [radix](https://github.com/yourbasic/radix) - fast string sorting algorithm.
    * [TySug](https://github.com/Dynom/TySug) - Alternative suggestions with respect to keyboard layouts.
    * [xj2go](https://github.com/stackerzzq/xj2go) - Convert xml or json to go struct.
    * [xurls](https://github.com/mvdan/xurls) - Extract urls from text.


## Utilities

*General utilities and tools to make your life easier.*

* [abutil](https://github.com/bahlo/abutil) - Collection of often-used Golang helpers.
* [apm](https://github.com/topfreegames/apm) - Process manager for Golang applications with an HTTP API.
* [backscanner](https://github.com/icza/backscanner) - A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward.
* [blank](https://github.com/Henry-Sarabia/blank) - Verify or remove blanks and whitespace from strings.
* [boilr](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates.
* [chyle](https://github.com/antham/chyle) - Changelog generator using a git repository with multiple configuration possibilities.
* [circuit](https://github.com/cep21/circuit) - An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern.
* [circuitbreaker](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go.
* [clockwork](https://github.com/jonboulle/clockwork) - A simple fake clock for golang.
* [command](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher.
* [copy-pasta](https://github.com/jutkko/copy-pasta) - Universal multi-workstation clipboard that uses S3 like backend for the storage.
* [ctop](https://github.com/bcicen/ctop) - [Top-like](http://ctop.sh) interface (e.g. htop) for container metrics.
* [ctxutil](https://github.com/posener/ctxutil) - A collection of utility functions for contexts.
* [Death](https://github.com/vrecan/death) - Managing go application shutdown with signals.
* [Deepcopier](https://github.com/ulule/deepcopier) - Simple struct copying for Go.
* [delve](https://github.com/derekparker/delve) - Go debugger.
* [dlog](https://github.com/kirillDanshin/dlog) - Compile-time controlled logger to make your release smaller without removing debug calls.
* [ergo](https://github.com/cristianoliveira/ergo) - The management of multiple local services running over different ports made easy.
* [evaluator](https://github.com/nullne/evaluator) - Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend.
* [fastlz](https://github.com/digitalcrab/fastlz) - Wrap over [FastLz](http://fastlz.org/) (free, open-source, portable real-time compression library) for GoLang.
* [filetype](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature.
* [filler](https://github.com/yaronsumel/filler) - small utility to fill structs using "fill" tag.
* [filter](https://github.com/gookit/filter) - provide filtering, sanitizing, and conversion of Go data.
* [fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go.
* [gaper](https://github.com/maxcnunes/gaper) - Builds and restarts a Go project when it crashes or some watched file changes.
* [generate](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex.
* [ghokin](https://github.com/antham/ghokin) - Parallelized formatter with no external dependencies for gherkin (cucumber, behat...).
* [git-time-metric](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git.
* [go-astitodo](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code.
* [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) - go:generate tool for wrapping symbols exported by golang plugins (1.8 only).
* [go-bsdiff](https://github.com/gabstv/go-bsdiff) - Pure Go bsdiff and bspatch libraries and CLI tools.
* [go-dry](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go.
* [go-funk](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...).
* [go-health](https://github.com/Talento90/go-health) - Health package simplifies the way you add health check to your services.
* [go-httpheader](https://github.com/mozillazg/go-httpheader) - Go library for encoding structs into Header fields.
* [go-rate](https://github.com/beefsack/go-rate) - Timed rate limiter for Go.
* [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go.
* [go-torch](https://github.com/uber/go-torch) - Stochastic flame graph profiler for Go programs.
* [go-trigger](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project.
* [goback](https://github.com/carlescere/goback) - Go simple exponential backoff package.
* [godaemon](https://github.com/VividCortex/godaemon) - Utility to write daemons.
* [godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox.
* [gohper](https://github.com/cosiner/gohper) - Various tools/modules help for development.
* [golarm](https://github.com/msempere/golarm) - Fire alarms with system events.
* [golog](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks.
* [gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs.
* [goplaceholder](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images.
* [goreleaser](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible.
* [goreporter](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report.
* [goseaweedfs](https://github.com/linxGnu/goseaweedfs) - SeaweedFS client library with almost full features.
* [gostrutils](https://github.com/ik5/gostrutils) - Collections of string manipulation and conversion functions.
* [gotenv](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go.
* [gpath](https://github.com/tenntenn/gpath) - Library to simplify access struct fields with Go's expression in reflection.
* [gubrak](https://github.com/novalagung/gubrak) - Golang utility library with syntactic sugar. It's like lodash, but for golang.
* [handy](https://github.com/miguelpragier/handy) - Many utilities and helpers like string handlers/formatters and validators.
* [htcat](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility.
* [hub](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal.
* [hystrix-go](https://github.com/afex/hystrix-go) - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker.
* [immortal](https://github.com/immortal/immortal) - \*nix cross-platform (OS agnostic) supervisor.
* [intrinsic](https://github.com/mengzhuo/intrinsic) - Use x86 SIMD without writing any assembly code.
* [jump](https://github.com/gsamokovarov/jump) - Jump helps you navigate faster by learning your habits.
* [koazee](https://github.com/wesovilabs/koazee) - Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays.
* [lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go.
* [mc](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems.
* [mergo](https://github.com/imdario/mergo) - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements.
* [mimemagic](https://github.com/zRedShift/mimemagic) - Pure Go ultra performant MIME sniffing library/utility.
* [mimesniffer](https://github.com/aofei/mimesniffer) - A MIME type sniffer for Go.
* [mimetype](https://github.com/gabriel-vasile/mimetype) - Package for MIME type detection based on magic numbers.
* [minify](https://github.com/tdewolff/minify) - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats.
* [minquery](https://github.com/icza/minquery) - MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off).
* [mmake](https://github.com/tj/mmake) - Modern Make.
* [moldova](https://github.com/StabbyCutyou/moldova) - Utility for generating random data based on an input template.
* [mole](https://github.com/davrodpin/mole) - cli app to easily create ssh tunnels.
* [mssqlx](https://github.com/linxGnu/mssqlx) - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind.
* [multitick](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers.
* [myhttp](https://github.com/inancgumus/myhttp) - Simple API to make HTTP GET requests with timeout support.
* [netbug](https://github.com/e-dard/netbug) - Easy remote profiling of your services.
* [okrun](https://github.com/xta/okrun) - go run error steamroller.
* [olaf](https://github.com/btnguyen2k/olaf) - Twitter Snowflake implemented in Go.
* [onecache](https://github.com/adelowo/onecache) - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc).
* [panicparse](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump.
* [peco](https://github.com/peco/peco) - Simplistic interactive filtering tool.
* [pgo](https://github.com/arthurkushman/pgo) - Convenient functions for PHP community.
* [pm](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API.
* [profile](https://github.com/pkg/profile) - Simple profiling support package for Go.
* [rclient](https://github.com/zpatrick/rclient) - Readable, flexible, simple-to-use client for REST APIs.
* [realize](https://github.com/tockins/realize) - Go build system with file watchers and live reload. Run, build and watch file changes with custom paths.
* [repeat](https://github.com/ssgreg/repeat) - Go implementation of different backoff strategies useful for retrying operations and heartbeating.
* [request](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™.
* [rerate](https://github.com/abo/rerate) - Redis-based rate counter and rate limiter for Go.
* [rerun](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes.
* [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client.
* [retry](https://github.com/kamilsk/retry) - The most advanced functional mechanism to perform actions repetitively until successful.
* [retry](https://github.com/percolate/retry) - A simple but highly configurable retry package for Go.
* [retry](https://github.com/thedevsaddam/retry) - Simple and easy retry mechanism package for Go.
* [retry](https://github.com/shafreeck/retry) - A pretty simple library to ensure your work to be done.
* [retry-go](https://github.com/rafaeljesus/retry-go) - Retrying made simple and easy for golang.
* [robustly](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics.
* [serve](https://github.com/syntaqx/serve) - A static http server anywhere you need.
* [silk](https://github.com/chrispassas/silk) - Read silk netflow files.
* [sliceconv](https://github.com/Henry-Sarabia/sliceconv) - Slice conversion between primitive types.
* [slicer](https://github.com/leaanthony/slicer) - Makes working with slices easier.
* [spinner](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options.
* [sqlx](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package.
* [sslice](https://github.com/yaa110/sslice) - Create a slice which is always sorted.
* [Storm](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB.
* [structs](https://github.com/PumpkinSeed/structs) - Implement simple functions to manipulate structs.
* [Task](https://github.com/go-task/task) - simple "Make" alternative.
* [toolbox](https://github.com/viant/toolbox) - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer.
* [ugo](https://github.com/alxrm/ugo) - ugo is slice toolbox with concise syntax for Go.
* [UNIS](https://github.com/esemplastic/unis) - Common Architecture™ for String Utilities in Go.
* [usql](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases.
* [util](https://github.com/shomali11/util) - Collection of useful utility functions. (strings, concurrency, manipulations, ...).
* [wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection.
* [xferspdy](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang.

