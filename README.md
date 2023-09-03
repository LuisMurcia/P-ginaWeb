# PáginaWeb
La página web es responsive; se adapta a todo tipo de dispositivos.  

**Nave, Sol, Luna y Tierra:**  
Cada elemento consta de un div propio.
Las he colocado debidamente y, en el css de móvil, les he disminuido el tamaño para adaptarlas de PC a móvil.

**Opciones:**  
Para los botones de Play, Reset y Help he creado un div para cada uno donde inserto sus respectivas imágenes y un enlace con la ruta debida. El play y el Reset te reconducen a la misma página del Lunar Lander. El Help, a una dónde he puesto un título que dice "Instrucciones" y un enlace llamado "Return to the Game", en medio de ambas cosas deben ir las instrucciones del juego.
Cuando  pasamos a la versión para móvil estos tres botones pasan a estar contenidos en un desplegable y ya no utilizo las imágenes respectivas a cada botón (las oculto con un display:none;), si no texto contenido en divs.

**Indicadores:**  
Velocidad y altura son dos divs contenidos en el div de la Luna. El fuel es un div dentro de otro div para que este pueda aumentar hasta el máximo del div exterior creando así el efecto de una barra.

**Modificaciones:**  
He sido fiel al diseño original del cliente salvo por una cosa:
En el formato para dispositivos móviles, he cambiado la localización de los indicadores de velocidad y de altura debido a que estos tapaban la trayectoria final del aterrizaje de la nave. Los he colocado en la parte superior izquierda de la pantalla vertical para que no se junten con el menú ni con la nave y para que sean fácilmente visibles por el usuario.

**Notas:**  
Me falla en aumentar mucho el tamaño de la página y en los dispositivos Tablet se ven algo pequeños los indicadores de velocidad y altura.

**Links:**  
Rawgit: https://rawgit.com/LuisMurcia/P-ginaWeb/master/Lunar_lander.html  // Enlace obsoleto actualmente.
Validador: https://validator.w3.org/nu/?doc=https%3A%2F%2Frawgit.com%2FLuisMurcia%2FP-ginaWeb%2Fmaster%2FLunar_lander.html
