# ZeraOS-repo

The official package repository for [ZeraOS](https://github.com/Dark8292/ZeraOS).

## Adding zeraos-repo to Arch Linux

### 1. Add the repository

Add the following to `/etc/pacman.conf`:

```ini
[zeraos-repo]
SigLevel = Optional TrustAll
Server = https://dark8292.github.io/ZeraOS-repo/x86_64
```

### 2. Sync repository

```bash
sudo pacman -Sy
```
