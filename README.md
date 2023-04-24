# Sistema de Subastas en Línea

Este proyecto es una aplicación de subastas en línea desarrollada utilizando Node y TypeScript. El objetivo principal es practicar y aplicar los principios SOLID, la arquitectura limpia (Clean Architecture) y los patrones de diseño Command, Chain of Responsibility, Mediator, Memento, Observer, State, Strategy y Visitor.

## Características principales

- Registro y autenticación de usuarios.
- Creación de productos para subasta.
- Participación en subastas.
- Cierre y adjudicación de subastas.
- Generación de historial de subastas.
- Sistema de notificaciones para usuarios.
- Administración de usuarios y subastas.

## Tecnologías y enfoques utilizados

- Lenguaje de programación: TypeScript.
- Entorno de ejecución: Node.js.
- Arquitectura: Clean Architecture.
- Principios de diseño: SOLID.
- Patrones de diseño: Command, Chain of Responsibility, Mediator, Memento, Observer, State, Strategy y Visitor.
- Metodología de desarrollo: Test-Driven Development (TDD).

## Cómo iniciar

1. Clona este repositorio en tu máquina local.
2. Instala las dependencias del proyecto utilizando `npm install`.
3. Ejecuta los tests con `npm test`.
4. Inicia el servidor de desarrollo con `npm start`.
5. Abre un navegador y accede a `http://localhost:3000` para interactuar con la aplicación.

## Estructura de carpetas

La estructura de carpetas sigue los principios de Clean Architecture y separa las preocupaciones en capas:

- `src`: Contiene el código fuente del proyecto.
  - `application`: Contiene la lógica de negocio y la implementación de los patrones de diseño.
  - `domain`: Define las entidades y reglas de negocio del dominio.
  - `infrastructure`: Incluye la implementación de servicios externos, como bases de datos y sistemas de notificación.
  - `interfaces`: Define las interfaces de los componentes y servicios utilizados en el sistema.
  - `presentation`: Contiene el código relacionado con la presentación y la interacción con el usuario.

## Contribuciones

Las contribuciones son siempre bienvenidas. Si deseas contribuir o reportar errores, no dudes en abrir un _issue_ o enviar un _pull request_.
