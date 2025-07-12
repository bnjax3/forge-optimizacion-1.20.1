# forge-optimizacion-1.20.1
optimizacion para forge 1.20.1
 
ARGUMENTOS DE LA JVM:

(-Xmx designa la ram maxima y -Xms la ram minima, modificar acordemente)
 
-Xmx4G -Xms3G -XX:+UseG1GC -Dsun.rmi.dgc.server.gcInterval=2147483646 -XX:+UnlockExperimentalVMOptions -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M


NOTAS :
 
-Para mejor eficiencia con entityCulling se deben desabilitar las opciones de culling de entidades en embeddium ya que las del mod anterior son mas eficientes
