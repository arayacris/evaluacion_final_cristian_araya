# evaluacion_final_cristian_araya
Actualizando CI.
Actualizado2.0




Actualización para probar el deploy
Este proyecto corresponde a la evaluación final del módulo de Automatización de Pruebas y CI/CD.
Su propósito es implementar un flujo DevOps completo utilizando Git, Maven, GitHub Actions y pruebas automatizadas.

El proyecto incluye:

Un flujo de trabajo Git basado en Trunk-Based Development (rama main y rama develop).

Un proyecto Maven configurado con dependencias de JUnit 5 y Selenium.

Pipelines de Integración Continua (CI) y Despliegue Continuo (CD).

Mecanismos de rollback automático y acceptance tests.

Estrategia de Pruebas Implementada

El proyecto utiliza:

JUnit 5 para pruebas unitarias.

Un ejemplo funcional en AppTest.java.

Ejecución automática de pruebas dentro del pipeline CI con mvn test.

Validación de que el JAR se construye correctamente mediante mvn clean package.

En el pipeline CI:

Se compila el proyecto.

Se ejecutan los tests.

Solo si todo pasa, continúa el flujo.
