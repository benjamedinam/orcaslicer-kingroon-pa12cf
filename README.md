# OrcaSlicer Profile: Kingroon PA12-CF (Nylon Carbon Fiber)

[English](#english) | [Español](#español)

---

## English

This repository contains a calibrated configuration profile for **Kingroon PA12-CF** filament in **OrcaSlicer**. Since this technical material lacks a native preset from the manufacturer, this independent tuning was developed to ensure excellent layer adhesion, minimized stringing, and optimal dimensional stability.

### 🛠️ Hardware Specifications
This profile was developed, tested, and fine-tuned using the following setup:
* **Printer:** Elegoo Centauri Carbon
* **Nozzle:** 0.4 mm Stainless Steel
* **Enclosure:** Yes (Stock enclosed chamber active)

### ⚙️ Key Profile Parameters
The main values embedded in the `.json` profile are summarized below:

| Parameter | Calibrated Value | Notes |
| :--- | :--- | :--- |
| **Nozzle Temperature** | `255 °C - 275 °C` | Optimal range for carbon fiber flow and interlayer bond |
| **Max Volumetric Speed** | `8 mm³/s` | Crucial to prevent clogging due to high material viscosity |
| **Retraction Speed** | `45 mm/s` | Strict control to mitigate thermal stringing |
| **Part Cooling Fan** | `Disabled (0%)` | Kept completely off to maximize intermolecular fusion |

### ⚠️ Mandatory Material Preparation (Drying)
Nylon (PA12) is highly hygroscopic and absorbs ambient moisture rapidly. Printing it wet will ruin the surface finish and drastically reduce part strength.
* **Recommended Drying Condition:** **70 °C for 12 hours** in a dedicated filament dryer or convection oven before printing.
* It is highly recommended to print directly from a dry box for extended print jobs.

### 🚀 How to Import into OrcaSlicer
1.  Download the `Kingroon_PA12-CF.json` file from this repository.
2.  Open **OrcaSlicer**.
3.  In the top menu bar, navigate to **File > Import > Import Presets**.
4.  Select the downloaded `.json` file.
5.  The profile will now be available in your filament dropdown menu as **Kingroon PA12-CF**.

---

## Español

Este repositorio contiene el perfil de configuración calibrado para el filamento **Kingroon PA12-CF** en **OrcaSlicer**. Dado que este material técnico no cuenta con un perfil nativo preconfigurado por el fabricante, este ajuste independiente se desarrolló para garantizar una excelente adhesión de capas, reducción de *stringing* (hilos) y una estabilidad dimensional óptima.

### 🛠️ Especificaciones del Hardware Utilizado
El perfil fue desarrollado, probado y afinado utilizando la siguiente configuración:
* **Impresora:** Elegoo Centauri Carbon
* **Boquilla (Nozzle):** Acero Inoxidable de 0.4 mm
* **Gabinete (Enclosure):** Sí (Cámara/gabinete cerrado de fábrica activado)

### ⚙️ Parámetros Clave del Perfil
A continuación se detallan los valores principales guardados en el archivo `.json`:

| Parámetro | Valor Calibrado | Notas |
| :--- | :--- | :--- |
| **Temperatura de Boquilla** | `255 °C - 275 °C` | Rango óptimo para fluidez de la fibra de carbono |
| **Velocidad Volumétrica Máxima** | `8 mm³/s` | Crucial para evitar atascos (*clogging*) debido a la alta viscosidad |
| **Velocidad de Retracción** | `45 mm/s` | Control estricto para mitigar el *stringing* térmico |
| **Ventilación (Cooling)** | `Desactivado (0%)` | Apagado por completo para maximizar la unión intermolecular |

### ⚠️ Preparación Obligatoria del Material (Secado)
El Nylon (PA12) es un material altamente higroscópico (absorbe humedad del aire con mucha facilidad). Imprimirlo húmedo arruinará el acabado superficial y debilitará estructuralmente la pieza.
* **Condición de secado recomendada antes de imprimir:** **70 °C durante 12 horas** en un secador de filamentos o un horno de convección deshidratador.
* Se recomienda imprimir directamente desde una *Dry Box* (caja seca) si la impresión toma varias horas.

### 🚀 Cómo importar este perfil en OrcaSlicer
1.  Descarga el archivo `Kingroon_PA12-CF.json` de este repositorio.
2.  Abre **OrcaSlicer**.
3.  En la barra de menús superior, ve a **File > Import > Import Presets**.
4.  Selecciona el archivo `.json` que descargaste.
5.  ¡Listo! El perfil ahora aparecerá disponible en tu sección de filamentos como **Kingroon PA12-CF**.

---
## 🤝 Contributions / Contribuciones
If you test this profile with 0.6 mm nozzles or find optimizations for higher speed settings, feel free to open a *Pull Request* or submit an *Issue*!

Si realizas pruebas con boquillas de 0.6 mm o encuentras mejoras en las velocidades de impresión para este filamento en específico, ¡siéntete libre de abrir un *Pull Request* o reportar un *Issue*!
