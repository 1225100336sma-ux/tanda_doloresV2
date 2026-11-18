# 💰 Tanda Doloreña (TDD)Sistema de ahorro rotativo vecinal desarrollado en Flutter aplicando Test-Driven Development (TDD).

# 📸 Evidencias de Ejecución
1. Pruebas Automatizadas (flutter test)
## Evidencia de TDD (ciclo Rojo → Verde por ronda)

En cada ronda se escribe primero la prueba, se ve fallar (rojo), se implementa lo mínimo para que pase (verde) y después se mejora el código. El rojo de cada captura es una demostración del ciclo sobre el código ya terminado: se retira `servicio_tanda.dart` para que la prueba falle y luego se restaura.

### Ronda 1: Registrar una aportación válida
**Rojo:**

![Ronda 1 rojo](assets/ronda1_rojo.png)

**Verde:**

![Ronda 1 verde](assets/ronda1_verde.png)

### Ronda 2: Rechazar una aportación repetida
**Rojo:**

![Ronda 2 rojo](assets/ronda2_rojo.png)

**Verde:**

![Ronda 2 verde](assets/ronda2_verde.png)

### Ronda 3: Rechazar aportaciones de quien no es participante
**Rojo:**

![Ronda 3 rojo](assets/ronda3_rojo.png)

**Verde:**

![Ronda 3 verde](assets/ronda3_verde.png)

### Ronda 4: Detectar cuándo todos ya aportaron
**Rojo:**

![Ronda 4 rojo](assets/ronda4_rojo.png)

**Verde:**

![Ronda 4 verde](assets/ronda4_verde.png)

### Ronda 5: Cerrar la ronda y entregar el turno
**Rojo:**

![Ronda 5 rojo](assets/ronda5_rojo.png)

**Verde:**

![Ronda 5 verde](assets/ronda5_verde.png)

### Ronda 6: No cerrar la ronda si faltan aportaciones
**Rojo:**

![Ronda 6 rojo](assets/ronda6_rojo.png)

**Verde:**

![Ronda 6 verde](assets/ronda6_verde.png)

### Ronda 7: Detectar cuándo la tanda ha terminado
**Rojo:**

![Ronda 7 rojo](assets/ronda7_rojo.png)

**Verde:**

![Ronda 7 verde](assets/ronda7_verde.png)

### Ronda 8: Refactor
En esta ronda no se agregan pruebas: se nombran las condiciones como reglas de negocio y las pruebas siguen en verde.

![Ronda 8 refactor verde](assets/ronda8_refactor_verde.png)

### Ronda 9: Prueba de integración (tanda completa)
**Rojo:**

![Ronda 9 rojo](assets/ronda9_rojo.png)

**Verde:**

![Ronda 9 verde](assets/ronda9_verde.png)

### Resultado final: todas las pruebas pasando
![Todas las pruebas](assets/final_todas_verde.png)


2. Aplicación en Funcionamiento (flutter run)
### Pantalla Principal
![Pantalla principal](assets/pantalla1.png)
### Entrega de Turno (Animación)
![Pantalla turno](assets/pantalla2.png)
