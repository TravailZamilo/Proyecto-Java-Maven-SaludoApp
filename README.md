# 🚀 Proyecto SaludoApp - Integración Continua con Jenkins y Maven

## 📌 Descripción del proyecto  
SaludoApp es una aplicación Java con Maven que implementa una función de saludo y su prueba unitaria. El proyecto busca automatizar la construcción, pruebas y empaquetado con Jenkins, integrando control de versiones con GitHub y configurando un pipeline de CI.

## ⚙️ Pasos principales realizados  
- Instalación y configuración de Jenkins con Java 11.  
- Creación del proyecto Maven con archetype quickstart.  
- Desarrollo de la clase principal con método `saludar` y prueba unitaria en JUnit.  
- Subida del proyecto a GitHub.  
- Creación de un job Pipeline en Jenkins que ejecuta el Jenkinsfile desde el repositorio.  
- Pipeline con etapas: clonar código, compilar, probar, empaquetar.

## 📦 Tecnologías y herramientas  
- Java 11  
- Maven 3.8.6  
- Jenkins (configurado con Maven y JDK 11)  
- Git / GitHub  

## 📝 Respuestas a preguntas del proyecto

**¿Qué beneficios concretos viste al automatizar la construcción con Jenkins?**  
Agiliza la validación continua, detecta errores temprano y asegura que el código pase pruebas antes de avanzar.

**¿Qué parte del proceso crees que sería más crítica en un equipo grande?**  
La integración continua con pruebas automáticas para evitar conflictos y errores al integrar código de varios desarrolladores.

**¿Cómo Jenkins asegura calidad antes de hacer despliegues?**  
Ejecutando pruebas unitarias automáticamente y validando que el build compile y empaquete sin errores.

**¿Qué cambiarías en este pipeline para prepararlo para producción?**  
Agregar análisis estático, pruebas de seguridad, despliegue a entornos de staging y notificaciones automáticas.

---

*Proyecto orientado a práctica de integración continua y despliegue automatizado con herramientas estándar.*
