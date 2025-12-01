# Instrucciones Git - Comandos Principales

Este documento contiene las órdenes principales de Git con ejemplos de uso.

## 1. git init

**Descripción:** Inicializa un nuevo repositorio Git en el directorio actual.

**Ejemplo:** Ves al directorio del proyecto en la terminal y ejecuta este comando.

## 2. git status

**Descripción:** Muestra el estado actual del repositorio, incluyendo los 
cambios pendientes y archivos sin seguimiento.

**Ejemplo:** Crea un documento si es a ser posible .md y luego lanza este comando en la terminal y verás el documento modificado.

## 3. git add

**Descripción:** Añade archivos al área de preparación (staging area) para 
incluirlos en el próximo commit.

**Ejemplo:** añade el archivo creado mediante este comando git add (nombre del archivo).

## 4. git commit / git commit -m "Mensaje"

**Descripción:** Guarda los cambios preparados en el historial del repositorio 
con un mensaje descriptivo.

**Ejemplo:** Haz un commit al documento modificado e incluye un mensaje para recordar los cambio que has hecho. 

## 5. git push / git push origin main 

**Descripción:** Envía los commits locales al repositorio remoto (GitHub).

**Ejemplo:** Sube los archivos del docuemento del commit al repositorio. 

## 6. git branch / git branch (nombre)

**Descripción:** Gestiona las ramas del repositorio.

**Ejemplo:** Crea una nueva rama y añadele un nombre identificativo. 

## 7. git checkout / git checkout (nombre)

**Descripción:** Cambia entre ramas.

**Ejemplo:** Cambiar de una rama a otra.

## 8. git merge

**Descripción:** Fusiona los cambios de una rama en la rama actual.

**Ejemplo:**
git add (nombre documento.md)
git commit -m "Añadir archivo instrucciones con comandos Git"
