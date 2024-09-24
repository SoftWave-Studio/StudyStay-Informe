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

<table align="center" border="1" width="100%" style="text-align:left;"> <tbody> <tr> <td colspan="2"><strong>Convenciones y Estilos de Lenguajes</strong></td> </tr> <tr> <td colspan="2"><strong>HTML</strong></td> </tr> <tr> 
<td>1.</td> <td>Declarar siempre el tipo de documento: `<!DOCTYPE html>` en la primera línea.</td> 
</tr> <tr> <td>2.</td> <td>Usar minúsculas para nombres de etiquetas y atributos.</td> </tr> <tr> 
<td>3.</td> <td>Cerrar todas las etiquetas para evitar errores de sintaxis.</td> </tr> <tr> 
<td>4.</td> <td>Incluir comillas para los valores de atributos.</td> </tr> <tr> <td>5.</td> 
<td>Especificar atributos `alt`, `width` y `height` en imágenes.</td> </tr> <tr> <td>6.</td> 
<td>No omitir `<title>` ni metadatos `<meta>` para SEO.</td> </tr> 
<tr> <td colspan="2"><strong>CSS</strong></td> </tr> <tr> <td>1.</td> <td>Usar nombres de clases generales y descriptivos.</td> </tr> <tr> <td>2.</td> <td>Usar nombres de clase cortos.</td> 
</tr> <tr> <td>3.</td> <td>Separar palabras en nombres de clase solo con guiones.</td> </tr> 
<tr> <td>4.</td> <td>Evitar selectores de ID; preferir selectores de clase.</td> </tr> <tr> 
<td>5.</td> <td>Usar propiedades abreviadas para reducir líneas de código.</td> </tr> <tr> 
<td colspan="2"><strong>JavaScript</strong></td> </tr> <tr> <td>1.</td> <td>Usar nombres cortos 
y claros para variables y funciones.</td> </tr> <tr> <td>2.</td> <td>Evitar el uso de variables 
globales (no usar `var`).</td> </tr> <tr> <td>3.</td> <td>Comentar y documentar líneas de código
complejas.</td> </tr> <tr> <td>4.</td> <td>Usar notaciones sencillas y comprensibles.</td> 
</tr> <tr> <td colspan="2"><strong>Gherkin</strong></td> </tr> <tr> <td>1.</td> <td>Diferenciar 
bloques “Given-When-Then” con buena indentación.</td> </tr> <tr> <td>2.</td> <td>Usar tablas para 
pasos que requieran más información.</td> </tr> <tr> <td>3.</td> <td>Usar comillas simples para 
parámetros.</td> </tr> <tr> <td>4.</td> <td>Separar escenarios con comentarios para mayor claridad.</td> 
</tr> <tr> <td colspan="2"><strong>C#</strong></td> </tr> <tr> <td>1.</td> <td>Usar interpolación de 
cadenas para concatenaciones cortas.</td> </tr> <tr> <td>2.</td> <td>Usar `StringBuilder` en bucles para grandes cantidades 
de texto.</td> </tr> <tr> <td>3.</td> <td>Usar `var` cuando 
el tipo pueda inferirse.</td> </tr> <tr> <td>4.</td> <td>Usar `using` para gestionar recursos `IDisposable`.</td> </tr> <tr> <td>5.</td> 
<td>Usar `&&` y `||` para evitar errores de evaluación.</td> </tr> <tr> <td>6.</td> <td>Usar inicializadores de objetos para simplificar la creación.</td> </tr> <tr> <td>7.</td> <td>Usar expresiones lambda para definir delegados anónimos.</td> </tr> <tr> <td>8.</td>
<td>Alinear cláusulas de consulta en LINQ para mejorar claridad.</td> </tr> <tr> <td colspan="2"><strong>Vue.js</strong></td> </tr> <tr> 
<td>1.</td> <td>Usar `v-bind` y `v-on` para enlazar datos y eventos.</td> </tr> <tr> <td>2.</td> <td>Dividir la interfaz en componentes reutilizables.</td> </tr> <tr> <td>3.</td> <td>Usar `props` y eventos para la comunicación entre componentes.</td> </tr> 
<tr> <td>4.</td> <td>Usar `computed` y `watch` para propiedades dependientes.</td> </tr> <tr> <td>5.</td> 
<td>Usar `v-model` para enlaces bidireccionales.</td> </tr> <tr> <td>6.</td> <td>Usar `v-if`, `v-else` y `v-show` para el renderizado condicional.</td> </tr> <tr> <td>7.</td> <td>Usar `v-for` para renderizar listas.</td> </tr> <tr> <td>8.</td> <td>Usar Vuex para gestionar el estado global de la aplicación.</td> </tr> <tr> <td colspan="2"><strong>ASP.Net</strong></td> </tr> <tr> <td>1.</td> <td>Usar el sufijo `Async` en métodos asíncronos.</td> </tr> <tr> <td>2.</td> 
<td>Seguir los ajustes predeterminados de Visual Studio.</td> </tr> <tr> <td>3.</td> <td>Usar `var` siempre que sea posible.</td> </tr> <tr> <td>4.</td> <td>Ser sensible a diferencias entre sistemas operativos.</td> </tr> <tr> <td>5.</td> <td>Evitar métodos de extensión innecesarios.</td> </tr> <tr> <td>6.</td> <td>Escribir comentarios de documentación para APIs públicas.</td> </tr> <tr> <td>7.</td> 
<td>Nombrar y organizar clases y métodos de prueba de forma consistente.</td>
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

Link del APIRestful desplegado: https://studystay-backend.onrender.com/docs

## 5.2.1. Sprint Backlogs.

<table align="center" border="1" width="70%" style="text-align:center;">
    <tbody>
        <tr>
            <td style="">Sprint#</td>
            <td colspan="8" style="text-align:center">Sprint 1</td>
        </tr>
        <tr>
            <td style="" colspan="2">User Story</td>
            <td colspan="6" style="text-align:center">Work-Item / Task</td>
        </tr>
        <tr>
            <td>ID</td>
            <td style="text-align:center;">Title</td>
            <td style="text-align:center;">ID</td>
            <td style="text-align:center;">Title</td>
            <td style="text-align:center;">Description</td>
            <td style="text-align:center;">Estimation (hours)</td>
            <td style="text-align:center;">Assigned To</td>
            <td style="text-align:center;">Status<br>(To-do / InProcess / ToReview / Done)</td>
        </tr>
        <tr>
            <td>SS01</td>
            <td>Apartado del Header</td>
            <td>S01</td>
            <td>Header responsivo</td>
            <td>Desarrollo e implementación de los estilos que corresponden al encabezado (Header) de manera responsive.</td>
            <td>3</td>
            <td>Luis Alejo</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>SS02</td>
            <td>Apartado del Footer</td>
            <td>S02</td>
            <td>Footer responsivo</td>
            <td>Desarrollo e implementación de los estilos que corresponden al pie de página (Footer) de manera responsive.</td>
            <td>2</td>
            <td>Fabio Horna</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>SS03</td>
            <td>Sección Hero</td>
            <td>S03</td>
            <td>Sección Hero responsiva</td>
            <td>Desarrollo e implementación de los estilos que corresponden a la sección Hero de manera responsive.</td>
            <td>3</td>
            <td>Francisco Hurtado</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>SS04</td>
            <td>Barra de Navegación</td>
            <td>S04</td>
            <td>Barra de Navegación responsiva</td>
            <td>Desarrollo e implementación de los estilos que corresponden a la Barra de Navegación de manera responsive.</td>
            <td>2</td>
            <td>Francisco Hurtado</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>SS05</td>
            <td>Testimonials</td>
            <td>S05</td>
            <td>Sección “Testimonios” responsiva</td>
            <td>Desarrollo e implementación de los estilos que corresponden a los testimonios de manera responsive.</td>
            <td>3</td>
            <td>Fabio Horna</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>SS06</td>
            <td>Sección Sobre Nosotros</td>
            <td>S06</td>
            <td>Información del equipo responsiva</td>
            <td>Desarrollo e implementación de los estilos que corresponden a la información del equipo de manera responsive.</td>
            <td>3</td>
            <td>Luis Alejo</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>SS07</td>
            <td>Sección Services</td>
            <td>S07</td>
            <td>Sección Services responsiva</td>
            <td>Desarrollo e implementación de los estilos que corresponden a los servicios de la página de manera responsive.</td>
            <td>3</td>
            <td>Tony Torres</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>SS08</td>
            <td>Interfaz Responsive</td>
            <td>S08</td>
            <td>Desarrollo de interfaz responsiva</td>
            <td>Desarrollo e implementación de un estilo responsive en toda la página.</td>
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

Link del Frotend desplegado: https://study-stay-front-end-pi.vercel.app/


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
StudyStay-LandigPage:
![GH3](https://github.com/user-attachments/assets/cdbd2ea7-d69c-48ca-b14b-9d87b518df35)

StudyStay-FrontEnd:
![GH2](https://github.com/user-attachments/assets/142a6feb-e87b-4db5-88ee-27f6a8a647a3)

StudyStay-BackEnd:
![GH1](https://github.com/user-attachments/assets/7f44a37c-e351-4cfa-b50d-5ef7fe3ea47a)
