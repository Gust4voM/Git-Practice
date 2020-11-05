Comandos Git:

git config --list (Lista de configuraciones globales)
git config global [Variable a configurar] (guardamos configuraciones globales de nuestro git)

git add --all (Pasamos las cosas del working area al staging area)
git commit -m "Mensaje" (Persistimos los cambios en el repo)
git commit --amend (Corregir commit anterior) 
git commit --amend -m (corregir el mensaje anterior)
git push origin <rama> (Los mandamos al repo en nube)

git log (changelog de cambios)
git log --oneline (ultimo cambio)
git log --graph (lo pido de manera grafica)

git diff <hash1> <hash2>
git difftool <hash1> <hash2>
git tag <etiqueta> <hash>

Archivo .gitignore:
Vamos a remarcar aca las extensiones de archivos que querramos que se ignoren para actualizar los repos, se escriben: [carpeta de origen]/*.[extension del archivo a ignorar].
Se puede acomplejar todo lo que querramos.
