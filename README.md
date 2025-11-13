# Wheel_fortune4
En l'últim exercici vam implementar un sistema de punts i una ruleta. En aquest exercici volem que els/les concursants, no només puguin dir lletres del panell, sinó que a més podran tractar de resoldre el panell en cas de saber la resposta o, almenys, creure-ho :)

Podeu fer servir el vostre propi codi font o el del vostre mentor.

que he hecho:

he clonado la parte 3 de wheel_fortune3 y he hecho algunas modificaciones.

Primero en Panel, he hecho la funcion de trySolve que basicamente hace que cuando conteste el participante compruebe si es igual que el panel 
(aun no he dado opcion a resolver).

A continuación paso a Contest, en el play que ya teniamos modifico con un if y preguntamos si quiere decir letra 'L' o quiere resolver'S' y llamaremos para comprobar a la función anterior en Panel.
