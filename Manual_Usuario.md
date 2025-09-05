

---

## 📑 Portada  
**Sistema de Gestión de Usuarios y Tareas**  
Manual de Usuario  


---

## 📑 Título  
**Manual de Usuario del Sistema de Gestión de Usuarios y Tareas**  

---

## 🔹 Introducción  
Este sistema permite gestionar usuarios y tareas internas de la organización.  
El usuario podrá:  
- Registrar, editar y eliminar usuarios.  
- Registrar, editar y eliminar tareas.  
- Consultar la información almacenada.  
- Filtrar tareas por usuario y prioridad.  
- Generar un resumen de tareas por usuario.  

Su finalidad es **optimizar la administración de actividades**, reduciendo errores y facilitando el acceso a la información.  

---

## 🎯 Objetivos  

### Objetivo general  
Brindar a los usuarios una herramienta sencilla y funcional para gestionar usuarios y tareas dentro de la organización.  

### Objetivos específicos  
- Permitir el registro y administración de usuarios.  
- Controlar el ciclo de vida de las tareas.  
- Facilitar la consulta, filtrado y resumen de la información.  
- Ofrecer un sistema fácil de instalar y utilizar.  

---

## 🖥️ Requisitos de instalación  

### Hardware  
- Procesador: Intel i3 o superior.  
- Memoria RAM: 4 GB mínimo.  
- Espacio en disco: 200 MB libres.  

### Software  
- Sistema operativo: Windows 10 o superior.  
- Archivo ejecutable: `main.exe` generado con PyInstaller.  
- Base de datos: SQLite (archivo `tareas.db`, incluido en la entrega).  

---

## ⚙️ Instalación y configuración  

1. Copia la carpeta del sistema a tu computadora.  
2. Asegúrate de que el archivo `main.exe` y la base de datos `tareas.db` estén en la misma carpeta.  
3. Haz doble clic en `main.exe` para iniciar el sistema.  
4. (Opcional) Crea un acceso directo en el escritorio para mayor comodidad.  

---

## 📝 Guía de uso de funciones básicas  

### 1. Registrar un usuario  
1. Ingresa el **nombre** y **correo electrónico**.  
2. Haz clic en **Registrar Usuario**.  
3. El sistema confirmará que el usuario fue agregado.
<img width="278" height="277" alt="image" src="https://github.com/user-attachments/assets/452984e8-6b20-47cb-92a3-9ce0c6a69ec4" />


### 2. Registrar una tarea  
1. Ingresa **título, descripción, prioridad** e **ID de usuario asignado**.  
2. Haz clic en **Registrar Tarea**.  
3. La tarea se guardará en la base de datos.
<img width="293" height="432" alt="image" src="https://github.com/user-attachments/assets/cf03bbd0-b6cd-4d04-92a9-882d541f74a6" />


### 3. Consultar tareas  
1. Haz clic en **Mostrar todas las tareas**.  
2. Se desplegará la lista de tareas con ID, título, prioridad y usuario asignado.  
<img width="198" height="37" alt="image" src="https://github.com/user-attachments/assets/c2b63210-54ab-4ce9-b30a-3dd415faa1ca" />

### 4. Editar y eliminar  
- Para **editar**, selecciona el botón correspondiente, ingresa el ID y los nuevos datos.  
- Para **eliminar**, selecciona el botón correspondiente, ingresa el ID y confirma la acción.
  <img width="153" height="88" alt="image" src="https://github.com/user-attachments/assets/3e02902d-f4cd-42b2-8cd2-4af7bc7d1270" />


### 5. Resumen de tareas  
Haz clic en **Resumen de Tareas por Usuario** para ver cuántas tareas tiene cada usuario.  
<img width="816" height="356" alt="image" src="https://github.com/user-attachments/assets/a4544fc7-56ea-4d0b-a59a-8e5d696414ea" />

---

## 📖 Glosario  

- **Base de datos (SQLite):** archivo donde se guarda toda la información del sistema.  
- **Registro:** conjunto de datos almacenados (ejemplo: un usuario o una tarea).  
- **ID:** número único que identifica a cada usuario o tarea.  
- **Ejecutable (.exe):** archivo que permite abrir el sistema sin necesidad de usar código.  

---



