# Cheat-Codes

1. To display the content of a file, which are not commented:

```
sed 's/#.*//' file.txt | grep -v '^\s*$'
```

2. To find a file from the current location:

```
ag -g 'filename'
```
