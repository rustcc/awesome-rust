# Awesome Rust
  Note:本项目由 [Rust中文社区](http://www.rust.cc) 发起和运作，最初翻译[kud1ing](https://github.com/kud1ing/awesome-rust)创建的awesome-rust

关于Rust代码和资源的一些汇总列表,受[awesome lists](https://github.com/bayandin/awesome-awesomeness)的启发
只有稳定的和对用户有用的才会增加,如果很长一段时间项目一直不能使用Rust-nightly去构建将会被移到[UNSTABLE.md](UNSTABLE.md).

- [Awesome Rust](#awesome-rust)
  - [代码](#代码)
    - [音频](#音频)
    - [构建系统](#构建系统)
    - [命令行参数解析](#命令行参数解析)
    - [压缩](#压缩)
    - [计算](#计算)
    - [密码学](#密码学)
    - [数据库](#数据库)
    - [编码](#编码)
    - [游戏开发](#游戏开发)
    - [游戏](#游戏)
    - [GUI](#gui)
    - [图像处理](#图像处理)
    - [网络编程](#网络编程)
    - [模板引擎](#模板引擎)
    - [测试](#测试)
    - [Web编程](#Web编程)
  - [资源](#资源)

## 代码


### 音频

* [bjz/openal-rs](https://github.com/bjz/openal-rs/) — [OpenAL 1.1](http://www.openal.org/)绑定
* [JeremyLetang/ears](https://github.com/JeremyLetang/ears) — 简易的声音播放库, 构建在OpenAL与libsndfile之上 [<img src="https://travis-ci.org/jeremyletang/ears.svg?branch=master">](https://travis-ci.org/JeremyLetang/ears)
* [JeremyLetang/rust-portaudio](https://github.com/JeremyLetang/rust-portaudio) — [PortAudio](http://www.portaudio.com/)绑定 [<img src="https://travis-ci.org/jeremyletang/rust-portaudio.svg?branch=master">](https://travis-ci.org/JeremyLetang/rust-portaudio)
* [musitdev/rust-portmidi](https://github.com/musitdev/rust-portmidi) — [PortMidi](http://portmedia.sourceforge.net/portmidi/)绑定 [<img src="https://travis-ci.org/musitdev/rust-portmidi.svg?branch=master">](https://travis-ci.org/musitdev/rust-portmidi)

### 构建系统

* [Cargo](http://crates.io) — Rust包管理
* CMake
  * [SiegeLord/RustCMake](https://github.com/SiegeLord/RustCMake) — 示例项目展示在Rust中使用CMake [<img src="https://travis-ci.org/SiegeLord/RustCMake.svg?branch=master">](https://travis-ci.org/SiegeLord/RustCMake)
* Make
  * [PistonDevelopers/rust-empty](https://github.com/PistonDevelopers/rust-empty) — 在Rust中使用Makefile构建,现已弃用被cargo取代

### 命令行参数解析

* [docopt/docopt.rs](https://github.com/docopt/docopt.rs) — Rust实现[DocOpt](http://docopt.org)用于命令行参数解析 [<img src="https://travis-ci.org/docopt/docopt.rs.svg?branch=master">](https://travis-ci.org/docopt/docopt.rs)

### 压缩

* [alexcrichton/bzip2-rs](https://github.com/alexcrichton/bzip2-rs) — [libbz2](http://www.bzip.org)绑定 [<img src="https://travis-ci.org/alexcrichton/bzip2-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/bzip2-rs)
* [alexcrichton/tar-rs](https://github.com/alexcrichton/tar-rs) — tar归档包读写 [<img src="https://travis-ci.org/alexcrichton/tar-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/tar-rs)
* [lifthrasiir/rust-zip](https://github.com/lifthrasiir/rust-zip) — ZIP归档包读写 [<img src="https://travis-ci.org/lifthrasiir/rust-zip.svg?branch=master">](https://travis-ci.org/lifthrasiir/rust-zip)

### 计算

* [eholk/rust-opencl](https://github.com/eholk/rust-opencl) — [OpenCL](https://www.khronos.org/opencl/)绑定 [<img src="https://travis-ci.org/eholk/rust-opencl.svg?branch=master">](https://travis-ci.org/eholk/rust-opencl)
* [thestinger/rust-gmp](https://github.com/thestinger/rust-gmp) — [libgmp](https://gmplib.org/)绑定

### 密码学

* [DaGenix/rust-crypto](https://github.com/DaGenix/rust-crypto) — Rust实现的各种加密算法 [<img src="https://travis-ci.org/DaGenix/rust-crypto.svg?branch=master">](https://travis-ci.org/DaGenix/rust-crypto)
* [dnaq/sodiumoxide](https://github.com/dnaq/sodiumoxide) — [libsodium](https://github.com/jedisct1/libsodium)绑定
* [klutzy/suruga](https://github.com/klutzy/suruga) — [TLS 1.2](http://tools.ietf.org/html/rfc5246)Rust实现
* [seb-m/common.rs](https://github.com/klutzy/suruga) — 实用的Rust加密工具
* [sfackler/rust-openssl](https://github.com/sfackler/rust-openssl) — [OpenSSL](https://www.openssl.org/)绑定 [<img src="https://travis-ci.org/sfackler/rust-openssl.svg?branch=master">](https://travis-ci.org/sfackler/rust-openssl)

### 数据库

* SQL
  * MySql
    * [blackbeam/rust-mysql-simple](https://github.com/blackbeam/rust-mysql-simple) — rust实现的Mysql客户端库 [<img src="https://travis-ci.org/blackbeam/rust-mysql-simple.svg?branch=master">](https://travis-ci.org/blackbeam/rust-mysql-simple)
  * PostgreSql
    * [sfackler/rust-postgres](https://github.com/sfackler/rust-postgres) — [PostgreSQL](http://www.postgresql.org)驱动 [<img src="https://travis-ci.org/sfackler/rust-postgres.svg?branch=master">](https://travis-ci.org/sfackler/rust-postgres)
  * Sqlite
    * [linuxfood/rustsqlite](https://github.com/linuxfood/rustsqlite) — [Sqlite3](http://www.sqlite.org/)绑定

### 编码

* Cap'n Proto
  * [dwrensha/capnproto-rust](https://github.com/dwrensha/capnproto-rust) — [<img src="https://travis-ci.org/dwrensha/capnproto-rust.svg?branch=master">](https://travis-ci.org/dwrensha/capnproto-rust)
* Character Encoding
  * [lifthrasiir/rust-encoding](https://github.com/lifthrasiir/rust-encoding) — [<img src="https://travis-ci.org/lifthrasiir/rust-encoding.svg?branch=master">](https://travis-ci.org/lifthrasiir/rust-encoding)
* CSV
  * [BurntSushi/rust-csv](https://github.com/BurntSushi/rust-csv) — [<img src="https://api.travis-ci.org/BurntSushi/rust-csv.svg?branch=master">](https://travis-ci.org/BurntSushi/rust-csv)
* HTML
  * [servo/html5ever](https://github.com/servo/html5ever) — 高性能浏览器级别的HTML5解析器 [<img src="https://travis-ci.org/servo/html5ever.svg?branch=master">](https://travis-ci.org/servo/html5ever)
* MsgPck
  * [mneumann/rust-msgpack](https://github.com/mneumann/rust-msgpack) — [<img src="https://travis-ci.org/mneumann/rust-msgpack.svg?branch=master">](https://travis-ci.org/mneumann/rust-msgpack)
* ProtocolBuffers
  * [stepancheg/rust-protobuf](https://github.com/stepancheg/rust-protobuf) — [<img src="https://travis-ci.org/stepancheg/rust-protobuf.svg?branch=master">](https://travis-ci.org/stepancheg/rust-protobuf)
* TOML
  * [alexcrichton/toml-rs](https://github.com/alexcrichton/toml-rs)
* Tnetstring
* XML
  * [Florob/RustyXML](https://github.com/Florob/RustyXML) — Rust写的一个XML解析器 [<img src="https://travis-ci.org/Florob/RustyXML.svg?branch=master">](https://travis-ci.org/Florob/RustyXM)
  * [netvl/rust-xml](https://github.com/netvl/rust-xml) — 基于流的XML解析库 [<img src="https://travis-ci.org/netvl/rust-xml.svg?branch=master">](https://travis-ci.org/netvl/rust-xml)

### 游戏开发

* [bbodi/rust-voxlap](https://github.com/bbodi/rust-voxlap) — [Voxlap](http://advsys.net/ken/voxlap.htm)绑定
* [PistonDevelopers/piston](https://github.com/pistondevelopers/piston) — [<img src="https://travis-ci.org/PistonDevelopers/piston.svg?branch=master">](https://travis-ci.org/PistonDevelopers/piston)
* [SiegeLord/RustAllegro](https://github.com/SiegeLord/RustAllegro) — [Allegro 5](http://liballeg.org/)绑定 [<img src="https://travis-ci.org/SiegeLord/RustAllegro.svg?branch=master">](https://travis-ci.org/SiegeLord/RustAllegro)

### 游戏

* [lifthrasiir/angolmois-rust](https://github.com/lifthrasiir/angolmois-rust) — 简约的音乐视频游戏支持BMS格式 [<img src="https://travis-ci.org/lifthrasiir/angolmois-rust.svg?branch=master">](https://travis-ci.org/lifthrasiir/angolmois-rust)

### GUI

* Cocoa
  * [mozilla-servo/rust-cocoa](https://github.com/mozilla-servo/rust-cocoa)
* Gtk+
  * [JeremyLetang/rgtk](https://github.com/JeremyLetang/rgtk) — [Gtk+](http://www.gtk.org)绑定 [<img src="https://travis-ci.org/jeremyletang/rgtk.svg?branch=master">](https://travis-ci.org/jeremyletang/rgtk)
* ncurses
  * [jeaye/ncurses-rs](https://github.com/jeaye/ncurses-rs) — [<img src="https://travis-ci.org/jeaye/ncurses-rs.svg?branch=master">](https://travis-ci.org/jeaye/ncurses-rs)
* OpenGL
  * [tomaka/glutin](https://github.com/tomaka/glutin) — 用于替代[GLFW](http://www.glfw.org/) [<img src="https://travis-ci.org/tomaka/glutin.svg?branch=master">](https://travis-ci.org/tomaka/glutin)
* SDL
  * [AngryLawyer/rust-sdl2](https://github.com/AngryLawyer/rust-sdl2) — [SDL2](http://www.libsdl.org/)绑定 [<img src="https://travis-ci.org/AngryLawyer/rust-sdl2.svg?branch=master">](https://travis-ci.org/AngryLawyer/rust-sdl2)
  * [brson/rust-sdl](https://github.com/brson/rust-sdl) — [SDL1](http://www.libsdl.org/)绑定 [<img src="https://travis-ci.org/brson/rust-sdl.svg?branch=master">](https://travis-ci.org/brson/rust-sdl)
* SFML
  * [jeremyletang/rust-sfml](https://github.com/JeremyLetang/rust-sfml) — [SFML](http://www.sfml-dev.org/)绑定 [<img src="https://travis-ci.org/jeremyletang/rust-sfml.svg?branch=master">](https://travis-ci.org/jeremyLetang/rust-sfml)
* Termbox
  * [gchp/rustbox](https://github.com/gchp/rustbox) — Rust实现的[termbox](http://github.com/nsf/termbox)库
* wxWidgets

### 图像处理

* [PistonDevelopers/image](https://github.com/PistonDevelopers/image) — 图像的编码与解码 [<img src="https://travis-ci.org/PistonDevelopers/image.svg?branch=master">](https://travis-ci.org/PistonDevelopers/image)

### 网络编程

* Low level
  * [libpnet/libpnet](https://github.com/libpnet/libpnet) — 跨平台、底层网络库 [<img src="https://api.travis-ci.org/libpnet/libpnet.svg?branch=master">](https://travis-ci.org/libpnet/libpnet)
* NanoMsg
  * [thehydroimpulse/nanomsg.rs](https://github.com/thehydroimpulse/nanomsg.rs) — ZeroMQ之后一个现代化的消息通信库 [<img src="https://travis-ci.org/thehydroimpulse/nanomsg.rs.svg?branch=master">](https://travis-ci.org/thehydroimpulse/nanomsg.rs)
* SSH
  * [alexcrichton/ssh2-rs](https://github.com/alexcrichton/ssh2-rs) — [libssh2](http://www.libssh2.org/)绑定 [<img src="https://travis-ci.org/alexcrichton/ssh2-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/ssh2-rs)
* Stomp
  * [zslayton/stomp-rs](https://github.com/zslayton/stomp-rs) — Rust实现[STOMP 1.2](http://stomp.github.io/stomp-specification-1.2.html)客户端 [<img src="https://api.travis-ci.org/zslayton/stomp-rs.svg?branch=master">](https://travis-ci.org/zslayton/stomp-rs)
* ZeroMQ

### 模板引擎

* Mustache
  * [rustache/rustache](https://github.com/rustache/rustache) — [<img src="https://travis-ci.org/rustache/rustache.svg?branch=master">](https://travis-ci.org/rustache/rustache)

### 测试

* [BurntSushi/quickcheck](https://github.com/BurntSushi/quickcheck) — Rust实现[QuickCheck](http://www.haskell.org/haskellwiki/Introduction_to_QuickCheck1) [<img src="https://travis-ci.org/BurntSushi/quickcheck.svg?branch=master">](https://travis-ci.org/BurntSushi/quickcheck)
* [farcaller/shiny](https://github.com/farcaller/shiny) — ruby's rspec或Objective-C's kiwi类似的语法 [<img src="https://travis-ci.org/farcaller/shiny.svg?branch=master">](https://travis-ci.org/farcaller/shiny)

### Web编程

See also [http://arewewebyet.com/](http://arewewebyet.com/)

* Core
  * [chris-morgan/rust-http](https://github.com/chris-morgan/rust-http) — 将会被[Teepee](http://teepee.rs/)取代 [<img src="https://travis-ci.org/chris-morgan/rust-http.svg?branch=master">](https://travis-ci.org/chris-morgan/rust-http)
  * [hyperium/hyper](https://github.com/hyperium/hyper) — [<img src="https://travis-ci.org/hyperium/hyper.svg?branch=master">](https://travis-ci.org/hyperium/hyper)
* Client
  * [carllerche/curl-rust](https://github.com/carllerche/curl-rust) — [libcurl](http://curl.haxx.se/libcurl/)绑定
  * [vhbit/curl-rs](https://github.com/vhbit/curl-rs) — [libcurl](http://curl.haxx.se/libcurl/)绑定
* Server
  * [Iron](http://ironframework.io/) — 灵感来源于[Express](http://expressjs.com/) [<img src="https://travis-ci.org/iron/iron.svg?branch=master">](https://travis-ci.org/iron/iron)
  * [Nickel](http://nickel.rs/) — 灵感来源于[Express](http://expressjs.com/) [<img src="https://travis-ci.org/nickel-org/nickel.rs.svg?branch=master">](https://travis-ci.org/nickel-org/nickel.rs)

## 资源

* [Rust by Example](http://rustbyexample.com/)
* [Rust CI](http://www.rust-ci.org) — a [Travis CI](https://travis-ci.com) dashboard for Rust projects
* [Rust Guidelines](http://aturon.github.io)
