# 📚 Actividad: Estructuras de Datos en Python  
## Conjuntos, Diccionarios, Pilas y Colas

Este proyecto muestra ejemplos prácticos del uso de **estructuras de datos fundamentales en Python**, incluyendo:

- **Conjuntos (`set`)**: para almacenar elementos únicos y realizar operaciones como pertenencia y eliminación de duplicados.
- **Diccionarios (`dict`)**: para manejar datos estructurados mediante pares clave-valor (ideal para representar objetos como estudiantes).
- **Pilas (`Stack`)**: implementadas con listas, siguiendo el principio **LIFO** (Last In, First Out).
- **Colas (`Queue`)**: implementadas con `collections.deque`, siguiendo el principio **FIFO** (First In, First Out), aplicadas en un sistema realista de gestión de pedidos.

---

## 🧪 Contenido del código

### 1. **Conjuntos**
- Creación de conjuntos a partir de listas y cadenas.
- Verificación rápida de pertenencia (`in`).
- Eliminación automática de duplicados.

### 2. **Diccionarios**
- Representación de estudiantes con atributos como nombre, edad, carrera y notas.
- Modificación y eliminación de claves.
- Verificación de existencia de claves (¡ojo! el ejemplo incluye un error común al verificar claves en una **lista de diccionarios**, no en un solo diccionario).

### 3. **Pilas (Stack)**
- Clase `Pila` con métodos:
  - `apilar()`
  - `desapilar()`
  - `ver_tope()`
  - `esta_vacia()`
  - `tamano()`
- Ejemplo práctico: **invertir una palabra** usando una pila.

### 4. **Colas (Queue)**
- Uso de `collections.deque` para eficiencia.
- Clase `SistemaPedidos` que simula un restaurante:
  - Agregar pedidos (entradas a la cola).
  - Procesar pedidos en orden (salidas desde el frente).
  - Mostrar estado del sistema (pendientes vs. completados).

---

## 📽️ Presentación

La actividad se explica en detalle en la siguiente presentación interactiva:

👉 **[Ver la presentación en Netlify]((https://pythoncd.netlify.app/))**

---

## 💾 Repositorio

Este código forma parte del repositorio oficial del curso:

🔗 **[github.com/feibertciin/SeguimientoPython](https://github.com/feibertciin/SeguimientoPython)**

### 🛠️ Cómo clonar el repositorio

Para obtener una copia local del proyecto, ejecuta en tu terminal:

```bash
git clone https://github.com/feibertciin/SeguimientoPython.git
