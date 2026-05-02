
# Dataset: One Piece - Proyecto de Inteligencia Artificial

Este repositorio contiene el conjunto de imágenes utilizado para el entrenamiento y validación del modelo de identificación de la caricatura **One Piece** para el proyecto de la materia de Inteligencia Artificial.

## 📏 Dimensionamiento y Formato de las Imágenes

Para garantizar que el modelo MobileNetV2 funcione correctamente, las imágenes deben cumplir con los siguientes estándares:

* **Resolución mínima:** 100 x 100 píxeles.
* **Tamaño estándar para el modelo (durante el preprocesamiento):** 224 x 224 píxeles.
* **Formatos permitidos:** `.jpg`, `.jpeg`, `.png` (en caso de usar PNG, el script interno lo convertirá a RGB para evitar errores de canales).

---

## 📌 Instrucciones para el Dataset

Para evitar duplicados y mantener un orden, los archivos deben nombrarse utilizando el siguiente formato secuencial:

`one_piece_{tipo}_{numero_secuencial}.jpg`

### Rangos de numeración asignados por integrante:

* **Integrante 1:** 000001 a 025000
* **Integrante 2:** 025001 a 050000
* **Integrante 3:** 050001 a 075000
* **Integrante 4:** 075001 a 100000

---

## ⚠️ Reglas de Recolección

1. **Sin duplicados:** Validar que no existan imágenes idénticas (pueden usar un script de hash para verificar).
2. **Diversidad:** Incluir imágenes de cuerpo entero, rostros, diferentes ángulos y diversos fondos para evitar el sobreajuste (*overfitting*).
3. **Crossovers:** El integrante enfocado en arte/comunidades debe incluir imágenes donde aparezcan personajes de One Piece mezclados con otros universos.
