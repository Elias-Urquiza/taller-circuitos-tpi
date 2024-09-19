# Proyecto Integrador del Taller de Circuitos Electrónicos

TP de tomi,nacho,elias y vero.

## 🐥 Git Branching: Guía Rápida con Panchito el Pollito 🐥

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

### 7. Cambiar a una rama existente y subirla

1. **Cambiar a una rama existente:**
   ```bash
   git checkout nombre-de-la-rama
   ```

2. **Subir la rama al repositorio remoto si aún no está allí:**
   ```bash
   git push origin nombre-de-la-rama
   ```

### 8. Sincronizar una rama con `origin`

1. **Obtener los cambios del repositorio remoto:**
   ```bash
   git fetch origin
   ```

2. **Fusionar los cambios del repositorio remoto con tu rama local:**
   ```bash
   git merge origin/nombre-de-la-rama
   ```

   O, para actualizar tu rama local con los cambios remotos sin hacer un merge, puedes usar:
   ```bash
   git pull origin nombre-de-la-rama
   ```

### 9. Eliminar una rama en `origin`

1. **Eliminar una rama remota:**
   ```bash
   git push origin --delete nombre-de-la-rama
   ```

### 10. Ver ramas en `origin`

1. **Ver todas las ramas remotas:**
   ```bash
   git branch -r
   ```

2. **Ver todas las ramas locales y remotas:**
   ```bash
   git branch -a
   ```

### 11. Configurar el "upstream" de la rama

Si ves un mensaje que te indica que la rama no tiene un "upstream" configurado, usá este comando para empujar la rama y, al mismo tiempo, configurarla para que se conecte automáticamente con el repositorio remoto en futuras ocasiones:

```bash
git push --set-upstream origin nombre-de-la-rama
```

### ¿Qué hace este comando?

1. `git push`: Empuja los cambios al repositorio remoto.
2. `--set-upstream`: Configura la rama actual para que se conecte con la rama del mismo nombre en el repositorio remoto (en tu caso, `origin`).
3. `origin nombre-de-la-rama`: Le dice a Git que esta rama debe asociarse con la rama del mismo nombre en el repositorio remoto `origin`.

De ahora en más, cuando estés en la rama `nombre-de-la-rama`, podés usar simplemente `git push` sin tener que configurar el upstream de nuevo. ¡Listo!

---
<img src="miscellanea/panchito.jpeg" alt="Descripción de la imagen" width="300"/>

## ¡Panchito dice: A practicar! 🐥🚀

Ahora que sabés cómo usar las ramas, ¡es hora de que te pongas a practicar! No tengas miedo de probar cosas nuevas. 
Git te cuida las espaldas, así que si algo no sale como esperabas, podés volver atrás sin problemas. ¡Vamos que se puede! 💪🐥🎉
