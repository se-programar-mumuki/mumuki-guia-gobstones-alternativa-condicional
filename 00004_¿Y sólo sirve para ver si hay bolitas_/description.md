Claro que no, ¡por suerte! :raised_hands:

La **condición** puede ser cualquier expresión _booleana_. En criollo: cualquier cosa que represente una "pregunta" que se pueda responder con **sí** o **no**.
En Gobstones el _sí_ se representa con el valor **True** (_Verdadero_ en castellano) y el _no_ con el valor **False** (_Falso_ en castellano).

En los ejercicios anteriores te mostramos una de las expresiones que trae Gobstones, `hayBolitas(color)`, que recibe un `color` y retorna _True_ o _False_. 

Otra que trae _True_ o _False_ (y que vas a tener que usar ahora) es `puedeMover(direccion)` que nos sirve para saber si el cabezal puede moverse en una cierta dirección.

Por ejemplo, si tenemos este tablero:

<gs-board>
  GBB/1.0
  size 2 3
  head 0 1    
</gs-board>

* `puedeMover(Norte)` será `True`.
* `puedeMover(Sur)` será `True`.
* `puedeMover(Este)` será `True`.
* Pero `puedeMover(Oeste)` será `False`

> Creá un programa que se mueva al `Este` sólo _si es_ posible. Recordá utilizar `puedeMover(direccion)`. 
