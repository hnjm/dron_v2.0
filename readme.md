# guiaburros instalacion
Ubuntu 14+
Python 3.4+

## Instala python y git
```bash
sudo apt-get update
sudo apt-get install python3
sudo apt-get install git
```

## Crea una carpeta y clona el repositorio dentro
```bash
mkdir dron
cd dron
git clone https://github.com/uborzz/dron_v2.0 .
```

## Instala pip y virtualenv
```bash
sudo apt-get install python3-pip
sudo pip3 install virtualenv
```

## Crea y activa el entorno virtual con python 3
```bash
virtualenv /usr/bin/python3.* dron-venv
source dron-venv/bin/activate
```

## Instala paquetes de python necesarios
```bash
pip3 install -r requirements.txt
```