## 🧩 Historias de Usuario (simuladas)

**HU001** – Como usuario, quiero iniciar sesión para acceder a mi cuenta.  
**HU002** – Como usuario, quiero buscar productos para encontrarlos fácilmente.  
**HU003** – Como usuario, quiero agregar productos al carrito para comprarlos más tarde.

---

# 📝 Casos de Prueba

## CP001 – Login exitoso
**Precondición:** El usuario tiene una cuenta válida  
**Pasos:**  
1. Ingresar email y contraseña válidos  
2. Hacer clic en "Iniciar sesión"  
**Resultado esperado:** El usuario accede al sistema y visualiza su panel principal

---

## CP002 – Búsqueda de producto
**Precondición:** El sistema contiene productos registrados  
**Pasos:**  
1. Escribir "zapatillas" en el buscador  
2. Hacer clic en "Buscar"  
**Resultado esperado:** Se muestran productos relacionados a "zapatillas"

---

## CP003 – Agregar producto al carrito
**Precondición:** El usuario está logueado  
**Pasos:**  
1. Buscar un producto  
2. Hacer clic en "Agregar al carrito"  
**Resultado esperado:** El producto aparece en el resumen del carrito
