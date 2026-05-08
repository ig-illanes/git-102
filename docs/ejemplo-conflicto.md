# Ejemplo simple de conflicto

## Linea original

```txt
Dos personas deben revisar los cambios antes de integrarlos.
```

## Cambio de Persona A

```txt
El lider del equipo debe revisar los cambios antes de integrarlos.
```

## Cambio de Persona B

```txt
Dos personas deben revisar los cambios antes de integrarlos.
```

## Que ocurre

Git no puede decidir automaticamente cual version conservar porque ambas personas modificaron la misma linea.

## Como se debe resolver

Un conflicto se resuelve tomando una decision:

1. Conservar la version A.
2. Conservar la version B.
3. Combinar ambas versiones.
4. Escribir una nueva version acordada.

## Version combinada posible

```txt
El lider del equipo o dos revisores asignados deben revisar los cambios antes de integrarlos.
```

## Mensaje clave

Un conflicto no es un error grave. Es una decision pendiente que requiere comunicacion.
