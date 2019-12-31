Payette API Documentation
-------------------------

This repository contains doducmentation for the Payette API. The documentation is based on the [Slate API documention system](https://github.com/slatedocs/slate) which creates API documentaiton from specially formatted Markdown.

Deployed version on our test server: https://minty-fresh.herokuapp.com/api/v1/docs/

Getting Started
------------------------------

### Prerequisites

You're going to need:

 - **Linux or macOS** — Windows may work, but is unsupported.
 - **Ruby, version 2.3.1 or newer**
 - **Bundler** — If Ruby is already installed, but the `bundle` command doesn't work, just run `gem install bundler` in a terminal.

### Getting Set Up

1. Clone this repository
2. Initialize and start Slate. You can either do this locally, or with Vagrant:

```shell
# either run this to run locally
bundle install
bundle exec middleman server

# OR run this to run with vagrant
vagrant up
```

You can now see the docs at http://localhost:4567.

Now that Slate is all set up on your machine, you'll probably want to learn more about [editing Slate markdown](https://github.com/slatedocs/slate/wiki/Markdown-Syntax), or [how to publish your docs](https://github.com/slatedocs/slate/wiki/Deploying-Slate).

If you'd prefer to use Docker, instructions are available [in the wiki](https://github.com/slatedocs/slate/wiki/Docker).

### Note on JavaScript Runtime

For those who don't have JavaScript runtime or are experiencing JavaScript runtime issues with ExecJS, it is recommended to add the [rubyracer gem](https://github.com/cowboyd/therubyracer) to your gemfile and run `bundle` again.
