# Cosas que le cuento a mi hijo sobre ingeniería de software

Guía interactiva creada por [Xavi Guardia](https://github.com/xaviguardia) para explicarle a su hijo los conceptos de ingeniería de software que ha ido aprendiendo en 35 años de carrera profesional.

Lo que empezó como apuntes sobre arquitectura hexagonal ha ido creciendo hasta cubrir patrones, observabilidad, data lakes, carreras profesionales, y esas preguntas que todos nos hacemos pero nadie ordena en un solo sitio.

**https://xaviguardia.github.io/hexagonal-web/**

## Contenido

- **Arquitectura hexagonal** - Concepto, capas, puertos y adaptadores, flujo completo
- **Dominio, aplicación e infraestructura** - Patrones tácticos por capa
- **Patrones** - Refactoring, rendimiento, transaccionalidad, testing
- **Observabilidad** - OpenTelemetry con puertos y decorators
- **Frontend hexagonal** - Dos hexágonos, metadata-driven UI, validaciones
- **BPMN** - Orquestación de procesos en hexagonal
- **Data Lake** - Arquitectura Medallion (Bronze/Silver/Copper/Gold), RLS
- **Carreras tech** - Mapa interactivo de tracks profesionales (Frontend, Backend, DevOps, Data, QA, Gestión, Arquitectura)
- **Conceptos y FAQ** - Deuda técnica, software legacy, Golden Master, síndrome del impostor
- **Explorador de código** - Ejemplos interactivos en TypeScript
- **Flashcards y Quiz** - Para repasar y autoevaluarse

## Implementación de ejemplo

El código de ejemplo que aparece en la web tiene su implementación real en TypeScript:

**https://github.com/xaviguardia/hexagonal-architecture**

## Tech stack

- [Astro](https://astro.build/) - Framework web
- [Tailwind CSS v4](https://tailwindcss.com/) - Estilos
- Desplegado en GitHub Pages via GitHub Actions

## Desarrollo local

```sh
npm install
npm run dev
```

## Créditos

Creado por **Xavi Guardia** con la ayuda de [Claude Code](https://claude.ai/claude-code) de Anthropic.
