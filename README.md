# Pasar resultados de git_leaks a un json
## Archivos
- git_leaks_a_json.py: script de python que se encarga de pasar el resultado de todos los commits obtenidos a un json.
- git_leaks.json: archivo .json que contiene todos los commits encontrados.
- skale-manager: carpeta con el directorio para extraer los commits.

## Descripción del script
En este script simplemente se toman los resultados obtenidos en el git_leaks, cuyos commits ya son devueltos en forma de diccionario, y se convierten a un json.
