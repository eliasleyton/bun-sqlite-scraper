# Bun SQLite Scraper

Because why not

### Build and install deps

```sh
docker build . -t bun-sqlite-scraper 
```

### Run Container

```sh
docker run --rm -it -v "$PWD":/app bun-sqlite-scraper /bin/bash
```

### Install dependencies

```sh
bun install
```

### Execute

```sh
bun run index.ts
```
