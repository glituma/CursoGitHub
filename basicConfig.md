1._ https://git-scm.com/downloads

2._ Configuramos git
  - $ git config --global user.name "xxx"
  - $ git config --global user.email "xxx@xxx.com"
  - $ git config --global color.ui auto
  - $ git config --global credential.helper "wincred"
  - $ git config --global core.editor "code --wait"

  //para borrar si se ingreso un parametro mal
  - $ git config --global --unset user.mail

3._ Create un nuevo repositorio
    //Crear un nuevo repositorio
    - $ echo "# CursoGitHub" >> README.md
    - $ git init
    - $ git add README.md
    - $ git commit -m "first commit"
    - $ git remote add origin https://github.com/glituma/CursoGitHub.git
    - $ git push -u origin master

    //push an existing repository from the command line

    - $ git remote add origin https://github.com/glituma/CursoGitHub.git
    - $ git push -u origin master

4._ Clonar repositorio

    - $ git clone https://github.com/glituma/curso-javascript.git

5._ Commit y push

    - $ git add .
    - $ git commit - m "mi primera nueva actualización"
    - $ git push

6.- Revisar el log
    - $ git log

7._ Regresar a una versión anterior del archivo
    - $ git checkout <6 primeros número del hash del commit>
    - $ git checkout ca01d8
    - $ git switch -c ca01d8
    - $ git status

8._ Regresar a la versión final
    - $ git checkout master

