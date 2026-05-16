# En Windows

## Habilitando ejecución de Scripts

Primero se deberá habilitar la ejecución de Scripts desde PowerShell y para lograr esto abrimos PowerShell como Administrador, entonces ejecutamos:

```bash

Set-ExecutionPolicy RemoteSigned -Scope CurrentUser

```

A la pregunta respondemos con 'Y' o 'S' para habilitar el permiso para nuestro usuario actual.

## Iniciando, y activando, un entorno virtual para Python

```bash

python -m venv venv

.\venv\Scripts\Activate.ps1

```

## Instalamos las dependencias necesarias

```bash

pip install -r requirements.txt

```

## Abrimos nuestro entorno de trabajo Python: Jupyter Notebook

```bash

jupyter notebook

```

Veremos, en los mensajes de log de consola, una URL con token parecida a la siguiente:

```bash

http://localhost:8888/tree?token=5558074eac01d69d22bcf92c7b337928eb8df8b99f1f5106

```

La copiamos y pegamos en algún navegador.

## Entonces abrimos el archivo

```bash

Graficas_RubenGonzaloSoriaSoria.ipynb

```

