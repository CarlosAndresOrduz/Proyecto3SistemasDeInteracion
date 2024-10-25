# Miniproyecto 4 - Sistemas de Interacción

## P1 - Control Básico (Sliders, Switches, Botones)
Funcionalidades principales de control de audio:

### 4 Sliders:
- **Volumen**: Controla la ganancia del audio.  
- **Velocidad**: Ajusta la velocidad de reproducción.  
- **Tonos altos**: Aumenta o reduce la amplitud de las frecuencias altas (EQ).  
- **Tonos bajos**: Aumenta o reduce la amplitud de las frecuencias bajas (EQ).  

> **Nota**: Los sliders de tonos altos y bajos no cambian la frecuencia, sino que ajustan la amplitud de un rango de frecuencias específico.

### 3 Switches (ON/OFF):
- **Activar/Desactivar base**: Habilita o silencia la base rítmica.  
- **Activar/Desactivar inicio de bucle**: Marca el punto inicial del bucle.  
- **Activar/Desactivar fin de bucle**: Marca el punto final del bucle.

### 3 Botones:
- **Volver al inicio del bucle**: Devuelve la reproducción al punto inicial del bucle.  
- **Pausar**: Pausa toda la reproducción.  
- **Reanudar**: Reanuda toda la reproducción.  

---

## P2 - Modulación Avanzada (Frecuencia y Forma de Onda)
Página dedicada a la manipulación avanzada de sonido mediante controles de frecuencia y forma de onda.

### 2 Ejes de Control:
- **Eje X**: Controla la frecuencia del sonido, permitiendo subir o bajar el tono.  
- **Eje Y**: Modifica la forma de la onda:  
  - **Centro**: Onda sinusoidal (sonido suave).  
  - **Hacia arriba**: Onda cuadrada (sonido más agresivo).  
  - **Hacia abajo**: Onda triangular (sonido más tenue).  

---

## P3 - Gestión de Base (Switches Rítmicos)
Página dedicada a la creación y manipulación de patrones de percusión.

### 24 Switches organizados en 4 columnas (6 switches por columna):
- **Cada columna representa un tiempo del compás (4/4)**:
  - Columna 1: Tiempo 1  
  - Columna 2: Tiempo 2  
  - Columna 3: Tiempo 3  
  - Columna 4: Tiempo 4  

- **Cada fila corresponde a un sonido de percusión**:
  - Fila 1: Bombo  
  - Fila 2: Caja  
  - Fila 3: Hi-hat abierto  
  - Fila 4: Hi-hat cerrado  
  - Fila 5: Clap  
  - Fila 6: Platillo  

**Función**:  
Cuando un switch se activa, su sonido correspondiente se reproduce en ese tiempo del compás.

> **Nota**: Todos los sonidos deben ser generados en Pure Data, evitando el uso de samples pregrabados.

---

## P4 - Gestión de Sonidos (Botones por Instrumento)
Página dedicada a seleccionar y gestionar sonidos de diferentes instrumentos.

### 24 Botones organizados en 4 columnas (6 botones por columna):
- **Cada columna representa un instrumento**:
  - Columna 1: Piano  
  - Columna 2: Synth  
  - Columna 3: Guitarra eléctrica  
  - Columna 4: Bajo  

- **Cada botón representa un sonido distinto**:
  - Ejemplo: Los botones del piano podrían activar diferentes acordes mayores o menores.

**Función**:  
Al presionar un botón, se reproduce el sonido asignado al instrumento.

---

## Entrega del Proyecto
- **Entrega Preliminar** – 24 de octubre:  
  Presentar los avances logrados hasta esta fecha.

- **Entrega y Sustentación Final** – 1 de noviembre:  
  Se recibirá el trabajo completo y se realizará la sustentación.

---

## Descripción del Proyecto
Usando la app **OSC Controller** (Open Sound Control) y el lenguaje **PureData (PD)**, se debe implementar un sistema de DJ. La idea es utilizar todos los widgets disponibles en la app (sliders y botones), asegurando que cada interacción tenga una respuesta auditiva en PD. El objetivo es permitir la creación de piezas de música electrónica al estilo de un DJ.

### Limitantes:
- Debe utilizarse **OSC** y **Pure Data**.  
- Se deben emplear diferentes interacciones ofrecidas por OSC (sliders, botones, etc.).  
- Todas las interacciones deben afectar el audio en PD.  
- Se debe subir un **video a YouTube** de no más de 5 minutos donde se muestre el funcionamiento del sistema (demo con una canción).
