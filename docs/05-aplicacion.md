# Ejercicio 5: Aplicación con Interfaz Gráfica

## Respuestas Analíticas

1. **¿Cuántos prefijos tiene una cadena de longitud \(n\)?**
   Una cadena de longitud \(n\) tiene exactamente **\(n + 1\)** prefijos. Esto se debe a que se cuentan las subcadenas desde la posición inicial $0$ hasta la longitud \(i\) para cada \(i \in \{0, 1, \dots, n\}\), incluyendo la cadena vacía \(\lambda\).

2. **¿Cuántas subcadenas distintas puede tener como máximo una cadena de longitud \(n\)?**
   Como máximo puede tener **\(\frac{n(n + 1)}{2} + 1\)** subcadenas distintas. Este valor máximo se alcanza cuando todos los símbolos de la cadena son distintos entre sí.

3. **Inclusión de la cadena vacía en prefijos y sufijos:**
   La cadena vacía (\(\lambda\)) **sí figura** entre los prefijos y los sufijos. Se adopta la convención formal donde para cualquier cadena \(w \in \Sigma^*\), se cumple que \(\lambda \cdot w = w \cdot \lambda = w\).

4. **Relación entre el límite de 200,000 cadenas y los conceptos de la unidad:**
   El número total de cadenas en un alfabeto de \(k\) símbolos para longitudes menores o iguales a \(n\) está dado por la suma geométrica: