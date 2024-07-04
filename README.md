…or create a new repository on the command line

echo "# ProyFinal2" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ElNuevoAprendiz/ProyFinal2.git
git push -u origin main

…or push an existing repository from the command line

git remote add origin https://github.com/ElNuevoAprendiz/ProyFinal2.git
git branch -M main
git push -u origin main

---------------------------------------------------------------------------------------------------------------------------
Ojo se debe descargar la dc Peli24119 e importarla creando previamente en phpmyadmin una base vacia con dicho nombre
OJo hay que verificar que el controlador tenga el puerto correcto de mysql pq p ej en este caso se cambio a 3307 y el mismo se debe cambiar en el controlador (del dao)
iguagual que el nombre de la db que se usando 
