# Práctica de commits — Git · ENP6 UNAM

Cada nivel te pide un cambio concreto en este archivo.  
Edita → `git add practica-commits.md` → `git commit -m "..."`

---

## Nivel 1 · Preséntate

**Qué hacer:** Llena los campos con tus datos.  
**Commit:** `feat(perfil): agrega presentación de [tu nombre]`

```
Nombre     : Gael
GitHub     : Gaelzon
Algo sobre mí : Me gusta todo lo relacionado a la electrónica y tengo una banda de rock
```

---

## Nivel 2 · Lo que ya sabes hacer

**Qué hacer:** Agrega al menos tres cosas que sabes hacer (no tienen que ser de programación).  
**Commit:** `feat(habilidades): agrega lista de habilidades`

- Toco la guitarra y compongo musica
- Tengo algo de habilidad motriz fina
- Se soldar
- Aprendo con facilidad temas relacionados a matemáticas

---

## Nivel 3 · Corrige los errores

**Qué hacer:** El párrafo de abajo tiene **cuatro errores**. Corrígelos todos en un solo commit.  
**Commit:** `fix(convenciones): corrige errores en descripción de Git`

> Git es un sistema de control de versiones creado en 2005 por Linus Torvalds
> para reemplazar a BitKeeper, que era de licencia y dejó de darse gratis al proyecto Linux.
> Cada commit guarda una fotografía de todos los archivos del repositorio en ese momento,
> identificada con un hash SHA-1 único. Para subir cambios al servidor usamos `git push`.

---

## Nivel 4 · Qué aprendí hoy

**Qué hacer:** Escribe tres cosas concretas que aprendiste en esta sesión.  
**Commit:** `docs(aprendizaje): agrega notas de la sesión`

1. La historia del origen de git, creado por el mismo creador de linux (Linus Traveus) y con motivaciones similares a la creación de linux
2. Que la rama main era antes llamada master, y se cambio por razones historicas controversiales
3. Que al iniciar un repo localmente me manda a master xd

---

## Nivel 5 · Tabla de comandos

**Qué hacer:** Completa las celdas vacías de la tabla.  
**Commit:** `docs(comandos): completa tabla de referencia`

| Comando | ¿Qué hace? |
|---------|------------|
| `git init` | | Inicia un repositorio local en la carpeta actual
| `git status` | | Muestra el rastro de los archivos (staging area)
| `git add .` | | Inicia con el rastro de un archivo modificado o creado
| `git commit -m "..."` | | Agrega un commit con el mensaje entre comillas
| `git log --oneline` | | Muestra el historial de commits y sus nombres
| `git push` | | Manda los commits realizados al repositorio remoto

---

## Nivel 6 · Marca tu avance

**Qué hacer:** Cambia `[ ]` por `[x]` en cada punto que ya dominas.  
**Commit:** `chore(practica): actualiza checklist de avance`

- [x] Hice `git init` sin ayuda
- [x] Entiendo para qué sirve el Staging Area
- [ ] Escribí un mensaje de commit con formato Conventional Commits
- [x] Puedo ver el historial con `git log`
- [x] Completé todos los niveles de esta práctica

---

## Referencia rápida

| Tipo | Cuándo |
|------|--------|
| `feat` | Agrego algo nuevo |
| `fix` | Corrijo un error |
| `docs` | Solo toco documentación o notas |
| `style` | Formato, sin cambiar contenido |
| `refactor` | Reorganizo sin cambiar el resultado |
| `chore` | Tareas de mantenimiento |
