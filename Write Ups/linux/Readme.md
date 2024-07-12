# Fancy Linux Commands

## Grep

Used to search for certain strings in huge data sets.

```hacker@dojo:~$ grep SEARCH_STRING /path/to/file```

Easy way to find flags - An Epic Filesystem Quest
```grep -r "pwn.college*" /o```

# ;

Using ; can split console scripts 
``` mkdir /tmp/pwn; touch /tmp/pwn/college```

# find
*is used for "it could be anything" type shi-.
```find / -type f -name "flag.*"```

# gzip
Read man always super helpfull
```
hacker@program-misuse~level17:/$ gzip -c flag > /home/hacker/flag.gz
hacker@program-misuse~level17:/$ cd ~
hacker@program-misuse~level17:~$ gunzip -c flag.gz
```
