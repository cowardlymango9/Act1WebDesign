# Application Web Design

## Datos personales:
- **Nombre:** [Kenia Gisel Carrillo Cocom]
- **Matrícula:** [2752452]
- **Titulación:** Ingeniería en Desarrollo de Software
- **Semestre:** sexto

## Datos de la asignatura:
- **Nombre:** [Diseño de Aplicaciones Web]
- **Profesor:** [Jose Antonio León Borges]

## ¿Qué es Markdown?
Markdown es un lenguaje de marcado ligero que permite formatear texto de manera sencilla utilizando caracteres especiales. Se usa en documentación, archivos README y más.

---

## 🏷️ Markdown Tagging Options  
Aquí hay algunas etiquetas comunes en Markdown:  

### **Encabezados**  
```md
# Título 1
## Título 2
### Título 3

**Texto en negritas**  
*Texto en cursiva*  
~~Texto tachado~~  

- Elemento de lista  
- Otro elemento  

1. Elemento numerado  
2. Otro elemento numerado  

`Código en línea`

# Código en bloque con sintaxis resaltada
echo "Hola Mundo"

## Opciones de Etiquetado en Markdown
Algunas etiquetas y su uso:

| Elemento     | Markdown         | Ejemplo Resultado |
|-------------|-----------------|------------------|
| Negrita     | `**Texto**`     | **Texto**       |
| Cursiva     | `*Texto*`       | *Texto*         |
| Encabezado  | `# Título`      | # Título        |
| Lista       | `- Item`        | - Item          |
| Código      | `` `código` ``  | `código`        |
| Enlace      | `[texto](url)`  | [GitHub](https://github.com) |

## Comandos Git Usados

### 📌 Revisión del estado del repositorio

git status
Muestra los cambios en archivos y el estado del repositorio.

### 📌 Agregar archivos al "Stage"

git add archivo.txt # Agregar un solo archivo
git add . # Agregar todos los archivos

Incluye los cambios en el área de "Stage" para ser confirmados.

### 📌 Hacer un commit con un mensaje

git commit -m "Descripción del cambio realizado"

Registra los cambios en el historial del repositorio.

### 📌 Subir cambios al repositorio remoto

Registra los cambios en el historial del repositorio.

### 📌 Subir cambios al repositorio remoto

git push origin main

Envía los cambios de la rama `main` a GitHub.

### 📌 Administrar ramas en Git

git branch # Listar ramas
git checkout -b nueva_rama # Crear y cambiar a una nueva rama
git branch -d rama # Eliminar una rama local
git push origin --delete rama # Eliminar una rama remota

### 📌 Revertir cambios en el repositorio

git reset --hard HEAD~1 # Deshacer el último commit sin dejar rastro
git revert HEAD # Deshacer el último commit pero manteniendo un registro
git checkout archivo.txt # Restaurar un archivo a su última versión committeada





