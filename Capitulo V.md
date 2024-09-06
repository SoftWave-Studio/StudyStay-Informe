# 5.1. Software Configuration Management.

## 5.1.1. Software Development Environment Configuration.

 
 Desarrollo del Landing Page: Para el desarrollo del landing page, se decidió con el equipo usar HTML, JS y CSS (desarrollo puro) y para llevarlo a cabo se eligieron diversas herramientas tecnológicas de las cuales el equipo ya está familiarizado y tiene  dominio. Estas herramientas son las siguientes:

 Visual Studio Code: Esta herramienta es un editor de código gratuito, moderno y potente gracias a que cuenta con varias funciones y extensiones para trabajar con casi cualquier lenguaje de programación y framework. Además, esta es bastante conocida por todos los integrantes del equipo y es por dicha razón por la cual se decidió trabajar con Visual Studio Code.
 <p>

<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/722507b6-6a9a-4c21-888b-f77dde874d52" alt="Descripción de la imagen">
</div>

<p>

Para la instalación del programa, el instalador se puede obtener de su página web oficial Visual Studio Code - Code Editing. Redefined, una vez descargado se puede proceder con la instalación de forma rápida y fácil siguiendo las instrucciones del instalador. 
### Git y GitHub:

 Se decidió hacer uso de estas herramientas por la razón de que hoy en día es un estándar usar Git para el control de versiones de software y se eligió GitHub por ser la plataforma más popular y fácil de usar para crear y manejar repositorios de software, tener funciones para ver los cambios, commits, pull requests y entre otros. El enlace de descarga del instalador de GitHub Desktop es [GitHub Desktop](https://github.com/apps/desktop)


<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/ff491b7b-1eaa-4c21-b23d-738291b25da5" alt="Descripción de la imagen">
</div>



### Live server: 

Finalmente, para acelerar el desarrollo del landing page, se hizo uso de esta herramienta que es una extensión para editor Visual Studio Code que sirve para visualizar los cambios inmediatamente después de alguna modificación que se hace en el código, así se evita estar recargando la página lo cual se traduce en ahorro de tiempo y comodidad a la hora de desarrollar:




<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/708d1b66-1414-47d3-9368-02fb18735db8" alt="Descripción de la imagen">
</div>






### Desarrollo de la aplicación web:

 Se hizo uso del framework Vue.js para el desarrollo del frontend de la aplicación, mientras que para el backend y los servicios web se usó .Net, puesto que brinda un enfoque más amplio y completo para el desarrollo de cada módulo de la aplicación. Para ello se usaron las siguientes herramientas:

### JetBrains WebStorm:
 Esta herramienta es un potente IDE para desarrollo web que ofrece soporte completo para Vue.js. Facilita la creación eficiente de aplicaciones gracias a su destacado conjunto de herramientas y características de refactorización, depuración y autocompletado.





<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/b685f4b4-87a6-444f-b863-968ba319a113" alt="Descripción de la imagen">
</div>



Para la instalación del programa, este se puede descargar desde su [página web](https://www.jetbrains.com/webstorm/)


### Node.js: 

Esta herramienta de desarrollo es un entorno de tiempo de ejecución de JavaScript de alto rendimiento, el cual es necesario para el desarrollo de aplicaciones con Vue.js, ya que se obtiene las características completas de desarrollo JavaScript tanto en el lado del cliente como en el servidor.



<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/3644a69e-af40-410a-995b-7bbb6efbf302" alt="Descripción de la imagen">
</div>



 Esta herramienta se puede descargar desde su [página oficial](https://nodejs.org/es) 


### JetBrains Rider: 
 
 Se decidió usar este IDE de desarrollo para .NET por que destaca por su eficiencia y rendimiento y facilita el desarrollo de aplicaciones .NET con herramientas avanzadas y una interfaz más intuitiva.


<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/b172f86a-4abf-435d-bd85-b59084ac7dda" alt="Descripción de la imagen">
</div>

Se puede descargar el programa desde su [página web](https://www.jetbrains.com/es-es/rider/) 

## 5.1.2. Source Code Management.

 
 Para mantener el orden al desarrollar una solución y evitar conflictos o superposiciones de información, los proyectos se trabajaron en un organización de GitHub y dentro de esta se encuentran los diferentes repositorios para cada proyecto cuyos enlaces de los repositorios son los siguientes:



Repositorio para el [landing page](https://github.com/SoftWave-Studio/StudyStay-LandigPage)


Repositorio para los [tests de aceptación]() 


Repositorio de la aplicación web : 
- [FrontEnd](https://github.com/SoftWave-Studio/StudyStay-FrontEnd)
- [Backend](https://github.com/SoftWave-Studio/StudyStay-BackEnd)



Con respecto a la implementación de Gitflow, este se llevará a cabo de la siguiente manera:
Para cada commit que se realice, ya sea para el landing page o los archivos .feature, se utilizará el formato de mensaje "Conventional Commits" para ayudar a reconocer mejor lo que se hizo en los commits y  de esta forma conocer mejor el estado del proyecto.

Cada repositorio de código tendrá sus respectivas ramas tal como lo describe Vincent Driessen en su artículo “A successful Git branching model”, donde estará presente la rama Master (que almacenará las versiones estables y finales), Develop (donde se irán integrando los cambios implementados por cada feature y estará en constante actualización), Release (donde se encontrará el código final de las versiones release) y Hotfix.

Además, cada feature desarrollado tendrá su propia rama que seguirá la siguiente convención para el nombre: feature- apellidos del colaborador


<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/c6fcbb79-0a69-4916-a592-e0552e6eb475" alt="Descripción de la imagen">
</div>




## 5.1.3. Source Code Style Guide & Conventions

A continuación, se darán a conocer las convenciones, formatos, estilos y otras propiedades de los lenguajes trabajados en la presente solución: HTML, JavaScript/TypeScript, CSS. Además, por el lado de las pruebas de aceptación, también se darán a conocer dichos temas para el lenguaje Gherkin.

#### HTML
Se hará uso de la guía “HTML Style Guide and Coding” de la página W3Schools, la cual menciona las convenciones y estándares de este lenguaje de etiquetas. Hemos considerado las siguientes como las más importantes:

- Declarar siempre el tipo documento: Colocar siempre la etiqueta `<!DOCTYPE html>` en la primera línea del código.
- Utilizar el nombre de las etiquetas y sus atributos en minúscula: Por un tema de estética y orden del código para que este se vea más limpio y sea más fácil de escribir.
- Cerrar todas las etiquetas: Esto evita futuros problemas o errores de sintaxis.
- Siempre colocar comillas para los valores de los atributos de las etiquetas: De esta forma los valores son más fáciles de leer y se deben utilizar obligatoriamente si este contiene espacios.
- Especificar siempre los atributos `alt`, `width` y `height` para las imágenes: Es importante en caso de que la imagen no se pueda mostrar por algún motivo y también ayuda con el tema de la accesibilidad de los usuarios.
- No omitir la etiqueta `<title>` ni los metadatos `<meta>`: Estas etiquetas son importantes para la optimización de motores de búsqueda (SEO).

#### CSS
Se siguió la guía “Google HTML/CSS Style Guide” donde se indican las convenciones, reglas y buenas prácticas para este lenguaje. Hemos considerado las siguientes recomendaciones como las más destacadas:

- Nombre de clases: Se recomienda usar nombres generales para las clases, no deben ser específicos, ya que deben comportarse como padres.
- Usar nombres de clase cortos: Se recomienda utilizar nombres de clase que sean cortos y descriptivos, para transmitir la idea de lo que representa de manera concisa.
- Usar delimitadores de nombres de clase adecuados: Se debe de separar las palabras en los nombres de clase con solo guiones.
- Evitar los selectores de ID: No se recomienda implementar este tipo de selectores, por la razón de que estos deben ser únicos en toda la página y en proyectos grandes que tengan muchos componentes es difícil de garantizar esa unicidad, es preferible usar selectores de clase.
- Usar propiedades abreviadas: Es muy recomendable usar propiedades que soporten ser declarados de forma abreviada (por ejemplo, la propiedad padding, margin, border, etc.) por la razón de que reduce de forma significativa la cantidad de líneas de código, y es más legible para el programador o diseñador.

#### JavaScript
Se consideró importante seguir una guía de buenas prácticas para un mejor desarrollo del código, para este caso se eligió la guía de la wiki “JavaScript best practices” del World Wide Web (W3C). Lo cual se destaca lo siguiente:

- Usar nombres cortos y fáciles de leer: Es recomendable nombrar adecuadamente las variables, clases, funciones y otros elementos para que sea más sencillo de leer y comprender.
- Evitar el uso de variables globales (keyword `var`): No se recomienda el uso de este tipo de variables en un proyecto, porque pueden generar muchos errores a medida que el proyecto crece y estas pueden sobrescribirse fácilmente afectando el valor y se pueden declarar otros elementos como funciones con el mismo nombre de la variable y generar errores.
- Comentar y documentar lo necesario: Se recomienda comentar líneas de código que son complejas de entender a simple vista explicando o dejando mensajes para que otros programadores lo entiendan.
- Usar notaciones sencillas de entender: JavaScript cuenta con diversas notaciones y operadores para crear o modificar ciertas estructuras de datos como objetos, arrays, selectivas, etc.

#### Gherkin
Se consideró conveniente usar la guía y convenciones que se mencionan en “Gherkin Conventions for Readable Specifications” para una correcta realización de las pruebas. A continuación, se mencionan los puntos que consideramos más importantes para nuestro trabajo:

- Los bloques “Given-When-Then” deben ser diferenciados: Se recomienda usar una correcta indentación de esos bloques para identificar mejor las secciones de la prueba y también añadiendo la keyword “And” para añadir otra línea en los pasos y otro bloque.
- Usar tablas para los pasos: Si uno de los pasos requiere de más información es recomendable usar tablas para organizar dicha información y tenga un aspecto más ordenado.
- Usar comillas simples para los parámetros: Se recomienda esta práctica para una mejor legibilidad de los parámetros en un paso y tener una sintaxis más simple.
- Separar los escenarios con comentarios: Si se da el caso de tener muchos escenarios en una prueba, es recomendable usar los comentarios como separadores para que visualmente sea más organizado, fácil de leer y distinguir mejor.

#### C#
Para el desarrollo del código en el lenguaje C#, se ha considerado usar la guía de convenciones de Microsoft Common C# code conventions y se destaca las siguientes convenciones:

- Usar la interpolación de cadenas: para concatenar cadenas cortas, en lugar de usar el operador `+` o `String.Format`.
- Usar `StringBuilder`: para concatenar cadenas en bucles, especialmente cuando se trabaja con grandes cantidades de texto.
- Usar `var`: solo cuando el tipo de la variable se pueda inferir de la expresión a la derecha de la asignación.
- Usar `using`: para simplificar la gestión de recursos que implementan `IDisposable`, como archivos o flujos.
- Usar los operadores `&&` y `||`: en lugar de `&` y `|` cuando se realizan comparaciones, para evitar errores en tiempo de ejecución por evaluación de cortocircuito.
- Usar inicializadores de objetos: para simplificar la creación de objetos, asignando valores a las propiedades en la misma línea de declaración.
- Usar expresiones lambda: para definir delegados anónimos, especialmente para controladores de eventos o métodos de LINQ.
- Alinear las cláusulas de consulta: debajo de la cláusula `from`, y usar `where` antes que otras cláusulas, para mejorar la claridad y el rendimiento de las consultas LINQ.

#### Vue.js
Para el framework de Vue.js se consideraron los style guidelines más importantes de la página oficial de Vue, las cuales son las siguientes:

- Usar `v-bind` y `v-on`: para enlazar datos y eventos a los elementos del DOM, en lugar de usar atributos HTML normales. Esto permite una mayor reactividad y flexibilidad.
- Usar componentes: para dividir la interfaz de usuario en piezas reutilizables y modulares, en lugar de usar un solo archivo HTML. Esto facilita el mantenimiento y la escalabilidad del código.
- Usar `props` y eventos: para comunicarse entre componentes padre e hijo, en lugar de usar `this.$parent` o mutar props. Esto hace que el flujo de datos sea más claro y predecible.
- Usar `computed` y `watch`: para definir propiedades y funciones que dependen de otros datos reactivos, en lugar de usar métodos o expresiones complejas. Esto mejora el rendimiento y la legibilidad del código.
- Usar `v-model`: para crear enlaces bidireccionales entre los datos y los elementos de entrada, en lugar de usar `v-bind` y `v-on` por separado. Esto simplifica la lógica y evita la duplicación de código.
- Usar `v-if`, `v-else` y `v-show`: para controlar la condición de renderizado de los elementos, en lugar de usar estilos CSS o JavaScript. Esto hace que el código sea más declarativo y fácil de seguir.
- Usar `v-for`: para renderizar una lista de elementos basada en un array o un objeto, en lugar de usar un bucle `for` o `while`. Esto hace que el código sea más conciso y reactivo.
- Usar Vuex: para gestionar el estado global de la aplicación, en lugar de usar `this.$root` o un bus de eventos global. Esto ofrece una solución centralizada y estructurada para el manejo del estado.

#### ASP.Net
Para el desarrollo con ASP.Net se siguió los coding styles y convenciones del repositorio Engineering guidelines de dotnet, y se destacaron los siguientes:

- Usar el sufijo `Async`: en todos los métodos asíncronos, y pasar tokens de cancelación como parámetros opcionales.
- Seguir los ajustes predeterminados de Visual Studio: para el formato del código, excepto poner los espacios de nombres `System` antes que otros.
- Usar `var` siempre que sea posible: y usar las palabras clave de C# en lugar de los nombres de tipos .NET.
- Ser sensible a las diferencias entre sistemas operativos: como los saltos de línea, las variables de entorno y los separadores de directorios.
- Evitar los métodos de extensión: a menos que sean necesarios para crear cadenas de métodos o mejorar la legibilidad.
- Escribir comentarios de documentación: para todas las APIs públicas, e indicar si son solo para uso interno.
- Nombrar y organizar las clases y métodos de prueba: siguiendo un patrón consistente y descriptivo, y separar las etapas Arrange, Act y Assert.



### Nombrar y organizar las clases y métodos de prueba: 
- Siguiendo un patrón consistente y descriptivo, y separar las etapas Arrange, Act y Assert.



## 5.1.4. Software Deployment Configuration.

A continuación, se dará a conocer el proceso del despliegue del las aplicaciones para que estas puedan ser visualizadas por el público y todo internet.

### Landing Page: 

Para este caso se usó el servicio “GitHub Pages” en donde se desplegará la aplicación automáticamente desde una rama de GitHub y este generará un enlace con un dominio establecido para acceder a la página. Para realizar esto se realizaron los siguientes pasos:

1. Una vez que se haya lanzado el release al repositorio y las ramas estén actualizadas, se procede a ingresar a GitHub, luego acceder al repositorio del proyecto y seguidamente hacer click en la pestaña “Settings”, buscar el ítem “Pages” del menú lateral.



![image](https://github.com/user-attachments/assets/3e1970b6-461b-40a1-b347-01a1cecb2d70)

![image](https://github.com/user-attachments/assets/1b3e3e84-3611-4802-a65a-be75c7ce52c0)

2. Seleccionar la rama principal y confirmar los cambios, luego de esto GitHub comenzará el proceso de deploy. Cuando GitHub tenga listo el enlace público, este se podrá ver desde el mismo menú en la parte superior.


![image](https://github.com/user-attachments/assets/f0f17353-2b79-40a6-98fa-d3f494822e21)

link de la [landing page](https://softwave-studio.github.io/StudyStay-LandigPage/)

## 5.2. Product Implementation & Deployment.

![image](https://github.com/user-attachments/assets/25776064-1c89-4460-80b9-3feb8281b53e)

![image](https://github.com/user-attachments/assets/d1ebdade-d814-4549-9dfc-1a4974cade43)

![image](https://github.com/user-attachments/assets/5edc9ecb-682e-4a6b-a198-c37eb4a4060a)

## 5.2.1. Sprint Backlogs.

<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
          <td style=";">Sprint#</td>
           <td colspan="8" "text-align:center">Sprint 1</td>
        </tr>
          <tr>
            <td style=";"colspan="2">User Story</td>
           <td colspan="6" "text-align:center">Work-Item / Task</td>
        </tr>
        <tr>
            <td>ID</td>
             <td style="text-align:center;">Title</td>
            <td style="text-align:center;">ID</td>
             <td style="text-align:center;">Title</td>
            <td style="text-align:center;">Description</td>
             <td style="text-align:center;">Estimation(hours)</td>
            <td style="text-align:center;">Assigned To</td>
            <td style="text-align:center;">Status
(To-do /
InProcess /
ToReview /
Done)
</td>
        </tr>
        <tr>
            <td>SS01</td>
            <td>Apartado del Header</td>
            <td>S01</td>
            <td>Header responsivos (Desarrollado en HTML y CSS).</td>
            <td>Desarrollo e implementación de los estilos que corresponden al encabezado (Header) de manera responsive.</td>
            <td>3</td>
            <td>Luis Alejo</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>SS02</td>
            <td>Apartado del Footer</td>
            <td>S02</td>
            <td>Footer responsivos (Desarrollado en HTML y CSS).</td>
            <td>Desarrollo e implementación de los estilos que corresponden al pie de página (Footer) de manera responsive.</td>
            <td>2</td>
            <td>Fabio Horna</td>
            <td>Done</td>
        </tr>
         <tr>
            <td>SS03</td>
            <td>Sección Hero</td>
            <td>S03</td>
            <td>(Desarrollado en HTML y CSS) Desarrollo e implementación de los estilos que corresponden a la sección Hero de manera responsive.</td>
            <td>Desarrollo e implementación de los estilos que corresponden a la sección Hero de manera responsive.

</td>
            <td>3</td>
            <td>Francisco Hurtado</td>
            <td>Done</td>
        </tr>
            <tr>
            <td>SS04</td>
            <td>Barra de Navegación</td>
            <td>S04</td>
            <td>Apartado “Hero” (Desarrollado en HTML y CSS) Desarrollo e implementación de los estilos que corresponden a la Barra de Navegación. Debe ser responsive.</td>
            <td>Desarrollo e implementación de los estilos que corresponden a la Barra de Navegación.
Debe ser responsive.
</td>
            <td>2</td>
            <td>Francisco Hurtado</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>SS05</td>
            <td>Testimonials</td>
            <td>S05</td>
            <td>Sección “Testimonios” (Desarrollado en HTML y CSS) Desarrollo e implementación de los estilos que corresponden a los testimonios de manera responsive.</td>
            <td>Desarrollo e implementación de los estilos que corresponden a los testimonios de manera responsive.

</td>
            <td>3</td>
            <td>Fabio Horna</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>SS06</td>
            <td>Sección Sobre Nosotros</td>
            <td>S06</td>
            <td>Información del equipo (Desarrollado en HTML y CSS) Desarrollo e implementación de los estilos que corresponden a la información del equipo de manera responsive.</td>
            <td>Desarrollo e implementación de los estilos que corresponden a la información del equipo de manera responsive.</td>
            <td>3</td>
            <td>Luis Alejo</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>SS07</td>
            <td>Sección Services</td>
            <td>S07</td>
            <td>Sección Services (Desarrollado en HTML y CSS) Desarrollo e implementación de los estilos que corresponden a los servicios de la página de manera responsive.</td>
            <td>
Desarrollo e implementación de los estilos que corresponden a los servicios de la página de manera responsive.</td>
            <td>3</td>
            <td>Tony Torres</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>SS08</td>
            <td>Interfaz Responsive</td>
            <td>S08</td>
            <td>Desarrollo responsive de la página (Desarrollado en HTML y CSS) Desarrollo e implementación de un estilo Responsive en toda la página.</td>
            <td>Desarrollo e implementación de un estilo Responsive en toda la página</td>
            <td>3</td>
            <td>Ariana Huapaya</td>
            <td>Done</td>
        </tr>
    </tbody>
</table>

# imagen sprint

## 5.2.2. Implemented Landing Page Evidence

![image](https://github.com/user-attachments/assets/a92b4121-f733-405d-900e-66c96d26aece)

![image](https://github.com/user-attachments/assets/48b2ab26-4ce3-49e6-bde3-7973b4cf3f71)

![image](https://github.com/user-attachments/assets/462d344a-6ee0-4443-b903-1b4ad3b78dac)

![image](https://github.com/user-attachments/assets/42e6669e-a9cc-4c00-a989-66a059d33fe3)

![image](https://github.com/user-attachments/assets/daf2e672-6bed-4512-bb3b-cc717aded1a4)

## 5.2.3. Implemented Frontend-Web Application Evidence

![image](https://github.com/user-attachments/assets/987a84bc-f752-4524-8119-7256e4edff9d)

![image](https://github.com/user-attachments/assets/05b594b8-5185-4997-9d7e-437118442485)

![image](https://github.com/user-attachments/assets/66a0cffa-6005-45c9-9093-19e289f16d56)

![image](https://github.com/user-attachments/assets/d18befef-7798-4f27-a2b3-c6683831f8f5)

![image](https://github.com/user-attachments/assets/787c8a23-cf6d-47b5-8739-0f44bca49e3f)




## 5.2.4. Implemented Native-Mobile Application Evidence

![image](https://github.com/user-attachments/assets/c637df74-a8dd-4edd-bb57-c5b101c794ca)

![image](https://github.com/user-attachments/assets/623988cc-bbee-4936-9595-fa277f1215c2)

![image](https://github.com/user-attachments/assets/4351d91c-2e48-4a34-b44a-f61bc7f58507)

## 5.2.5. Implemented RESTful API and/or Serverless Backend Evidence

![image](https://github.com/user-attachments/assets/4a3dd43a-4ea4-409e-8f64-61da2564ad3a)

![image](https://github.com/user-attachments/assets/94f12563-c1b2-401e-a274-922e6e73ffad)



## 5.2.6. RESTful API documentation

![image](https://github.com/user-attachments/assets/8beedd70-ab4b-4e57-9901-f0eb043aeadc)

![image](https://github.com/user-attachments/assets/10bcb106-5db4-43c4-8c94-23c7225211b7)

![image](https://github.com/user-attachments/assets/92604939-5890-48f0-b4c7-e7d3f8f6be45)

![image](https://github.com/user-attachments/assets/b391c405-ee26-4e26-8a3b-08cc94419676)

![image](https://github.com/user-attachments/assets/4fb06db6-e163-438d-a707-7ccaf7dfd895)

![image](https://github.com/user-attachments/assets/c661cf68-3442-4423-a811-5e70c7a942aa)

![image](https://github.com/user-attachments/assets/59916071-8133-4dd8-8bac-d522340f2414)


## 5.2.7. Team Collaboration Insights

# imagen