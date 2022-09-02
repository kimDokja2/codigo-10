# Primer Dia con Git/Github
comando para configurar el correo y usuario

para ver la version de git
```bash
git --version
```

Para configurar el correo
```bash
git config global user.email "email"
```

para poder configurar el Username

```bash
git config global user.name "username"
```
comando que sirve para poder empezar a usar git en nuestra carpeta

```bash
git init
```
agreaga los archivos a la memoria en la pc

```bash
git add .
```
crea el registro de los cambios realizados

```bash
git commit -m "reseña del cambio"
```

poder ver el historial de versiones

```bash
git log
```
para ver detalles de un ID de un registro 
```bash
git show cec67d44590eb0cef2857d787bbd47acdfcd4805
```
para conectar remotamente el proyecto
```bash
git remote add origin https://github.com/kimDokja2/codigo-10
```
para subir a github

```bash
git push origin main
```
para cambiar de Master a main
```bash
git branch -M main
```


mostrar la url del repositorio después del nombre de dicho repositorio.
Para ver a que url esta vinculado nuestro proyecto

```bash
git remote -v
```

para cambiar el url 
```bash
git remote set-url origin http://asjfkajs
```

