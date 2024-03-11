# A simple wordlist for directory bruteforcing 

<h1 align="center">
  <br>

 Fuzzing
  <br>
</h1>

# Dorks

```bash

site:*/swagger/index.html intext:"Swagger UI"

```
# Tool

# FFUF 
 https://github.com/ffuf/ffuf


# NB:Still a work in progress we want a PERFECT WORDLIST

```bash
# Usage with a burpsuite proxy

# Dirbuster wordlist

$ ffuf -w "subs.txt:DOMAIN" -w /home/xii/dirsearch/db/dicc.txt -u https://DOMAIN/FUZZ -t 400 -o ffuzresults2.txt -replay-proxy http://127.0.0.1:8080

# Our wordlist

ffuf -w "subs.txt:DOMAIN" -w /home/xii/Documents/xiii/wordlist/wordlist.txt -u https://DOMAIN/FUZZ -t 400 -o ffuzresults2.txt -replay-proxy http://127.0.0.1:8080

i think you should be able to play around with the wordlist path 

```


# You may also like...

- [TrickShot  IO](https://github.com/Thabisoc123/Trickshot) - Trickshot IO app


> Twitter [@CNThabiso](https://twitter.com/CNThabiso)
