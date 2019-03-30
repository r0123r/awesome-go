# Awesome Go

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

# Functional

*Packages to support functional programming in Go.*

* [fpGo](https://github.com/TeaEntityLab/fpGo) - Monad, Functional Programming features for Golang.
* [fuego](https://github.com/seborama/fuego) - Functional Experiment in Go.
* [go-underscore](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities.

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


## OpenGL

*Libraries for using OpenGL in Go.*

* [gl](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow).
* [glfw](https://github.com/go-gl/glfw) - Go bindings for GLFW 3.
* [goxjs/gl](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android).
* [goxjs/glfw](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events.
* [mathgl](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM.


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

