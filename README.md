# Git 102: Trabajo colaborativo con ramas y Pull Requests

Este repositorio acompaña un KT practico de 15 minutos sobre uso colaborativo de Git.

El objetivo no es aprender comandos avanzados, sino entender un flujo comun que cualquier equipo puede adaptar:

```txt
Rama -> Cambio -> Pull Request -> Revision -> Integracion
```

## Objetivo del KT

Al finalizar, los participantes deberian poder explicar:

- Por que no conviene trabajar directo sobre `main`.
- Para que sirve una rama de trabajo.
- Que representa un Pull Request.
- Que revisar antes de aprobar cambios.
- Que hacer cuando aparece un conflicto.
- Como adaptar este flujo al trabajo de su departamento.

## Publico objetivo

Equipos o departamentos que ya usan Git como control de versiones en sus proyectos, aunque no necesariamente sean desarrolladores.

Ejemplos:

- Producto
- QA
- Data
- Diseno
- Marketing
- Documentacion
- Operaciones
- Desarrollo

## Estructura del repositorio

```txt
git-102-team-workflow-kt/
  README.md
  docs/
    FACILITADOR.md
    PARTICIPANTE.md
    flujo-equipo.md
    checklist-pr.md
    ejemplo-conflicto.md
    roles.md
  .github/
    pull_request_template.md
```

## Practica principal

Cada participante debe:

1. Clonar el repositorio.
2. Crear una rama.
3. Modificar `docs/flujo-equipo.md` adaptando el flujo a su area.
4. Guardar y subir el cambio.
5. Abrir un Pull Request.
6. Revisar el Pull Request usando la checklist.
7. Entender que hacer si aparece un conflicto.

## Comandos minimos

```bash
git clone <url-del-repo>
cd git-102-team-workflow-kt
git checkout -b mejora-flujo-mi-area
git add .
git commit -m "docs: adapt workflow"
git push
```

El foco del KT no esta en memorizar comandos. El foco esta en entender el proceso de colaboracion.

## Mensaje central

Una rama es el espacio de trabajo.

Un Pull Request es el espacio de conversacion y revision.

`main` debe representar la version estable o aprobada.
