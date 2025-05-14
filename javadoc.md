
#### **3️⃣ Rama JAVADOC** (`javadoc/javadoc.md`)
```markdown
# Documentación con Javadoc - Alexandru Mihai

## 📌 Sintaxis
```java
/**
 * Calcula el IVA de un producto.
 * @param precio Precio sin IVA (double)
 * @return Precio con IVA (double)
 */
public double calcularIVA(double precio) {
    return precio * 1.21;
}

Generar documentación

javadoc -d docs -encoding UTF-8 MiClase.java