# PRACTICA-1

# Integrantes:
 - Edgar Zahid Hernandez Garcia
 - Gael Mateo Rangel Chavez
 - Alejandro Saldaña Garcia

# Itroducción
Epson Robots es el líder industrial en facilidad de uso, desempeño y confiabilidad, además de proveer una extensa selección de opciones para elegir la mejor solución en automatización. Los robots compactos y de alto rendimiento Epson de 6 ejes permiten un rango de movimiento notable en un espacio reducido.
La precisión que se tiene con los Robots Epson ayuda a reducir los costos de producción y aumentar la calidad de los productos. Los robots SCARA de Epson son insuperables en rendimiento y confiabilidad. La finalidad de esta practica es familiarizarnos con este robot y comorender su funcionamiento.

# Instrucciones
Instalacion de Software

Como primer paso de instalo el programa EpsonRC+, que es un entorno de enseñanza simple y visual creado para usuarios que son nuevos en la automatización de robots y tienen poca o ninguna experiencia en programación, como nosotros.

Conexion al robot Epson C4

Para la conexion de EpsonRC+ con el Robot se hizo uso de un cable USB desde la computadora hasta el controlador del robot Epson C4. se puso el entorno en modo "Prueba" y se le dio movilidad de forma manual, dentro del modo prueba el se limitó el pocentaje de fuerza a un 30% y en caso de colision de paraba de manera automatica evitando daños en el equipo. Dentro del Software de mostró el estado del robot, incluyendo su posición actual y los estados de los ejes.

Partes del robot
- Base
  Es la parte inferior del robot que proporciona estabilidad y soporte. Es donde se anclan las demás partes del robot
- Eje 1 (Rotación de la Base):
  Permite la rotación del robot alrededor de su eje vertical, orientando la estructura superior.
- Eje 2 (Articulación del Brazo Inferior):
  Proporciona movimiento hacia adelante y atrás, extendiendo o retrayendo el brazo inferior.
- Eje 3 (Articulación del Brazo Superior):
  Facilita movimientos verticales, ajustando la altura y profundidad del robot.
- Eje 4 (Rotación de la Muñeca):
  Gira la muñeca del robot, cambiando la orientación del efector final.
- Eje 5 (Flexión de la Muñeca):
  Permite el movimiento de inclinación de la muñeca hacia arriba y abajo.
- Eje 6 (Rotación del Efector Final):
  Proporciona rotación final al efector, ajustando su orientación en el eje longitudinal.

Movimiento del robot en World y Joint

Modo World:
El robot se mueve en relación a un sistema de coordenadas global, fijo en el espacio de trabajo, lo que nos permite movimientos lineales y circulares en el espacio, ideal para tareas que requieren precisión en la ubicación absoluta del efector final.

Modo Joint:
El robot se mueve en relación a sus propios ejes de articulación, controlando cada junta de manera independiente, lo que nos facilita movimientos más rápidos y flexibles, adecuado para trayectorias complejas donde se requiere un control preciso de cada articulación.

# Conclusiones 
- Edgar Zahid Hernandez Garcia:
  Entendi que el modo de movimiento World seria como guiarte mediante un plano preestablecido, donde se pueden realizar movimientos lineales y circulares para llegar al punto 
  deseado, teniendo una presicion asegurada y por otro lado el modo joint nos permite movimientos sin un orden o plano fijo, de manera que puede realizar diferentes tipos de rotacion, extension o contraccion para 
  realizar una accion de manera mas rapida sin seguir una trayectoria precisa.

- Gael Mateo Rangel Chavez:

  
- Alejandro Saldaña Garcia:

