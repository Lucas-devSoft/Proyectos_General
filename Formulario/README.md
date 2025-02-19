<img width = 950px align = "center" src="https://github.com/Lucas-devSoft/Python/assets/111676352/b02ed5b7-61ed-4352-8294-36598e3eb536"></img>

# Segundo Proyecto Personal
 
## Sección de Índices 

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Herramientas utilizadas](#herramientas-utilizadas)
- [Funcionalidades](#funcionalidades)
  - [Banner](#banner)       
    - Con Conexión
    - Sin conexion         
  - [Interacciones](#interacciones)
  - [Errores](#errores)
- [Ejecutable](#ejecutable)
- [Desarrollador](#desarrollador)
 
## Descripción del Proyecto
 
*He desarrollado esta aplicación en el entorno de Windows utilizando el IDE Visual Studio Code para su ejecución en la consola del sistema operativo. El proyecto simula formularios en los que se puede ingresar información en varios campos. Esta información se almacenará en una base de datos (MongoDB) si el usuario lo desea. La funcionalidad principal de la aplicación depende de la conexión a la base de datos: si no se establece una conexión, la opción de guardar no estará disponible. Además, la aplicación ofrece otras funcionalidades, como la capacidad de enviar la información a través de Gmail y exportarla en formato JSON a un archivo externo.*
 
## Herramientas Utilizadas
 
### Entorno Virtual

*En el proyecto, empleo los módulos necesarios en un entorno virtual para brindar un acceso sencillo a la aplicación sin requerir ninguna descarga en el sistema del usuario. Todos los componentes necesarios están instalados en el entorno virtual, lo que permite ejecutarlo en la consola de su propio sistema.*
 
### Módulos
 
*En el proyecto, utilizo los módulos **colorama**, **pymongo**, **smtplib** y **getpass**. Los modulos como **smtplib** y **getpass** estan preinstalados en python, **colorama** y **pymongo** no están incluidos en la instalación predeterminada de Python.*

### Programación
 
*El proyecto se codificó en Python, siguiendo la práctica de separar el código en módulos correspondientes. Esta estructura me permitió realizar cambios de forma más sencilla en partes específicas del programa. Esta práctica no solo aumenta la flexibilidad para modificar el software, sino que también ayuda a mantener un código más organizado y descriptivo.*
 
### Base de Datos
 
*La base de datos que utilizo en este proyecto es mongoDB, el usuario puede conectarse en modo local o con su cuenta MongoDB atlas.*
 
## Funcionalidades
 
## Banner

*El banner en general proporciona detalles sobre la conexión a la base de datos MongoDB, como el estado, el nombre del servidor, el nombre de la base de datos y la documentación con la que se está trabajando, así como la versión de MongoDB. En este caso particular, la información que se muestra corresponde a la base de datos predeterminada generada automáticamente por el código. Sin embargo, si el usuario crea una base de datos con su propio nombre, se establecerá la conexión con esa base de datos y el contenido del banner cambiará en consecuencia.*
 
- **Banner con conexión activada**

**Local - Banner con nombre de BD elegida por el usuario** 

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/736625b7-98a4-40a6-8c14-3fbd3ba200d2)

**Local - Banner con nombre de BD por defecto** 

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/bf14ee05-c0c7-407a-b846-55688a4b2a82)

- **Atlas - Banner con nombre de BD elegida por el usuario**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/01d4f7fe-80b4-4332-b1d6-6d8dfe2dff3d)

- **Atlas - Banner con nombre de BD por defecto**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/a703a99c-bce0-4c8f-818d-d80af299e9e3)

- **Sin conexión**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/f7f6f8c6-b8c6-4b3f-ab30-300eb08440b7)

## Interacciones

*Cada interacción en el programa cumple una función específica: permitir al usuario elegir lo que desea hacer y esperar una respuesta precisa que se ajuste a su solicitud, para así continuar con las diferentes funcionalidades del programa.*

- **Consulta para generar la conexión con la BD**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/64f4b9b0-2a16-4a05-8948-a1e3291bd8a7)

- **Consulta para saber con que tipo de conexión ingresar**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/4234daa0-b741-4fb1-8b93-40d6c9e4e385)

- **Local - Consulta para crear la BD con el nombre que eliga el usuario**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/afb39462-19a3-497e-a379-ec697e17fee1)

- **Local - Creación y existencia de BD**

**Creacion exitosa**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/81a170a6-5594-4734-a523-c44de76a9057)

**BD ya existente**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/c3a53f73-ada2-4079-b5f2-c92de2cefb6e)

- **Conexión al servidor de MongoDB Atlas**

*Se solicitarán los datos del servidor de la cuenta del usuario de MongoDB Atlas para establecer la conexión con su cuenta en la nube. Esto permitirá almacenar la información de los formularios de manera segura y confiable.*

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/31b7c569-b7e4-464a-bf5d-2c57df05426e)

- **Atlas - Consulta para crear la BD con el nombre que eliga el usuario**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/a0ebe387-57aa-41a9-8450-82b2c2e3f220)

- **Atlas - Creación y existencia de base de datos**

**Creación exitosa**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/f649ba5b-9d32-42a5-93d8-39a90d35e563)

**BD ya existente**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/80ada130-814e-4a82-a969-345354192e01)

- **Avisos de Formularios**

*En esta ocasión, se notifica que el usuario ha completado el formulario y no se le permitirá volver a completarlo hasta que realice el reinicio.*

**Completado satisfactoriamente**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/c26a1745-e69f-4bdc-aeec-dca9970f0e2f)

**Formulario ya completado**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/d2bbf21c-71e2-4999-b1f2-252fb9de4574)

- **Los 3 Formularios completos**

*Una vez que los tres formularios estén completos y si el usuario está conectado a la base de datos, se habilitará una opción del menú para guardar la información. En caso contrario, el menú guardar no aparecera dentro de la misma.*

**Con conexión**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/95354440-e3c9-428f-9247-ad407b29e6f1)

**Sin conexión**

*La opcíón guardar no esta habilitada*

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/154d2e9c-7f9b-4605-a04d-fb1afb589905)

- **Guardando los datos**

*Una vez que la información se haya guardado, se activará el menú para visualizar lo que se ha almacenado en la base de datos.*

**Datos guardados**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/912a582a-403d-444b-a20a-0c14e24878c3)

**Menu de visualización habilitado**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/c27464a2-b991-4596-ae5f-2943b4a17a36)

- **Visualización del formulario A**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/970a6f69-1219-4f33-bc56-3f3b398cf182)

- **Visualización del formulario B**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/9f9fbf86-e992-467d-85fc-f69e7081200d)

- **Visualización del formulario C**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/7d31899f-d85d-4c7b-b9ab-4564d6d3a4c7)

- **Exportación de furmularios a JSON** 

*La exportación de la información de los formularios verificará la existencia del archivo de exportación. En caso de que el archivo no exista, se creará automáticamente. Por otro lado, si el archivo ya existe, se mostrará una advertencia de su existencia.*

*Exportacion exitosa*

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/75d2ad8a-9217-467c-95d4-0470120ddedd)

*Archivo existente*

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/e6e2d1e6-0498-48e7-bfc6-850af4cabe04)

*visualización del contenido*

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/40cf7feb-f11a-4c6b-84c8-e1addb7732fe)

- **Ingreso al servicio de envio por Gmail**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/35cf999e-ced7-4846-a454-4908dc8603ad)

- **Pasos previos para el envio de Gmail**

**Ingreso de la cuenta**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/15a029d6-b734-496c-8f31-d1d56bded8ff)

**Una vez ingresada a la cuenta**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/15a5a1a0-dde4-44f1-af10-0dd7437a347d)

- **Envio del Email**

*Mensaje enviado con exito*

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/542e38b4-0236-477c-8fdd-fe4862332d9a)

*Correo recibido con exito*

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/6fd55cbe-89af-4876-b081-a9dd973ccd3b)

<hr>

## Errores

*La función del error es alertar al usuario en todo momento cuando haya ingresado una respuesta incorrecta. Por lo tanto, para poder avanzar en el flujo del programa, será necesario que vuelva a intentarlo hasta que ingrese los datos correctos; de lo contrario, los mensajes de error persistirán.*

- **Error - Conexión a la BD**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/b735486b-3c8b-4bcb-ab50-05e884ee0158)

- **Error - Tipo de conexión**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/66c41a72-86c3-48da-8d3c-64d4034bd66c)

- **Error en modo local - Creación de BD**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/dfcc12b9-6e68-4bb7-9b7d-997cfe577b47)

- **Error en modo local - Creación del nombre de BD**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/ce0915db-c14c-41ce-9cad-bd67bbcd6ebe)

- **Error - Menú**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/d8f935f7-0495-4dbd-8dc7-13ca04e5d28b)

- **Error - Campo**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/417dc5bd-ff6f-459b-8568-74e8053ef391)

- **Error - Formulario completado**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/7fb07f18-6094-4e56-ae54-0212c33a35b2)

- **Error - Menú de guardadado activo**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/bf9e1251-d72d-451d-9dcf-9469d5352879)

- **Error - Menú de visualización de datos**

 ![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/87eb7a04-a52d-44c0-80f5-e481cd8ce3cd)

- **Error - Retroceder**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/764cba03-b2db-404e-8a42-484380f1fcca)

- **Mensaje de Cierre**

![Sin título](https://github.com/Lucas-devSoft/Python/assets/111676352/02dc6059-ab2b-40ce-97e5-ebcac99927c5)

<hr>

## Ejecutable

*Si tenes sistema operativo Windows y tenes curiosidad por probar el programa, te dejo el ejecutable en la carpeta "Ejecutable .exe" dentro de la subcarpeta "dist" vas a encontrar el archivo main.exe*

<hr>
   
## Desarrollador

![Open](https://github.com/Lucas-devSoft/Python/assets/111676352/6d78f829-b40e-4b95-9d98-c6ba05e26f03) <br>
[Perfil Linkedin](https://www.linkedin.com/in/lucasdevsoft2022/ "Perfil Linkedin")   |   [Pagina Web](https://lucas-devsoft.github.io/CV/ "Curriculum Web")
