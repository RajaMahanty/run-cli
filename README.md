cat << 'EOF' > README.md

# run

A tiny universal runner for C, C++, Python, and JavaScript.

## Features

- Compile & run C/C++
- Run Python and Node scripts
- Automatic cleanup
- Correct exit codes
- Ctrl+C safe

## Install

```bash
curl -fsSL https://raw.githubusercontent.com/rajaMahanty/run/main/run \
  -o ~/.local/bin/run
chmod +x ~/.local/bin/run
```

## Usage

```
run main.cpp
run script.py
run app.js
```
