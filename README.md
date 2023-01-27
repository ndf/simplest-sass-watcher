# Simplest Bootstrap sass watcher
The most simple bootstrap sass watch script

# Why
Because you not always need all the features of the other watchers, compilers
and so on.

# What
This script watches your sass files and compiles them to css. It also copies
assets like fonts and images to the destination folder. Also, javascript files
are copied to the destination folder.

Please note how this script copies assets from node packages in such a way that
you can only use the "dist" folder on production, without the need to distribute
the "src" and "node_modules" folders.

# How

## Install

```bash
$ npm install
```

## Run

### 1. Copy assets from src to dist.

```bash
$ npm run copy-assets-to-dist
```

### 2. Watch sass files and compile during development.

```bash
$ npm run sass-dev
```

### 3. Start browser-sync during development.

```bash
$ npm run browser-sync
```

### 4. Compiles sass files for production.

```bash
$ npm run sass-prod
```
