# Ejemplo de como usar Maven con LWJGL

## Comandos

* mvn archetype:generate -DarchetypeArtifactId=maven-archetype-quickstart -DgroupId=mx.edu.tecmm.zapopan -DartifactId=ejemplo-lwjgl -Dversion=1.0-SNAPSHOT -DarchetypeVersion=1.4 -DinteractiveMode=false
* mvn package
* java -cp target/ejemplo-lwjgl-1.0-SNAPSHOT.jar mx.edu.tecmm.zapopan.App
* mvn compile exec:java -Dexec.mainClass=mx.edu.tecmm.zapopan.App


## Referencias

* http://wiki.lwjgl.org/wiki/Setting_Up_LWJGL_with_Maven.html
