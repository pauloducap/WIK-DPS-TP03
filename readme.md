## Pour lancer :
```docker-compose up -d ```
puis aller sur http://localhost:8081/ping
## A l'aide de docker desktop , on peut voir les hostnames. 
EX :
```wik-dps-tp03-my_app-4 | b8cf4b513d94
wik-dps-tp03-reverse-proxy-1 | 172.20.0.1 - - [14/Nov/2022:23:59:33 +0000] "GET /ping HTTP/1.1" 200 736 "-" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/107.0.0.0 Safari/537.36"
```