# ☀️Helios

Helios es un bot diseñado para dar información acerca de los recursos de los servidores del usuario, los transmite por correo eléctronico.
## ⚙️Requerimientos
Requerimientos necesarios para poder utilizar **Helios**
## 🤖n8n (opcional)
Se puede usar este script con n8n haciendo peticiones a su endpoint **/helios**
## 🔐.env
Para poder hacer este script funcional tendremos que crear un arhcivo .env (junto con la líbreria python-dotenv)

En el .env tendremos que poner 3 párametros, uno para el que **envía** el correo, otro para quién lo **recibe**. Él último párametro será la **contraseña de app** que nos dará google

## 🏠Instancia en Flask

## 🛖Entorno
Antes de comenzar vamos a tener que crear un entorno en python

```
python3 -m venv nombre-entorno
source nombre-entorno/bin/activate
```

Ahora vamos a instalar las dependencias (dentro del entorno)
```
pip install -r requirements.txt
```

## ⚔️Ejecucción
Para iniciar este script hay que ejecutarlo con python, tendremos 2 archivos, **main.py** y **reporter.py**, tendremos que ejecutar el archivo **main.py**

```
nohup python3 main.py &
```
## 🧙‍♂️Authors

- [@Erikgavs](https://www.github.com/Erikgavs)

