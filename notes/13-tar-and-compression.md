# 📦 File Packaging and Compression in Linux

## Commands Used

- `tar -cvf` (create archive)
- `tar -xvf` (extract archive)
- `tar -xzvf` (extract compressed archive)
- `gzip` (compress file)
- `gunzip` (decompress file)

## Description

- **Packaging (tar)** → combines multiple files/directories into a single file
- **Compression (gzip)** → reduces file size by removing redundancy
- These are separate processes but often used together (`.tar.gz`)

## Examples

- `tar -cvf textos.tar textos` → create archive from folder
- `gzip textos.tar` → compress archive into `.tar.gz`
- `gunzip textos.tar.gz` → decompress file
- `tar -xvf textos.tar` → extract files from archive
- `tar -xzvf textos.tar.gz` → decompress and extract in one step

## Key Learnings

- Packaging groups files; compression reduces size
- `.tar` = packaged file, `.tar.gz` = packaged + compressed
- `tar` can handle both steps using the `z` flag
- Common workflow: package → compress → transfer → extract
- Understanding both concepts is essential for file management and distribution