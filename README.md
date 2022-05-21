# Beltalowda

*For the many.*

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

## Roadmap

### POC

1. Configure PosgreSQL.
2. ???

### MVP

1. Configure gpg to work from devcontainer
    ```
    vscode ➜ /workspace (mvp) $ git commit -m MVP
    error: gpg failed to sign the data
    fatal: failed to write commit object
    ```
2. Fix permissions for `workdir`:
    ```
    vscode ➜ /workspace $ git status
    fatal: unsafe repository ('/workspace' is owned by someone else)
    To add an exception for this directory, call:

            git config --global --add safe.directory /workspace
    ```

### v1.0

1. Replace PostgreSQL with MySQL.
2. ???


## Links

* https://docs.docker.com/samples/rails/
* https://hub.docker.com/_/ruby/
* https://code.visualstudio.com/docs/containers/docker-compose
* https://code.visualstudio.com/docs/containers/debug-common