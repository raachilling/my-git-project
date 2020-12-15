Last login: Tue Dec 15 11:57:44 on ttys000
Raquel@MacBook-Pro-Rachel ~ % mkdir my-git-project
Raquel@MacBook-Pro-Rachel ~ % cd my-git-project
Raquel@MacBook-Pro-Rachel my-git-project % touch my_file.py
Raquel@MacBook-Pro-Rachel my-git-project % git init
Inicializado repositorio Git vacío en /Users/admin/my-git-project/.git/
Raquel@MacBook-Pro-Rachel my-git-project % ls
my_file.py
Raquel@MacBook-Pro-Rachel my-git-project % ls -la
total 0
drwxr-xr-x   4 Raquel  staff   128 15 dic 12:05 .
drwxr-xr-x+ 48 Raquel  staff  1536 15 dic 12:04 ..
drwxr-xr-x   9 Raquel  staff   288 15 dic 12:05 .git
-rw-r--r--   1 Raquel  staff     0 15 dic 12:05 my_file.py
Raquel@MacBook-Pro-Rachel my-git-project % git status 
En la rama master

No hay commits todavía

Archivos sin seguimiento:
  (usa "git add <archivo>..." para incluirlo a lo que se será confirmado)
	my_file.py

no hay nada agregado al commit pero hay archivos sin seguimiento presentes (usa "git add" para hacerles seguimiento)
Raquel@MacBook-Pro-Rachel my-git-project % git add my_file.py
Raquel@MacBook-Pro-Rachel my-git-project % git status
En la rama master

No hay commits todavía

Cambios a ser confirmados:
  (usa "git rm --cached <archivo>..." para sacar del área de stage)
	nuevo archivo:  my_file.py

Raquel@MacBook-Pro-Rachel my-git-project % git commit -m "Initial commit"
[master (commit-raíz) 33aef5a] Initial commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 my_file.py
Raquel@MacBook-Pro-Rachel my-git-project % git remote add origin https://github.com/raachilling/my-git-project.git
Raquel@MacBook-Pro-Rachel my-git-project % git remote -v
origin	https://github.com/raachilling/my-git-project.git (fetch)
origin	https://github.com/raachilling/my-git-project.git (push)
Raquel@MacBook-Pro-Rachel my-git-project % git push -u origin main
error: src refsoec main: no concuerda con ninguno
error: falló el push de algunas referencias a 'https://github.com/raachilling/my-git-project.git'
Raquel@MacBook-Pro-Rachel my-git-project % git push -u origin master
Enumerando objetos: 3, listo.
Contando objetos: 100% (3/3), listo.
Escribiendo objetos: 100% (3/3), 217 bytes | 217.00 KiB/s, listo.
Total 3 (delta 0), reusado 0 (delta 0), pack-reusado 0
To https://github.com/raachilling/my-git-project.git
 * [new branch]      master -> master
Rama 'master' configurada para hacer seguimiento a la rama remota 'master' de 'origin'.
Raquel@MacBook-Pro-Rachel my-git-project % vim README.md

#My Git Project 

> My code for the git project
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
-- INSERT --
