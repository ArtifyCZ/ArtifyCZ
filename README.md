# Hi, I'm Richard Tichý,

a software engineer, a system administrator and a system designer from the Czech Republic.

I have used many programming languages such as C, C#, Rust, Kotlin or Clojure,
server technologies such as Redis, MySQL, MariaDB or PostgreSQL and
 know system stuff in the Linux world, as I daily drive Linux, as the main OS.

## Projects

*As an example of my work, I can give you those few ones.*

### [Rusjure](https://github.com/rusjure/rusjure)

A compiler of a [Clojure](https://clojure.org/)-like language, written in [Rust](https://www.rust-lang.org/).
Parsing is built using library [Pest](https://pest.rs/), which allowed me to define the syntax using
[PEG](https://en.wikipedia.org/wiki/Parsing_expression_grammar) format.
Although in many languages the parsing part is quite complicated,
in [Lisp](https://en.wikipedia.org/wiki/Lisp_(programming_language))-like dialect I found the parsing quite simple.
I found more complicated though implementation of the [macros](https://clojure.org/reference/macros).
I had to understand that in Clojure, in fact, the code is *not translated*, but rather executed. Even a definition of
a function is a macro invocation.

### [Sportisimo Marks](https://github.com/artifycz/sportisimo-marks)

An information system imitating a part of an internal system of Sportisimo, written in [PHP](https://www.php.net/),
using the [Nette](https://nette.org/) framework, the [Latte](https://latte.nette.org/) templating system,
[Naja](https://naja.js.org/) and [Materialize](https://materializecss.com/). It is meant to be used with
a MySQL database. I also wrote a Dockerfile and a Docker Compose file, so you are able to run it locally
by yourself in Docker.

Because of code readability, I had to find an object-oriented way to use
the [Nette Database](https://doc.nette.org/en/database). Because it's not an ORM framework, I had to implement a custom
class for entities, as I had found the usage of entities the best way. There was also a problem with saving changes
in entities, because the Nette ActiveRow does not allow to set values by property setting...

### [Minesweeper](https://github.com/ArtifyCZ/minesweeper)

A web implementation of game Minesweeper, written in [C#](https://learn.microsoft.com/en-us/dotnet/csharp/),
using [Asp.Net Boilerplate (ABP)](https://abp.io/). Developed with the domain driven design in mind, it is,
in my opinion, a well readable code. Although it is playable, it does not contain, for example,
authorization and score recording. It was developed with usage of Postgres in mind.

### [Secret Hitler](https://github.com/artifycz/secrethitler)

A web implementation of game [Secret Hitler](https://www.secrethitler.com/), with the backend written in
[Rust](https://www.rust-lang.org/) using [Axum](https://github.com/tokio-rs/axum) framework and
[Sea-orm](https://www.sea-ql.org/SeaORM/) with connecting to PostgreSQL database. The frontend is written
in [Dart](https://dart.dev/) using [Flutter](https://flutter.dev/).

---

## Contact

- Email - tichy@artify.zone
- Matrix - [@artify:artify.zone](https://matrix.to/#/@artify:artify.zone)
- Web - [artify.zone](https://artify.zone/)
