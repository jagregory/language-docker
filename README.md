# Atom Docker syntax highlighting

Atom syntax highlighting for Dockerfiles.

## Highlighting of `Dockerfile.<suffix>`
Highlighting based on wildcards is [not supported](https://github.com/atom/first-mate/issues/64) in Atom. You can use package [file-types](https://atom.io/packages/file-types) with this in you `config.cson` to enable it.
```cson
  "file-types": {
    "^Dockerfile\\..*$": "source.dockerfile"
  }
```
