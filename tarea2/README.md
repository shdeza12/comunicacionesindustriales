# Tarea 2 - Comunicación RS232 y Código ASCII

Este documento presenta información sobre el código **ASCII** y el protocolo **RS232**.

---

## 1. Código ASCII

**Historia y descripción:** 

El código ASCII (American Standard Code for Information Interchange) fue creado en 1963 por el comité ANSI para estandarizar la representación de caracteres en computadoras y equipos de telecomunicaciones.  

**Funcionamiento:**

- Asigna un número a cada carácter (0 a 127 en 7 bits). **Ejemplo:** "A" = 65, "0" = 48.
- Incluye letras, números, símbolos y caracteres de control.

**Importancia:**
- Base de la comunicación textual en sistemas digitales.
- Punto de partida para estándares modernos como UTF-8.
- Usado en protocolos de transmisión serie como RS232.

## 2. Pines de los conectores DB9 y DB25 en RS232

### DB9 - Descripción de pines.

<div align="center">


| Pin | Señal | Descripción                |
|-----|-------|----------------------------|
| 1   | DCD   | Data Carrier Detect        |
| 2   | RXD   | Receive Data               |
| 3   | TXD   | Transmit Data              |
| 4   | DTR   | Data Terminal Ready        |
| 5   | GND   | Ground (Tierra)            |
| 6   | DSR   | Data Set Ready             |
| 7   | RTS   | Request To Send            |
| 8   | CTS   | Clear To Send              |
| 9   | RI    | Ring Indicator             |
</div>

### DB25 – Pines más usados  

<div align="center">

| Pin | Señal | Descripción                |
|-----|-------|----------------------------|
| 1   | GND   | Chasis / Tierra            |
| 2   | TXD   | Transmit Data              |
| 3   | RXD   | Receive Data               |
| 4   | RTS   | Request To Send            |
| 5   | CTS   | Clear To Send              |
| 6   | DSR   | Data Set Ready             |
| 7   | GND   | Signal Ground              |
| 8   | DCD   | Data Carrier Detect        |
| 20  | DTR   | Data Terminal Ready        |
| 22  | RI    | Ring Indicator             |
</div>
---

## 3. Formato del protocolo RS232

**Estructura de la trama:**

1. **Bit de inicio (Start bit):** Siempre en bajo (0 lógico).  
2. **Bits de datos:** Entre 5 y 9 bits, típicamente 8.  
3. **Bit de paridad (opcional):** Par, impar o sin paridad.  
4. **Bits de parada (Stop bits):** 1, 1.5 o 2 en alto (1 lógico).  

