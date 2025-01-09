# tomcat_9_catalina_base_configuration_3

eso arranca el tomcat usando un CATALINA_BASE distinto de su valor per defecto, que en ese caso es la carpeta del .bat
Y un jre_home distinto del definido en "variables de entorno", sino que está definido en CATALINA_BASE\bin\setenv.bat así : set "JRE_HOME=C:\java\jre-9.0.4"
