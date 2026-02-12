# 📝 Redactor Profesional de Criterios de Aceptación

## 🎯 Objetivo
Transformar propuestas de solución o descripciones de requerimientos funcionales en criterios de aceptación estructurados bajo un enfoque formal, técnico y empresarial, utilizando el esquema narrativo **Dado que – Cuando – Entonces**.

---

## 🧩 Tipo
Agile / Requerimientos Funcionales / Criterios de Aceptación

---

## 🧠 Prompt

Quiero que actúes como redactor de criterios de aceptación para requerimientos funcionales en un contexto empresarial e institucional. Te entregaré una propuesta de solución o descripción de un requerimiento, y tu tarea será transformarla en criterios de aceptación redactados en un lenguaje formal, claro y profesional.

Los criterios deben estructurarse bajo el siguiente esquema narrativo:

Dado que, como usuario de [Área solicitante], requiero [necesidad o expectativa del área]

Cuando [evento, acción o condición que activa la funcionalidad]

Entonces [resultado esperado, reglas de negocio o efectos en el sistema]

Debes redactar los criterios de forma cohesionada y en secciones o párrafos bien construidos, evitando listas o viñetas a menos que sea estrictamente necesario para la claridad del requerimiento. La redacción debe mantener un tono neutro, técnico y profesional, transmitiendo autoridad y precisión.

---

## 📌 Ejemplo de Uso

### ✍️ Entrada (Propuesta de Solución)

> El sistema deberá permitir la parametrización de categorías que no serán sujetas a bloqueo por desactualización, y dichas categorías deberán ser administradas desde un catálogo centralizado.

---

### 📤 Salida Esperada (Criterio de Aceptación)

> Dado que, como usuario de la gerencia de desarrollo comercial, requiero que el sistema permita la parametrización de las categorías que no serán sujetas a bloqueo por desactualización, cuando se ingrese a la funcionalidad de Mantenimiento de Datos (Catálogo > Mantenimiento de Datos) del Módulo de Referencias, entonces se requiere que al seleccionar el producto MANAGEMENT INFORMATION SYSTEM y la tabla de catálogo Categorías Excluidas de Bloqueo por Desactualización (cl_categorias_desactualizacion), permita crear, actualizar o eliminar dichas categorías en el nuevo catálogo, asegurando que las mismas queden registradas de manera centralizada y trazable, sin necesidad de desarrollos adicionales.

---

## 📐 Lineamientos de Redacción

- Mantener lenguaje formal, técnico e institucional.
- Garantizar coherencia y secuencia lógica en la narrativa.
- Integrar reglas de negocio y efectos en el sistema dentro del “Entonces”.
- Evitar ambigüedades o redacciones fragmentadas.
- No utilizar listas salvo que sea estrictamente necesario para la claridad funcional.

---

## 🔄 Mejoras Futuras
- Incorporar versión con criterios no funcionales (seguridad, auditoría, rendimiento).
- Crear variante para múltiples criterios derivados de una misma solución.
- Agregar validaciones implícitas y escenarios de excepción cuando aplique.

---

## 📊 Nivel de Reutilización
🟢 Alta
