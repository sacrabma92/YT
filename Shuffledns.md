
<h1>Shuffledns</h1>

Repositorio:
```
https://github.com/projectdiscovery/shuffledns
```

<h2>Instalación de Go</h2>

```
sudo apt install gccgo-go 
sudo apt install golang-go
```

<h1>Instalación</h1>

Repositorio:
```
sudo apt install massdns
go install -v github.com/projectdiscovery/shuffledns/cmd/shuffledns@latest
sudo cp ~/go/bin/shuffledns /usr/local/bin
```

Instalar los resolver

```
wget https://github.com/blechschmidt/massdns/blob/master/lists/resolvers.txt
```

<h1>Uso</h1>

Fuerza Bruta:
```
shuffledns -d mercadolibre.com.co -w SecLists/Discovery/DNS/subdomains-top1million-5000.txt -r resolvers.txt -mode bruteforce
```