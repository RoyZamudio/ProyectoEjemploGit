# Introducción a Git

## Descripción
Este repositorio contiene un programa escrito en el lenguaje de programación Python que imprime un mensaje en la consola. 

## Objetivo de la práctica
Repasar los comandos básicos de Git y crear un repositorio en GitHub.

## Instrucciones de uso
Para ejecutar el programa, usa el siguiente comando desde alguna terminal:

```bash
python HolaMundo.py
```

## Comandos utilizados en la práctica
- `git init`: Inicializa el repositorio.
- `git add <archivo>`: Añade un archivo al área de preparación.
- `git commit -m "<mensaje>"`: Realiza un commit con un mensaje descriptivo.
- `git status`: Verifica el estado del repositorio.
- `git remote add origin <URL>`: Conecta el repositorio local con un repositorio remoto.
- `git push -u origin main`: Sube los cambios al repositorio remoto.

## Notas sobre el archivo .gitignore
- El archivo `.gitignore` se creó para excluir archivos que no deberían ser rastreados en el repositorio, como archivos de registro o depuración.

- Este `.gitignore` ignora todos los archivos con extensión `.log`, evitando que el archivo `debug.log` se suba al repositorio remoto.

## Resultado esperado
Al ejecutar el programa, se mostrará el mensaje "Hola Git" en la consola. Para verificar que `debug.log` no se subió, revisa el repositorio en GitHub y confirma que el archivo no aparece en la lista de archivos.