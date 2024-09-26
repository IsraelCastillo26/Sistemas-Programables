# **Actuadores**

## **¿Qué son?**
Los actuadores son dispositivos que convierten una forma de energía en movimiento mecánico. Su función principal es mover o controlar un mecanismo o sistema, ejecutando acciones físicas en respuesta a una señal de control. En otras palabras, los actuadores son responsables de la parte "activa" en un sistema de control, donde se necesita realizar un trabajo físico, como mover un objeto, abrir una válvula, levantar una carga, o girar una palanca.

![Actuadores](https://roboticoss.com/wp-content/uploads/2023/04/Actuadores-para-robotica-1.webp "Actuadores")
---

## **Actuadores eléctricos** 
Los actuadores eléctricos son dispositivos que convierten energía eléctrica en movimiento mecánico. Son ampliamente utilizados en aplicaciones industriales y automatización debido a su precisión, control y facilidad de integración. A continuación, te explico los tipos, funcionamiento, características y modos de comunicación de los actuadores eléctricos.

![Actuadores electricos](https://imgs.search.brave.com/l7_rLuLLKGkVO6XYj048N22RUoIHUDa8O6jnbS_GdWc/rs:fit:500:0:0:0/g:ce/aHR0cHM6Ly9wb3dl/cmRlcG90LmNvbS5t/eC93cC1jb250ZW50/L3VwbG9hZHMvMjAy/My8xMS9hY3R1YWRv/cmVsZWN0cmljby1r/ZXlzdG9uZS5qcGc "Actuadores electricos")

## **Tipos** 

- **Actuadores Lineales**:  
     Convierten la energía eléctrica en movimiento lineal (recto). Utilizan tornillos de avance, husillos o cilindros eléctricos.
    
- **Actuadores Rotativos:**:  
     Convierten la energía eléctrica en movimiento rotativo (giro). Pueden ser servomotores o motores paso a paso.

- **Servomotores:**:  
     Son actuadores rotativos con un sistema de retroalimentación para controlar su posición, velocidad o par.

- **Motores paso a paso:**:  
     Avanzan en pequeños pasos a través de pulsos eléctricos, permitiendo un control preciso de la posición.

---

## **Funcionamiento**

### **Conversión de energía:** 
- La energía eléctrica se convierte en movimiento mecánico mediante mecanismos como tornillos, engranajes o sistemas electromagnéticos.

### **Control:** 
- La dirección, velocidad y posición del actuador se controlan mediante señales eléctricas que pueden ser analógicas o digitales.

### **Retroalimentación:** 
 - Algunos actuadores (como los servomotores) utilizan sensores para ajustar su movimiento en función de la retroalimentación recibida.

---

## **Características**

### **Precisión:** 
Los actuadores eléctricos ofrecen un control preciso del movimiento, lo que los hace ideales para aplicaciones de alta exactitud.

### **Velocidad:** 
La velocidad puede ser controlada con alta precisión, y los actuadores pueden moverse a diferentes velocidades según la necesidad de la aplicación.

### **Fuerza/Torque:**
Dependiendo del tipo de actuador, pueden ofrecer diferentes niveles de fuerza o torque para mover cargas ligeras o pesadas.

### **Mantenimiento:** 
Requieren menos mantenimiento que los actuadores neumáticos o hidráulicos, ya que no necesitan fluidos o compresores.

### **Durabilidad:** 
Los actuadores eléctricos suelen ser más duraderos debido a la ausencia de componentes móviles en el caso de los motores sin escobillas.

---

## Modos de comunicación
### **Señal Analógica (4-20 mA o 0-10 V):**
- Controlan el movimiento del actuador a través de un rango continuo de voltaje o corriente.


### **Señal Digital (Modbus, CAN, Profibus, Ethernet/IP):**
- Permiten la comunicación entre el actuador y un controlador o PLC mediante protocolos de comunicación industrial.


### **Controladores Integrados:**
- Algunos actuadores eléctricos vienen con controladores integrados que permiten la configuración y operación sin necesidad de controladores externos.

### **Comunicación Inalámbrica:**
- Permite el control remoto de los actuadores a través de señales inalámbricas, aunque es menos común en aplicaciones industriales.

---

## **Actuadores hidráulicos** 
Los actuadores hidráulicos son dispositivos que convierten la energía hidráulica (presión de un fluido) en movimiento mecánico. Se utilizan en aplicaciones que requieren grandes fuerzas y movimientos controlados, y son comunes en maquinaria pesada, sistemas industriales, y equipo móvil.

![Actuadores hidraulicos](https://imgs.search.brave.com/PE23CJSaLcOawgG3KY4bWVPhdchUzkQt_FEITv6CmSE/rs:fit:500:0:0:0/g:ce/aHR0cHM6Ly93d3cu/ZGlwcmF4LmVzL3dw/LWNvbnRlbnQvdXBs/b2Fkcy9DSUxJTkRS/T1MtSElEUkFVTElD/T1MtREUtUEFMRVRB/Uy1ST1RBVElWQVMt/U0VSSUUtSFBTRC1E/SVBSQVgtMi5qcGc "Actuadores hidraulicos")
## **Tipos** 

- **Cilindros Hidráulicos:**  
     Convierten la energía del fluido hidráulico en movimiento lineal. Consisten en un cilindro y un pistón; cuando el fluido presurizado entra en el cilindro, empuja el pistón, generando movimiento. 
     ### Subtipos
     - **Cilindros de Simple Efecto:**  
        El fluido hidráulico actúa en un solo lado del pistón, generando movimiento en una dirección. El retorno se realiza mediante un resorte o por la fuerza de la gravedad.

     - **Cilindros de Doble Efecto:**  
        El fluido actúa en ambos lados del pistón, permitiendo el movimiento en ambas direcciones.

- **Motores Hidráulicos:**  
     Convierten la energía hidráulica en movimiento rotativo. Funcionan de manera similar a un motor eléctrico, pero usan la presión del fluido para generar torque y rotación.

     ### Subtipos
     - **Motores de Engranajes:**  
        Utilizan engranajes para convertir el flujo del fluido en movimiento rotativo.

     - **Motores de paletas:**  
        Utilizan paletas móviles en un rotor para generar movimiento rotativo.

     - **Motores de funciones radiales:**  
        Utilizan pistones dispuestos radialmente en un cilindro para generar rotación.  

- **Actuadores de Palanca Hidráulica:**  
     Usan la presión del fluido para mover una palanca, que a su vez genera movimiento mecánico.

---

## **Funcionamiento**

### **Energía hidráulica:** 
- Los actuadores hidráulicos funcionan a través de la presión de un fluido (generalmente aceite hidráulico) que se bombea a través de un sistema cerrado. Este fluido se introduce en el actuador, donde su presión se convierte en movimiento lineal o rotativo.

### **Control:** 
- La velocidad y la fuerza del movimiento pueden controlarse ajustando la cantidad de fluido y su presión. La dirección del movimiento se controla mediante válvulas que direccionan el flujo del fluido.

### **Capacidad de carga:** 
 - Los actuadores hidráulicos son capaces de generar grandes fuerzas, haciéndolos ideales para aplicaciones que requieren una alta potencia.

---

## **Características**

### **Precisión:** 
Ofrecen un control preciso de la velocidad y la fuerza del movimiento.

### **Velocidad:** 
La velocidad puede ser controlada con alta precisión, y los actuadores pueden moverse a diferentes velocidades según la necesidad de la aplicación.

### **Alta Fuerza y Potencia: **
Pueden generar grandes fuerzas con tamaños relativamente compactos.

### **Mantenimiento:** 
Requieren un mantenimiento regular, incluyendo la inspección y reemplazo de sellos y la filtración del fluido para prevenir contaminación.

### **Durabilidad:** 
Son robustos y pueden operar en condiciones adversas, incluyendo ambientes con polvo, calor, y humedad.

### **Respuesta Rápida:**
Responden rápidamente a cambios en la presión del fluido, lo que permite un control dinámico.

---

## Modos de comunicación
Los actuadores hidráulicos en sí no tienen modos de comunicación, pero pueden ser integrados en sistemas que permiten monitoreo y control a través de diferentes tecnologías.

### **Sensores de Posición y Presión:**
- Sensores instalados en el sistema hidráulico que monitorean la posición del pistón o la presión del fluido.


### **Válvulas Proporcionales Controladas Electrónicamente:**
- Válvulas que regulan el flujo del fluido en función de señales electrónicas. Estas señales pueden ser controladas por un PLC o un sistema de control automático.


### **Controladores Hidráulicos Integrados:**
- Sistemas integrados que combinan sensores, válvulas, y controladores electrónicos para gestionar la operación de los actuadores hidráulicos.

### **Protocolos de Comunicación Industrial (CAN, Modbus, Profibus):**
- Los actuadores hidráulicos pueden ser parte de un sistema de control más amplio que usa protocolos de comunicación industrial para integrar diferentes componentes, como actuadores, sensores y controladores.

## **Actuadores mecánicos** 
Los actuadores mecánicos son dispositivos que convierten una forma de energía en movimiento mecánico, utilizando principios mecánicos para operar una carga o realizar una función. Estos actuadores pueden ser accionados por diferentes tipos de energía, como energía eléctrica, neumática o hidráulica, pero el énfasis está en la conversión y transmisión del movimiento a través de medios mecánicos.

![Actuadores mecanicos](https://imgs.search.brave.com/22cNWX0V_xyAtlgnDgs7iqiV0SRSyk3EvbLXb6if_ag/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9pbWcu/aW50ZXJlbXByZXNh/cy5uZXQvRm90b3NB/cnRQcm9kdWN0b3Mv/UDU2ODg4LmpwZw "Actuadores mecanicos")


## **Tipos** 

- **Actuadores de Tornillo:**  
     Utilizan un tornillo y una tuerca para convertir el movimiento rotativo en movimiento lineal. El tornillo gira dentro de una tuerca, moviéndose linealmente en una dirección.
    
- **Actuadores de Cremaillera y Piñón:**  
     Convierten el movimiento rotativo en movimiento lineal mediante un engranaje (piñón) que se desplaza sobre una barra dentada (cremallera).

- **Actuadores de Leva:**  
     Son actuadores rotativos con un sistema de retroalimentación para controlar su posición, velocidad o par.

- **Actuadores de Cable y Polea:**  
     Utilizan un sistema de poleas y cables para convertir el movimiento de tracción en movimiento lineal o angular.

- **Actuadores de Resortes:**  
     Aprovechan la energía almacenada en un resorte comprimido o estirado para generar movimiento cuando se libera.

---

## **Funcionamiento**

### **Principios Mecánicos: ** 
- Los actuadores mecánicos funcionan mediante la conversión de energía y la transmisión del movimiento a través de mecanismos como tornillos, engranajes, palancas o resortes.

### **Energía de Entrada:** 
- Pueden ser accionados por energía manual, eléctrica, neumática o hidráulica, pero la salida siempre es movimiento mecánico.

### **Movimiento:** 
 - Generan movimiento lineal, rotativo o una combinación de ambos, dependiendo del diseño del actuador.

---

## **Características**

### **Precisión:** 
Algunos actuadores, como los de tornillo, ofrecen alta precisión en el control de la posición.

### **Velocidad:** 
Pueden ser diseñados para funcionar a diferentes velocidades, dependiendo de las necesidades de la aplicación.

### **Simplicidad:**
Generalmente, los actuadores mecánicos son simples en diseño y fáciles de mantener.

### **Mantenimiento:** 
Aunque son duraderos, requieren lubricación y mantenimiento periódico para asegurar un funcionamiento óptimo.

### **Durabilidad:** 
Son robustos y pueden soportar condiciones de trabajo difíciles, como altas cargas y ambientes adversos.

---

## Modos de comunicación
Los actuadores mecánicos en sí no tienen modos de comunicación como los actuadores eléctricos. Sin embargo, pueden ser integrados en sistemas más amplios donde se utilizan sensores y controladores para monitorear y controlar su funcionamiento. En esos casos, los modos de comunicación serían parte del sistema de control, no del actuador mecánico en sí.

### **Sensores de Posición:**
- Sensores acoplados al actuador para monitorear su posición o estado. La información se comunica a un controlador externo.

### **Sistemas de Retroalimentación:**
- Uso de retroalimentación mecánica, como topes o indicadores, para informar sobre la posición o el estado del actuador.

### **Interfaz con Controladores Externos:**
- Aunque los actuadores mecánicos no tienen comunicación integrada, pueden ser controlados mediante actuadores eléctricos, neumáticos o hidráulicos, que sí pueden comunicarse con sistemas de control mediante señales analógicas, digitales o protocolos industriales.


