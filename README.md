# 📡 Comunicaciones Industriales

Repositorio con información de sensores disponibles en los semilleros.  
Autores: **Santiago Hernández Ávila**

---

## 📖 Contenido
- [Dynamixel RX-28](#dynamixel-rx-28)
- [Milone eTape Continuous Fluid Level Sensor](#milone-etape-continuous-fluid-level-sensor)
- [Sensor de Velocidad de Viento RK100-02](#sensor-de-velocidad-de-viento-rk100-02)

---

## 1. 🔧 Dynamixel RX-28

El **Dynamixel RX-28** es un servo motor inteligente fabricado por **Robotis**, parte de la serie RX.  
Integra **sensores internos** que permiten control y protección.

<p align="center">
  <img src="imagenes/dynamixel_rx28.jpg" alt="Dynamixel RX-28" width="350"/>
</p>

**Tabla 1. Sensores internos del Dynamixel RX-28**

| Tipo de sensor        | Qué mide                                | Para qué sirve                            |
|------------------------|-----------------------------------------|-------------------------------------------|
| Encoder (posición)    | Ángulo del eje (0–1023 pasos → 0°–300°) | Determinar la posición del servo          |
| Temperatura           | Temperatura interna en °C               | Apagar o limitar si se calienta demasiado |
| Voltaje               | Voltaje de alimentación                 | Proteger ante subidas/bajadas de voltaje  |
| Corriente / carga     | Esfuerzo que hace el motor              | Detectar bloqueos o sobrecargas           |

---

## 2. 🌊 Milone eTape Continuous Fluid Level Sensor

El **Milone eTape** es un sensor de nivel de fluido que mide de forma continua la altura del líquido dentro de un tanque o recipiente.

<p align="center">
  <img src="imagenes/milone_etape.jpg" alt="Milone eTape Continuous Fluid Level Sensor" width="350"/>
</p>

**Características principales:**
- Tecnología: tira resistiva que cambia su resistencia según la presión hidrostática.
- Salida: resistencia variable (algunos modelos incluyen salida analógica en voltaje mediante un conversor).
- Rango típico: versiones de 20 cm a 120 cm.
- Precisión: alta, detecta pequeños cambios en el nivel.
- Ventaja: entrega medición proporcional (no por pasos como un flotador).
- Aplicaciones: tanques de agua, combustible, químicos no corrosivos.

**Cómo funciona:**  
Cuando el sensor está sumergido, la presión del líquido cambia la resistencia interna de la tira. Esa variación puede leerse con un microcontrolador (Arduino, ESP32, etc.) para calcular la altura del fluido.

---

## 3. 🌬️ Sensor de Velocidad de Viento RK100-02

El **RK100-02** es un sensor de velocidad de viento tipo **anemómetro de tres copas**, diseñado para medir de forma continua la velocidad del viento en exteriores.

<p align="center">
  <img src="imagenes/rk100_02.jpg" alt="Sensor de Viento RK100-02" width="350"/>
</p>

**Cómo funciona:**  
El viento hace girar las copas → el sensor mide la velocidad de rotación → convierte la señal en una salida proporcional a la velocidad del viento.  
Según el modelo, la salida puede ser pulsos, voltaje (0–5V) o corriente (4–20mA).

**Características:**
- Material: ABS o aluminio (según versión).
- Rango de medición: 0–45 m/s.
- Precisión: ±(0.3 + 0.03V) m/s.
- Señal de salida: pulsos, analógica (0–5V) o corriente (4–20mA).
- Alimentación: 5–30 VDC.
- Aplicaciones: estaciones meteorológicas, parques eólicos, monitoreo ambiental.

---
