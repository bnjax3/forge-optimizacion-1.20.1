# forge-optimizacion-1.20.1
optimizacion para forge 1.20.1
 
ARGUMENTOS DE LA JVM:

(-Xmx designa la ram maxima y -Xms la ram minima, modificar acordemente) 
-Xmx5G -Xms4G -XX:+UseG1GC -XX:+UnlockExperimentalVMOptions -XX:G1NewSizePercent=35 -XX:G1MaxNewSizePercent=60 -XX:G1HeapRegionSize=16M -XX:G1ReservePercent=25 -XX:MaxGCPauseMillis=100 -XX:+ParallelRefProcEnabled -XX:+AlwaysPreTouch -XX:+PerfDisableSharedMem -Dsun.rmi.dgc.client.gcInterval=2147483646 -Dsun.rmi.dgc.server.gcInterval=2147483646 -Dfml.readTimeout=90

NOTAS :
 
-Para mejor eficiencia con entityCulling se deben desabilitar las opciones de culling de entidades en embeddium ya que las del mod anterior son mas eficientes
