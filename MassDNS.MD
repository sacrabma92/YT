
<h1>MassDNS</h1>

Repositorio:
```
https://github.com/blechschmidt/massdns
```

<h2>Instalación</h2>
```
git clone https://github.com/blechschmidt/massdns
cd massdns
make
sudo make install
```

<h2>Uso</h2>
```
assetfinder google.com --subs-only | massdns -r lists/resolvers.txt -o S -w resolved.txt
```

<h2>Filtrar</h2>
```
cat resolved.txt | grep mercadolibre.com.co | awk '{print $3}' | sort -u
```

