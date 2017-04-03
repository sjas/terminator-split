# terminator-split
Wrapper script for easier opening split Terminator terminals.

- Needs Terminator terminal emulator to work.
- Tested with python3, needs python configobj lib.
- Renamed to 'tsp' for easier usage, compared to the original version.

```shell
$ tsp --help
usage: tsp [-h] [-d]
                        [-e COMMAND] [-g CONFIG] [-t TERMINATOR]
                        [TERMINATOR_OPTIONS]
                        hostname [hostname ...]


positional arguments:
  hostname

optional arguments:
  -h, --help            show this help message and exit
  -d, --debug
  -e COMMAND, --command COMMAND
  -g CONFIG, --config CONFIG
  -t TERMINATOR, --terminator TERMINATOR
```

```shell
tsp -m localhost localhost localhost localhost
```

![](https://github.com/sjas/terminator-split/blob/master/images/terminator-split-4.png?raw=true)

```shell
tsp -m localhost localhost localhost localhost localhost localhost localhost localhost
```

![](https://github.com/sjas/terminator-split/blob/master/images/terminator-split-8.png?raw=true)
