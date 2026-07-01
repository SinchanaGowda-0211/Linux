# Linux File Permission Commands

## chmod
Changes the permissions of a file or directory.

```bash
chmod 755 file.txt
chmod +x script.sh
chmod -w file.txt
```

## chown
Changes the owner of a file or directory.

```bash
sudo chown username file.txt
sudo chown username:groupname file.txt
```

## ls -l
Displays detailed information about files, including permissions.

```bash
ls -l
```

## umask
Shows or sets the default file permissions.

```bash
umask
umask 022
```

## stat
Displays detailed information about a file or directory.

```bash
stat file.txt
```
