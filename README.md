# Teoría de Autómatas
# Para subir nuestro avance al repositorio remoto

```
git status
git add . 
git status
```

```
git commit -m "nombre del commit"
```
(te va a arrojar error que falta tu nombre de usuario y mail)
```
git config --global user.email "micorreo@uandresbello.edu"
git config --global user.name "su_nick_unab"
```
(ahora esta listo para hacer un commit)
```
git commit -m "nombre del commit"
git push origin master
```
(ahora revisamos nuestro repositorio en github y el commit aparece ahi)

# Para compilar manual
```
g++ main.cpp -o main.exe
```
(donde main.cpp es el nombre del programa fuente que programamos y main.exe es el nombre del programa objeto)

(Para ejecutar, llamamos al programa objeto de la siguiente manera)
```
./main.exe
```

(En caso de tener parametros de entrada)
```
./main.exe -f file1.in -s file2.in -o myfile.out
```
