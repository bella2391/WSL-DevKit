# WSL-DevKit

## Demo
[https://youtu.be/1l8aeATnrZM](https://youtu.be/1l8aeATnrZM)

## Require
* Docker
* Python

## Command
```
usage: setup.py [-h] [-i] [-d] [--no-cache] [-y] [--set-env]

Script for setup of WSL environment with docker

options:
  -h, --help     show this help message and exit
  -i, --install  Install: Build & Export *.wsl & Import into WSL
  -d, --debug    Enable debug mode: Build & Run container & Enter it with tty
  --no-cache     Build with no cache
  -y             Response by default value for all prompts
  --set-env      Set environment variable, saving into .env
```

## Note
If you want to use gui application like discord.  
You should write `C:\Users\<user>\.wslconfig` like below.  
```
[wsl2]
guiApplications = true
```

## License
[MIT](LICENSE.txt)
