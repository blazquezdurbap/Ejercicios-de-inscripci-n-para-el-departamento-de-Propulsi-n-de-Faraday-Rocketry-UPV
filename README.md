# 🚀 Ejercicios de inscripción para el departamento de Propulsión de Faraday Rocketry UPV

Bienvenido a este repositorio. Aquí documento y comparto mi resolución técnica para las pruebas de acceso al departamento de Propulsión del equipo universitario **Faraday Rocketry UPV**. 

El objetivo de este proyecto es diseñar desde cero los sistemas necesarios para impulsar un cohete sonda a 11 km de apogeo, probar sus motores en tierra de forma segura y garantizar un encendido fiable.

## 📂 Estructura del Repositorio

Este proyecto se divide en tres bloques principales de ingeniería:

### 1. Diseño del Motor Sólido
Diseño preliminar de un motor de propulsante sólido capaz de alcanzar 11 km de altura sin superar un límite estructural de cámara de 60 bar.
* **Propulsante:** APCP (HTPB/AP/Al).
* **Geometría del grano:** Estrella (Star Grain) para estabilizar la curva de presión.
* **Rendimiento:** Impulso total de ~25.000 Ns y empuje máximo de ~12.000 N.
* **Archivos incluidos:** Archivos de balística interna en OpenMotor.

### 2. Banco de Pruebas Vertical de 20 kN
Diseño mecánico y electrónico de un banco de pruebas estático en configuración vertical, adaptable a diferentes longitudes y diámetros de motor, con un presupuesto optimizado (<3000€).
* **Mecánica:** Estructura de perfiles de aluminio, guías lineales HGR20 con patines para aislar el eje Z, y base móvil con puntal mecánico para ajuste de altura.
* **Adquisición de datos (DAQ):** Arquitectura basada en microcontrolador ESP32, módulo ADC externo (ADS1256 de 24 bits) para muestreo a 1 kHz, y célula de carga tipo *pancake*.
* **Archivos incluidos:** Ensamblajes y piezas en SolidWorks, además de la lista de materiales (BOM).

### 3. Sistema de Ignición
Desarrollo conceptual y mecánico de un sistema de encendido para motores de alta potencia.
* **Química:** Análisis y selección de un ignitor compuesto termítico (Epoxi-Metal) por su nula sensibilidad a la fricción y su masivo aporte térmico convectivo.
* **Hardware:** Herramienta de inserción impresa en 3D (varilla hueca con tope cónico centrador) que garantiza el posicionamiento milimétrico del ignitor en la parte frontal de la cámara de combustión.
* **Archivos incluidos:** Archivos en SolidWorks de la herramienta.

## 🛠️ Tecnologías y Herramientas Utilizadas
* **CAD & Mecánica:** SolidWorks
* **Simulación Balística:** OpenMotor
* **Simulación de Vuelo:** OpenRocket
* **Electrónica:** ESP32, Sensores Industriales (Célula de carga, transductor de presión 0-100 bar, termopares).

## 📄 Documentación Técnica
Para una explicación detallada de los cálculos termodinámicos, la toma de decisiones iterativa y la justificación de seguridad, puedes consultar el documento completo en formato PDF incluido en este repositorio.

---
*Si te interesa la ingeniería aeroespacial, el diseño CAD o el desarrollo de hardware, no dudes en conectar conmigo en www.linkedin.com/in/blazquezdurbapablo.*
