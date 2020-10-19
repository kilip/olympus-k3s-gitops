Olympus K3S GitOps
====
My Home Edge Kubernetes Setup

Installation
====

### Install task file

Follow this url to install taskfile: https://taskfile.dev/#/installation

### Python Dependencies

With `taskfile` installed, initialize new python virtual environment with this command:

```console
$ taskfile pyenv
```

Install python dependencies:

```console
$ taskfile deps
```

### Configures your dotenv files

Make copy of `.env.default` files:

```console
$ cp .env.default .env
```

Edit `.env` file to match your needs.


### Configures your inventory

Make copy of sample inventory:

```console
$ cp inventory/sample inventory/prod
```

