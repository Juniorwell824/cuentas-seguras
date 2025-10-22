# 1. Conectar tu repositorio local con GitHub
git remote add origin https://github.com/Juniorwell824/cuentas-seguras.git

# 2. Cambiar a la rama main (si no estás ahí)
git branch -M main

# 3. Hacer pull primero (porque el README ya existe en GitHub)
git pull origin main --allow-unrelated-histories

# 4. Hacer push de tu código
git push -u origin main
