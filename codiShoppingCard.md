# Pull Request (PR): Guía Completa

## ¿Qué es una Pull Request?

Una Pull Request (Solicitud de Extracción) es un mecanismo en plataformas como GitHub y GitLab que permite proponer cambios en un repositorio. Básicamente, es una solicitud para fusionar cambios de una rama a otra (generalmente de una rama de característica a la rama principal).

## ¿Para qué sirve?

- **Revisión de código:** Permite que otros desarrolladores revisen los cambios antes de incorporarlos
- **Control de calidad:** Asegura que el código cumpla con los estándares del proyecto
- **Documentación:** Genera un historial de por qué se tomaron ciertos cambios
- **Discusión:** Facilita la comunicación entre miembros del equipo
- **Integración continua:** Permite ejecutar pruebas automáticas antes de fusionar

## Ventajas

1. Mejora la calidad del código mediante revisión  
2. Previene errores antes de que lleguen a producción  
3. Facilita el aprendizaje en equipos  
4. Mantiene un historial claro de cambios  
5. Permite discusión constructiva sobre la implementación  
6. Reduce bugs gracias a múltiples pares de ojos  

## Desventajas

1. Puede ralentizar el desarrollo si las revisiones son lentas  
2. Requiere disciplina del equipo para funcionar bien  
3. Puede generar conflictos si no se resuelven adecuadamente  
4. Necesita que haya suficientes revisores disponibles  
5. A veces crea burocracia innecesaria en equipos pequeños  

## Flujo típico de una PR

1. Crear una rama nueva basada en `main`
2. Hacer cambios en esa rama
3. Hacer push de la rama al repositorio remoto
4. Crear una Pull Request en GitHub/GitLab
5. Otros desarrolladores revisan el código
6. Se realizan cambios si es necesario
7. Se aprueba y fusiona la PR
8. Se elimina la rama de característica

## Mejores Prácticas

- Mantén las PRs pequeñas y enfocadas
- Escribe descripciones claras de los cambios
- Vincula issues relacionados
- Responde a los comentarios de revisión
- Asegúrate de que pasen todos los tests antes de fusionar