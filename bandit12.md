# Bandit Level 12 → Level 13

## Level Goal
The password for the next level is stored in the file data.txt, which is a hexdump of a file that has been repeatedly compressed. For this level it may be useful to create a directory under /tmp in which you can work. Use mkdir with a hard to guess directory name. Or better, use the command “mktemp -d”. Then copy the datafile using cp, and rename it using mv (read the manpages!)

#### Commands used
```bash
mktemp -d
cp data.txt /tmp/tmp.9Me161lUzI
cd /tmp/tmp.9Me161lUzI
xxd -r data.txt > data.bin
# Reverse the hexdump into binary

# Begin inspecting and decompressing layer by layer:
# .gz -> Gzip    -> Decompress with: gunzip file.gz
# .bz2 -> Bzip2  -> Decompress with: bunzip2 file.bz2
# .tar -> Tar    -> Extract with: tar -xf file.tar
```

<img width="1226" height="813" alt="image" src="https://github.com/user-attachments/assets/325621b0-f1dc-438e-a09a-01af307f9fdf" />
<img width="1201" height="384" alt="image" src="https://github.com/user-attachments/assets/43d01a30-c943-40f0-b9b0-f05274da15d0" />

- Password got : FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn
