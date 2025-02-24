# Rust Web Development Resources
This is a curated list of resources for web application development in Rust. The [Awesome Rust](https://github.com/rust-unofficial/awesome-rust) list covers many topics, including web development, but this list focuses specifically on web-related resources for easier access.

## Backend frameworks
  - [Axum](https://github.com/tokio-rs/axum) - Ergonomic and modular web framework built with Tokio, Tower, and Hyper
  - [Actix Web](https://actix.rs/) - Actix Web is a powerful, pragmatic, and extremely fast web framework for Rust
  - [Poem](https://github.com/poem-web/poem) - A full-featured and easy-to-use web framework with the Rust programming language.
  - [Ntex](https://ntex.rs/) - Ntex is a powerful, pragmatic, and extremely fast framework for composable networking services for Rust
  - [Rocket](https://github.com/rwf2/Rocket) - Rocket is an async web framework for Rust with a focus on usability, security, extensibility, and speed.

    
## Frontend(and Full Stack) frameworks
  - [Dioxus](https://dioxuslabs.com/) - Dioxus is the Rust framework for building fullstack web, desktop, and mobile apps.
  - [Leptos](https://leptos.dev/) - Leptos is a full-stack, isomorphic Rust web framework leveraging fine-grained reactivity to build declarative user interfaces.
  - [Yew](https://github.com/yewstack/yew) - Rust / Wasm framework for creating reliable and efficient web applications
  - [Loco](https://loco.rs/) - It’s Like Ruby on Rails, but for Rust. Get the same great building experience of Rails, with the incredible performance and safety of Rust.

## Database libraries
  - Generic (libraries that support multiple databases)
    - [sqlx](https://github.com/launchbadge/sqlx) - SQLx is an async, pure Rust SQL crate featuring compile-time checked queries without a DSL.
    - [sea-query](https://github.com/SeaQL/sea-query) - A dynamic SQL query builder for MySQL, Postgres and SQLite
    - [sea-schema](https://github.com/SeaQL/sea-schema) - SeaSchema is a library to help you manage database schema for MySQL, Postgres and SQLite
  - Mariadb/MYSQL
    - [mysql_async](https://github.com/blackbeam/mysql_async) - Tokio based asynchronous MySql client library for The Rust Programming Language.
    - [mysql-proxy-rs](https://github.com/AgilData/mysql-proxy-rs) - A highly scalable MySQL Proxy framework written in Rust
    - [rust-mysql-simple](https://github.com/blackbeam/rust-mysql-simple) - Mysql client library implemented in rust.
  - Microsoft SQL
    - [tiberius](https://github.com/prisma/tiberius) - TDS 7.2+ (Microsoft SQL Server) driver for Rust
  - ORM
      - [SeaORM](https://crates.io/crates/sea-orm) - SeaORM is a relational ORM to help you build web services in Rust with the familiarity of dynamic languages.
      - [Diesel](https://github.com/diesel-rs/diesel) - A safe, extensible ORM and Query Builder for Rust

## Networking and Infrastructure Frameworks
  - [Pingora](https://github.com/cloudflare/pingora) - A Rust async multithreaded framework that assists in constructing HTTP proxy services.  A library for building fast, reliable and evolvable network services.

## Authentication
  - [oauth2-rs](https://github.com/ramosbugs/oauth2-rs) - Extensible, strongly-typed Rust OAuth2 client library
  - [jsonwebtoken](https://github.com/Keats/jsonwebtoken) - Create and parses JWT (JSON Web Tokens)

## Mocking Libraries
 - [httpmock](https://github.com/alexliesenfeld/httpmock) - Simple yet powerful HTTP mocking library for Rust
 - [mockito](https://github.com/lipanski/mockito) - Mockito is a library for generating and delivering HTTP mocks in Rust. You can use it for integration testing or offline work.

## Platforms
  - [Shuttle](https://www.shuttle.dev/) - Build & ship a backend without writing any infrastructure files.
  - [Dioxus Labs\(Coming Soon\)](https://dioxuslabs.com/deploy/) - The batteries-included platform for deploying desktop, web, and mobile apps. Iterate quickly, collaborate with your team, and scale to millions.

## Other realted libraries
  - [Hyper](https://github.com/hyperium/hyper) - An HTTP library for Rust
