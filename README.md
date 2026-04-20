# Installation :
1. Add the repo :
```bash
echo "deb [trusted=yes] https://q0so.github.io/makecommand/ ./" | sudo tee /etc/apt/sources.list.d/makecommand.list
```
2. Update packages :
```bash
sudo apt update
```
3. Install `makecommand` package :
```bash
sudo apt install makecommand
```

# Usage :
Show help menu :
```bash
makecommand -help
```
Add shortcut command :
```bash
makecommand "YOUR COMMAND" "NAME"
```
Run your command :
```bash
run NAME
```


# Uninstall:
```bash
sudo apt purge makecommand && sudo apt remove makecommand
```
<br>
This package made by AI, but with some edit from Aliraq1.
<br><br>
<a href="https://aliraq1.xyz">By Aliraq1</a>
