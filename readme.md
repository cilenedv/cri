#Cuando hago click me debe salir en forma ordenada el color de las circunferencias que se muestras y cuando escribo en el input  el nombre de color y le doy a Super Click se debe sobrear el color mencionado.

- Usamos un window.addEventListene ya que vamos a trabajar con listas de allí le damos una variable boton a nuestro button con el id "cri" de allí un contador para que corra cada vez que haga click classList.add --> es para agregar el borde y classList.remove es para quitar el borde.

- A diferencia de solo hacer click ahora debemos escribir el nombre en el input declaramos una variable con boton2  con el id "superCri" de alli una variable letra donde se escribira el nombre del color, cuando ponemos la condición if() vamos a declarar la variable letra que  se ha igual al color que vamos escribir es este casa por ejemplo "rojo" y dentro de las{} colocamos.

- document.getElementById("rojo").classList.add("borde-rojo");
Nos indica que va agregar el borde de rojo

- document.getElementById("verde").classList.remove("borde-verde");
Nos indica que vamos a quitar el borde de verde

- document.getElementById("azul").classList.remove("borde-azul");
Nos indica que vamos a quitar el borde de azul 

- Hacemos dos remove tanto de verde y azul ya que no sabemos que es primero que va a escribir el usuario.