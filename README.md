This is an example of using a backend based on Rust Rocket project and a Client side app based on ReactJs (Webpack, Babel and company stack).

# Requirements

* [Rust nightly build](https://doc.rust-lang.org/book/nightly-rust.html)
* [NodeJS](https://nodejs.org/)

# Installation

To build the project just run:

```
npm run build
```

It compiles the Rust Rocket framework based server side application, then it installs nodejs depencency and it compiles client side application assets using Webpack.

```
npm start
```

Starts the Rust server. Open your browser at [http://localhost:8000](http://localhost:8000) and enjoy a basic Client side ReactJS based application.
