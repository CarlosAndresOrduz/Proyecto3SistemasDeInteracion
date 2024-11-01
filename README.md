# Miniproyecto 4 - Sistemas de Interacción

## Carlos Andres Orduz Guacaneme
> LINK: **https://youtu.be/tIA9TS8uaZY**

## P1 - Control de Grabación y Efectos (Sliders, Switches, Botones)
Funcionalidades de control de audio en la primera página:

### 4 Sliders:
- **Volumen Grabación**: Ajusta el volumen general de la grabación.
- **Efecto Eco**: Controla la intensidad del efecto de eco.
- **Volumen Eco**: Ajusta el volumen del eco, modificando su presencia en la mezcla.
- **Velocidad Base**: Cambia la velocidad de reproducción de la base rítmica en la página 3.

### 3 Switches (ON/OFF):
- **Detener Grabación (de 0)**: Detiene la grabación actual cuando ya está en proceso.
- **Activar Metrónomo**: Habilita el metrónomo para mantener el ritmo.
- **Sonido Prueba Eco**: Permite probar el efecto de eco en tiempo real.

### 3 Botones:
- **Abrir Grabación (de 0)**: Inicia una nueva grabación desde cero.
- **Iniciar Grabación (de 0)**: Comienza a grabar el audio desde el inicio.
- **Reproducir Grabación (ya grabada)**: Reproduce la última grabación almacenada.

---

## P2 - Modulación Avanzada (Frecuencia y Amplitud)
Página de modulación avanzada mediante los ejes de frecuencia y amplitud.

### 2 Ejes de Control:
- **Eje Y (Frecuencia)**: Ajusta la frecuencia del sonido para cambiar el tono.
- **Eje X (Amplitud)**: Modifica la amplitud del sonido para variar el volumen percibido.

---

## P3 - Gestión de Base (Switches Rítmicos)
Controles de base rítmica que permiten crear patrones de percusión en un compás.

### 24 Switches organizados en 4 columnas (6 instrumentos de percusión por columna):
  
**Función**: Al activar un switch, se programa el instrumento seleccionado para que se reproduzca en el tiempo asignado, permitiendo crear bases rítmicas con variaciones y repeticiones hasta que el usuario lo desee.

---

## P4 - Gestión de Sonidos (Botones de Piano y Efectos de Sonido)
Página dedicada a la reproducción de sonidos específicos por instrumento.

### 24 Botones organizados en 2 grupos:
- **12 botones para sonidos de piano**: Cada botón representa un sonido específico del piano.
- **12 botones para efectos de sonido**: Cada botón permite activar un efecto de sonido específico.

**Función**: Al presionar un botón, se reproduce el sonido asignado, permitiendo explorar diversos timbres y efectos.

---

## Entrega del Proyecto
- **Entrega Preliminar** – 24 de octubre:  
  Presentar los avances logrados hasta esta fecha.

- **Entrega y Sustentación Final** – 1 de noviembre:  
  Se recibirá el trabajo completo y se realizará la sustentación.

---

## Descripción del Proyecto
Usando la app **OSC Controller** (Open Sound Control) y el lenguaje **Pure Data (PD)**, se debe implementar un sistema de DJ. La idea es utilizar todos los widgets disponibles en la app (sliders y botones), asegurando que cada interacción tenga una respuesta auditiva en PD. El objetivo es permitir la creación de piezas de música electrónica al estilo de un DJ.

### Limitantes:
- Debe utilizarse **OSC** y **Pure Data**.  
- Se deben emplear diferentes interacciones ofrecidas por OSC (sliders, botones, etc.).  
- Todas las interacciones deben afectar el audio en PD.  
- Se debe subir un **video a YouTube** de no más de 5 minutos donde se muestre el funcionamiento del sistema (demo con una canción).

