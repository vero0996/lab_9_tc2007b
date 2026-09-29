Veronica Paola Zapata Sanchez 
A01199193

1. La inyección de dependencias es un patrón de diseño donde una clase recibe los objetos que necesita para funcionar a través de su constructor en lugar de crearlos ella misma. Esto desacopla las clases y facilita cambiarlas o probarlas.
2. La interfaz de TareasRepository funciona como un enchufe ya que permite que el ViewModel use el repositorio sin importar de dónde vienen las tareas.
3. La indica a Hilt qué implementación concreta debe instanciar y entregar cuando alguna clase solicite una interfaz especifica. 