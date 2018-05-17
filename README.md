# EOS node manager

Run and use EOSIO local testnode using Docker

## Requirements

- Docker
- Git

## Installation

Clone the repo and run `bin/eos`

```bash
$ git clone git@github.com:intlcoin/eos-docker.git

$ ./eos-docker/bin/eos pull
```

## Usage

```
./eos-docker/bin/eos COMMAND [DATA]

Commands:
    start - starts eos container
    replay - starts eos container (in replay mode)
    shm_size - resizes /dev/shm to size given, e.g. ./run.sh shm_size 10G
    stop - stops eos container
    status - show status of eos container
    restart - restarts eos container
    pull - pulls latest docker image from server (no compiling)
    logs - show all logs inc. docker logs, and eos logs
    wallet - open cli_wallet in the container
    remote_wallet - open cli_wallet in the container connecting to a remote seed
    shell - enter a bash session in the container
```
## Contributing
Thanks for idea to https://github.com/Someguy123
Bug reports and pull requests are welcome on GitHub at https://github.com/intlcoin/eos-docker.
