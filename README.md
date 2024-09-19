# Proyecto Integrador del Taller de Circuitos Electrónicos

TP de tomi,nacho,elias y vero.


# 🐥 Git Branching: Guía Rápida con Panchito el Pollito 🐥

¡Hola, ameo! Soy Panchito, el pollito piola fui creado por IA para hacer más copado el usar Git 🐥, y te voy a guiar paso a paso para que aprendas cómo usar ramas (branches) en Git. Tranquilo, que lo hacemos simple y sin vueltas. ¡Vamo a meterle! 💪

---

## ¿Qué es una rama (branch)? 🌿

Bueno, imaginate que estás laburando en tu proyecto y querés probar algo nuevo sin que se rompa lo que ya tenés hecho. Ahí es donde entran las **ramas**. 🌱 Cada rama es como una copia separada del proyecto en la que podés hacer lío sin romper nada. Cuando ya esté todo pipí cucú, unís los cambios al proyecto principal y listo. 🎉

---

## Comandos Básicos para Trabajar con Ramas 🐾

### 1. Verificar en qué rama estás 🔍

Primero lo primero, ¿en qué rama estás? Para saberlo, usá este comando:

```bash
git branch
```

Te va a mostrar todas las ramas y te pone un asterisco `*` al lado de la que tenés activa. ¡Así sabés bien en qué andás! 💡

### 2. Crear una nueva rama 🌱

Cuando quieras hacer algo nuevo, lo mejor es crear una rama aparte (esto lo vamos a hacer todos una vez sola). Mandá este comando:

```bash
git branch pruebas_pepe
```

Este comando te crea la nueva rama, pero ¡ojo! todavía no te moviste a ella. Ahora vamos a eso. 🐥

### 3. Cambiar a una nueva rama 🎯

Para empezar a trabajar en la nueva rama, usá el siguiente comando:

```bash
git checkout pruebas_pepe
```

¡Listo! Ya estás en la nueva rama y podés hacer todos los cambios que quieras sin afectar el resto del proyecto. 🚀

### 4. Crear y cambiar a una nueva rama al mismo tiempo ⚡

Si te da fiaca hacer dos pasos, podés crear y cambiar a la nueva rama de una:

```bash
git checkout -b pruebas_pepe
```

Así no perdés tiempo y ya te ponés a laburar directo, como Panchito corriendo de acá para allá. 🐤

### 5. Verificar que estás en la nueva rama 🦅

Para asegurarte de que estás en la rama correcta, tirá de nuevo:

```bash
git branch
```

Ahí vas a ver el asterisco `*` al lado de la rama en la que estás. ¡Pío pío, ya estás listo para seguir! 🐥

### 6. Subir la nueva rama al repositorio remoto 🌍

Si querés compartir tus cambios con otros o simplemente guardar la rama en un repositorio remoto (como GitHub), tenés que hacer esto:

```bash
git push origin pruebas_pepe
```

Así, todo el mundo puede ver lo que hiciste y meter mano si hace falta. ¡No te olvides de esto cuando termines! 😉

---

## Resumen de los comandos 📝

Acá te dejo todo bien resumidito para que lo tengas a mano cuando lo necesites:

- **Verificar la rama actual**:
  ```bash
  git branch
  ```

- **Crear una nueva rama**:
  ```bash
  git branch pruebas_pepe
  ```

- **Cambiar de rama**:
  ```bash
  git checkout pruebas_pepe
  ```

- **Crear y cambiar a una nueva rama al mismo tiempo**:
  ```bash
  git checkout -b pruebas_pepe
  ```

- **Subir la nueva rama a GitHub (u otro repo remoto)**:
  ```bash
  git push origin pruebas_pepe
  ```

---

## ¿Por qué usar ramas? 🤔

Las ramas son lo mejor para:

- **Probar cosas nuevas** sin romper todo el proyecto principal(MAMA CORTASTE TODA LA LOOOS). No te arriesgás a hacer lío en el código de los demás.
- **Organizarte mejor**, ya que podés trabajar en cada cosa por separado y que no te de amsiedad.
- **Colaborar con otros**, porque cada uno trabaja en su rama sin pisarse, menos bardo. 🐥

---

## ¡Panchito dice: A practicar! 🐥🚀

Ahora que sabés cómo usar las ramas, ¡es hora de que te pongas a practicar! No tengas miedo de probar cosas nuevas. Git te cuida las espaldas, así que si algo no sale como esperabas, podés volver atrás sin problemas. ¡Vamos que se puede! 💪🐥🎉
