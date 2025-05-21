<h1>MassDNS</h1>

Repositorio:
```
https://github.com/Screetsec/Sudomy
```

<h2>Instalación</h2>

```
git clone --recursive https://github.com/screetsec/Sudomy.git
cd sudomy
```

<h2>Creamos entorno virtual de Python</h2>

```
sudo apt install python3-venv
python3 -m venv .venv
source .venv/bin/activate
```

<h2>Instalar Go</h2>

```
sudo apt install gccgo-go 
sudo apt install golang-go
go install github.com/tomnomnom/unfurl@latest
sudo cp ~/go/bin/unfurl  /usr/local/bin
go install github.com/dwisiswant0/cf-check@latest
sudo cp ~/go/bin/cf-check  /usr/local/bin
go install -v github.com/rverton/webanalyze/cmd/webanalyze@latest
sudo cp ~/go/bin/webanalyze /usr/local/bin 
```

<h2>Instalamos las dependencias requeridas por el programa</h2>

```
python3 -m pip install -r requirements.txt
sudo apt-get update
sudo apt-get install jq nmap npm chromium parallel
npm i phantomjs
sudo npm i -g wappalyzer wscat
sudo apt-get install httpx dnsx gowitness subjack
```