# 💻 Actividad Frontend

Este repositorio contiene la estructura de trabajo para el desarrollo de una propuesta en HTML basada en un diseño de Figma. Se ha organizado en varias ramas para que cada miembro del equipo pueda trabajar de manera independiente y luego fusionar sus cambios en una rama final.

## 📚 Estructura del Repositorio

El repositorio sigue el siguiente esquema de ramas:

- `dev-paviag` → Rama de desarrollo de **paviag**.
- `dev-JeanC221` → Rama de desarrollo de **JeanC221**.
- `dev-LofoMarin` → Rama de desarrollo de **LofoMarin**.
- `final` → Rama de integración donde se fusionan todas las contribuciones.
- `main` → Rama principal con la versión final estable.

## ⚙️ Pasos Realizados

### 1. Creación del repositorio

Se creó el repositorio en GitHub llamado **actividad-frontend** y se inicializó con un README.

### 2. Clonación del repositorio

Cada miembro del equipo clona el repositorio con:

```sh
git clone https://github.com/TU_USUARIO/actividad-frontend.git
cd actividad-frontend
```

### 3. Creación de ramas de desarrollo

Se crearon las siguientes ramas para cada miembro:

```sh
git checkout -b dev-paviag
git push origin dev-paviag

git checkout -b dev-JeanC221
git push origin dev-JeanC221

git checkout -b dev-LofoMarin
git push origin dev-LofoMarin
```

### 4. Cada usuario trabaja en su branch

Cada miembro del equipo desarrolla su parte en su respectiva rama y sube los cambios con:

```sh
git add .
git commit -m "Subiendo propuesta HTML"
git push origin dev-suusuario
```

### 5. Creación de la rama `final`

Se creó una rama `final` para integrar todos los cambios:

```sh
git checkout -b final
git push origin final
```

### 6. Validación y fusión a `main`

Si todo está correcto en `final`, se hace merge con `main`:

```sh
git checkout main
git merge final
git push origin main
```

---

## 🛠️ Lo que hay que hacer

1. **Cada miembro trabaja en su rama** (`dev-paviag`, `dev-JeanC221`, `dev-LofoMarin`) y sube sus cambios.
2. **Mergear todo en la rama `final`** para integración y prueba.
3. **Probar el proyecto** en la rama `final`.
4. **Fusionar `final` con `main`** para tener la versión final estable.

---

## 🌟 Buenas Prácticas

- **Commits claros:** Utilizar mensajes descriptivos en los commits.
- **Trabajo en ramas:** No trabajar directamente en `main`.
- **Revisar código antes de mergear:** Asegurar que el código cumpla con los estándares antes de hacer un PR.
