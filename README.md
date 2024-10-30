# Instalación Git Hub

GitHub es una plataforma de desarrollo colaborativo que permite a los programadores y equipos trabajar juntos en proyectos de software. Aquí tienes algunas de sus principales funciones y beneficios:

## Installation


Para configurar Git en tu máquina local con tu nombre y correo electrónico, sigue estos pasos:

## 1. Abre tu terminal.

## 2. Configura tu nombre de usuario con el siguiente comando:

```bash
git config --global user.name "Tu Nombre"
```

## 3. Configura tu correo electrónico con el siguiente comando:

```bash
git config --global user.email "tu_correo@example.com"
```

## 4. Verifica la configuración ejecutando:

```bash
git config --global --list
```
## Esto mostrará algo como:
```bash
user.name=Tu Nombre
user.email=tu_correo@example.com
```
Con esto, habrás configurado correctamente tu nombre y correo electrónico en Git.

## Crear un nuevo repositorio en Git Hub:
Crear un nuevo repositorio en GitHub es bastante sencillo. Aquí te dejo los pasos a seguir:

Inicia sesión en GitHub: Ve a github.com y accede a tu cuenta.

## Crea un nuevo repositorio:

1. Haz clic en el botón de "+" en la esquina superior derecha de la página.
Selecciona "New repository" del menú desplegable.
Configura tu nuevo repositorio:

2. Nombre del repositorio: Escribe un nombre único para tu repositorio.
Descripción (opcional): Puedes agregar una breve descripción de lo que contendrá tu repositorio.
Visibilidad: Elige si quieres que sea público (cualquiera puede verlo) o privado (solo tú y las personas que invites pueden verlo).
3. Inicializar este repositorio con: Puedes optar por agregar un README, un archivo .gitignore o elegir una licencia.
Crea el repositorio: Haz clic en el botón "Create repository".

4. Clona el repositorio (opcional): Si quieres trabajar en tu repositorio localmente, puedes clonarlo usando Git. Abre tu terminal y usa el comando:

## Subir un repositorio en Git Hub

1. Inicializa el repositorio Git
Si tu proyecto aún no es un repositorio Git, inicialízalo:

```bash
git init
```
2. Agrega los archivos al repositorio
Agrega todos los archivos de tu proyecto al repositorio:

```bash
git add .
```
3. Realiza un commit
Realiza un commit con un mensaje descriptivo:

```bash
git commit -m "Mensaje descriptivo de tu commit"
```
4. Conecta tu repositorio local con GitHub
Vincula tu repositorio local con el repositorio de GitHub. Reemplaza tu_usuario y nombre_repositorio con tu información:

```bash
git remote add origin https://github.com/tu_usuario/nombre_repositorio.git
```
5. Sube tu proyecto a GitHub
Finalmente, sube tu proyecto a GitHub:

```bash
git push -u origin master
```

6. Verifica en GitHub
Ve a tu repositorio en GitHub para asegurarte de que todos los archivos se hayan subido correctamente.
