Each guide shows how to use Tokio in a different context.

# Pages:

* [Proxy](#proxy)
* [Database](#database)
* [Client](#client)
* [Game development](#game-dev)
* [Library](#library)
* [JavaScript Developers](#javascript-devs)

TODO: Fill out

<a name="proxy"></a>
## Proxy

**Status**: Assigned ([@olix0r](https://github.com/olix0r))

How to use Tokio to build a proxy. This guide may talk about other libs (like
tower, h2, hyper, etc...) but the goal is to approach it from the point of view
of someone getting started with Tokio.

The guide should cover application structure, concurrency, back pressure
concerns, and whatever other relevant real world concerns exist when
implementing a proxy.

#### Contents

TODO: Fill out

<a name="database"></a>
## Database

**Status**: Unassigned.

How to use Tokio to build a database.

#### Contents

TODO: Fill out

<a name="client"></a>
## Client

**Status**: Unassigned.

How to use Tokio to build a networking client.

#### Contents

TODO: Fill out

<a name="game-dev"></a>
## Game development

**Status**: Unassigned.

How to use Tokio as part of a game.

#### Contents

TODO: Fill out

<a name="library"></a>
## Library

**Status**: Unassigned.

How to write a library that uses Tokio.

#### Contents

TODO: Fill out

<a name="javascript-devs"></a>
## JavaScript Developers

**Status**: Unassigned.

How to use Tokio for those familiar with how promises work in JavaScript

#### Contents

* Differences to the JavaScript Model:
    * Callbacks
    * Promises (hint to future of async/await)
* Tokio & parallelism
    * JS is single threaded.
    * Tokio offers options
        * Brief discussion of `Send` w/ external links
        * Default `tokio::run` is mulit-threaded.
        * runtime::current_thread` is single threaded.
* Equivalents of:
    * setTimeout/setInterval
    * fetch
    * fs.readFile
