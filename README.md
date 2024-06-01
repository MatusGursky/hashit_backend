
# Backend for HashIt App

Aplikácia HashIt umožňuje vytváranie hashov pomocou implementovaného algoritmu SHA-256 a ponúka aj možnosť využiť ostatné hashovacie funkcie ako MD5, SHA3, SHA-224 a ďalšie dostupné cez knižnicu crypto-js. Umožňuje tiež porovnávanie hashov tým, že uložíme hodnotu hashu a následne ju porovnávame so súčasným hashom. Uložená hodnota hashu obsahuje aj informáciu o použitej hashovacej funkcii. Ak sa hashe zhodujú, textové polia sa zafarbia zelenou farbou. Aplikácia tiež umožňuje skopírovať hodnotu hashu pre ďalšie použitie.

Je to klient-server aplikácia. Klient bol naprogramovaný využitím frameworku Vue.js 3 v TypeScript a komponentového frameworku Quasar. Klient obsahuje watch property pre automatické vykonanie hashu pri písaní a pri zvolení hashovacej funkcie. Server bol naprogramovaný využitím frameworku FastAPI v Pythone.

### Prepare python environment
```bash

python3 -m venv venv     
source ./venv/bin/activate

```

### Run application with the following commands:
```bash

project_KB_backend$ pip install -r requirements.txt

project_KB_backend$ python3 run.py

```

### API documentation

http://0.0.0.0:8000/docs#/
