Crea el repositorio en GitHub
Crea el repositorio en GitHub
Entra en https://github.com y autentícate.
Haz clic en New repository (o “Nuevo repositorio”).
Ponle un nombre (por ejemplo sena-cinema), elige Public o Private, y deja las opciones “Initialize this repository with a README” sin marcar (porque ya tienes código).
Al crearla, GitHub te mostrará la URL remota (HTTPS o SSH). Cópiala, la vas a usar en el siguiente paso.
Prepara tu proyecto local
Abre tu terminal y sitúate en la carpeta donde están tus archivos HTML y CSS: cd /ruta/a/tu/proyecto Si aún no tienes Git configurado a nivel global, primero define tu nombre y correo: git config --global user.name "Tu Nombre" git config --global user.email "tu@correo.com"

Inicializa el repositorio y haz el primer commit
Inicializas un repositorio Git en tu carpeta
git init
Cambias el nombre de la rama principal a "main"
git branch -M main
Añades todos los archivos al área de staging
git add .
4. Haces tu primer commit
git commit -m "Inicial: proyecto SENA-CINEMA con HTML y CSS"
Conecta con el remoto de GitHub y sube tu código
Sustituye por la que copiaste de GitHub (algo como https://github.com/tu-usuario/sena-cinema.git):
Añades el remoto llamado "origin"
git remote add origin <URL-del-repo>
Subes la rama main al remoto y estableces el upstream
git push -u origin main
A partir de ahora, cuando cambies código bastará con:

git add .
git commit -m "Explico qué cambios hice"
git push
