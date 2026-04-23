<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Montserrat&size=28&pause=1000&color=8B0000&center=true&vCenter=true&width=420&lines=Procedimientos" />
</div>

Los datos se obtienen desde **Datos Abiertos Bogotá** y los canales oficiales de **TransMilenio**, siguiendo una metodología de tres etapas:

```mermaid
flowchart TD
    A[Recolección] --> B[Limpieza]
    B --> C[Análisis]
    C --> D[Propuestas]
```

<<div align="center">
<table>
<tr><th>Etapa</th><th>Acción</th><th>Resultado</th></tr>
<tr><td><b>1. Recolección</b></td><td>Fuentes existentes de Datos Abiertos Bogotá y TransMilenio</td><td>Datos por estación</td></tr>
<tr><td><b>2. Limpieza</b></td><td>Depuración de datos incompletos</td><td>Datos organizados</td></tr>
<tr><td><b>3. Agrupación</b></td><td>Clasificación por horas pico y horas valle</td><td>Patrones de demanda</td></tr>
<tr><td><b>4. Indicador</b></td><td>Validaciones vs frecuencia de la ruta FJ23</td><td>Brecha oferta-demanda</td></tr>
<tr><td><b>5. Diagnóstico</b></td><td>Identificación de franjas críticas</td><td>Momentos de congestión</td></tr>
</table>
</div>

> *La capacidad de transporte = frecuencia de buses × capacidad por bus. Si capacidad < validaciones → congestión identificada.*

---

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Montserrat&size=28&pause=1000&color=8B0000&center=true&vCenter=true&width=350&lines=Producto" />
</div>

El entregable final es un **tablero de visualización interactivo** que permite:

<div align="center">
<table>
<tr><th>Funcionalidad</th><th>Descripción</th></tr>
<tr><td>Validaciones por día</td><td>Patrones de uso semanal por estación</td></tr>
<tr><td>Filtro por hora</td><td>Demanda específica por franja horaria</td></tr>
<tr><td>Oferta vs Demanda</td><td>Comparació SI/NO de cobertura del sistema</td></tr>
<tr><td>Escenarios comparativos</td><td>Simulación de rutas nuevas o mayor frecuencia</td></tr>
</table>
</div>

```mermaid
flowchart LR
    A[Dashboard] --> B[Validaciones por dia]
    A --> C[Análisis por hora]
    A --> D[Brecha oferta-demanda]
    A --> E[Escenarios comparativos]
    E --> F[Mayor frecuencia FJ23]
    E --> G[Nueva ruta complementaria]
```

<div align="center">
<img src="https://img.shields.io/badge/Herramienta-Dashboard-red?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Enfoque-Optimización-darkred?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Impacto-Movilidad+Sostenible-orange?style=for-the-badge"/>
</div>

<br/>

> *El producto no solo muestra el problema — evalúa las soluciones.*

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=8B0000&height=120&section=footer" width="100%"/>
</div>



---
<div align="center">

![Analisis](https://readme-typing-svg.demolab.com?font=Montserrat&size=28&pause=1000&color=8B0000&center=true&vCenter=true&width=350&lines=Analisis)

</div>

En la gráfica se observa que en las **horas pico de la tarde**, especialmente entre las **4:00 p.m. y las 6:00 p.m.**, la cantidad de pasajeros en las estaciones **Museo del Oro**, **Las Aguas** y **Los Ríos** supera la capacidad del sistema, lo que evidencia un problema de congestión.

Esto se debe a que estas estaciones dependen únicamente de la ruta **FJ23** durante todo el día, por lo que toda la demanda se concentra en un solo servicio.

---

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Montserrat&size=28&pause=1000&color=8B0000&center=true&vCenter=true&width=350&lines=Solucion+Propuesta" />
</div>

<p align="center">
<img src="./2019_Bogotá_-_Estación_Las_Aguas_de_Transmilenio.jpg" width="65%" style="border-radius:12px;">
</p>

En las horas pico de la tarde, especialmente entre las **4:00 p.m. y las 6:00 p.m.**, la demanda en las estaciones **Museo del Oro**, **Las Aguas** y **Los Ríos** supera la capacidad del sistema. Dado que estas estaciones dependen únicamente de la ruta **FJ23**, toda la carga recae sobre un solo servicio.

Se propone **modificar el recorrido de la ruta H76**, que actualmente sale con baja ocupación desde Universidades-City U, para que inicie en la estación **Las Aguas**, baje por el **Eje Ambiental**, conecte con **Museo del Oro** y se integre en **Avenida Jiménez** antes de continuar hacia la troncal Caracas.

```mermaid
flowchart LR
    A[Las Aguas] --> B[Eje Ambiental]
    B --> C[Museo del Oro]
    C --> D[Avenida Jimenez]
    D --> E[Troncal Caracas]
```
> *Al contar con una segunda ruta en horas pico, se reduce la necesidad de aumentar la frecuencia de la FJ23.*
