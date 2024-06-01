
# Backend for HashIt App

Aplikácia HahsIt umožňuje vytváranie hashov pomocou implementovaného algoritmu SHA-256. Taktiež ponúka aj možnosť využiť ostatné hashovacie funkcie ako MD5, SHA3, SHA-224 a pod., ktoré sú dostupné cez knižnicu crypto-js. Okrem toho, umožňuje porovnávanie hashov tým, že si uložíme hodnotu hashu a následne sa porovnáva so súčasným hashom. Uložená hodnota hashu obsahuje aj informáciu o použitej hashovacej funkcii. Ak sa hashe zhodujú, textové polia sa zafarbia zelenou farbou. Taktiež je možné skopírovať hodnotu hashu pre ďalšie použitie.

Je to klient-server aplikácia. Klient bol naprogramovaný využitím frameworku Vue.js 3 v TypeScirpt a komponentovým frameworkom Quasar. Klient obsahuje watch property pre automatické vykonanie hashu pri písaní a pri zvolení hashovacej funkcie. Server bol naprogramovaný využitím frameworku FastAPI v Python.

## Prepare python environment
```bash

python3 -m venv venv     
source ./venv/bin/activate

```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash

project_KB_backend$ pip install -r requirements.txt

project_KB_backend$ python3 run.py

```

### API documentation

http://0.0.0.0:8000/docs#/
