#  Comandos básicos de Git y GitHub  

Este documento reúne los comandos más importantes para trabajar con **Git** y **GitHub**, usados durante el proyecto colaborativo.  

---

## Configuración inicial  

```bash
# Configurar nombre de usuario
git config --global user.name "TuNombre"

# Configurar correo (debe ser el mismo que en GitHub)
git config --global user.email "tuemail@example.com"

# Verificar configuración
git config --list

#cambiar editor por defecto (Ej:visual studio code)
git config --global core.editor "code --wait"

#abrir configuracion por defecto en el editor por defecto 
code ~/.gitconfig
```

---

## Flujo básico de trabajo  

```bash
# Clonar un repositorio existente desde GitHub
git clone https://github.com/usuario/repositorio.git

# Verificar estado de los archivos (cambios pendientes)
git status

# Agregar archivos específicos al área de preparación
git add nombre-archivo

# Agregar todos los archivos modificados
git add .

# Guardar cambios en un commit con un mensaje
git commit -m "Descripción clara del cambio"

# Enviar los cambios al repositorio remoto (GitHub)
git push origin main
```

---

## Actualizar el repositorio local  

```bash
# Descargar los últimos cambios de GitHub
git pull origin main
```
---

---

## 🔹 Ramas (Branches)  

```bash
# Combinar cambios de una rama a otra (ej. main)
git merge nombre-rama
# Cambiar a una rama existente
git checkout nombre-rama
# Crear y cambiar a la vez
git checkout -b nombre-rama
# Crear una nueva rama
git branch nombre-rama
```
---

---

## Buenas prácticas  

✅ Hacer **commits pequeños y descriptivos**.  
✅ Usar ramas para nuevas funcionalidades.  
✅ Ejecutar `git pull` antes de empezar a trabajar.  
✅ Verificar siempre con `git status`.  
✅ Todos los integrantes deben hacer **al menos un commit y un push**.  

---

✍️ **Equipo de desarrollo**  
Cada integrante debe agregar su nombre aquí una vez haga su primer commit.  

- [ Heidy vivas]  
- [Valeria Gamboa ] 
- [ Saira Yineth] 
