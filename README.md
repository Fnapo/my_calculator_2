# my_calculator

Mi primer fichero en mi primer repositorio, Francisco Sola Porcuna.

Un pequeño repositorio Git para crear una calculadora en HTML paso a paso.
A la vez que se emplea algunos comandos de GIT y GITHUB.

Las primeras operaciones a crear son: x³ y x⁴, en la rama master.
Ambas opereaciones en 2 commits consecutivos y en ese orden.

Después se añade la función seno (sin(x)) en una rama lateral,
llamada sine, a partir del commit donde se creó x³.

Después se fusionan (merge) ambas ramas, primero en sine y
posteriormente en master (fast-foward).

Finalmente se actualiza el commit remoto con los comandos:
git remote add origin <https://github.com/Fnapo/my_calculator.git>
y git push -u origin master.
