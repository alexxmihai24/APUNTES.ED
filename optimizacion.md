#### **4️⃣ Rama OPTIMIZACION** (`optimizacion/optimizacion.md`)
```markdown
# Optimización de código - Alexandru Mihai

## 🚩 Code Smells
```java
// Antes (redundante)
if (edad >= 18) {
    return true;
} else {
    return false;
}

// Después (optimizado)
return edad >= 18;