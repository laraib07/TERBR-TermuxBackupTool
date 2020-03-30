# TERBR - TERMUX BACKUP/RESTORE TOOL

### Created by [MrAlpha786](https://github.com/MrAlpha786)

_Take backup and restore with just one command. Choose a directory to save backup and easily find them._

## Installation

Just enter following commands in respective order:

1.
```bash
apt-get update && apt-get upgrade -y
```
2.
```bash
apt-get install wget curl tar -y
```
3.
```bash
wget https://raw.githubusercontent.com/MrAlpha786/TERBR/master/terbr && chmod u+x terbr && mv terbr $PREFIX/bin/
```
or
```bash
curl -O https://raw.githubusercontent.com/MrAlpha786/TERBR/master/terbr && chmod u+x terbr && mv terbr $PREFIX/bin/
```
4.
```bash
terbr
```
##
On first run it will ask you to choose a Backup destination. You can choose a custom location or use the default.

Refer to "help" for further usage.
