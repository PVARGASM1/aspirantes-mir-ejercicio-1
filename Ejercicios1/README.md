C:\cmder_mini
λ
C:\cmder_mini
λ pwd
C:\cmder_mini

C:\cmder_mini
λ mkdir ejercicios

C:\cmder_mini
λ cd ejercicios\

C:\cmder_mini\ejercicios
λ code .

C:\cmder_mini\ejercicios
λ gi init
"gi" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

C:\cmder_mini\ejercicios
λ git init
Initialized empty Git repository in C:/cmder_mini/ejercicios/.git/



C:\cmder_mini\ejercicios (master)
λ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Ejercicios1/

nothing added to commit but untracked files present (use "git add" to track)

C:\cmder_mini\ejercicios (master)
λ cd ..ls
El sistema no puede encontrar la ruta especificada.

C:\cmder_mini\ejercicios (master)
λ ls
Ejercicios1/

C:\cmder_mini\ejercicios (master)
λ ls -al
total 8
drwxr-xr-x 1 Andrea 197121 0 mar.  1 20:09 ./
drwxr-xr-x 1 Andrea 197121 0 mar.  1 20:06 ../
drwxr-xr-x 1 Andrea 197121 0 mar.  1 20:15 .git/
drwxr-xr-x 1 Andrea 197121 0 mar.  1 20:08 Ejercicios1/

C:\cmder_mini\ejercicios (master)
λ git add .

C:\cmder_mini\ejercicios (master)
λ git commit -m 'Versióninicial'
[master (root-commit) 65ac2ac] 'Versióninicial'
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Ejercicios1/README.md

C:\cmder_mini\ejercicios (master)