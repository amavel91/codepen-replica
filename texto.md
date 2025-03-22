# I. Condicionales

En Python, las sentencias `if`, `else` y `elif` permiten que un programa tome decisiones, ejecutando ciertas instrucciones solo si se cumplen determinadas condiciones. Este tipo de lógica es fundamental donde muchas acciones dependen de los valores y resultados que se están procesando.

En la vida diaria, las personas toman decisiones constantemente: **si llueve, se usa paraguas; si hace frío, se usa abrigo**. En la programación sucede algo similar: los programas deben "decidir" qué hacer en función de ciertas condiciones.

Estas decisiones se manejan con **sentencias condicionales**, que en Python tienen varias formas: `if`, `if-else`, `if` anidado e `if-elif-else`. (DataScientest, s.f.).

---

## 1.1. Funcionamiento de la sentencia `if`

La sentencia `if` permite ejecutar un bloque de código únicamente si una condición es verdadera. Se escribe la palabra `if`, seguida de la condición, y debajo el bloque de código que debe ejecutarse si esa condición se cumple.  
**Ejemplo:**

```python
if edad > 18:
    print("Acceso permitido")
