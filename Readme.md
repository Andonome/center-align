# Center

This tool centres the text output on stdout to the centre of the opened terminal.

```bash
  This command will take input from pipe (stdout) and will centre that data in terminal

flags:
    -h, --help: show this help
    -a, --all: will centre every line individually (Horizontal centre)

usage:
    command | centre
    command | centre -a
```

## Installation

```
sudo make install
```

## Uninstall
```
sudo make uninstall
```

# Check
![image](https://user-images.githubusercontent.com/60490474/232287874-ddf82867-cec6-4c2f-96e2-367ca5f44658.png)

Fun Command to give a try:
```
watch -n1 -t "date +%A%n%x%n%X | figlet  | centre -a"
```
![image](https://user-images.githubusercontent.com/60490474/232287938-a7e18d34-4f39-4f0c-bdde-0f30baa920eb.png)

