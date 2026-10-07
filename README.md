# Calidad de Software

Este documento presenta una introducción breve a la calidad de software y a algunas prácticas esenciales para asegurar que una aplicación funcione correctamente, sea mantenible y cumpla con las necesidades del usuario.

## ¿Qué es la calidad de software?

La calidad de software se refiere al grado en que un sistema cumple con requisitos funcionales, no funcionales y expectativas de usuarios y clientes. Un software de calidad debe ser:

- Funcional
- Confiable
- Mantenible
- Usable
- Seguro
- Eficiente
- Prueba de que cumple con lo esperado

## Importancia de la calidad

Una buena calidad en el software ayuda a:

- Reducir errores y fallos en producción
- Facilitar el mantenimiento del sistema
- Mejorar la experiencia del usuario
- Aumentar la confianza del cliente
- Reducir costos por correcciones tardías

## Pruebas de software

Las pruebas son una parte fundamental del proceso de desarrollo. Permiten verificar que el comportamiento del sistema sea correcto y que cambios futuros no rompan funcionalidades existentes.

### 1. Pruebas unitarias

Las pruebas unitarias validan unidades individuales de código, como funciones, métodos o módulos, de forma aislada.

Objetivos principales:

- Verificar el comportamiento esperado de cada pieza
- Detectar errores en lógica de negocio
- Facilitar la refactorización segura
- Mejorar la calidad del código

Ejemplo de concepto:

- Si una función suma dos números, una prueba unitaria valida que retorne el resultado correcto para varios escenarios.

Características:

- Son rápidas de ejecutar
- Se enfocan en una sola funcionalidad
- Se ejecutan con frecuencia durante el desarrollo

### 2. Pruebas end-to-end (E2E)

Las pruebas E2E validan el sistema completo desde la perspectiva del usuario, simulando flujos reales de uso en la aplicación.

Objetivos principales:

- Verificar que los componentes interactúan correctamente entre sí
- Comprobar flujos completos como login, compra, registro o navegación
- Detectar problemas en la integración de interfaces, backend y bases de datos

Ejemplo de concepto:

- Una prueba E2E puede abrir una aplicación web, iniciar sesión, completar un formulario y comprobar que el usuario puede acceder a la página correcta.

Características:

- Son más lentas que las pruebas unitarias
- Cubren escenarios más reales
- Ayudan a detectar fallos funcionales del sistema en conjunto

## Relación entre pruebas unitarias y E2E

Las pruebas unitarias y E2E cumplen roles distintos, pero complementarios:

- Las pruebas unitarias detectan errores a nivel de lógica
- Las pruebas E2E validan la experiencia del usuario y la integración del sistema

En la práctica, una estrategia sólida suele combinar ambos tipos de pruebas para obtener una mayor cobertura y confianza.

## Buenas prácticas en pruebas

- Escribir pruebas claras y mantenibles
- Probar casos normales y casos límite
- Automatizar la ejecución de pruebas
- Mantener la cobertura de pruebas adecuada
- Revisar y actualizar pruebas cuando cambia el software

## Conclusión

La calidad de software no depende solo de escribir código funcional, sino también de validar que el sistema se comporte correctamente en todas sus etapas. Las pruebas unitarias y las pruebas E2E son herramientas clave para asegurar robustez, confianza y sostenibilidad en el desarrollo de software.
