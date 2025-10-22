# 🧩 Práctica: Configuración del Editor en Eclipse
**Asignatura:** Entorno de Desarrollo  
**Repositorio:** `PROG-U2-PracticaEclipseEditor`  

---

## 🎯 Objetivo
Familiarizarse con las principales preferencias del editor Java en Eclipse: personalización visual, ayudas de escritura, acciones automáticas, plantillas y estilo del código.

Se han explorado distintas opciones del editor, documentando cada una con una breve explicación y su respectiva captura de pantalla.

---

## 📁 Estructura del repositorio

```
PROG-U2-PracticaEclipseEditor/
│
├── README.md
├── src/
│   └── Ejemplo.java
└── capturas/
    ├── 01_general.png
    ├── 02_save_actions.png
    ├── 03_content_assist.png
    ├── 04_syntax_coloring.png
    ├── 05_mark_occurrences.png
    ├── 06_typing.png
    └── 07_templates.png
```

---

## 💻 Código de ejemplo usado

```java
public class Ejemplo {
    public static void main(String[] args) {
        int x = 5;
        if (x < 10) {
            System.out.println("Valor menor que 10");
        }
    }
}
```

---

## 1️⃣ Opciones generales: **Matching Bracket**

📸 **Captura:**  
![Matching Bracket](capturas/01_general.png)

**Descripción:**  
La opción *Matching Bracket* resalta el par de llaves, paréntesis o corchetes correspondiente al que se encuentra el cursor.  

**Utilidad:**  
Ayuda a identificar fácilmente bloques de código, especialmente en estructuras anidadas, evitando errores de cierre y mejorando la legibilidad del código.

---

## 2️⃣ Save Actions

📸 **Captura:**  
![Save Actions](capturas/02_save_actions.png)

**Configuración aplicada:**  
- ✅ *Format source code*  
- ✅ *Organize imports*

**Explicación:**  
- *Format source code* → Aplica el formato automático definido (indentación, espacios, saltos de línea).  
- *Organize imports* → Elimina importaciones innecesarias y ordena las existentes.

**Efecto observado:**  
Al guardar con **Ctrl + S**, el código se reordena y formatea automáticamente, lo que mejora la consistencia y el estilo del proyecto.

---

## 3️⃣ Content Assist

📸 **Captura:**  
![Content Assist](capturas/03_content_assist.png)

**Configuración:**  
- *Auto activation delay (ms)* = **1000**

**Explicación:**  
Este parámetro controla el retardo (en milisegundos) antes de que aparezcan las sugerencias automáticas.  
- Con **1000 ms**, hay un leve retraso en mostrar las sugerencias.  
- Con **0 ms**, aparecen instantáneamente.  

**Utilidad:**  
*Content Assist* sugiere métodos, variables y clases mientras se escribe, acelerando la programación y reduciendo errores de escritura.

---

## 4️⃣ Syntax Coloring

📸 **Captura:**  
![Syntax Coloring](capturas/04_syntax_coloring.png)

**Cambios simulados:**  
- Comentarios → Color verde claro.  
- Palabras clave → Azul oscuro.  

**Explicación:**  
Un buen contraste visual entre los distintos elementos del código (comentarios, palabras clave, literales, etc.) mejora la legibilidad y reduce la fatiga visual durante sesiones prolongadas de trabajo.

---

## 5️⃣ Mark Occurrences

📸 **Captura:**  
![Mark Occurrences](capturas/05_mark_occurrences.png)

**Acción realizada:**  
Desactivado *Mark Occurrences* y se usó **Ctrl + Shift + U** sobre una variable.

**Diferencias:**  
- *Mark Occurrences* → Resalta automáticamente todas las apariciones del elemento seleccionado en el editor.  
- *Search References (Ctrl + Shift + U)* → Realiza una búsqueda manual y muestra los resultados en la vista *Search*, permitiendo navegar entre ellos.

**Utilidad:**  
Ideal para localizar el uso de variables o métodos y entender su alcance en proyectos grandes.

---

## 6️⃣ Typing

📸 **Captura:**  
![Typing](capturas/06_typing.png)

**Opciones activadas:**  
- Auto close brackets  
- Auto close strings  
- Auto close braces  

**Explicación:**  
Estas ayudas completan automáticamente paréntesis, comillas o llaves, reduciendo errores comunes de escritura y mejorando la velocidad al escribir código.

---

## 7️⃣ Templates

📸 **Captura:**  
![Templates](capturas/07_templates.png)

**Plantilla usada:** `sysout`

**Explicación:**  
Las *templates* son fragmentos de código predefinidos que pueden insertarse rápidamente con **Ctrl + Espacio**.  
Permiten escribir código repetitivo de forma instantánea, como `System.out.println()`.  

**Ruta:**  
`Window → Preferences → Java → Editor → Templates`

---

## 🧠 Conclusión

De todas las opciones configuradas, la que considero **más útil** es **Save Actions**, ya que automatiza tareas de formato y limpieza de imports al guardar.  
Esto mantiene el código limpio y uniforme sin esfuerzo, permitiendo centrarse en la lógica del programa en lugar de la presentación.

---

## 📘 Resultado final

Un repositorio organizado, con código funcional y capturas que muestran el dominio de las preferencias más relevantes del editor de Eclipse.
