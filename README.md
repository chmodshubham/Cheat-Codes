# Cheat-Codes

1. To display the content of a file, which are not commented:

```bash
sed 's/#.*//' file.txt | grep -v '^\s*$'
```

2. To find a file from the current location:

```bash
ag -g 'filename'
```

3. To compare 2 folders:

```bash
meld folder1 folder2
````

4. To search a particular word in `vim`:

```bash
/example
Enter
button "n" for FORWARD SEARCH
button "N" for BACKWARD SEARCH
```

5. To find out the distribution name and version of a Linux system:

```bash
lsb_release -a
```
