## Como Criar o Script e Integrar no Zabbbix
---

**REQUISITOS:**

* Python 3
* beautifulsoup4
* cloudscraper
* requests
* openssl 1.1.1

---
Debian / Ubuntu
```
apt install python3-pip
pip3 install bs4
pip3 install requests
pip3 install cloudscraper
```
---
CRIE OS ARQUIVOS NA PASTA E DE PERMISSÃO:
```
chown zabbix. /usr/lib/zabbix/externalscripts/downdetector*
chmod a+x /usr/lib/zabbix/externalscripts/downdetector*.py
```
---
INTEGRANDO NO ZABBIX:

Importe o template, após importe o host no zabbix. Pronto, tudo deve estar funcionando

### Teve dificuldades para criar o script? Assista o video abaixo:

:heart: https://www.youtube.com/watch?v=xKlHfJUV7Hs
