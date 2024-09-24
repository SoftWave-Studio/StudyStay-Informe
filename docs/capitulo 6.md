# Capítulo VI: Product Verification & Validation

## 6.1. Testing Suites & Validation

### 6.1.1. Core Entities Unit Tests
En esta fase de pruebas, se validan las entidades principales del sistema, como `Post`, `Reservation` y `User`. Se trata de pruebas unitarias que verifican que los componentes más pequeños de la aplicación funcionen de manera correcta y aislada. Utilizamos **Jest** como framework de pruebas y **Vue Test Utils** para montar y manipular componentes de Vue.js. Estas herramientas permiten simular comportamientos y verificar los resultados sin necesidad de depender de la infraestructura completa.







### 6.1.2. Core Integration Tests
Las pruebas de integración se centran en verificar que los diferentes módulos o componentes de la aplicación interactúen correctamente entre ellos. Para estas pruebas, simulamos flujos completos, como la creación de posts o reservas, asegurándonos de que las entidades trabajen de forma correcta al unísono. Se mockean algunos servicios como las APIs para asegurar que la lógica entre componentes sea coherente.









### 6.1.3. Core Behavior-Driven Development
En el marco de BDD (Behavior-Driven Development), nos centramos en describir el comportamiento esperado del sistema desde la perspectiva del usuario final. Utilizamos **Jest-Cucumber** para escribir las pruebas en formato **Gherkin**, lo que permite definir escenarios con `Given`, `When`, y `Then`. Esto asegura que el sistema se comporta correctamente según los requisitos establecidos, probando casos como la creación de un post o la reserva de una habitación.






### 6.1.4. Core System Tests
Las pruebas del sistema verifican el comportamiento del sistema en su conjunto, incluyendo todas las partes integradas (frontend, backend, base de datos). Estas pruebas simulan interacciones de usuario reales y aseguran que todo el flujo del sistema funcione sin problemas, desde la capa de presentación hasta la base de datos. En este caso, se utilizan servicios reales o simulaciones avanzadas para asegurar la coherencia en todo el sistema.






