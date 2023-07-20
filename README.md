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

6. To find out which of the devices is a `usb` device:

```bash
find /dev/disk -ls | grep usb
```

7. To decompress a `.gz` file, you can use the `gunzip` command:

```bash
gunzip abc.gz
```

8. To show the status of all network devices in a pretty human-readable format:

```bash
nmcli -p dev
```

9. Use the `ls` command to list the files and the `wc` command to count them:
   
```bash
ls | wc -l
```

10. To check the size of a directory:

```bash
du -sh /path/to/directory
```
