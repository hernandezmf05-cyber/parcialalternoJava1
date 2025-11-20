# 👕 Gestor de Prendas Java

¡Bienvenido al repositorio del **Gestor de Prendas en Java**! 📝 Este proyecto es una aplicación de consola que permite almacenar, visualizar y gestionar prendas en un inventario simple.

---

## 📌 Descripción del Proyecto

Este proyecto consiste en una **app de consola** donde el usuario puede:

- Registrar prendas con nombre, talla y precio.  
- Mostrar el inventario de prendas registrado.  
- Manejar un login básico para acceder al sistema.  

El código ha sido **mejorado y corregido** para asegurar su funcionamiento sin errores de sintaxis y con buenas prácticas de programación. 💻

---

## 🔧 Mejoras Realizadas

Durante la revisión del código original, se realizaron las siguientes mejoras:

1. ✅ **Corrección de errores de sintaxis:**  
   - Se revisó la estructura general del código y se eliminaron errores que impedían la compilación.
   
2. 🖊️ **Renombramiento de variables:**  
   - Se cambiaron nombres de variables poco claros a nombres más descriptivos, por ejemplo:
     - `productoUno` → `prenda`
     - `estudiante` → `inventario`  
   Esto mejora la legibilidad y mantenibilidad del código.

3. 🔁 **Uso de `for-each` en la impresión del inventario:**  
   - Antes se podía haber usado un `for` tradicional, pero ahora se recorre la lista de prendas con un **`for-each`**, lo que simplifica el código y evita errores de índice.

4. ⚡ **Manejo de excepciones:**  
   - Se implementaron bloques `try-catch` para capturar entradas inválidas (como letras donde se espera un número) y evitar que la app se caiga.  

5. 🎨 **Mejoras en la presentación de la consola:**  
   - Se añadieron colores (rojo, verde y amarillo) para diferenciar mensajes de error, éxito e información.  
   - Se ajustaron los nombres de las prendas para que tengan un formato uniforme al mostrarse en pantalla.

---

## 🖥️ Funcionalidades

1. **Login del usuario**  
   - Verifica nombre, correo y contraseña antes de permitir el acceso.

2. **Agregar prenda al inventario**  
   - Solicita nombre, talla y precio de la prenda.  
   - Valida que el precio sea un número entero.  

3. **Mostrar inventario**  
   - Muestra una lista formateada de las prendas registradas usando `for-each`.  

4. **Salir del sistema**  
   - Permite finalizar la ejecución de manera segura.  

---

## ⚡ Tecnologías Utilizadas

- Java 11+
- Estructuras de datos: `ArrayList` y `HashMap`
- Manejo de excepciones con `try-catch`
- Scanner para entrada por consola

---

## 🛠️ Mejoras Futuras

- Persistencia real en una base de datos (actualmente los datos se pierden al cerrar la app)  
- Implementación de validaciones más robustas (correo, contraseña fuerte)  
- Interfaz gráfica opcional con JavaFX o Swing  

---

## 🎯 Notas del Proyecto

Este proyecto es ideal para **practicar manejo de listas y diccionarios en Java**, uso de bucles `for-each`, manejo de excepciones y buenas prácticas de nombramiento de variables.  

---

## 📌 Autor

👤 **Mafer** – Programadora Java | GitHub: MaFernandaDev_15




