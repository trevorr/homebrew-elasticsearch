# Homebrew ElasticSearch

A repository for ElasticSearch-related brews.

## Requirements

* [Homebrew](https://github.com/Homebrew/homebrew)
* MacOS Mojave. Untested everywhere else.
* The Homebrew `versions` tap - `brew tap homebrew/versions`

## Keg Installation

```sh
brew tap trevorr/homebrew-elasticsearch
```

## Usage

### Service Install

```sh
brew install elasticsearch@1.3.9
```

### Service Start

```sh
brew services start elasticsearch@1.3.9
```

### Service Stop

```sh
brew services stop elasticsearch@1.3.9
```

### Service Status

```sh
brew services list
```

### Verify Running

```sh
curl http://localhost:9200
```
