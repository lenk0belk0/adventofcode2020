# adventofcode2020

see https://adventofcode.com/2020

## How to run scripts
### With docker
see https://hub.docker.com/r/superpaintman/lua
```shell
$ docker run -it --rm --name my-adventofcode2020-script -v "$PWD":/usr/src/adventofcode2020 -w /usr/src/adventofcode2020 superpaintman/lua:latest lua path_to_script.lua
```