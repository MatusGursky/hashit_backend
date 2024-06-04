
# Backend - HashIt App

The HashIt application allows the creation of hashes using the implemented SHA-256 algorithm and also offers the option to use other hashing functions such as MD5, SHA3, SHA-224, and others available through the crypto-js library. It also enables hash comparison by saving the hash value and then comparing it with the current hash. The saved hash value includes information about the used hashing function. If the hashes match, the text fields are highlighted in green. The application also allows copying the hash value for further use. The client contains a watch property for automatically performing the hash when typing and when selecting the hashing function.

This is a client-server application. The client was programmed using the Vue.js 3 framework in TypeScript and the Quasar component framework. The server was programmed using the FastAPI framework in Python.

### Prepare python environment
```bash

python3 -m venv venv     
source ./venv/bin/activate

```

### Run application with the following commands:*
```bash

project_KB_backend$ pip install -r requirements.txt

project_KB_backend$ python3 run.py

```

### API documentation

http://0.0.0.0:8000/docs#/
