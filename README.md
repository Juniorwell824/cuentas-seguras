# 1. Conectar tu repositorio local con GitHub (ESTE ESTÁ BIEN)
git remote add origin https://github.com/Juniorwell824/cuentas-seguras.git

# 2. CORREGIR: Cambiar a la rama main (usa -M mayúscula)
git branch -M main

# 3. Hacer pull primero (CORREGIR los guiones)
git pull origin main --allow-unrelated-histories

# 4. Hacer push de tu código (ESTE ESTÁ BIEN)
git push -u origin main
