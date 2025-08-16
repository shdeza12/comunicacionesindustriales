# Comunicaciones Industriales

Repositorio con información de sensores y dispositivos usados en prácticas y proyectos de la materia.

---

## 📖 Contenido
- [Dynamixel RX-28](#dynamixel-rx-28)
- [Milone eTape Continuous Fluid Level Sensor](#milone-etape-continuous-fluid-level-sensor)
- [Sensor de Velocidad de Viento RK100-02](#sensor-de-velocidad-de-viento-rk100-02)
- [Notas adicionales](#notas-adicionales)

---

## 🔧 Dynamixel RX-28
El **Dynamixel RX-28** no es un sensor, sino un **actuador inteligente** de tipo **servo** utilizado en robótica.  
Principales características:
- Protocolo de comunicación: TTL Half Duplex Asynchronous Serial.
- Resolución: 10 bits (1024 posiciones).
- Velocidad de rotación: hasta 85 RPM a 12V.
- Torque máximo: 2.5 N·m.
- Voltaje de operación: 12V.
- Retroalimentación: posición, velocidad, carga, voltaje, temperatura.

Usos comunes:
- Brazos robóticos.
- Robots humanoides.
- Proyectos de mecatrónica avanzada.

---

## 🌊 Milone eTape Continuous Fluid Level Sensor
El **eTape** es un **sensor resistivo de nivel de líquidos**.  
Características principales:
- Cambia su resistencia según la altura del líquido.
- Rango de medida: depende del modelo (normalmente 0–30 cm).
- Alimentación: 5V DC.
- Salida: resistencia variable proporcional al nivel del fluido.
- Compatible con microcontroladores (Arduino, Raspberry Pi, etc.).

Aplicaciones:
- Medición de nivel en tanques.
- Control de procesos industriales.
- Proyectos de IoT relacionados con líquidos.

---

## 🌬️ Sensor de Velocidad de Viento RK100-02
El **RK100-02** es un **anemómetro de cazoletas**.  
Características:
- Material: ABS o aluminio (según versión).
- Rango de medición: 0–45 m/s.
- Precisión: ±(0.3 + 0.03V) m/s.
- Señal de salida:  
  - Pulsos (reed switch, transistor NPN) o  
  - Analógica (0-5V o 4-20mA, según modelo).
- Alimentación: 5–30 VDC.

Aplicaciones:
- Estaciones meteorológicas.
- Parques eólicos.
- Monitoreo de condiciones ambientales.

---

## 📝 Notas adicionales
- Todos estos dispositivos requieren una etapa de acondicionamiento y comunicación adecuada con el microcontrolador.
- En este repositorio se documentarán ejemplos de conexión y códigos de prueba para cada sensor.
<<<<<<< HEAD
mi primer proyecto
=======
# comunicacionesindustriales
>>>>>>> 4c56a09f7eacfcc6bbd4b22a4143fb059a943b16
