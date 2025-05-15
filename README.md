# calculator-top
calculator-top

App para construir una calculadora como proyecto final de TOP foundations de HTML, CSS y Javascript.

## ✅ Hecho
- [x] Crear funciones básicas: `add`, `subtract`, `multiply`, `divide`.
- [x] Crear función `operate(operator, a, b)`.
- [x] Estructurar HTML base con botones y display.

---

## 🛠️ Por hacer

### 🧠 Lógica básica
- [ ] Crear variables para:
  - Primer número (`firstOperand`)
  - Segundo número (`secondOperand`)
  - Operador (`currentOperator`)
  - Estado de reinicio (`shouldResetDisplay`)
- [ ] Manejar click en números:
  - Agregar dígitos al display.
  - Reemplazar display si `shouldResetDisplay` es `true`.
- [ ] Manejar click en operadores:
  - Guardar `firstOperand` y `currentOperator`.
  - Establecer `shouldResetDisplay` en `true`.

### ➕ Botón igual (=)
- [ ] Calcular el resultado con `operate`.
- [ ] Mostrar el resultado en el display.
- [ ] Redondear si hay muchos decimales.
- [ ] Preparar el resultado como nuevo `firstOperand`.

### 🔁 Control de flujo
- [ ] Evitar evaluación si no hay dos operandos.
- [ ] Evitar evaluación si se presionan operadores consecutivos.
- [ ] Si se presiona un número después del resultado, reiniciar display.

### 🔢 Funcionalidad adicional
- [ ] Botón `clear`: reiniciar todos los valores y el display.
- [ ] Botón `backspace`: eliminar el último dígito del display.
- [ ] Botón `.` para números decimales:
  - Evitar múltiples puntos en el mismo número.

### 🧰 Mejora UX/UI
- [ ] Mostrar mensaje divertido en caso de división por 0 (“Nope!”).
- [ ] Limitar largo del número en el display para evitar overflow.
- [ ] Agregar soporte de teclado (opcional avanzado).