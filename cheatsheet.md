# 🖥 Linux Terminal Cheatsheet

## 📁 Navigation (Daily Essentials)

| Command | Description |
|--------|------------|
| `pwd` | Print current directory |
| `ls` | List files |
| `ls -la` | List all files (including hidden) with details |
| `ls -lh` | Human-readable sizes |
| `cd <dir>` | Change directory |
| `cd ..` | Go up one level |
| `cd -` | Go to previous directory |
| `cd ~` | Go to home directory |


## ⚡ Pro Tips (Navigation)

- Use `TAB` for auto-completion  
- Use `cd -` to quickly switch between folders  
- Use relative paths when possible (cleaner & faster)  


## 🧪 Real Examples

```bash
cd /var/www/project
ls -la
cd ..
```

## 📄 File & Directory Management

| Command | Description |
|--------|------------|
| `touch file.txt` | Create file |
| `mkdir folder` | Create directory |
| `mkdir -p a/b/c` | Create nested directories |
| `cp file.txt copy.txt` | Copy file |
| `cp -r folder/ copy/` | Copy directory |
| `mv file.txt new.txt` | Rename file |
| `mv file.txt folder/` | Move file |
| `rm file.txt` | Delete file |
| `rm -r folder/` | Delete directory |
| `rm -rf folder/` | Force delete (⚠️ dangerous) |


## ⚡ Best Practices

- Avoid `rm -rf` unless you are 100% sure  
- Use `-i` flag for safety:
  ```bash
  rm -i file.txt
  ```

## 🧪 Real Examples

```bash
mkdir project
cd project
touch index.js
mv index.js app.js
```

## 📖 Viewing Files

| Command | Description |
|--------|------------|
| `cat file.txt` | Show content |
| `less file.txt` | Scrollable view |
| `head file.txt` | First lines |
| `tail file.txt` | Last lines |
| `tail -f file.txt` | Live logs |


## ⚡ Pro Tips

- Use `less` instead of `cat` for large files  
- Use `tail -f` for logs (VERY common in real work)  


## 🧪 Real Examples

```bash
tail -f app.log
head -n 20 file.txt
```

## 🔍 Search & Filtering

| Command | Description |
|--------|------------|
| `grep "text" file.txt` | Search text |
| `grep -i "text"` | Case insensitive |
| `grep -r "text" .` | Recursive search |
| `find . -name file.txt` | Find file |
| `find . -type d` | Find directories |


## ⚡ Pro Tips

- Combine `grep` with pipes:

```bash
ps aux | grep node
grep "error" logs.txt
```
## 🧪 Real Examples

```bash
grep "error" app.log
find . -name "*.js"
```

## 🔐 Permissions

| Command | Description |
|--------|------------|
| `ls -l` | Show permissions |
| `chmod +x file.sh` | Make executable |
| `chmod 755 file.sh` | Set permissions |
| `chown user file.txt` | Change owner |


## ⚡ Key Concept


- Owner → rwx  
- Group → r-x  
- Others → r-x  


## 🧪 Real Examples

```bash
chmod +x script.sh
chmod 755 script.sh
```

## ⚙️ Processes

| Command | Description |
|--------|------------|
| `ps` | Show processes |
| `ps aux` | Detailed list |
| `top` | Real-time monitor |
| `kill <pid>` | Kill process |
| `kill -9 <pid>` | Force kill |


## 🧪 Real Examples

```bash
ps aux | grep node
kill 1234
```


## 🌐 Networking

| Command | Description |
|--------|------------|
| `curl http://example.com` | HTTP request |
| `curl -O url` | Download file |
| `ping google.com` | Test connection |
| `ip a` | Show IP |


## 🧪 Real Examples
```bash
curl http://localhost:3000/api
curl -O https://example.com/file.zip
```

## 🔗 Pipes & Redirection

| Command | Description |
|--------|------------|
| `command > file.txt` | Output to file |
| `command >> file.txt` | Append |
| `command \| grep text` | Pipe output |


## ⚡ Productivity

| Command | Description |
|--------|------------|
| `history` | Show history |
| `!!` | Repeat last command |
| `alias ll="ls -la"` | Create alias |


## 🧠 Interview Tips

- Use pipes to combine commands  
- Prefer CLI tools over manual inspection  
- Show efficiency (aliases, history, grep usage)  


## 🧪 Real Examples

```bash
history | grep docker
ls -la | grep .js