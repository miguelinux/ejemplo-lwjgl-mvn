# Ejemplo de como usar Maven con LWJGL

## Comandos

* mvn archetype:generate -DarchetypeArtifactId=maven-archetype-quickstart -DgroupId=mx.edu.tecmm.zapopan -DartifactId=ejemplo-lwjgl -Dversion=1.0-SNAPSHOT -DarchetypeVersion=1.4 -DinteractiveMode=false
* mvn package
* java -cp target/ejemplo-lwjgl-1.0-SNAPSHOT.jar mx.edu.tecmm.zapopan.App
