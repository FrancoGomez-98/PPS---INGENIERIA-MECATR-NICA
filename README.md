![Logo Institucional](https://github.com/JonatanBogadoUNLZ/PPS-Jonatan-Bogado/blob/9952aac097aca83a1aadfc26679fc7ec57369d82/LOGO%20AZUL%20HORIZONTAL%20-%20fondo%20transparente.png)
# Universidad Nacional de Lomas de Zamora - Facultad de Ingeniería
# Universidad Nacional de Lomas de Zamora - Facultad de Ingeniería

## Puesta a Punto y Mejora del Brazo Robótico SCORBOT EX IX

![Logo Institucional](https://github.com/JonatanBogadoUNLZ/PPS-Jonatan-Bogado/blob/9952aac097aca83a1aadfc26679fc7ec57369d82/LOGO%20AZUL%20HORIZONTAL%20-%20fondo%20transparente.png)

---

## Introducción / Objetivo

Este proyecto forma parte de la *Práctica Profesional Supervisada (PPS)* desarrollada en el **Laboratorio CIM Robótica** de la Facultad de Ingeniería (UNLZ). El objetivo principal consistió en realizar la **puesta a punto**, **mejora**, **programación**, y **documentación operativa** del brazo robótico **SCORBOT EX IX**, junto con su estación de trabajo y el sistema automatizado gestionado por el *Manager* central.

El trabajo abordó tareas de programación en ACL, configuración de entradas y salidas, calibración, creación de rutinas automatizadas, mejoras operativas y documentación integral para facilitar su uso por futuros estudiantes.

---

## Índice

* Descripción
* Instrucciones de Uso
* Tecnologías Utilizadas
* Listado de Componentes
* Esquemáticos
* Fotos / Videos
* Autor
* Carpetas del Proyecto

---

## Descripción

La PPS se desarrolló en el laboratorio CIM Robótica, donde se trabajó con una línea de producción automatizada provista por **ESHED Robotics**, compuesta por:

* Brazo robótico **SCORBOT EX IX**
* Base lineal Slidebase
* Cinta transportadora
* Estaciones de trabajo automatizadas
* Tablero central de control (*Manager*)

Se diseñó y programó un conjunto de rutinas para controlar la Estación de Trabajo Nº2, coordinando entradas y salidas digitales, movimientos cartesianos y articulares, secuencias automáticas y subprogramas específicos.

El proyecto implicó:

* Creación del programa principal **LOBBY**
* Desarrollo de subprogramas **GETXX** y **PUTXX**
* Rutinas de ensamblado y operaciones específicas (**ENSAM**, **PRCAJ**, **TORN**, **TORN2**)
* Configuración de vectores, velocidades, ciclos, variables y movimientos
* Puesta en marcha, pruebas y depuración

---

## Instrucciones de Uso

Para operar el sistema se deben seguir los siguientes pasos básicos:

### **1. Encendido del sistema**

* Encender controlador y PC con **ATS (Advanced Terminal Software)**.
* Ejecutar el comando `RUN HOMES` para el homing.
* En caso de bloqueo, ejecutar `RUN SHUTD`.

### **2. Activación de ejes con Teach Pendant**

1. Selector en modo **TEACH**.
2. Presionar **CONTROL ON/OFF** hasta ver “Con ALL”.
3. Confirmar con **ENTER**.

### **3. Ejecución de programas**

* Para activar los ciclos automáticos: `RUN LOBBY`.
* El sistema quedará a la espera de pulsos provenientes del Manager.

### **4. Apagado correcto**

* Ejecutar `RUN SHUTD`.
* Esperar a que finalice antes de apagar.

---

## Tecnologías Utilizadas

* **Robótica:** SCORBOT EX IX, Slidebase, Teach Pendant
* **Electrónica:** Tablero Manager, entradas/salidas digitales, electroválvulas
* **Programación:** Lenguaje **ACL** en software ATS
* **Automatización:** Integración de sensores, movimientos interpolados y control secuencial

---

## Listado de Componentes

* Brazo robótico **SCORBOT EX IX**
* Lineal Slidebase ESHED ROBOTEC
* Controlador ESHED ROBOTEC
* Teach Pendant
* Tablero central **Manager**
* Cinta transportadora y estaciones automatizadas
* Electroválvula del gripper
* PC con software **ATS**

---

## Esquemáticos

* Circuito eléctrico del controlador con entradas, salidas y gripper
* Cableado entre Manager y controlador
* Diagramación de plataformas y estaciones

*(Imágenes disponibles en la carpeta PLANOS)*

---

## Fotos / Videos

Incluyen:

* SCORBOT EX IX
* Controlador, Teach Pendant y Slidebase
* Plataformas de trabajo
* Circuito eléctrico
* Bandejas correspondientes a PR1, PR2, PR3 y PR4

*(Disponible en la carpeta MULTIMEDIA)*

---

## Autor

Proyecto realizado por:

* **Audisio, Juan Pablo** – 43.671.648
* **Gomez Franco Gabriel** – 41.451.020
* **Reyna, Valentín** – 43.798.677

Como parte de la **Práctica Profesional Supervisada** de la carrera Ingeniería Mecatrónica.

---

## Carpetas del Proyecto

* **CODIGO:** Programas ACL → LOBBY, PRs, GETXX, PUTXX
* **MULTIMEDIA:** Imágenes, fotografías y videos
* **PLANOS:** Esquemáticos y diagramas eléctricos
* **DATASHEET:** Hojas de datos de componentes
* **INFORMES:** PPS en PDF, Word y documentación complementaria

---

> Este README replica el formato de la plantilla original, incorporando la totalidad del contenido relevante del informe "PPS - ROBOTICA".
