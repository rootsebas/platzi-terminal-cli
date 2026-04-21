# 🔐 File Permissions in Linux

## Commands Used

- `ls -la` (view file permissions)
- `chmod` (change permissions)
- `chmod -R` (recursive permission changes)

## Description

- `ls -la` → displays files with their permission structure
- `chmod` → modifies file or directory permissions
- `chmod -R` → applies permission changes recursively

Permissions are divided into three groups:
- **User (u)** → file owner
- **Group (g)** → users in the same group
- **Others (o)** → everyone else

Each group has:
- `r` → read (4)
- `w` → write (2)
- `x` → execute (1)

## Examples

- `-rwxrw-r--`  
  - User → read, write, execute  
  - Group → read, write  
  - Others → read  

- `chmod u+x script.sh` → gives execute permission to the owner
- `chmod 755 script.sh` → full permissions for user, read/execute for others
- `chmod 644 file.txt` → read/write for user, read-only for others
- `chmod 700 script.sh` → only the owner has full access

## Key Learnings

- File permissions control access and security in Linux systems
- The numeric system (4,2,1) simplifies permission assignment
- Avoid using `777` as it grants full access to everyone (security risk)
- Use `chmod -R` carefully to prevent unintended changes
- Follow the principle of least privilege (only necessary permissions)
- `755` is commonly used for executable scripts