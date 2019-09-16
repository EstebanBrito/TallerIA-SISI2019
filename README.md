# TallerIA-SISI2019
Taller de introducción al Machine Learning impartido durante el SISI 2019 en el Instituto Tecnológico de Mérida. Talleristas: Esteban Emmanuel Brito Borges y Paúl Alexander Mena Zapata

## Instalacion

De no funcionar el comando 'python3', sustituir por 'python'.

Descarga el repo.

```bash
$ git clone https://github.com/EstebanBrito/TallerIA-SISI2019
```

Crea un entorno virtual para Python en la carpeta del repo.

```bash
$ python3 -m venv env
```

Activa el entorno virtual

```bash
$ source env/bin/activate
```

Instala las librerías necesarias.

```bash
(env) $ python3 -m pip install -r requeriments.txt
```

De no funcionar el comando anterior, instalar librerías manualmente

```bash
(env) $ python3 -m pip install jupyter numpy pandas scipy matplotlib seaborn scikit-learn
```

## Uso

Inicia el servidor de Jupyter para acceder a las notebooks.

```bash
$ (env) jupyter notebook
```
El navegador debería abrirse. Sino, copia el link que aparecerá en la consola y abrelo en el navegador.
Una vez cargue, navega por el explorador de archivos de Jupyter en el navegador para consultar las notebooks.



