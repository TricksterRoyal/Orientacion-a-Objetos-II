Ejercicio 1
======
Discuta los requerimientos y dise�e una soluci�n. Si aplica un patr�n de dise�o, indique cu�l es y justifique su aplicabilidad.

Soluci�n
------

En este caso voy a aplicar el decorator ya que a una de las clases(la del FileOO2) necesito aplicarle capas encima din�micamente y de forma transparente(sin afectar a otros objetos). Cada capa ser� representada por un decorador. Habr� un cliente(el FileManager) y los componentes: los decoradores y el fileOO2.
