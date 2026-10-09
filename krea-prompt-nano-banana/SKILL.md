---
name: krea-prompt-nano-banana
description: Prompts de imagen ultrarrealistas para Nano Banana con el método de Krea (4:5, en inglés, look de foto de smartphone real). Usar cuando se pida un prompt de imagen, se mande una imagen de referencia o se quiera poner a una persona propia (character sheet) en una escena.
---

# Krea · Prompt para Nano Banana

Skill creada por Krea (@krea_uy), agencia de contenido con IA para marcas.
Convierte una idea, una imagen de referencia o una escena con tus propios personajes en un prompt listo para pegar en Nano Banana. **No genera la imagen: entrega solo el prompt.**

## Reglas fijas (aplicar siempre)

1. **Idioma:** el prompt final va siempre en inglés. La conversación con el usuario, en su idioma.
2. **Formato:** siempre 4:5 (vertical), salvo que el usuario pida otro explícitamente.
3. **Ultrarrealismo:** tiene que parecer una foto real, nunca un render. Incluir siempre rasgos de cámara de smartphone real: grano sutil, ligera compresión óptica, piel con textura natural (poros visibles), rango dinámico de celular y una nitidez natural, no perfecta.
4. **Atractivo antes que imperfección:** realismo sí, pero la persona tiene que verse atractiva y con una expresión agradable. No acumular imperfecciones (nada de granos, asimetrías marcadas ni ojos entrecerrados a propósito). Como máximo, uno o dos detalles naturales y sutiles.
5. **Caras nuevas:** si la referencia tiene modelos, cambiar la cara por una persona nueva e inventada, con rasgos distintos, para no usar a una persona real. Mantener el ultrarrealismo.
6. **La referencia es solo una base:** mantener la idea, la escena y el mood, pero variar algo: otra modelo, otra pose, otro detalle de vestuario o de encuadre. Nunca replicarla al 100%.
7. **Respetar la cámara original:** si la referencia es de cámara vieja (analógica, digital de los 2000, camcorder, flash directo), mantener ese look y no modernizarlo.
8. **Calidad máxima:** pedir siempre la mejor calidad posible (highly detailed, sharp focus where intended, natural color science).

## Modos de trabajo

### A) Imagen de referencia
El usuario manda una foto de inspiración. Analizarla (sujeto, escena, luz, cámara, encuadre, paleta) y escribir un prompt que describa la escena completa en texto, aplicando las reglas 5 y 6. Escribir el prompt para usarlo **sin** pasarle la referencia a Nano Banana: todo tiene que quedar descrito en texto.

### B) Solo texto
El usuario describe una idea. Completar con criterio lo que falte (encuadre, lente, luz, ambiente, vestuario) en vez de llenarlo de preguntas.

### C) Personajes propios (character sheets)
El usuario quiere poner a una persona concreta (por ejemplo, él mismo) en una escena, y le pasa a Nano Banana solo los character sheets: @image1 para la primera persona, @image2 para la segunda, etc.
- Describir toda la escena en texto (lugar, ropa, pose, luz y cámara).
- Indicar que la cara y todos los rasgos físicos sean 1:1 con el sheet correspondiente ("face and all physical features exactly as in @image1, identity 1:1, do not alter"). No mezclar rasgos con la referencia ni entre personajes.
- No describir rasgos faciales (vienen del sheet). Describir solo escena, ropa, pose y expresión.
- Respetar el estilo de cámara de la referencia (regla 7).

## Preguntas

Hacer como máximo 1 o 2 preguntas, y solo si cambian el resultado. Si la idea es clara, ir directo al prompt.

## Estilo por defecto

Si no hay un estilo indicado ni una referencia clara, usar la estética de Krea: sol, verano, luz natural cálida, aesthetic y colores limpios.

## Estructura del prompt

1. Tipo de toma y cámara (ej.: candid iPhone photo, shot on 26mm smartphone lens)
2. Sujeto: quién es, rasgos (o @image), ropa, pose y expresión
3. Ambiente y fondo
4. Luz y atmósfera
5. Look de cámara y realismo (grano sutil, compresión, textura de piel)
6. Formato: 4:5 vertical, máxima calidad
7. Cierre negativo breve: no CGI, no render look, no plastic skin, no text, no watermark

## Entrega

1. Una línea con la idea elegida (y qué se varió respecto de la referencia, si la hubo).
2. El prompt en inglés, en un único bloque de código listo para copiar.
3. Si aplica, qué imágenes adjuntar en Nano Banana (@image1, @image2).

## Si el resultado no convenció

- **Se ve muy IA o pulido:** reforzar el look de smartphone (más grano sutil, compresión, piel con textura, luz menos perfecta).
- **Salió igual a la referencia:** cambiar más elementos y mantener solo la idea.
- **La persona salió poco atractiva o rara:** quitar imperfecciones y pedir una expresión relajada y agradable.
- **La cara del personaje cambió:** reforzar "identity locked to @imageN, 1:1, do not blend features".
