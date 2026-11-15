# Amour du Cinéma

Repositorio de implementación del sitio web y la identidad digital de Amour du Cinéma.

## Flujo de trabajo diseño ↔ código

- Figma es la fuente de verdad para identidad visual, composición, tipografía, color, espaciado y comportamiento esperado.
- GitHub es la fuente de verdad para implementación, componentes, contenido publicado, pruebas y despliegue.
- Ningún cambio de diseño se considera implementado hasta que exista un PR revisado y aprobado.
- Ningún cambio de código que afecte la interfaz se considera validado hasta compararlo con el frame correspondiente de Figma.

## Ciclo de trabajo

1. Diseñar o modificar el frame en Figma y dejar una descripción del objetivo, breakpoint y estados relevantes.
2. Crear una rama `design/<tema>` o `feat/<tema>`.
3. Implementar en GitHub respetando los componentes, tokens y assets aprobados.
4. Abrir un Pull Request con el frame de Figma, capturas antes/después, alcance, pruebas y posibles diferencias.
5. Revisar visualmente contra Figma en desktop y mobile. Corregir desvíos antes de aprobar.
6. Fusionar a `main` únicamente después de la revisión.
7. Si la implementación exige cambiar el diseño, documentar la decisión y actualizar Figma antes de cerrar el PR.

## Convenciones

- Ramas: `design/*`, `feat/*`, `fix/*`, `content/*`.
- Commits: mensajes breves en modo imperativo.
- No subir secretos, tokens ni credenciales.
- No reemplazar assets aprobados por aproximaciones sin documentarlo.
- Mantener los cambios acotados y reversibles.

## Integración con Figma

La conexión de GitHub debe autorizarse desde Figma mediante la aplicación oficial de Figma para GitHub. Para trabajo con código editable, usar un Code Layer vinculado a este repositorio y trabajar en ramas; enviar cambios a `main` mediante Pull Requests.

Code Connect puede vincular componentes publicados de una biblioteca de Figma con componentes reales del repositorio. No sustituye el proceso de revisión visual ni sincroniza automáticamente todos los cambios de diseño y código.

## Estado inicial

Repositorio inicializado con el protocolo de colaboración. La estructura y el stack de la web se definirán después de inspeccionar los frames completos de Figma y acordar la arquitectura de implementación.
