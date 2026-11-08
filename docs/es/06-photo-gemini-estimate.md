# 6. Foto de comida: estimación con Gemini

Gemini estima la comida a partir de la foto: nombre, gramos, calorías y macros.

**Requisitos:** Una clave de API de Gemini introducida en Ajustes (ver escenario 10) y tu acuerdo para enviar fotos. Mientras haya una clave, la foto se envía a Google en cada captura.

## Pasos

1. Fotografía la comida o elige una foto. La primera vez, una alerta pregunta **¿Enviar a Google Gemini?**; léela y toca **Aceptar y continuar**. Con **Ahora no** no se envía nada.

2. Tras unos segundos la estimación de Gemini aparece bajo la foto, una tarjeta por comida con sus ingredientes.

   ![Foto de comida: estimación con Gemini – 2](../../media/06-photo-gemini-estimate/en-01-estimate.png)

3. Toca el **Añadir** verde de una tarjeta. La entrada va a la comida elegida como estimación, con la foto. La estrella guarda el plato como favorito.

## Resultado

Las estimaciones son aproximadas. Si algo no cuadra, corrígelo con el siguiente escenario. Sin clave, la foto solo recibe las etiquetas del dispositivo.

---

[← Anterior](05-photo-offline-labels.md) · [Volver al contenido](../../README.es.md#contenido) · [Siguiente →](07-edit-estimate-add-all.md)
