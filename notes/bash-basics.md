# Basic Bash Scripting

## Shebang
A Bash script commonly begins with:

```bash
#!/bin/bash
```

This indicates the interpreter to use.

## Commands
Terminal commands can be used inside scripts.

```bash
#!/bin/bash
echo "Hello"
ls
```

## `sleep`
```bash
sleep 2
```

Pauses execution for the specified number of seconds.

## Variables
```bash
name="Rishi"
echo "$name"
```

## `read`
`read` waits for user input and stores it in a variable.

```bash
read name
echo "Hello $name"
```

## Running scripts

```bash
bash script.sh
```

The notes also covered making a script executable with `chmod` and then running it directly:

```bash
chmod +x script.sh
./script.sh
```

Nano was used for editing scripts.
