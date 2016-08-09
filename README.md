# Atom Docker Syntax Highlighting

Atom syntax highlighting for Dockerfiles.

## Install

Install the package `language-docker` in Atom (Preferences->Packages) or Atom's package manager from a shell:

```bash
$ apm install language-docker
```

## Syntax support

language-docker supports most Dockerfile syntax features, as well as .dockerignore files.

## Highlighting of `Dockerfile.<suffix>`

Highlighting based on wildcards is [not supported](https://github.com/atom/first-mate/issues/64) in Atom. You can use package [file-types](https://atom.io/packages/file-types) with this in you `config.cson` to enable it.

```cson
  "file-types": {
    "^Dockerfile\\..*$": "source.dockerfile"
  }
```
