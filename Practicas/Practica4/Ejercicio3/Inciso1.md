Inciso 1
======
Dise�e una soluci�n aplicando un patr�n y justifique la elecci�n del mismo. Indique qu� parte del enunciado coincide con la aplicabilidad del patr�n.

En este caso yo aplicar�a tambi�n un proxy, mas espec�ficamente uno virtual, ya que la idea es crear objetos costosos por encargo. Hay una parte del ejercicio que dice "Ud. debe aplicar un patr�n para poder cargar en memoria los usuarios en la medida en que �stos se necesiten.". Yo lo que entiendo con eso es que necesito un patr�n para cargar usuarios en la medida en que se vayan necesitando, es decir, bajo demanda. Adem�s, un usuario, en este caso, es un recurso costoso en s� mismo para mantener en memoria, por lo que hay que mantener la menor cantidad posible.