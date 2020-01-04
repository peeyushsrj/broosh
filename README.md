broosh
------

**Aim**: Make reading efficient; by reading less.

command line html parser based on python3 beautiful Soap packages. 

takes input from stdin. 

outputs to stdout.

### Prerequisite

1. python3 
2. bs4 package (do pip install bs4 --user)

### Usage 

1. Get me h1, h2 tags:

```
curl -s https://www.seeedstudio.com/blog/2019/09/29/top-20-best-raspberry-pi-4-projects-that-you-must-try-now/ | ./broosh h1 h2 | less
```

2. Get me h1 tags, 7th h2 tag including contents within it

```
curl -s https://www.seeedstudio.com/blog/2019/09/29/top-20-best-raspberry-pi-4-projects-that-you-must-try-now/ | ./broosh h2[6] | less
```

*Play around and convert yourself to markdown too.*
