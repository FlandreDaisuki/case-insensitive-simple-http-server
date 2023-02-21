# case-insensitive-simple-http-server

Just support case insensitive to http.server

## Why

Some game developers made their game by RPG Maker MV/MZ on Windows. Their file namings are bad but their game works on Windows file system. However, the error "Failed to load" happens on Linux.

## Installation

```shell
wget https://raw.githubusercontent.com/FlandreDaisuki/case-insensitive-simple-http-server/master/case-insensitive-simple-http-server
chmod +x case-insensitive-simple-http-server
sudo mv case-insensitive-simple-http-server /usr/bin/ # or other path in your $PATH
```

## Usage

```shell
cd path/to/game-folder # which has index.html
case-insensitive-simple-http-server
```

or

```shell
case-insensitive-simple-http-server -d path/to/game-folder # which has index.html
```
