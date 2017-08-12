## Docker image for building Elixir applications

This is a simple Docker image, meant to be used as a base image for building Elixir applications, for example using [multi-stage builds](https://docs.docker.com/engine/userguide/eng-image/multistage-build/).

It installs the `alpine-sdk` and `bash` as prerequisites, and both Erlang and Elixir via the excellent [asdf](https://github.com/asdf-vm/asdf) version manager.

#### Current versions

|  | Version
|---|:---:|
| Alpine | 3.6 |
| Erlang | 20.0 |
| Elixir | 1.5.1 |
