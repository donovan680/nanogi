# Generate runC config fit to your environment.

## Requirements

* node.js 


## Setup

Assume nanogi-dist.tar.bz2(generated by `../export-nanogi-dist.sh` script) is placed at `../` directory.

## Run

    $ sh setup.sh
    # config.json and runtime.json will be generated.

    $ sudo runc start

## Known issues

Elapsed time(`-t` option) based rendering does not work well when you use checkpoint/restore feature to nanogi process.
