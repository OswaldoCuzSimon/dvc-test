## install
~~~shell
wget https://dvc.org/rpm/dvc.repo
cp dvc.repo /etc/yum.repos.d/
dnf update
dnf install dvc
~~~
iniciar proyecto
~~~shell
dvc init
~~~

Configuracion
Agregar copia remota
~~~shell
dvc remote add -d myremote /tmp/dvc-storage
~~~
aggregar archivo
~~~shell
dvc add data.xml
dvc push
~~~
crea un archivo .dvc que debe ser traqueado por git

~~~shell
dvc pull
~~~
