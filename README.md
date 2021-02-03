# **LABORATORIO No.02 - PATTERNS**

## **PATTERNS - FACTORY**

### **LA HERRAMIENTA MAVEN**
* **Cuál es su mayor utilidad**

    La mayor utilidad es la cual permite a los desarrolladores comprender el estado completo del proyecto en el menor tiempo posible. Tambien es el hacer mas facil el proceso de contruccion.

* **Fases de maven**
    1. process-resources
    2. compile
    3. process-test-resources
    4. test-compile
    5. test
    6. package
    7. install
    6. deploy

* **Ciclo de vida de la construcción**
    1. **compile**: Genera los ficheros .class compilando los fuentes .java
    2. **test**: Ejecuta los test automáticos de JUnit existentes, abortando el proceso si alguno de ellos falla.
    3. **package**: Genera el fichero .jar con los .class compilados
    4. **install**: Copia el fichero .jar a un directorio de nuestro ordenador donde maven deja todos los .jar. De esta forma esos .jar pueden utilizarse en otros proyectos maven en el mismo ordenador.
    5. **deploy**: Copia el fichero .jar a un servidor remoto, poniéndolo disponible para cualquier proyecto maven con acceso a ese servidor remoto.

* **Para qué sirven los plugins**

    Fragmento o componente de codigo hecho para ampliar las funciones de un programa o una herramienta.

* **Qué es y para qué sirve el repositorio central de maven**

    El repositorio central de Maven son una serie de librerias que sirven para el desarrollo y construccion de software. Esto sirve para permitir que el proyecto tenga artefactos implementados en el repositorio central.

### **HACER EL ESQUELETO DE LA APLICACION**
* **¿Cuál(es) de las anteriores instrucciones se ejecutan y funcionan correctamente y por qué?**

    Todas las intrucciones se ejecutaron, pero solo la ultima funciono correctamente, ya que la instruccion solo recibe como parametro los nombres exactos de cada figura (primera letra en mayuscula y las demas en minuscula).


### **PARA QUE SIRVE Y COMO SE USA "gitignore"**

Gitignore sirve basicamente para configurar un respositorio y hacer que archivos que no queremos que sean agregados automaticamente no se agreguen al momento de subir o
actualizar archivos en nuestro repositorio. El uso de este se puede observar en

### EJERCICIO DE LAS FIGURAS
> ## COMPILAR Y EJECUTAR
>> ## Ejecutar la clase con su nombre y apellido como parámetro. ¿Qué sucedió?
>>> Solo imprime "Hello world" porque es la unica indicaciín que tiene el programa App
## **BIBLIOGRAFIA**
* [https://1984.lsi.us.es/wiki-egc/index.php/Primeros_pasos_con_Maven#Ciclo_de_vida_y_fases]()
* [https://1984.lsi.us.es/wiki-egc/index.php/Primeros_pasos_con_Maven#Ciclo_de_vida_y_fases]()
* [https://maven.apache.org/repository/index.html]()
* [https://www.genbeta.com/desarrollo/que-es-maven]()

