# Denaro CPU solo miner

## Installation

```bash
git clone https://github.com/geiccobs/denaro-solo-miner
cd denaro-solo-miner
```

### Compiling by source

You can skip this if you wanna use pre-built binary.  
[Install golang first](https://go.dev/doc/install)
```bash
go mod tidy
go build
```

## Usage

[Download latest binary](https://github.com/geiccobs/denaro-solo-miner/releases/latest) according to your system architecture. 
 
Use `./solo-miner-{yourarchitecture} -help` to see the full list of arguments. 
 
Notice: `share_difficulty` should be adjusted according to your hashrate: if you see a lot of shares accepted, increment it.

### Running on Linux

```bash
./solo-miner-linux64 -address youraddress -workers corescount -share_difficulty 6
```

### Running on Windows

```bash
start solo-miner-win64.exe -address youraddress -workers corescount -share_difficulty 6
```

### Running on MacOS

```bash
./solo-miner-macos-amd64 -address youraddress -workers corescount -share_difficulty 6
```
