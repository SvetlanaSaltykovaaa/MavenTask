# MavenTask
Building Maven project


Add desktop-game-engine.jar to local (.m2) repository with command:
mvn install:install-file -Dfile=C:\Users\....\lib\desktop-game-engine.jar -DgroupId="com.javarush" -DartifactId=desktop-game-engine -Dversion="1.0" -Dpackaging=jar
