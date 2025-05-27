# 📑PROYECTO TRANSVERSAL ASIXc

## 📋 Información General
- [Introducción](#pro01---proyecto-transversal-asixc)
- [Módulos y Resultados de Aprendizaje implicados](#módulos-y-resultados-de-aprendizaje-ra-implicados)
- [Metodología del proyecto](#cómo-se-realiza-el-proyecto)
- [Entrega](#cómo-se-entrega-la-tarea)
- [Descripción del proyecto](#descripción-del-proyecto)
- [Objetivos](#objetivos-del-proyecto)

## 🔍 Tareas a Realizar

### 📊 1. [Propuesta de CPD](#1-propuesta-de-cpd)
- [Brainstorming conceptual](#brainstorming-conceptual-del-diseño)
- [Infraestructura IT](#infraestructura-it)
- [Infraestructura eléctrica](#infraestructura-eléctrica)
- [Seguridad física y lógica](#seguridad-física-y-lógica)
- [Sostenibilidad](#sostenibilidad)
- [Estimación de precio del CPD](#estimación-precio-cpd)
- [Implementación en AWS](#implementación-del-cpd-a-la-nube-aws-con-los-servicios-utilizados-mínimo-de-4---el-servicios-de-audio-video-y-bases-de-datos-se-valoran-en-los-otros-bloques)
- [Comparativa de proveedores cloud](#investigar-y-comparar-eficiencia-energética-con-otros-proveedores-de-la-nube)

### 🎧 2. [Servicios de Audio y Video](#2-implantación-de-los-servicios-de-audio-y-video)
- [Descripción de requerimientos](#bloque-03757-i-03758)
- [Instalación y configuración](#instalación-configuración-y-monitorización-de-un-servidor-de-audio-y-video)
- [Servidor de Audio con IceCAST](#despliegue-de-servidor-de-audio-con-icecast--darkice)
- [Servidor de Video con GStreamer](#despliegue-de-servidor-de-vídeo-con-gstreamer-y-rtp-streaming)
- [Pruebas de ancho de banda](#comprobación-del-ancho-de-banda-con-iperf3)

### 💾 3. [Base de Datos](#3-diseño-e-implementación-de-una-base-de-datos)
- [Modelo Entidad-Relación](#1-modelo-entidad-relación-e-r)
- [Modelo Relacional](#2-transformación-al-modelo-relacional)
- [Implementación](#implementación-de-la-base-de-datos)

### [4. 🌐 Nuestros Servicios](#nuestros-servicios)
- [SRV1](#srv1)
  - [NGINX](#nginx)
- [SRV2](#srv2)
  - [OpenFire](#openfire)
- [SRV3](#srv3)
  - [Bind9](#bind9)
  - [Segundo Servicio SFTP (Secure File Transfer Protocol)](#segundo-servicio-sftp-secure-file-transfer-protocol)
  - [Copias de seguridad/Backups](#copias-de-seguridadbackups)

### 🌱 5. [Sostenibilidad](#4-sostenibilidad)
- [Eficiencia energética](#sostenibilidad-y-eficiencia-energética)
- [Cálculo de huella ecológica](#cálculo-de-la-huella-ecológica-del-proyecto-realizado)
- [Cumplimiento Agenda 2030](#cumplimiento-de-los-objetivos-de-la-agenda-2030)
- [Medidas de reducción](#3--propuesta-de-medidas-de-reducción-u-optimización-por-ejemplo)

### 📝 6. [Entrega y Presentación](#5-entrega-y-presentación)
- [Requisitos de presentación](#5-entrega-y-presentación)
- [Vídeo de presentación](#5-entrega-y-presentación)
- [Exposición oral](#5-entrega-y-presentación)

## 📊 [Rúbricas de Evaluación](#rúbricas)
- [Bloque 0371 Fundamentos de maquinaria](#bloque-0371-fundamentos-de-maquinaria)
- [Bloque 0373 Lenguajes de marcas](#bloque-0373-lenguajes-de-marcas)
- [Bloque 0375 Servicios de redes e internet](#bloque-0375-servicios-de-redes-e-internet)
- [Bloque 0377 Administración de bases de datos](#bloque-0377-administración-de-bases-de-datos)
- [Bloque 1665 Digitalización aplicada](#bloque-1665-digitalización-aplicada-a-los-sectores-productivos)
- [Bloque 1708 Sostenibilidad](#bloque-1708-sostenibilidad)
- [Bloque 1709 IPO](#bloque-1709-ipo)
- [Presentación y defensa](#bloque-presentación-y-defensa-30-de-mayo)

## Pro01 - Proyecto Transversal ASIXc

### Módulos y Resultados de Aprendizaje (RA) implicados

| Módulo | Peso | Tarea | RA | Descripción |
|--------|------|-------|----|--------------------|
| 0371 Conocimientos de maquinaria | 30 | 1 | RA4 | Implanta hardware específico de centros de proceso de datos (CPD), analizando las características y aplicaciones |
| 0373 Lenguaje de Marcas | 2 | 5 | RA3 | Accede y manipula documentos web utilizando lenguajes de guiones de cliente. |
| 0373 Lenguaje de Marcas | 2 | 5 | RA5 | Realiza conversiones sobre documentos para el intercambio de información utilizando técnicas, lenguajes y herramientas de procesamiento. |
| 0373 Lenguaje de Marcas | 2 | 5 | RA6 | Gestiona la información en formatos de intercambio de datos analizando y utilizando tecnologías de almacenamiento y lenguajes de consulta. |
| 0375 Servicios de Redes e internet | 15 | 2 | RA7 | Administra servicios de audio identificando las necesidades de distribución y adaptando los formatos |
| 0375 Servicios de Redes e internet | 15 | 2 | RA8 | Administra servicios de video identificando las necesidades de distribución y adaptando los formatos |
| 0377 Administración de Bases de datos | 10 | 3 | RA3-RA4 | Implanta métodos de control de acceso utilizando asistentes, herramientas gráficas y pedidos del lenguaje |
| 1665 Digitalización aplicada a los sectores productivos | 2 | 1, 2, 3, 5 | RA3 | Caracteriza las tecnologías habilitadoras digitales necesarias para la adecuación/transformación de las empresas a entornos digitales describiendo sus características y aplicaciones. |
| 1665 Digitalización aplicada a los sectores productivos | 2 | 1, 2, 3 | RA5 | Evalúa la importancia de los datos, así como su protección en una economía digital globalizada, definiendo sistemas de seguridad y ciberseguridad tanto a nivel de equipo/sistema, como globales. |
| 1708 Sostenibilidad | 2 | 4 | RA3 | Establece la aplicación de criterios de sostenibilidad en el desempeño profesional y personal, identificando los elementos necesarios. |
| 1708 Sostenibilidad | 1 | 4 | RA4 | Propone productos y servicios responsables teniendo en cuenta los principios de la economía circular. |
| 1708 Sostenibilidad | 2 | 4 | RA5 | Realiza actividades sostenibles minimizando el impacto de las mismas en el medio ambiente. |
| 1709 IPO | | 3 | RA3 | Analiza sus condiciones laborales como persona trabajadora por cuenta ajena, identificándolas en los principales tipos de cambios y vicisitudes relevantes que se pueden presentar en la relación laboral, en la normativa laboral y, especialmente, en el convenio colectivo del sector |
| | 10 | | | Presentación 30 de mayo |

### Cómo se realiza el proyecto:
- Trabajo en grupos de 4 alumnos 
- Hay que generar un proyecto con el nombre: 
  pro-grupoDeClase-grupoDeTrabajo 
  Ejemplo: pro-asixc1a-g1 

### Cómo se entrega la tarea:  
- Informe detallado con las respuestas y justificaciones
- Video-demostración práctico que muestre el proyecto
- Respetar la fecha de entrega

### Descripción del proyecto: 
InnovateTech es una empresa dedicada a la creación y distribución de contenido digital.
Como parte de nuestro compromiso con la innovación tecnológica y la sostenibilidad nos dirigimos a ustedes con el objetivo de diseñar e implantar una arquitectura de Centro de Proceso de Datos (CPD) a la nube adaptada a nuestras necesidades actuales y futuras.

Buscamos una solución integral que integre servicio web de la empresa y de transmisión de audio y video, que sea eficaz en términos de rendimiento, seguridad, y eficiencia energética, alineándose con los Objetivos de Desarrollo Sostenible (ODS) de la Agenda 2030.

InnovateTech se compromete con el desarrollo responsable y sostenible, tal como se refleja en nuestra apuesta por soluciones que cumplan con los Objetivos de Desarrollo Sostenible (ODS) de la Agenda 2030. Concretamente, queremos contribuir activamente a los ODS 7 (Energía asequible y no contaminante), ODS 9 (Industria, innovación e infraestructura), ODS 12 (Producción y consumo responsables), ODS 13 (Acción por el clima) y ODS 16 (Paz, justicia e instituciones sólidas).

### Objetivos del proyecto:
- Diseñar e implantar una infraestructura tecnológica de CPD eficiente, segura y sostenible.
- Implementar una arquitectura de sistemas y comunicaciones que apoyen a los requerimientos de negocio definidos.
- Garantizar la calidad del servicio de transmisión de audio y video con pruebas de ancho de banda realizadas.
- Proteger los datos de clientes y usuarios según las normativas internacionales de seguridad.
- Optimizar el uso de recursos y minimizar el impacto ambiental de la infraestructura tecnológica.
- Calcular la huella ecológica de diferentes procesos.
- Realización de documentación en formato markdown. 

## Tarea a realizar 

### Definición de la Arquitectura de CPD Sostenible
InnovateTech necesita un CPD que sea capaz de gestionar nuestros sistemas de información de manera eficiente y con un mínimo impacto ambiental. Nos gustaría una arquitectura que integre soluciones energéticamente eficientes y con un enfoque claro en la sostenibilidad, como la utilización de energía renovable y sistemas de refrigeración natural. Además, queremos que la solución ofrece un alto nivel de seguridad para proteger tanto nuestra información como la de nuestras plataformas de contenido digital.

## 1. Propuesta de CPD 

Hay que proponer una solución de CPD que contemple -como mínimo- los siguientes requerimientos:

### Brainstorming conceptual del diseño:

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/raw/2436318a60033d2b8823b38d579b37c35dcb9e06/Images/image12.png)

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/75bd6a0e21bbce31b0d908b59996031fe63925b7/Images/image20.png)

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/75bd6a0e21bbce31b0d908b59996031fe63925b7/Images/image108.png)

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/75bd6a0e21bbce31b0d908b59996031fe63925b7/Images/image148.png)

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/405c68e405da9a29112c15d846055d3bac82e3c5/Images/image169.png)

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/405c68e405da9a29112c15d846055d3bac82e3c5/Images/image43.png)

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/405c68e405da9a29112c15d846055d3bac82e3c5/Images/image164.png)

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/405c68e405da9a29112c15d846055d3bac82e3c5/Images/image62.png)


#### 1. Ubicación Física
**Situación dentro del edificio**

El CPD se ubicará en la planta semisótano del edificio corporativo situado en Barcelona (zona verde técnica en el parque natural de Collserola). Su diseño innovador apuesta por la arquitectura más sostenible y moderna del país teniendo en cuenta los objetivos de la agenda 2030. La finalidad de este diseño es realizar el menor impacto posible combinando distintos sistemas de refrigeración natural y el consumo eléctrico mediante la obtención de energías renovables.

La ubicación privilegiada del CPD se debe a distintos factores para poder asegurar el buen funcionamiento de las instalaciones y seguridad de la estructura, ya que al estar en una zona elevada, es más seguro tanto para hurtos como para condiciones climáticas adversas tales como inundaciones, terremotos, tsunamis, etc. Y su elevación proporciona y garantiza el máximo aprovechamiento de la luz solar durante todo el día. Su estructura se adapta perfectamente a la Serralada de Collserola camuflándose entre ella gracias a su diseño discreto y cubierta de césped y jardín natural.

**Materiales y recubrimientos:**
- Aislamiento a base de fibra de madera y pinturas ecológicas sin COV.
  
  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cda8835b4fc2dd518f3d37273f71f294dc529b64/Images/image35.png)
  
- Muros verdes en el exterior para reducir la temperatura ambiente y favorecer el aislamiento térmico y el filtraje y canalización de aguas pluviales.

  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cda8835b4fc2dd518f3d37273f71f294dc529b64/Images/image115.png)

  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cda8835b4fc2dd518f3d37273f71f294dc529b64/Images/image139.png)

  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cda8835b4fc2dd518f3d37273f71f294dc529b64/Images/image123.png)

  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cda8835b4fc2dd518f3d37273f71f294dc529b64/Images/image47.png)
  
- Gestión de aguas: Sistema de recogida de aguas pluviales para climatización indirecta y uso general.

  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cda8835b4fc2dd518f3d37273f71f294dc529b64/Images/image2.png)
  
**Dimensiones y accesos:**
- Pasillos con ancho mínimo de 2 m.

  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cda8835b4fc2dd518f3d37273f71f294dc529b64/Images/image158.png)

- Iluminación LED inteligente con sensores de presencia.

  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cda8835b4fc2dd518f3d37273f71f294dc529b64/Images/image11.png)

#### 2. Sistemas de Climatización y Eficiencia Energética
**2.1 Climatización Activa**
- Unidad CRAC: Aire acondicionado de precisión (Computer Room Air Conditioner) de 30 kW con soporte geométrico.

  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cda8835b4fc2dd518f3d37273f71f294dc529b64/Images/image60.png)

**Rangos operativos:**
- Temperatura: 20 °C – 22 °C (media entre 20 °C y 23 °C).
- Humedad relativa: 45 % – 55 % (oscila entre 40 % y 60 %).

**Filtrado de aire:**
- Prefiltro G4 y filtro HEPA para polvo y partículas.

**2.2 Climatización Pasiva y Geotermia**
- Free Cooling: Ventilación cruzada cuando la temperatura externa sea < 18 °C.

  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cda8835b4fc2dd518f3d37273f71f294dc529b64/Images/image15.png)


  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cda8835b4fc2dd518f3d37273f71f294dc529b64/Images/image156.png)

- Túneles subterráneos: Aprovechamiento del aire fresco de túneles con compuertas inteligentes y sensores climáticos.

  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cda8835b4fc2dd518f3d37273f71f294dc529b64/Images/image56.png)
  
- Geotermia: Pozos verticales de 100 m de profundidad para refrigeración base.

  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cda8835b4fc2dd518f3d37273f71f294dc529b64/Images/image34.png)

  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cda8835b4fc2dd518f3d37273f71f294dc529b64/Images/image135.png)

**2.3 Reutilización de Calor Residual**
- El calor generado por los servidores se canalizará para calefacción de oficinas y agua sanitaria mediante recuperación térmica.
- En invierno, se integrará con el sistema de radiadores del edificio.

  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cda8835b4fc2dd518f3d37273f71f294dc529b64/Images/image107.png)

**2.4 Eficiencia Energética**
- Funcionamiento 24/7 optimizado para bajo consumo sin perder potencia.
- Cubierta solar fotovoltaica de 100 m² con potencia estimada de 30 kWp.

  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/8b6d779db8b4db6d436a2da7355c8be84cc55a6a/Images/image61.png)

#### 3. Seguridad y Discreción
**Dificultad de identificación:**
- Puerta sin señalización ni imágenes que revelen el CPD.
- Paredes acústica y visualmente aisladas.

**Vigilancia:**
- Cámaras de seguridad y sensores de movimiento con monitoreo 24/7.
- Alarmas de humo y control de accesos biométrico.

#### 4. Suelo y Techo Técnico
**4.1 Suelo Técnico Elevado**
- Altura de elevación: 35–40 cm. Techo técnico con conductos modulares de ventilación.
- Refrigeración inferior: Mejor circulación de aire y espacio para cableado.

**Materiales:**
- Sulfato cálcico (aislamiento térmico y acústico, mejora aireación).
- Aglomerado revestido con lámina de PVC o HPL resistente al fuego.
- Cubierta: Vinilo antiestático o conductivo.

  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/8b6d779db8b4db6d436a2da7355c8be84cc55a6a/Images/image137.png)

**4.2 Techo Técnico**
- Modelo: Bergvik Iso Floor (diseño flexible y alta estabilidad estructural).
- Conductos modulares de ventilación intégrés para flujo de aire controlado.

  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/8b6d779db8b4db6d436a2da7355c8be84cc55a6a/Images/image37.png)

#### 5. Distribución y Gestión del Cableado
- Estructura: Bandejas superiores con dos canales separados para datos y alimentación.
- Cableado de datos: UTP Cat 8 para altas velocidades y compatibilidad CPD.
- Cableado de alimentación: Con protección contra subidas y bajadas de tensión.
- Etiquetado: Identificación individual de cada cable para facilitar mantenimiento y reparaciones.

  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/8b6d779db8b4db6d436a2da7355c8be84cc55a6a/Images/image88.jpg)

#### 6. Estructuración de Racks
Se dispondrá de 3 racks idénticos de 42U, 600 mm de ancho y 800 mm de profundidad, color negro, con puertas frontales de cristal templado y traseras de chapa ciega reforzada.

| Rack | Tipo y Modelo | Contenido principal |
|------|---------------|---------------------|
| x3 | Armario rack 19" multipropósito (Lapara Networking) | - U1–U42: PDU y SAI<br>- U1–U2: Firewall FortiGate HA<br>- U3–U6: Core switches (Catalyst & Nexus)<br>- U7–U10: Core Spine adicionales y leaf stacks<br>- U11–U14: Patch panels (UTP y fibra)<br>- U15–U24: Servidores Dell R650 con sus VMs<br>- U25–U42: Reserva para futuros nodos o almacenamiento<br>- Switch de respaldo<br>- SAI secundario<br>- Sistema de monitorización |

**6.1 Características Comunes**
- Patas regulables y ruedas omnidireccionales.
- Techo con ranuras de ventilación y accesos para cableado.
- Paneles laterales desmontables con cerraduras de seguridad.

#### 7. Planos y Diagramas
Se incluirán planos arquitectónicos detallados y diagramas de flujo de aire, distribución de racks y cableado en formato CAD y PDF para su revisión y validación.

  ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/8b6d779db8b4db6d436a2da7355c8be84cc55a6a/Images/image8.jpg)

### Infraestructura IT: 
#### Servidores: Número y tipo de modelo. 

Total: 3 servidores físicos
Model: Dell PowerEdge R650
Recursos por servidor:
- CPU: 32 vCores (2×AMD EPYC)
- RAM: 256 GB DDR4
- Almacenamiento local: 4×1 TB NVMe

#### Switching y Core de red
**Core Layer (Backbone):**
- 1× Cisco Catalyst 9500-24Q (24 × 10 GbE SFP+)
- 2× Cisco Nexus 93180YC-EX en VPC (48 × 1/10 GbE + 6 × 40 GbE)

**Enlaces Troncal:**
- 2× 40 GbE entre Catalyst 9500 y cada Nexus
- Trunks llevando VLAN_DMZ, VLAN_IT, VLAN_DB y VLAN_AV

#### Patch panels. 
En cada rack:
- 2× Patch Panel Cat6A de 24 puertos (UTP RJ-45)
- 1× Patch Panel fibra multimode OM4 de 12 fibras (LC) para uplinks 10/40 GbE

#### Switches de acceso (Leaf).

**Leaf 1 – "Servers & PoE"**
- 2× Cisco Catalyst 9300-48P (48 puertos PoE+, 4× 10 GbE uplink)
- Stack FlexStack-Plus en anillo

**Leaf 2 – "User Access & Patch"**
- 2× Cisco Catalyst 9300-24T (24 puertos Gigabit, 4× 10 GbE uplink)
- Stack FlexStack-Plus en anillo

#### Estimación de coste de material para el CPD (material técnico):

Estimación de coste para toda la Infraestructura IT descrita (equipos, redes y mobiliario):

| CONCEPTO | CANTIDAD | PRECIO (uds.) aprox. | SUBTOTAL aprox. |
|----------|----------|----------------------|-----------------|
| Servidores Dell PowerEdge R650 (32 vCPU, 256 GB, 4×1 TB NVMe) | 3 | 12.000 € | 36.000 € |
| Firewall FortiGate 100F (HA pair) | 2 | 15.000 € | 30.000 € |
| Core Switch Cisco Catalyst 9500-24Q (24×10 GbE) | 1 | 25.000 € | 25.000 € |
| Core Switch Cisco Nexus 93180YC-EX (48×1/10 GbE + 6×40 GbE) | 2 | 40.000 € | 80.000 € |
| Leaf Switch Cisco Catalyst 9300-48P (48 PoE+, 4×10 GbE) | 2 | 12.000 € | 24.000 € |
| Leaf Switch Cisco Catalyst 9300-24T (24 GbE, 4×10 GbE) | 2 | 8.000 € | 16.000 € |
| Patch panels Cat6A 24 puertos | 6 | 200 € | 1.200 € |
| Patch panels Fibra multimodo OM4 (12 LC) | 3 | 300 € | 900 € |
| Armarios/Racks 42U | 3 | 1.000 € | 3.000 € |
| Cables (UTP Cat6A, fibra, fibra OM4) | __ | __ | 2.000 € (estim.) |
| **Total aproximado** | | | **218.100 €** |

#### Planells i diagrames de com estan distribuïts els racks amb els servidors, patch panels i switches. 

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/8b6d779db8b4db6d436a2da7355c8be84cc55a6a/Images/image120.png)
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/8b6d779db8b4db6d436a2da7355c8be84cc55a6a/Images/image76.png)

U1–U2: Firewall FortiGate HA
U3–U6: Core switches (Catalyst & Nexus)
U7–U10: Core Spine adicionales y leaf stacks
U11–U14: Patch panels (UTP y fibra)
U15–U24: Servidores Dell R650 con sus VMs
U25–U42: Reserva para futuros nodos o almacenamiento
Switch de respaldo
SAI secundario
Sistema de monitorización
U25–U42: Reserva para futuros nodos o almacenamiento

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/8b6d779db8b4db6d436a2da7355c8be84cc55a6a/Images/image110.png)
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/8b6d779db8b4db6d436a2da7355c8be84cc55a6a/Images/image74.png)
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/8b6d779db8b4db6d436a2da7355c8be84cc55a6a/Images/image128.png)

### Infraestructura eléctrica: 
#### Sistemas de alimentación redundante. 
Para garantizar una alta disponibilidad, implementaremos:
Un dual feed (doble tendido eléctrico en español): dos fuentes de alimentación independientes conectadas a distintos cuadros eléctricos, evitando así fallos en el suministramiento de energía, permitiendo el mantenimiento de componentes electrónicos sin parar los servicios y de esta manera alinearse con las buenas prácticas de diseño de CPD, que aparecen en el estándar del Uptime Institute.

#### SAIS. Cálculo de cuántas baterías o componentes para tener los servidores operativos sin corriente eléctrica y tiempo que voláis de funcionamiento sin señal eléctrica en los servidores.
Vamos a utilizar la siguiente fórmula para saber la duración de las baterías:
SAI / UPS = ((N x V x AH x Eff) / VA) x 60
- Siendo:

N = número de baterías en el SAI
V = voltaje de las baterías
AH = Amperios-Hora de las baterías
Eff = eficiencia del SAI (por norma, suele oscilar entre el 90% y el 98% dependiendo del SAI)
VA = Volti-Amperios del SAI

Tenemos 3 servidores de consumo medio: 400 W cada uno → 1200 W total
Utilizaremos un SAI de 1000 VA → 	Eaton 5PX 1000i RT2U

Eficacia (Eff): 0,95 (95%) ![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/8b6d779db8b4db6d436a2da7355c8be84cc55a6a/Images/image51.png)

Batería → 6x 12V 9Ah AGM:

N = 6 baterías
V = 12V por batería 
AH = 9 Ah

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/9f286f70adc3536b8f16c355c99fa5b28d75f467/Images/image103.png)

Cálculo, energía total de las baterías:

N x V x AH = 6 x 12V x 9Ah = 648 Wh
				
Añadiendo la eficiencia
				
432 x 0,95 = 615,6 Wh

Lo dividimos entre la potencia (VA)

410,4 / 1000 = 0,6156 horas → 0,4104 × 60 = 36,936 minutos
			
Este tiempo es la duración del SAI a máxima demanda, es decir que a menor consumo mayor duración y esta es la duración mínima (37 min aprox.)

### Seguridad física y lógica: 

#### Física: 
##### Elementos de control de acceso a incorporar en el CPD
Para el control de acceso tendremos una doble autenticación, la cual consta de acceso biométrico y tarjetas RFID, para esto utilizaremos el siguiente:

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/9f286f70adc3536b8f16c355c99fa5b28d75f467/Images/image22.png)

##### Videovigilancia
En cuanto la videovigilancia tendremos 2 cámaras las cuales están grabando 24/7, estas tendrán características como visión nocturna, con calidad de grabación de full hd a 30 fps y con la tecnología de Ultra Compresión H.265+, esto para tratar de consumir el menor almacenamiento posible estas estarán configuradas con ips fijas, estas estarán ubicadas en la entrada de la sala del CPD.

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/9f286f70adc3536b8f16c355c99fa5b28d75f467/Images/image167.png)

##### Sistemas de prevención, detección y de extinción de incendios. 
1. **Prevención**
   - Control de temperatura y humedad para mantener condiciones estables para evitar sobrecalentamientos y riesgos eléctricos.

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/9f286f70adc3536b8f16c355c99fa5b28d75f467/Images/image93.png)

   - Mantenimiento eléctrico y revisión de cableado: Evita cortocircuitos y fallos que puedan generar chispas.

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/9f286f70adc3536b8f16c355c99fa5b28d75f467/Images/image84.png)
     
   - Uso de materiales ignífugos en racks, suelos y techos técnicos: Reduce la propagación en caso de fuego.

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/9f286f70adc3536b8f16c355c99fa5b28d75f467/Images/image18.png)

1. **Detección**

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/12fcee646d497078b9c25a60013f80b1a0a9ad9e/Images/image65.png)

   - Sistema VESDA (Very Early Smoke Detection Apparatus): Detección de humo muy temprana mediante aspiración continua del aire. Ideal para entornos críticos como CPDs.

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/12fcee646d497078b9c25a60013f80b1a0a9ad9e/Images/image149.png)
     
   - Detectores ópticos de humo: Refuerzan la seguridad, ubicados en techos y zonas sensibles.

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/12fcee646d497078b9c25a60013f80b1a0a9ad9e/Images/image129.png)

   - Sensores de temperatura y gases: Detectan aumentos bruscos o liberación de compuestos combustibles.

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/12fcee646d497078b9c25a60013f80b1a0a9ad9e/Images/image111.png)

1. **Extinción**

   - Sistema de gas limpio (FM-200 o Novec 1230): Apaga el fuego sin dañar los equipos electrónicos y sin dejar residuos.

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/12fcee646d497078b9c25a60013f80b1a0a9ad9e/Images/image50.png)
     
   - Botellas presurizadas con sensores de activación automática: Se activan automáticamente tras la detección o manualmente desde un panel de control.

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/fa82b6ab91277ce1afe07377d329175694376850/Images/image106.png)

   - Panel de alarma y corte eléctrico de emergencia: Detiene la energía en caso de incendio para evitar más daños.

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/fa82b6ab91277ce1afe07377d329175694376850/Images/image79.png)

##### Vías de evacuación. 
Hemos instalado salidas de emergencia con señalización LED autónoma, visible incluso en condiciones de humo o fallo eléctrico. Además, hemos colocado planos de evacuación bien señalizados que muestran las rutas de escape, zonas seguras y el punto donde te encuentras. Las puertas están equipadas con barras antipánico y fabricadas con materiales ignífugos, sin necesidad de llaves para abrirlas, lo que nos garantiza una evacuación rápida y segura en caso de cualquier emergencia.

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/fa82b6ab91277ce1afe07377d329175694376850/Images/image45.png)

##### Diagrames, planells i fotografies de tota la seguretat física incorporada.

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/fa82b6ab91277ce1afe07377d329175694376850/Images/image46.png)

#### Seguridad lógica: 
##### Restricción de acceso mediante autorización.

El sistema que hemos elegido, es que para acceder al CPD solo puedan
acceder ciertos usuarios, dependiendo de su rol, y a qué grupo / OU 
pertenecen, para ello usaremos AD (Active Directory)

##### Firewalls. 

El firewall que hemos elegido es Pfsense, hemos elegido esto es porque 
tiene ciertas características:

- Funciones de routing y firewall avanzado 
- Balanceador de carga
- Servidor DNS
- Traducciones de Direcciones de Red (NAT)
- Cliente / Servidor de VPN con IPsec y OpenVPN
- Monitorización de red mediante log y gráficas
- IPS e IDS

**Sistemas de Prevención de Intrusos (IPS)**
**Sistema de Detección de Intrusos (IDS)**

**¿Cuál es su función?**

Se complementan entre sí, ya que ambos sistemas se encargan de vigilar el tráfico, miran los puertos, los paquetes, para poder detectar paquetes sospechosos. 

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/bf96cacb6431441214ce53564aaadc9dbf47fbb8/Images/Image173.png)
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/bf96cacb6431441214ce53564aaadc9dbf47fbb8/Images/Image174.png)

##### Monitorización. 

El software de monitorización que utilizaremos es el Zabbix, porque dispone de 
ciertas características entre las que destacamos:

- Gratuito
- Personalizable mediante scripts y plantillas. 
- Puede supervisar servidores, redes, base de datos, incluso aplicaciones y servicios que tengamos.
- Notificaciones: Activar alertas por múltiples plataformas, gmail, Telegram, sms entre otras.
- Flexibilidad: Ya que permite monitorizar múltiples dispositivos y sistemas.
- Escalabilidad: Puede escalarse y monitorizar más dispositivos a medida que la empresa vaya creciendo.
- Uso: Dispone de una interfaz gráfica muy amigable, para que podamos usarla con facilidad.
- Comunidad: Dispone de una comunidad que a día de hoy está activa, con desarrolladores de soporte y ayuda. 

##### Copias de seguridad/Backups

Al tratarse de una base de datos de tamaño reducido, poco cambiante, nos limitaremos a realizar solo copias de seguridad completas semanales cada lunes que además estarán encriptadas para mayor seguridad (con GPG). Utilizaremos mysqldump para hacer las copias de seguridad. De tener mayor complejidad la base de datos nos regiríamos por el principio abuelo-padre-hijo, es decir:

- Abuelo (Grandfather): Copia de seguridad completa realizada una vez al mes.
- Padre (Father): Copia de seguridad diferencial realizada una vez a la semana.
- Hijo (Son): Copias incrementales realizadas diariamente.

Conservariamos las copias de seguridad “hijo” (diarias) durante 7 a 14 días, las copias de seguridad “padre” (semanales) durante 4 a 6 semanas y las copias de seguridad “abuelo” (mensuales) durante 12 a 24 meses.

##### RAIDs. 

Utilizaremos un RAID 5 por las siguientes razones:

- Mayor capacidad en discos: Con este RAID solo no usaremos un disco, pero podremos aprovechar más los otros discos.
- Equilibrio: Con este RAID tendremos un equilibrio entre el rendimiento de lectura y escritura, así como también la tolerancia a fallos, en caso de que falle uno, el disco duro que no estemos utilizando se activará automáticamente.

#### Prevención de riesgos laborales: 

##### Medidas aplicadas en materia de prevención de RRLL en el CPD
Aplicamos medidas de prevención de riesgos laborales para proteger al personal y los equipos. Contamos con alfombras antiestáticas para evitar descargas, 

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/e61c771e04b90abff69c27c5448560e6235d8bd7/Images/image28.png)

iluminación con sensores de movimiento para mayor seguridad y eficiencia.

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/e61c771e04b90abff69c27c5448560e6235d8bd7/Images/image114.png)

Señalización clara sobre riesgos y el uso obligatorio de EPIs (como el calzado aislante). 

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/e61c771e04b90abff69c27c5448560e6235d8bd7/Images/image94.png)

Además, hemos instalado extintores de CO₂

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/e61c771e04b90abff69c27c5448560e6235d8bd7/Images/image145.png)

luces de emergencia, señales de información visible que garantizan una evacuación segura en caso de incidente y se dispone de un mapa de evacuación.

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/e61c771e04b90abff69c27c5448560e6235d8bd7/Images/image9.png)

### Sostenibilidad: 

#### Resumen de sostenibilidad del CPD:

El CPD dispone de una unidad CRAC de 30 kW y tres servidores Dell PowerEdge R650 con un consumo medio conjunto de 1,2 kW, funcionando 24/7, lo que arroja un consumo anual aproximado de 273.312 kWh. La cubierta fotovoltaica de 100 m² (30 kWp) produciría unos 49.380 kWh/año, es decir, un 18,1 % de la energía necesaria provendría directamente de renovables. A este ahorro se suman las estrategias pasivas (free cooling, geotermia), la reutilización de calor residual y las medidas de eficiencia (iluminación LED con sensores, recogida de aguas pluviales, optimización de paradas de equipos), que permiten reducir notablemente la huella energética y económica del CPD.

#### Cómo optimizar el consumo de energía:

**Free Cooling:**
- Ventilación cruzada cuando la temperatura exterior < 18 °C, permitiendo prescindir del compresor CRAC y ahorros de hasta un 40 % en refrigeración.
- Aprovechamiento de túneles subterráneos con compuertas inteligentes y sensores climáticos para usar aire fresco.

**Geotermia:**
- Pozos verticales de 100 m de profundidad que aprovechan la inercia térmica del subsuelo para refrigeración base.

**Reutilización de calor residual:**
- El 98 % de la energía consumida se convierte en calor, recuperado para calefacción de oficinas y agua sanitaria.
- Integración con radiadores del edificio en invierno.

**Optimización de operación 24/7:**
- Parada automática de equipos de comunicaciones cuando no hay carga.
- Mantenimiento preventivo de cableado y componentes para evitar sobreconsumos.

**Iluminación LED inteligente:**
- Sensores de presencia que apagan luces cuando no hay personas, reduciendo hasta un 40 % el consumo de iluminación.

#### Uso de energía verde para el CPD: 

**Cubierta solar fotovoltaica:**
- 100 m² instalados → 30 kWp de potencia.
- Producción estimada: 30 kWp × 1.646 kWh/kWp = 49.380 kWh/año.
- 18,1 % del consumo anual (273.312 kWh) proviene de energía solar in situ.

**Recomendaciones futuras:**
- Ampliar potencia PV o incorporar seguimiento bifacial (> 2.000 kWh/kWp).
- Instalar baterías para maximizar autoconsumo y almacenamiento nocturno.

#### Ahorro en longitud de cableado:

**Diseño de racks y bandejas:**
- Distribución optimizada de racks y patch paneles para trayectos de cable más cortos.
- Bandejas superiores con dos canales separados (datos y alimentación) minimizan cruces y longitudes innecesarias.

#### Sistemas de circulación de aire que aprovechen condiciones naturales:

- Free Cooling y túneles subterráneos (ver "Cómo optimizar el consumo de energía").
- Suelo técnico elevado con apertura de conductos modulares:
  - Mejor circulación del aire frío desde la base de racks.
- Techo técnico con conductos integrados:
  - Flujo de aire controlado en la parte superior, cerrando el circuito de ventilación natural.

#### Parada de equipos de comunicaciones cuando no hay carga:

**Automatización inteligente:**
- Sistemas de monitorización que detectan inactividad y detienen switches y servidores de acceso.
- Hardware de bajo consumo:
  - Equipos con modos de suspensión y wake-on-LAN que reducen drásticamente el consumo en periodos de baja carga.

#### Equipos de bajo consumo energético:

**Servidores Dell PowerEdge R650:**
- Consumo medio: 400W por equipo, optimizados para eficiencia en virtualización.
- SAI Eaton 5PX 1000i RT2U:
  - Eficiencia del 95 % en la conversión, minimizando pérdidas durante la alimentación de reserva.
- Iluminación LED y pinturas ecológicas (sin COV):
  - Materiales de bajo impacto que reducen la demanda indirecta de climatización.

### ESTIMACIÓN PRECIO CPD:

A continuación mostramos el cálculo estimado de costes para implementar nuestro CPD, teniendo en cuenta todas las siguientes categorías:

#### 🖥️ Hardware y Equipamiento de Red

| Concepto | Cantidad | Precio Unitario | Subtotal |
|----------|----------|-----------------|----------|
| Servidores Dell PowerEdge R650 | 3 | 12.000 € | 36.000 € |
| Firewall FortiGate 100F (HA pair) | 2 | 15.000 € | 30.000 € |
| Core Switch Cisco Catalyst 9500-24Q | 1 | 25.000 € | 25.000 € |
| Core Switch Cisco Nexus 93180YC-EX | 2 | 40.000 € | 80.000 € |
| Leaf Switch Cisco Catalyst 9300-48P | 2 | 12.000 € | 24.000 € |
| Leaf Switch Cisco Catalyst 9300-24T | 2 | 8.000 € | 16.000 € |
| Patch panels Cat6A 24 puertos | 6 | 200 € | 1.200 € |
| Patch panels Fibra multimodo OM4 (12 LC) | 3 | 300 € | 900 € |
| Armarios/Racks 42U | 3 | 1.000 € | 3.000 € |
| Cables (UTP Cat6A, fibra, fibra OM4) | — | — | 2.000 € (estim.) |
| **Subtotal Hardware y Red** | | | **218.100 €** |

#### 💻 Licencias de Software y Sistemas Operativos

| Concepto | Cantidad | Precio Unitario | Subtotal |
|----------|----------|-----------------|----------|
| VMware vSphere Essentials Plus (3 hosts, 144 cores) | 1 | 7.500 € | 7.500 € |
| Windows Server 2025 Datacenter (3 licencias) | 3 | 400 € | 1.200 € |
| CALs Windows Server 2025 (50 usuarios) | 50 | 47 € | 2.350 € |
| Zabbix (versión gratuita) | — | 0 € | 0 € |
| Splunk Enterprise (licencia básica) | 1 | 1.500 € | 1.500 € |
| Veeam Backup Essentials (3 servidores) | 1 | 1.500 € | 1.500 € |
| **Subtotal Licencias y Software** | | | **14.050 €** |

#### 🔋 Sistemas de Alimentación Ininterrumpida (SAI)

| Concepto | Cantidad | Precio Unitario | Subtotal |
|----------|----------|-----------------|----------|
| SAI Eaton 5PX 1000i RT2U | 3 | 1.200 € | 3.600 € |
| Baterías adicionales (6x 12V 9Ah AGM por SAI) | 3 sets | 300 € | 900 € |
| **Subtotal SAI y Baterías** | | | **4.500 €** |

#### ❄️ Climatización y Eficiencia Energética

| Concepto | Cantidad | Precio Unitario | Subtotal |
|----------|----------|-----------------|----------|
| Unidad CRAC de 30 kW | 1 | 25.000 € | 25.000 € |
| Sistema de geotermia (pozos de 100 m) | 1 | 15.000 € | 15.000 € |
| Sistema de free cooling y túneles subterráneos | 1 | 10.000 € | 10.000 € |
| Cubierta solar fotovoltaica (100 m², 30 kWp) | 1 | 30.000 € | 30.000 € |
| **Subtotal Climatización y Energía** | | | **80.000 €** |

#### 🔐 Seguridad Física y Lógica

| Concepto | Cantidad | Precio Unitario | Subtotal |
|----------|----------|-----------------|----------|
| Control de acceso biométrico y tarjetas RFID | 1 | 5.000 € | 5.000 € |
| Cámaras de videovigilancia (Full HD, H.265+) | 2 | 500 € | 1.000 € |
| Sistema VESDA (detección temprana de humo) | 1 | 10.000 € | 10.000 € |
| Sistema de extinción por gas limpio (FM-200/Novec 1230) | 1 | 20.000 € | 20.000 € |
| Panel de alarma y corte eléctrico de emergencia | 1 | 2.000 € | 2.000 € |
| Señalización y salidas de emergencia | 1 | 1.000 € | 1.000 € |
| **Subtotal Seguridad** | | | **39.000 €** |

#### 🏗️ Infraestructura Física y Cableado

| Concepto | Cantidad | Precio Unitario | Subtotal |
|----------|----------|-----------------|----------|
| Suelo técnico elevado (35–40 cm) | 1 | 15.000 € | 15.000 € |
| Techo técnico Bergvik Iso Floor | 1 | 10.000 € | 10.000 € |
| Bandejas superiores para cableado | 1 | 5.000 € | 5.000 € |
| Cableado estructurado (UTP Cat8, alimentación) | 1 | 10.000 € | 10.000 € |
| **Subtotal Infraestructura Física** | | | **40.000 €** |

#### 🔄 Instalación, Configuración y Mantenimiento

| Concepto | Cantidad | Precio Unitario | Subtotal |
|----------|----------|-----------------|----------|
| Instalación y configuración de hardware y software | 1 | 10.000 € | 10.000 € |
| Mantenimiento preventivo anual | 1 | 5.000 € | 5.000 € |
| **Subtotal Servicios** | | | **15.000 €** |

#### 💰 Resumen de Costes

| Categoría | Subtotal |
|-----------|----------|
| Hardware y Equipamiento de Red | 218.100 € |
| Licencias de Software y Sistemas | 14.050 € |
| Sistemas de Alimentación (SAI) | 4.500 € |
| Climatización y Energía | 80.000 € |
| Seguridad Física y Lógica | 39.000 € |
| Infraestructura Física y Cableado | 40.000 € |
| Instalación y Mantenimiento | 15.000 € |
| **Total Aproximado** | **410.650 €** |

### Implementación del CPD a la nube AWS con los servicios utilizados (mínimo de 4 - el servicios de audio, video y bases de datos se valoran en los otros bloques).

## Nuestros Servicios

### SRV1

#### NGINX

Primero actualizamos los paquetes de la máquina:

```bash
sudo apt update
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image147.png)

Luego instalamos el servicio de nginx:

```bash
sudo apt install nginx apache2-utils -y
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image64.png)

Creamos la estructura de directorios web:

```bash
sudo mkdir -p /var/www/pt-grup1-asixcd1.itb.cat/web
sudo mkdir -p /var/www/pt-grup1-asixcd1.itb.cat/admin
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image95.png)

Agregamos contenido temporal para poder hacer pruebas en las páginas:

```bash
echo "<h1>Web Page</h1>" | sudo tee /var/www/pt-grup1-asixcd1.itb.cat/web/index.html
echo "<h1>Admin Page</h1>" | sudo tee /var/www/pt-grup1-asixcd1.itb.cat/admin/index.html
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image91.png)

Agregamos permisos:    

```bash
sudo chown -R www-data:www-data /var/www/pt-grup1-asixcd1.itb.cat
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image121.png)

Creamos el usuario admin con la contraseña pirineus para la web:

```bash
sudo htpasswd -c /etc/nginx/.htpasswd admin
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image58.png)

Configuramos nginx con virtual host y https:

Primero creamos los directorios para los certificados:

```bash
sudo mkdir -p /etc/ssl/pt-grup1
cd /etc/ssl/pt-grup1
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image52.png)

Creamos el certificado con openssl:

```bash
sudo openssl req -x509 -newkey rsa:2048 -keyout /etc/nginx/ssl/server.key pt-grup1.key -out  pt-grup1.crt -days 365 -nodes
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image72.png)

Luego creamos el archivo de configuración `/etc/nginx/sites-available/pt-grup1-asixcd1.itb.cat` y añadimos el siguiente contenido:

```nginx

server {
    listen 80;
    server_name pt-grup1-asixcd1.itb.cat;
    return 301 https://$host$request_uri;
}

server {
    listen 443 ssl;
    server_name pt-grup1-asixcd1.itb.cat;

    ssl_certificate /etc/ssl/pt-grup1/pt-grup1.crt;
    ssl_certificate_key /etc/ssl/pt-grup1/pt-grup1.key;

    root /var/www/pt-grup1-asixcd1.itb.cat/web;
    index index.html;

    location / {
        try_files $uri $uri/ =404;
    }

    location /admin/ {
        alias /var/www/pt-grup1-asixcd1.itb.cat/admin/;
        auth_basic "Restricted Content";
        auth_basic_user_file /etc/nginx/.htpasswd;
        index index.html;
        # Configuramos para que al apartado de admin solo se pueda acceder mediante la ip publica del #inst
        allow 3.214.255.64;
        deny all;
    }
}
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image102.png)

Creamos el enlace simbólico para activar el sitio:

```bash
sudo ln -s /etc/nginx/sites-available/pt-grup1-asixcd1.itb.cat /etc/nginx/sites-enabled/
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image38.png)

Verificamos y reiniciamos el servicio:

```bash
sudo nginx -t
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image172.png)

Comprobamos mediante el curl:

https (admin)
```bash
curl -k -u admin:pirineus https://pt-grup1-asixcd1.itb.cat/admin/
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image122.png)

http (web)
```bash
curl -k https://pt-grup1-asixcd1.itb.cat
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image171.png)

Comprobación desde el exterior:

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image155.png)

Comprobación de la página admin:

Credenciales:

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image134.png)

Resultado:

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image42.png)

Ahora mediante nginx cumplimos los siguientes objetivos:
- Servir contenido multimedia (audio y vídeo bajo demanda)
- Simular pruebas de carga y ancho de banda
- Proteger rutas sensibles (/admin)
- Visualizar estadísticas de acceso al servidor

Estructura del nginx:
- Hemos creado estas carpetas en el servidor:
  - /web → Para los archivos públicos (mp3, bin, vídeo, HTML)

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image25.png)

  - /admin → Para estadísticas y contenido restringido

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image23.png)

Servidor de audio con nginx de baja demanda:
```bash
sudo mkdir -p /web/audio
sudo cp sample.mp3 /web/audio/
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image159.png)

Servidor de video con nginx:
```bash
sudo mkdir -p /web/video
sudo cp sample.webm /web/video/
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image48.png)

Simulación de ancho de banda, hemos generado un archivo grande (test100mb.bin) con dd para que mediante el curl los clientes puedan ver el ancho de banda:
```bash
dd if=/dev/urandom of=/web/test100mb.bin bs=1M count=100
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image166.png)

Estadísticas del servidor (GoAccess):
- Hemos instalado GoAccess y lo usamos para generar stats.html
- Este archivo muestra las estadísticas de tráfico, archivos accedidos, IPs, etc.
- Lo colocamos en /admin, protegido por usuario y contraseña + IP

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f5805997ecddd61cec236651922479b4342bec77/Images/image90.png)

### SRV2

#### OpenFire

Primero haremos un apt update y upgrade:

```bash
sudo apt update && sudo apt upgrade -y
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cb844f9f55e72b0f13452d5e6c98d0dd324b662c/Images/image152.png)

Instalaremos una versión de java ya que el OpenFire usa este:

```bash
sudo apt install openjdk-11-jre -y
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cb844f9f55e72b0f13452d5e6c98d0dd324b662c/Images/image116.png)

Creamos el directorio openfire y desde ahí lo ejecutaremos:

```bash
mkdir -p ~/openfire
cd ~/openfire
wget https://www.igniterealtime.org/downloadServlet?filename=openfire/openfire_4.9.2_all.deb -O openfire_4.9.2_all.deb
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cb844f9f55e72b0f13452d5e6c98d0dd324b662c/Images/image57.png)
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/cb844f9f55e72b0f13452d5e6c98d0dd324b662c/Images/image132.png)


Iniciamos el servicio de Openfire:

```bash
sudo systemctl start openfire
sudo systemctl enable openfire
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/3f5fc6880554e02d2113c67a1b7ca20a48372781/Images/image89.png)


Abrimos el puerto y accedemos a la consola web de Openfire:

```bash
sudo ufw allow 9090/tcp
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/3f5fc6880554e02d2113c67a1b7ca20a48372781/Images/image78.png)
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/3f5fc6880554e02d2113c67a1b7ca20a48372781/Images/image140.png)
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/3f5fc6880554e02d2113c67a1b7ca20a48372781/Images/image80.png)
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/3f5fc6880554e02d2113c67a1b7ca20a48372781/Images/image71.png)
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/50400c2d0b9bf67b3612a70df9cee2441ac69a3e/Images/image70.png)


Nos conectamos a la consola y accedemos con el usuario:

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/50400c2d0b9bf67b3612a70df9cee2441ac69a3e/Images/image151.png)
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/50400c2d0b9bf67b3612a70df9cee2441ac69a3e/Images/image112.png)

Creamos los usuarios:

Biel: <br>
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/50400c2d0b9bf67b3612a70df9cee2441ac69a3e/Images/image117.png)

Giuseppe: <br>
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/50400c2d0b9bf67b3612a70df9cee2441ac69a3e/Images/image29.png)

Bryan: <br>
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/50400c2d0b9bf67b3612a70df9cee2441ac69a3e/Images/image66.png)

Dani: <br>
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/50400c2d0b9bf67b3612a70df9cee2441ac69a3e/Images/image1.png)

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/50400c2d0b9bf67b3612a70df9cee2441ac69a3e/Images/image109.png)

Comprobamos desde los clientes el correcto funcionamiento:

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/50400c2d0b9bf67b3612a70df9cee2441ac69a3e/Images/image53.png)

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/50400c2d0b9bf67b3612a70df9cee2441ac69a3e/Images/image83.png)

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/50400c2d0b9bf67b3612a70df9cee2441ac69a3e/Images/image81.png)

### SRV3

#### Bind9

Instalamos el bind9:

```bash
sudo apt install bind9 bind9utils -y
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/3339d10bb2b1e693a731abd4a34441fc79690ea5/Images/image124.png)

En AWS asignamos la IP pública como IP elástica, es decir, que la IP Pública no cambia.
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/3339d10bb2b1e693a731abd4a34441fc79690ea5/Images/image63.png)

Editaremos este archivo de la siguiente manera:

```bash
sudo nano /etc/bind/named.conf.local
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/3339d10bb2b1e693a731abd4a34441fc79690ea5/Images/image105.png)

Ahora lo configuramos de la siguiente manera:

```bash
sudo nano /etc/bind/db.pt-grup1-asixcd1.itb.cat
```

```
; BIND data file for local loopback interface
$TTL    604800
@       IN      SOA     ns1.pt-grup1-asixcd1.itb.cat. admin.pt-grup1-asixcd1.itb.cat. (
                             2               ; Serial
                        604800               ; Refresh
                         86400               ; Retry
                       2419200               ; Expire
                        604800 )             ; Negative Cache TTL

;       
@       IN      NS      ns1.pt-grup1-asixcd1.itb.cat.
@       IN      A       3.214.255.64
ns1     IN      A       44.217.11.138
pt-grup1-asixcd1    IN      A       3.214.255.64
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/3339d10bb2b1e693a731abd4a34441fc79690ea5/Images/image138.png)


Ahora configuramos este archivo de la siguiente manera:

```bash
sudo nano /etc/bind/db.3.214.255
```

```
; BIND data file for local loopback interface
$TTL    604800
@       IN      SOA     ns1.pt-grup1-asixcd1.itb.cat. admin.pt-grup1-asixcd1.itb.cat. (
                             2           ; Serial
                         604800       ; Refresh
                          86400       ; Retry
                        2419200       ; Expire
                         604800 )     ; Negative Cache TTL

; 
@       IN      NS      ns1.pt-grup1-asixcd1.itb.cat.
@       IN      A       3.214.255.64
ns1     IN      A       44.217.11.138
pt-grup1-asixcd1 IN A       3.214.255.64
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/3339d10bb2b1e693a731abd4a34441fc79690ea5/Images/image138.png)


Probamos la conectividad al dominio:

```bash
nslookup pt-grup1-aslxcdi.ttb.cat 44.217.11.138
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/281373f25304329cd1d809da02d2475a9983b673/Images/imagen_2025-05-26_211112210.png)

```bash
ping pt-grup1-asixcd1.itb.cat
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/281373f25304329cd1d809da02d2475a9983b673/Images/image55.png)

#### Segundo Servicio SFTP (Secure File Transfer Protocol)

Update y Upgrade:

```bash
sudo apt update && sudo apt upgrade -y
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c0ca8fbaa7f4bfe3a5072750712708cc235bc089/Images/imagen_2025-05-26_211833909.png)

Instalamos el proftpd:

```bash
sudo apt install proftpd -y
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c0ca8fbaa7f4bfe3a5072750712708cc235bc089/Images/image13.png)

Hacemos un primer start del servicio de ftp:

```bash
sudo systemctl start proftpd
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c0ca8fbaa7f4bfe3a5072750712708cc235bc089/Images/image67.png)

Comprobamos el estado del servicio:

```bash
sudo systemctl status proftpd
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c0ca8fbaa7f4bfe3a5072750712708cc235bc089/Images/image104.png)

Configuramos el archivo de la siguiente manera añadiendo o descomentando líneas en `/etc/proftpd/proftpd.conf`:

```
<Limit LOGIN>
    Allowuser ftp
    DenyAll
</Limit>

<Anonymous /var/ftp/>
    User ftp
    Group nogroup
    # We want clients to be able to login with "anonymous" as well as "ftp"
    UserAlias anonymous ftp
    # Cosmetic changes, all files belong to ftp user
    DirFakeUser on ftp
    DirFakeGroup on ftp

    RequireValidShell off

    # Limit the maximum number of anonymous logins
    MaxClients 10

    # We want 'welcome.msg' displayed at login, and '.message' displayed
    # in each newly chdir directory.
    DisplayLogin welcome.msg
    DisplayChdir .message

    # Limit WRITE everywhere in the anonymous chroot
    <Directory *>
        <Limit WRITE>
            DenyAll
        </Limit>
    </Directory>

    # Uncomment this if you're brave.
    # <Directory incoming>
    #     Umask 022 is a good standard umask to prevent new files and dirs
    #     (second parm) from being group and world writable.
    #     Umask022 022
    #     <Limit READ WRITE>
    #         DenyAll
    #     </Limit>
    #     <Limit STORE>
    #         AllowAll
    #     </Limit>
    # </Directory>
</Anonymous>
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/06c56644eba54dd42818963351cc5ce067d0f4bd/Images/image118.png)

Hacemos la prueba para acceder como anónimo:

```bash
ftp 44.217.11.138
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/06c56644eba54dd42818963351cc5ce067d0f4bd/Images/image136.png)

Ahora configuramos el sftp con el fin de poder acceder como administrador:

```bash
sudo cat /etc/proftpd/sftp.conf
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/06c56644eba54dd42818963351cc5ce067d0f4bd/Images/image119.png)

Puertos pasivos:

```bash
ftp ftp@44.217.11.138
quote PASV
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/06c56644eba54dd42818963351cc5ce067d0f4bd/Images/image77.png)

Backups:
- Utilizaremos el siguiente script:

```bash
#!/bin/bash

#Requisitos previos: en ambos servidores tener instalada
#la herramienta llamada mysqldump
#con tal de automatizarlo utilizamos crontab -e y agregamos la siguiente linea:
#0 2 * * * /home/ubuntu/backup.sh >> /home/ubuntu/backup.log 2>&1

# Configuración
FECHA=$(date +%Y%m%d_%H%M%S)
HOY=$(date +%u)      # Día de la semana (1-7, 1=lunes)
DIA_MES=$(date +%d)  # Día del mes
BACKUP_ROOT="/home/ubuntu/backups"
MYSQL_USER="root"
MYSQL_PASS=""
DB_NAME="BD_Transversal"
REMOTE_USER="ubuntu"
REMOTE_IP="172.31.44.222"
REMOTE_DIR="/home/ubuntu/backups"
KEY="/home/ubuntu/SRV1-KEY.pem"

# Clasificación por tipo
if [ "$DIA_MES" == "01" ]; then
  TIPO="monthly"
  RETENCION_DIAS=730  # 24 meses
elif [ "$HOY" == "7" ]; then
  TIPO="weekly"
  RETENCION_DIAS=42   # 6 semanas
else
  TIPO="daily"
  RETENCION_DIAS=14   # 14 días
fi

DESTINO_LOCAL="$BACKUP_ROOT/$TIPO"
mkdir -p $DESTINO_LOCAL
BACKUP_FILE="$DESTINO_LOCAL/backup_${TIPO}_$FECHA.sql"

# Crear respaldo
echo "Creando respaldo $TIPO..."
mysqldump -u"$MYSQL_USER" "$DB_NAME" > "$BACKUP_FILE"

if [ $? -ne 0 ]; then
  echo "Error creando respaldo"
  exit 1
fi

# Encriptar con GPG
GPG_PASS="SRV1-KEY.pem"
gpg --batch --yes --passphrase "$GPG_PASS" -c "$BACKUP_FILE"
rm "$BACKUP_FILE"  # Borramos el archivo plano
BACKUP_FILE="$BACKUP_FILE.gpg"

# Transferir al servidor remoto
scp -i "$KEY" $BACKUP_FILE "$REMOTE_USER@$REMOTE_IP:$REMOTE_DIR/$TIPO/"

if [ $? -eq 0 ]; then
  echo "Transferencia completada."
else
  echo "Error en transferencia"
  exit 1
fi

# Limpieza local: eliminar backups antiguos según retención
echo "Limpiando respaldos locales antiguos..."
find "$DESTINO_LOCAL" -type f -name "*.sql" -mtime +$RETENCION_DIAS -delete

# Limpieza remota: eliminar backups remotos antiguos (opcional y requiere SSH sin password o clave)
echo "Limpiando respaldos remotos antiguos..."
ssh -i "$KEY" "$REMOTE_USER@$REMOTE_IP" "find $REMOTE_DIR/$TIPO -type f -name '*.sql' -mtime +$RETENCION_DIAS -delete"

echo "Respaldo $TIPO completado y limpieza realizada."
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/06c56644eba54dd42818963351cc5ce067d0f4bd/Images/image40.png)
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/06c56644eba54dd42818963351cc5ce067d0f4bd/Images/image127.png)

En el Crontab -e meteremos la siguiente línea para que se inicie al iniciar el servidor:

```
0 2 * * * /home/ubuntu/backup.sh >> /home/ubuntu/backup.log 2>&1
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/06c56644eba54dd42818963351cc5ce067d0f4bd/Images/image87.png)

Comprobación:

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/7aac80fa7e811e22f865bd2b5d81997ff5d49bbf/Images/image6.png)

Añadimos estas líneas con tal de encriptar la información saliente del SRV2 al SRV3. La información está encriptada.

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/7aac80fa7e811e22f865bd2b5d81997ff5d49bbf/Images/image75.png)


La información está encriptada, y la desencriptaremos

```
ls
sudo cat backup_daily_20250526_102315.sql.gpg
gpg --decrypt backup_daily_20250526_102315.sql.gpg > backup_daily_20250526_102315.sql
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/7aac80fa7e811e22f865bd2b5d81997ff5d49bbf/Images/image153.png)

Al ver el contenido del sql aparecerá lo siguiente:

```
ls
sudo cat backup_daily_20250526_102315.sql
```
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/95b2a47a8b98e8301f11992f51698fc925c42128/Images/image99.png)

### Investigar y comparar eficiencia energética con otros proveedores de la nube. 
Cómo los diferentes proveedores ofrecen soluciones de CPD administrados por estas empresas y cómo dan cobertura a los requerimientos expuestos anteriormente.

**Resumen de la investigación:**
- **PUE y eficiencia:** AWS logra un PUE de 1,08 a las últimas generaciones de datacenters; Google Cloud reporta un TTM PUE de 1,08–1,09 el 2024; Microsoft introduce diseños que consuman cero agua para refrigeración y se fija objetivos de PUE ≤ 1,2 en el último informe.

- **Renovables:** AWS y Microsoft han llegado al 100% de electricidad renovable en multitud de regiones (AWS desde el 2022, Microsoft avanza hacia el 100% en 2025); Google tiene un compromiso de 24/7 con energía libre de carbón en todos sus campus antes del 2030.

- **Soluciones administradas:**
  - AWS Outposts y Local Zonas (infraestructura AWS idéntica a la nube, "donde-premises") cubren requisitos de proximidad, seguridad y redundancia.
  - Azure Stack HCI / Azure Stack Hub permite desplegar servicios Azure completos localmente, con gestión centralizada e integración con servicios nativos de seguridad de Microsoft.
  - Google Distributed Cloud ofrece soluciones híbridas bajo el paraguas de Google Cloud, incluyendo procesamiento Ay/ML con los mismos controles de seguridad.

| Proveedor | Solución Híbrida/On-Prem | Localización | Seguridad | Climatización | Monitoraje |
|-----------|--------------------------|--------------|-----------|---------------|------------|
| AWS | Outposts, Local Zones | Multi-AZ, Països amb Regió AWS | ISO 27001, SOC 2, PCI-DSS, portes biomètriques, gestió clau KMS | Free cooling, PUE 1,08, recuperació calor | CloudWatch, Customer Carbon Footprint |
| Azure | Azure Stack Hub, HCI | Regió + Data Box Edge | ISO 27001, SOC 2, PCI DSS, Azure Security Center | Dissenys zero-agua, PUE ≤ 1,2 | Azure Monitor, Sustainability Calculator |
| Google | Distributed Cloud Edge | Multi-regió, Edge Locations | ISO 27001, SOC 2, HIPAA, Cloud Armor | PUE Q4 2024 = 1,08, refrigeració líquida | Carbon Footprint Dashboard, Stackdriver |

**Localización & Redundancia:** Todos ofrecen arquitectura global multi-zona, con SLA ≥ 99,9% y opción de ubicación física próxima vía dispostivos Edge (Local Zonas, Azure Stack, Google Distributed Cloud).

**Seguridad física:** Controles biométricos, vigilancia 24/7, acceso segregado y auditorías periódicas (TI, completions de datos).

**Climatización:** Free Cooling integrado, diseños de nueva generación con refrigeración líquida o geotérmica, y recuperación térmica por ofimática.

**Monitorización & Reporting:** Herramientas nativas en cada plataforma para mesurar consumo eléctrico, agua, emisiones (Carbon Footprint Tool, Sustainability Calculator) y PUE/*WUE público.

*PUE (Power Usage Effectiveness) es un indicador que mide la eficiencia energética de un centro de datos. Se calcula dividiendo la energía total consumida por el centro entre la energía usada por los equipos informáticos. Cuanto más se acerque el resultado a 1, mayor será la eficiencia.

## 2. Implantación de los servicios de audio y video

### Bloque 0375.7 i 0375.8:
**Implantación de un servidor de audio (0375.7):**
Nos interesa implementar un servidor de audio de forma que pueda gestionar transmisiones en tiempo real para nuestros clientes y usuarios. La infraestructura tiene que ser capaz de soportar el volumen de tráfico que genera este tipo de servicio sin comprometer la calidad del contenido. Además, queremos que se realicen comprobaciones de ancho de banda para asegurarnos que nuestra red puede gestionar de manera eficiente este tráfico.

**Implantación de un servidor de streaming de video (0375.8):**
Otro de nuestros servicios clave es lo streaming de video. Solicitamos la implantación de un servidor que permita una distribución fluida y de calidad de nuestro contenido audiovisual, tanto en formatos de video en directo como bajo demanda. A la vegada, nos gustaría que se llevaran a cabo pruebas exhaustivas de ancho de banda para evitar saturaciones de la red y garantizar una experiencia de usuario óptima, maximizando el uso de los recursos disponibles de manera responsable.

**Comprobaciones de ancho de banda (0375.7 y 0375.8):**
Las comprobaciones de ancho de banda serán una prioridad para asegurarnos que el sistema diseñado puede gestionar adecuadamente los flujos simultáneos de audio y vídeo sin pérdidas de calidad ni colapsos de la red. Queremos una solución que optimice el uso de la infraestructura existente y minimice el impacto ambiental de los servicios que ofrezcamos.

### Instalación, configuración y monitorización de un servidor de audio y video.

**Introducción**
En esta parte del proyecto transversal se valora las Raído 7 y 8 del módulo 375 de Servicios en Red.

Estáis planteando una infraestructura de streaming de audio y video en tiempo real sin parte web (frontend), basada exclusivamente en montaje de sistemas.

Los requisitos principales que tenemos que tener en cuenta son los siguientes:
- Transmisión en tiempo real (audio + video)
- Sin frontend web
- Focalizado en la calidad del servicio
- Monitorización del ancho de banda
- Alto eficiencia de red
- Automatizable en entornos como AWS

La arquitectura de sistemas propuesta para llevar a cabo el proyecto es la siguiente:

| Componente | Tecnología | Observaciones |
|------------|------------|---------------|
| Audio | Icecast2 + DarkIce / BUTT | Para emisión de audio por HTTP |
| Video | GStreamer (RTSP/RTP/UDP) | Formato CLI, potente para vídeo en tiempo real |
| Monitorización | vnstat, iftop, iperf3, htop | Análisis de tráfico y uso de recursos |
| Sistema Operativo | Ubuntu Server 20.04/22.04 | — |
| Infraestructura | AWS EC2 (instancias t2.large o c5) | Para capacidad de tráfico elevada |

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/95b2a47a8b98e8301f11992f51698fc925c42128/Images/image98.png)

### Despliegue de servidor de audio con IceCAST + DarkICE
Este despliegue incluye:
- Instalación de Icecast2 (https://icecast.org/)
- Instalación y configuración de darkice (http://www.darkice.org/#:~:text=DarkIce%20is%20a%20live%20audio%20streamer.)
- Configuración básica para emisión
- Apertura de puertos
- Monitoreo con vnstat, iftop, iperf3

Este despliegue para un servidor de audio con Icecast2 y DarkIce es sobre un sistema Ubuntu (ideal para EC2 o máquina virtual).

**Instalación del server de audio**

```bash
sudo apt install -y icecast2 darkice vnstat iftop iperf3 ufw
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/95b2a47a8b98e8301f11992f51698fc925c42128/Images/image73.png)

```bash
# Activar Icecast2
sudo sed -i 's/ENABLE=false/ENABLE=true/' /etc/default/icecast2
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/95b2a47a8b98e8301f11992f51698fc925c42128/Images/image3.png)

```bash
# Configuración básica para /etc/icecast2/icecast.xml
sudo tee /etc/darkice.cfg > /dev/null
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/95b2a47a8b98e8301f11992f51698fc925c42128/Images/image97.png)

Configuración de /etc/darkice.cfg

```bash
[general]
duration         = 0
bufferSecs       = 5
reconnect        = yes

[input]
device           = hw:1,1
sampleRate       = 44100
bitsPerSample    = 16
channel          = 2

[icecast2-0]
bitrateMode      = cbr
format           = mp3
quality          = 1.0
bitrate          = 128
server           = localhost
port             = 8000
password         = sourcepass
mountPoint       = grup1.mp3
name             = Stream d'audio
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/629085df39d62b855c050506a1d5f0432d899342/Images/image49.png)

```bash
# Abrimos los puertos del firewall
sudo ufw allow 8000/tcp
sudo ufw allow 22/tcp
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/629085df39d62b855c050506a1d5f0432d899342/Images/image165.png)

```bash
# Iniciamos los servicios
sudo systemctl restart icecast2
sudo systemctl enable icecast2
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/629085df39d62b855c050506a1d5f0432d899342/Images/image113.png)

```bash
# Icecast2 en funcionamiento
# Para iniciar la emisión de audio con DarkIce, ejecuta
# sudo darkice
```

El stream estará disponible en: http://3.214.255.64:8000/grup1.mp3

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/7b52833692ea6023099af4662456dd902bf340fa/Images/image31.png)

**Cómo usar el server de audio**
		
Guardamos el contenido en un fichero:
```bash
#!/bin/bash


# Cargar módulo loopback (snd-aloop)
echo "Cargando módulo snd-aloop..."
sudo modprobe snd-aloop > /dev/null 2>&1


# Mostrar las tarjetas de audio disponibles
echo "Listando tarjetas de audio:"
aplay -l


# Reiniciar el servicio darkice
echo "Reiniciando servicio darkice..."
sudo systemctl restart darkice > /dev/null 2>&1

# Ejecutar darkice con configuración explícita (en background)
echo "Ejecutando darkice con configuración /etc/darkice.cfg..."
sudo darkice -c /etc/darkice.cfg > /dev/null 2>&1 &

# Reproducir el mp3 en bucle infinito en hw:1,0 (en background)
echo "Reproduciendo /home/ubuntu/musica/trueno-feid.mp3 en hw:1,0 en bucle infinito..."
mpg123 -q --loop -1 -o alsa -hw:1,0 /home/ubuntu/musica/trueno-feid.mp3 &
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/7b52833692ea6023099af4662456dd902bf340fa/Images/image33.png)

Hacemos que este fichero sea ejecutable:
```bash
chmod +x play_and_stream.sh
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/7b52833692ea6023099af4662456dd902bf340fa/Images/image10.png)

Lo ejecutamos como root:
```bash
sudo ./play_and_stream.sh
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/7b52833692ea6023099af4662456dd902bf340fa/Images/image21.png)
	
**Hacemos una prueba**

Accedemos a la web de icecast:

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/7b52833692ea6023099af4662456dd902bf340fa/Images/image68.png)

Mediante VLC al darle al botón M3U:

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/7b52833692ea6023099af4662456dd902bf340fa/Images/image24.png)

Desde el navegador http://3.214.255.64:8000/grup1.mp3:

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/7b52833692ea6023099af4662456dd902bf340fa/Images/image31.png)

### Despliegue de servidor de vídeo con GStreamer y RTP Streaming

Este despliegue incluye:
- Instalación de GStreamer (https://gstreamer.freedesktop.org/)
- Instalación y configuración de RTP Streaming
- Apertura de puertos

**Instalación del server de vídeo**

```bash
# Instalación GStreamer y herramientas de vídeo
sudo apt update
sudo apt install -y gstreamer1.0-tools gstreamer1.0-plugins-base \
  gstreamer1.0-plugins-good gstreamer1.0-plugins-bad \
  gstreamer1.0-plugins-ugly gstreamer1.0-libav \
  gstreamer1.0-alsa gstreamer1.0-pulseaudio \
  vnstat iftop iperf3 v4l-utils
```
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/7b52833692ea6023099af4662456dd902bf340fa/Images/image154.png)

```bash
# Instalación GStreamer finalizada
# Abriendo puerto para RTP
sudo ufw allow 5000/udp
sudo ufw allow 5004/udp
sudo ufw allow 22/tcp
# Configuración básica finalizada
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/7b52833692ea6023099af4662456dd902bf340fa/Images/image101.png)

**Ejemplos para lanzar vídeo vía RTP:**
1. Enviar vídeo de la webcam a un cliente por RTP (H.264):
```bash
gst-launch-1.0 -v v4l2src ! videoconvert ! x264enc tune=zerolatency ! rtph264pay ! udpsink host=CLIENT_IP port=5000 
```

2. Recibir y ver este stream (cliente):
```bash
gst-launch-1.0 -v udpsrc port=5000 caps=\"application/x-rtp,media=video,encoding-name=H264,payload=96\" ! rtph264depay ! avdec_h264 ! autovideosink
```

**Cómo usar el server de vídeo**
Guardamos el contenido en un fichero:

```bash
#!/bin/bash
# Ruta del archivo de video a transmitir
VIDEO="/home/ubuntu/video/trueno.mp4"

# Configuración del servidor Icecast
ICECAST_IP="3.214.255.64"   # Dirección IP del servidor Icecast
ICECAST_PORT="8000"         # Puerto del servidor Icecast
MOUNT="/video.webm"         # Punto de montaje donde se publicará el stream
PASSWORD="sourcepass"       # Contraseña para emitir en Icecast


# Esperar unos segundos para asegurarse de que el sistema esté listo
echo "Esperando 10 segundos para la inicialización del sistema..."
sleep 10


echo "Iniciando bucle de transmisión infinita..."
# Bucle infinito para mantener la transmisión activa continuamente
while true; do
    echo "Reproduciendo $VIDEO hacia $ICECAST_IP:$ICECAST_PORT$MOUNT..."

    # Comando GStreamer para reproducir el video y transmitirlo a Icecast
    gst-launch-1.0 -q \
    filesrc location="$VIDEO" \     # Cargar el archivo de video desde el disco
    decodebin name=dec \            # Decodificar el archivo en audio y video
    dec. ! queue ! videoconvert \   # Convertir el video al formato compatible
    videoscale ! video/x-raw,width=1280,height=720 ! vp8enc deadline=1 \ # Codificar el video con VP8 (formato WebM)
    ! webmmux streamable=true name=mux \ # Multiplexar el audio y video en un contenedor WebM
    ! shout2send mount="$MOUNT" port="$ICECAST_PORT" password="$PASSWORD" ip="$ICECAST_IP" \ 

    # Procesamiento del audio
    dec. ! queue ! audioconvert \   # Convertir el audio a un formato compatible
    ! audioresample \                # Ajustar la frecuencia de muestreo
    ! vorbisenc \                    # Codificar el audio con Vorbis (formato WebM)
    ! mux.                            # Unir el audio al contenedor y redirigir salida

    # Si la transmisión termina, esperar unos segundos y reiniciar
    echo "Stream finalizado. Reiniciando en 3 segundos..."
    sleep 3
done
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/7b52833692ea6023099af4662456dd902bf340fa/Images/image54.png)

Hacemos que este fichero sea ejecutable:

```bash
chmod +x video_stream_server.sh
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/7b52833692ea6023099af4662456dd902bf340fa/Images/image131.png)

Lo ejecutamos como root:
```bash
 ./video_stream_server.sh
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image7.png)

**Hacemos una prueba**

Accedemos a la web de icecast:

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image144.png)

Mediante VLC al darle al botón M3U:

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image30.png)

Desde el navegador 3.214.255.64:8000/video.webm:

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image133.png)

**Comprobación del ancho de banda con iperf3**
Instalación:
```bash
sudo apt update
sudo apt install -y iperf3
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/bf96cacb6431441214ce53564aaadc9dbf47fbb8/Images/Image175.png)

Para hacer la prueba al servidor (receptor):

```bash
iperf3 -s
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image160.png)

Salida esperada: Server listening on 5201

Al cliente (emisor): Sustituye IP_SERVIDOR por la dirección IP del servidor:
```bash
iperf3 -c IP_SERVIDOR
```

Salida esperada:
```
Connecting to host IP_SERVIDOR, port 5201
[ ID] Interval           Transfer     Bandwidth
[  5]   0.00-1.00   sec   112 MBytes   938 Mbits/sec
```

Desde un cliente de VirtualBox instalamos el paquete de iperf3, de igual manera lo instalamos en el servidor, ejecutamos en el servidor `iperf3 -s` y nos muestra el ancho de banda en nuestro cliente:

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image92.png)

En el servidor nos aparecerá esto, con la IP pública del cliente y el puerto utilizado:

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image17.png)

## 3. Diseño e implementación de una base de datos 
Se trata de diseñar e implementar una base de datos para la gestión del personal de la empresa. Los requisitos que se piden son los siguientes: 
- Los empleados se identifican por su DNI. Además hemos de registrar el nombre, apellidos, dirección y teléfono. 
- Estos empleados están asignados a un determinado departamento. Los departamentos se identifican con un código y también guardaremos el nombre completo del departamento y el teléfono. 
- Cada empleado tiene asignado un grupo-nivel. Un grupo-nivel se identifica por un código (A1, B1, etc.) y también registraremos el salario total, el período de prueba y los días de vacaciones. 
- Hay que tener en cuenta que en vuestra base de datos hay un empleado/a de cada grupo y nivel del área 2 del convenio "Consultoría, tecnologías de la información y estudios de mercado y de la opinión pública". Como sabéis, este es uno de los convenios que más se aplican en vuestro sector. De estos empleados -mirando el convenio-, hay que poner el salario total, el período de prueba y las vacaciones. 
- Hay que tener en cuenta que los datos que cojáis sean los de 2025

**Convenio colectivo estatal de empresas de consultoría, tecnologías de la información y estudios de mercado y de la opinión pública. : [BOE-A-2025-7766](https://www.boe.es/boe/dias/2025/04/16/pdfs/BOE-A-2025-7766.pdf) para más detalles.**

Se pide hacer el diseño entidad-relación, la transformación a relacional y la implementación en un Sistema Gestor de Bases de Datos (MySQL, Oracle, etc.) con la introducción de un número significativo de datos.

Área 2 del convenio, contiene la siguiente información relevante en cuanto a salarios, crearemos un empleado de cada grupo nivel con estas características, tomamos solo el valor de total:

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image143.png)

Con relación al periodo de prueba y vacaciones:

– Área funcional 1 y 2 del Convenio Colectivo (periodo de prueba):
- Grupo A: Seis meses.
- Grupo B: Seis meses.
- Grupo C: Cuatro meses.
- Grupo D: Tres meses.
- Grupo E: Tres meses.

Art.21 Vacaciones:
1. Todas las personas trabajadoras al servicio de las empresas sujetas a este convenio disfrutarán de veintitrés (23) días laborables de vacaciones anuales retribuidas, salvo lo dispuesto en el párrafo siguiente.

Excepciones: En general son 23 días laborables, pero se reducen a 22 si la empresa da más de 2 meses de jornada intensiva o más de 2 días no laborables extra.

Inicio y fin: Las vacaciones siempre empiezan en día laborable, salvo que toda la plantilla tenga un período fijo.

Incapacidades: Si coinciden con baja por embarazo, parto, lactancia o permisos del art. 48 ET, se pueden disfrutar después, incluso fuera del año. Para otras bajas, también se pueden tomar posteriormente si no pasan 18 meses desde el fin del año.

### 1. Modelo Entidad-Relación (E-R)
**Entidades y Atributos**

**Empleado**
- DNI (PK)
- Nombre
- Apellidos
- Dirección
- Teléfono
- CódigoDepartamento (FK)
- CódigoGrupoNivel (FK)

**Departamento**
- CódigoDepartamento (PK)
- Nombre
- Teléfono

**GrupoNivel**
- CódigoGrupoNivel (PK)
- SalarioTotal
- PeriodoPrueba
- DiasVacaciones

**Relaciones**
- Un empleado pertenece a un Departamento.
- Un Empleado está asignado a un GrupoNivel.

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image157.png)

### 2. Transformación al Modelo Relacional
**Tablas y Claves**

**Empleado**
- DNI: VARCHAR(9) PRIMARY KEY
- Nombre: VARCHAR(50)
- Apellidos: VARCHAR(100)
- Dirección: VARCHAR(100)
- Teléfono: VARCHAR(15)
- CódigoDepartamento: VARCHAR(10) FOREIGN KEY
- CódigoGrupoNivel: VARCHAR(10) FOREIGN KEY

**Departamento**
- CódigoDepartamento: VARCHAR(10) PRIMARY KEY
- Nombre: VARCHAR(100)
- Teléfono: VARCHAR(15)

**GrupoNivel**
- CódigoGrupoNivel: VARCHAR(10) PRIMARY KEY
- SalarioTotal: DECIMAL(10,2)
- PeriodoPrueba: INT
- DiasVacaciones: INT

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image16.png)

### IMPLEMENTACIÓN DE LA BASE DE DATOS:

Actualizamos los paquetes de nuestro servidor (SRV2):

```bash
sudo apt update && sudo apt upgrade -y
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image100.png)

Instalación de MySQL:

```bash
sudo apt install mysql-server -y
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image26.png)

Revisamos que los servicios estén funcionando correctamente:

```bash
sudo systemctl status mysql
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image27.png)

Configuración de la BD en modo seguro:

```bash
sudo mysql_secure_installation
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image36.png)

Creamos la base de datos llamada BD_Transversal:

```sql
CREATE DATABASE BD_Transversal;
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image59.png)

Seleccionamos la Base de Datos creada:
```sql
USE BD_Transversal;
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image39.png)
  
Creamos las tablas, en este caso Departamento:
```sql
CREATE TABLE Departamento (
    CódigoDepartamento VARCHAR(10) PRIMARY KEY,
    Nombre VARCHAR(100) NOT NULL,
    Teléfono VARCHAR(15)
);
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image86.png)

Ahora creamos la tabla de GrupoNivel:
```sql
CREATE TABLE GrupoNivel (
    CódigoGrupoNivel VARCHAR(10) PRIMARY KEY,
    SalarioTotal DECIMAL(10,2) NOT NULL,
    PeriodoPrueba INT NOT NULL,
    DiasVacaciones INT NOT NULL
);
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image168.png)

Y seguimos con la tabla de Empleado:
```sql
CREATE TABLE Empleado (
    DNI VARCHAR(9) PRIMARY KEY,
    Nombre VARCHAR(50) NOT NULL,
    Apellidos VARCHAR(100) NOT NULL,
    Dirección VARCHAR(100),
    Teléfono VARCHAR(15),
    CódigoDepartamento VARCHAR(10),
    CódigoGrupoNivel VARCHAR(10),
    FOREIGN KEY (CódigoDepartamento) REFERENCES Departamento(CódigoDepartamento),
    FOREIGN KEY (CódigoGrupoNivel) REFERENCES GrupoNivel(CódigoGrupoNivel)
);
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image163.png)

Insertamos los datos a la tabla de Departamento:
```sql
INSERT INTO Departamento (CódigoDepartamento, Nombre, Teléfono) VALUES
('DEP001', 'Desarrollo', '932123456'),
('DEP002', 'Marketing', '932123457'),
('DEP003', 'Recursos Humanos', '932123458'),
('DEP004', 'Finanzas', '932123459'),
('DEP005', 'Operaciones', '932123460');
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image69.png)
 
Y aquí añadimos los datos a la tabla de GrupoNivel:
```sql
INSERT INTO GrupoNivel (CódigoGrupoNivel, SalarioTotal, PeriodoPrueba, DiasVacaciones) VALUES
('A1', 35000.00, 6, 23),
('A2', 32000.00, 6, 23),
('B1', 28000.00, 6, 23),
('B2', 25000.00, 6, 23),
('C1', 22000.00, 4, 23),
('C2', 20000.00, 4, 23),
('D1', 18000.00, 3, 23),
('D2', 16000.00, 3, 23),
('E1', 14000.00, 3, 23),
('E2', 12000.00, 3, 23);
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image14.png)

Y para finalizar insertamos los datos a la tabla Empleado:
```sql
INSERT INTO Empleado (DNI, Nombre, Apellidos, Dirección, Teléfono, CódigoDepartamento, CódigoGrupoNivel) VALUES
('11111111A', 'Ana', 'García Pérez', 'Calle Gran Vía 1, Madrid', '611111111', 'DEP001', 'A1'),
('22222222B', 'Juan', 'Martínez López', 'Avenida Diagonal 100, Barcelona', '622222222', 'DEP002', 'A2'),
('33333333C', 'María', 'González Ruiz', 'Calle Serrano 25, Madrid', '633333333', 'DEP003', 'B1'),
('44444444D', 'Carlos', 'Fernández Sánchez', 'Paseo de Gracia 75, Barcelona', '644444444', 'DEP001', 'B2'),
('55555555E', 'Laura', 'Rodríguez Álvarez', 'Gran Vía 56, Valencia', '655555555', 'DEP004', 'C1'),
('66666666F', 'Pedro', 'Navarro Torres', 'Rambla Catalunya 23, Barcelona', '666666666', 'DEP005', 'C2'),
('77777777G', 'Sofía', 'Moreno Castro', 'Calle Mayor 10, Sevilla', '677777777', 'DEP002', 'D1'),
('88888888H', 'Miguel', 'Jiménez Vargas', 'Plaza España 5, Madrid', '688888888', 'DEP003', 'D2'),
('99999999I', 'Carmen', 'Ruiz Flores', 'Avenida del Puerto 120, Valencia', '699999999', 'DEP004', 'E1'),
('10101010J', 'David', 'Serrano Gil', 'Paseo Marítimo 45, Barcelona', '610101010', 'DEP005', 'E2');
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image32.png)

Vemos que estén creados con select:
```sql
SELECT * FROM Empleado;
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image126.png)

Creamos los usuarios y le damos los permisos:
```sql
mysql> CREATE USER 'sofia'@'%' IDENTIFIED BY 'Sofia2025!';
Query OK, 0 rows affected (0.01 sec)

mysql> GRANT SELECT, INSERT, UPDATE, DELETE ON BD_Transversal.Empleado TO 'sofia'@'%';
Query OK, 0 rows affected (0.01 sec)

mysql> CREATE USER 'miguel'@'%' IDENTIFIED BY 'Migu3l2025!';
Query OK, 0 rows affected (0.02 sec)

mysql> GRANT SELECT, INSERT, UPDATE ON BD_Transversal.Empleado TO 'miguel'@'%';
Query OK, 0 rows affected (0.01 sec)

mysql> CREATE USER 'elena'@'%' IDENTIFIED BY 'El3na2025!';
Query OK, 0 rows affected (0.01 sec)

mysql> GRANT SELECT ON BD_Transversal.Empleado TO 'elena'@'%';
Query OK, 0 rows affected (0.01 sec)

mysql> CREATE USER 'raul'@'%' IDENTIFIED BY 'Raul2025!';
Query OK, 0 rows affected (0.01 sec)
```

Permisos
```bash
mysql> GRANT SELECT (Nombre, Apellidos, CodigoGrupoNivel) ON BD_Transversal.Empleado TO 'raul'@'%';
Query OK, 0 rows affected (0.01 sec)

mysql> CREATE USER 'joel'@'%' IDENTIFIED BY 'J03l2025!';
Query OK, 0 rows affected (0.01 sec)

mysql> GRANT SELECT ON BD_Transversal.Empleado TO 'joel'@'%';
Query OK, 0 rows affected (0.01 sec)

mysql> FLUSH PRIVILEGES;
Query OK, 0 rows affected (0.01 sec)

mysql>
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image19.png)

Accedemos a la BD:

```bash
mysql -h 52.200.122.76 -P 3306 -u sofia -p
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image146.png)

Prueba desde un ordenador cliente de fuera de la red:
```bash
mysql -h 52.200.122.76 -P 3306 -u sofia -p
```

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/c799924e1adcaee2423f19e7b75e0aab37131aaf/Images/image44.png)

## 4. Sostenibilidad
### Sostenibilidad y eficiencia energética:
Alineándonos con nuestros valores empresariales y los ODS, es fundamental para nosotros que todo el proyecto sea diseñado con un enfoque claro de sostenibilidad. Buscamos optimizar el uso de la energía y utilizar soluciones que reduzcan el impacto ambiental de nuestras operaciones. Nos gustaría explorar el uso de fuentes de energía renovables, así como la implementación de prácticas de eficiencia energética dentro del CPD (Centro de Procesamiento de Datos).

### Cálculo de la huella ecológica del proyecto realizado:
**Estimación de la Huella de Carbono del CPD:**
- Consumo energético anual estimado: el CPD tiene un consumo energético anual estimado de 273.312 kWh.
- Emisiones asociadas al consumo eléctrico: Según datos del Instituto por la Diversificación y Ahorro de la Energía (IDAE), el factor de emisión medio para la electricidad en España es de 0,231 kg CO₂/kWh.
- Emisiones totales anuales: 273.312 kWh × 0,231 kg CO₂/kWh = 63.144 kg CO₂

- Contribución de la energía renovable: el CPD cuenta con una instalación fotovoltaica de 100 m² con una potencia estimada de 30 kWp, que genera aproximadamente 49.380 kWh anuales.
- Porcentaje de energía renovable utilizada: (49.380 kWh / 273.312 kWh) × 100 = 18,1%
- Emisiones evitadas gracias a la energía solar: 49.380 kWh × 0,231 kg CO₂/kWh = 11.402 kg CO₂

### Huella de carbono limpia:
**Emisiones netas anuales:** 63.144 kg CO₂ - 11.402 kg CO₂ = 51.742 kg CO₂

| Concepto                          | Cálculo                                | Resultado          |
|-----------------------------------|----------------------------------------|--------------------|
| Emisiones brutas del CPD          | 273.312 kWh × 0,231                    | 63.144 kg CO₂      |
| Generación solar (100 m², 30 kWp) | —                                      | 49.380 kWh/año     |
| Porcentaje energía renovable      | (49.380 / 273.312) × 100               | 18,1 %             |
| Emisiones evitadas                | 49.380 × 0,231                         | 11.402 kg CO₂      |
| Emisiones netas (huella limpia)   | 63.144 - 11.402                        | 51.742 kg CO₂      |


**Estimación de la Huella de Carbono de la infraestructura en AWS:**
- Basado en el despliegue de 2 instancias EC2 t2.large y 1 t2.medium, con servicios de streaming (RTMP, Nginx, OpenFire, FTP, MySQL), más CDN (CloudFront) y almacenamiento (S3/Glacier):

| Fuente                                      | Energía anual estimada | Factor de emisión (kg CO₂/kWh) | Emisiones estimadas (kg CO₂/año) |
|---------------------------------------------|------------------------|-------------------------------|----------------------------------|
| EC2 (3 instancias)                         | 429 kWh                | 0,10 (media global)           | 42,9 kg CO₂                      |
| Tráfico de red (streaming 1080p @ 5 Mbps, 50 usuarios simultáneos) | 98.550 kWh | 0,10 | 9.855 kg CO₂ |
| Total AWS                                  | 98.979 kWh             | —                             | 9.897,9 kg CO₂                   |

El tráfico de red representa más del 99 % de la huella de carbono estimada para esta infraestructura.

### Observaciones clave

- Migrar parte del servicio a AWS, especialmente si se seleccionan regiones como `eu-north-1` (Suecia), donde AWS opera con energía 100 % renovable, puede disminuir significativamente las emisiones (hasta 90 % menos que el CPD tradicional).

- El uso de CloudFront (CDN) ayuda a distribuir contenido de forma más eficiente, reduciendo latencia y emisiones por distancia recorrida.

- La huella del CPD físico sigue siendo considerable pese al autoconsumo solar, aunque la instalación fotovoltaica evita unas 11 toneladas de CO₂ al año.
  
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/f301adbe832b1ba77c5f4c02006056075e98c847/Images/Grafica.png)

### El gráfico muestra:

- El gran impacto del CPD físico (63.144 kg brutos), frente a la menor huella de las soluciones en la nube (AWS EC2 y especialmente streaming).

- La contribución significativa de la energía solar en el CPD, que reduce más de 11.000 kg de CO₂ anuales.

- Una comparación directa entre los modelos cloud y on-premise (neto vs. bruto).

- Cumplimiento de los Objetivos de la Agenda 2030:

**Cumplimiento de los Objetivos de la Agenda 2030:**

| ODS | Descripción | Evidencia en el proyecto |
|-----|-------------|--------------------------|
| 7 | Energía asequible y no contaminante | • Cubierta fotovoltaica (30 kWp) aporta 18,1 % de la energía necesaria.<br>• Estrategias pasivas (free-cooling, geotermia). |
| 9 | Industria, innovación e infraestructura | • Diseño de CPD de alta eficiencia y automatización 24/7.<br>• Sistemas de monitorización avanzada (Zabbix, VESDA). |
| 11 | Ciudades y comunidades sostenibles | • Integración paisajística en Collserola (cubierta ajardinada).<br>• Gestión de aguas pluviales para climatización y riego. |
| 12 | Producción y consumo responsables | • Materiales ecológicos (aislamiento de fibra de madera, pinturas sin COV).<br>• Iluminación LED con sensores de presencia. |
| 13 | Acción por el clima | • Reducción de emisiones operativas a 24,2 t CO₂eq/año; compensable con 0,86 ha forestal.<br>• Reutilización de calor residual. |
| 6 | Agua limpia y saneamiento | • Captación y uso de aguas pluviales para climatización indirecta.<br>• Filtrado y canalización de aguas en muros verdes. |
| 15 | Vida de ecosistemas terrestres | • Integración arquitectónica y mínima fragmentación en zona de alto valor ecológico.<br>• Muros verdes para biodiversidad. |
| 16 | Paz, justicia e instituciones sólidas | • Captura de pantalla del JSON de políticas IAM en AWS con roles y permisos granulares.<br> • Extracto de CloudTrail mostrando auditoría de eventos críticos (creación/elim. de instancias).<br>• Documento PDF del Plan de Continuidad de Negocio con procedimientos de recuperación.<br>• Log de ejecución del script de backup/restauración automatizado (cron).|

De este modo, el CPD no solo minimiza su huella de carbono y optimiza recursos, sino que también aborda de forma integrada múltiples metas de la Agenda 2030, garantizando sostenibilidad ambiental, innovación tecnológica y resiliencia.

### Propuesta de medidas de reducción u optimización:

- **Reducir horas de funcionamiento**
  - Apagar servicios no críticos (por ejemplo, entornos de pruebas) en horarios valle.
  - Automatizar paradas con AWS Lambda/EventBridge.
  - Ahorro estimado: hasta 86 kWh/año (~8,6 kg CO₂).

- **Usar energía renovable**
  - Migrar a regiones de AWS con 100 % renovable (ej. `eu-north-1`, `us-west-2`).
  - En el CPD, ampliar paneles solares o incluir baterías.
  - Reduce casi a cero las emisiones en AWS.

- **Elegir regiones más eficientes**
  - Priorizar regiones con baja huella (ej. Estocolmo, Frankfurt).
  - Redirigir tráfico CloudFront a PoPs sostenibles.
  - Evaluar con AWS Carbon Footprint Tool.

- **Optimizar tráfico y streaming**
  - Usar códecs eficientes (H.265, AV1) y streaming adaptativo.
  - Comprimir objetos estáticos (Brotli, Zstd).
  - Reducción estimada de datos: hasta 40 % (~4 t CO₂ menos).

- **Mejorar almacenamiento**
  - Activar S3 Intelligent-Tiering.
  - Migrar backups antiguos a almacenamiento en frío.
  - Eliminar duplicados y versiones innecesarias.

- **Monitorizar la huella**
  - Activar AWS Carbon Footprint Tool y métricas en CloudWatch.
  - Establecer KPIs como g CO₂ por stream o kWh por usuario.


**1- Identificar los recursos empleados, por ejemplo:**
- Qué servicios se han desplegado (tipos de máquinas, servicios de nube, protocolos)
- Qué recursos consumen (CPU, RAM, almacenamiento, ancho de banda)
- Cuál es la previsión de uso (horas de funcionamiento, usuarios, tráfico estimado)

**2- Estimar el consumo energético y la huella de carbono:**
- Estimar el consumo energético de:
  - Las instancias de la nube (puede utilizar valores aproximados o herramientas del proveedor como la Carbon Footprint Calculator de AWS o similares de GCP/Azure).
  - https://aws.amazon.com/es/aws-cost-management/aws-customer-carbon-footprint-tool/
  - El tráfico generado por el streaming (considerando, por ejemplo, watts por GB transferido).
  - El consumo de los servidores virtuales o servicios en funcionamiento continuamente.
  - Utilizar factores de equivalencia para convertir energía (kWh) en emisiones (kg CO₂ eq.).

**Recursos:**
- https://www.carbontrust.com/
- Factores medios globales o por región del proveedor cloud.

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/893027ef5c59721779db8bd05e6f57cd28886428/Images/image82.png)
![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/893027ef5c59721779db8bd05e6f57cd28886428/Images/image142.png)

**3- Propuesta de medidas de reducción u optimización, por ejemplo:**
- ¿Reducir horas de funcionamiento?
- ¿Utilizar servicios con energía renovable?
- ¿Elegir regiones de nube más eficientes?

## 5. Entrega y presentación
1. Es obligatoria la presentación para poder evaluar las RAs.
2. Vídeo de 3 minutos el cual debe tener:
   a. Una Introducción donde se plantee un problema, una necesidad … y la solución propuesta (Poco tiempo de duración)
   b. Una parte con la demo donde se vean el servidor y los clientes en funcionamiento.
   c. Una conclusión, finalización del vídeo / presentación donde justifiquéis porqué vuestro despliegue funciona y sirve para …
3. Exposición de duración de 10-15 minutos explicando los puntos y aspectos más importantes del proyecto transversal. Se valorará:
   a. La calidad del material de la presentación: claridad, estructura, faltas de ortografía.
   b. Exposición realizada del proyecto y ceñida al tiempo disponible.
   c. Participación de todos los miembros del grupo de forma equitativa.
   d. Interacción y respuesta a las preguntas al respecto.
4. Enlace publicado en GitHub del documento en Markdown con la recopilación de evidencias de todos los apartados y las respuestas teóricas justificadas

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/893027ef5c59721779db8bd05e6f57cd28886428/Images/image130.png)

## Rúbricas 
### Evaluación Proyecto transversal: 

![Captura de pantalla](https://github.com/DanielLopez7e8/pro-asixc1d-g1-/blob/893027ef5c59721779db8bd05e6f57cd28886428/Images/image125.png)

#### Bloque 0371 Fundamentos de maquinaria: 
**PUNTO DE CONTROL - RA4**
- Ubicación física (1 p) 
- Infraestructura IT (1 p) 
- SAI (1 p) 
- Seguridad física y lógica (1,5 p) 
- Sostenibilidad (1 p) 
- Implementación en la nube AWS (4 p) 
- Comparativa proveedores (0,5 p)

#### Bloque 0373 Lenguajes de marcas: 
**PUNTO DE CONTROL - RA3**
- Publicación en GitHub (1,25p) 
- Documentar en Markdown (1,25p)

**PUNTO DE CONTROL - RA5**
- Publicación en GitHub (2,5p) 
- Documentar en Markdown (2,5p)

**PUNTO DE CONTROL - RA6**
- Publicación en GitHub (1,25p) 
- Documentar en Markdown (1,25p)

#### Bloque 0375 Servicios de redes e internet: 
**PUNTO DE CONTROL - RA7**
- Instalación servidor de audio (2,5 p) 
- Configuración servidor de audio (3 p) 
- Instalación del source client (2,5 p) 
- Consumo del streaming de audio desde el cliente (2 p)

**PUNTO DE CONTROL - RA8**
- Instalación servidor video (2,5 p) 
- Configuración servidor video (3 p) 
- Instalación del source client (2,5 p) 
- Consumo del streaming de vídeo desde el cliente (2 p)

#### Bloque 0377 Administración de bases de datos: 
**PUNTO DE CONTROL - RA3-RA4**
- Creación de Usuarios (3 p) 
- Creación de Roles (2 p) 
- Gestión de Permisos de Usuario (5 p)

#### Bloque 1665 Digitalización aplicada a los sectores productivos: 
**PUNTO DE CONTROL - RA3**
- Publicación en GitHub (0,5p) 
- Ubicación física (0,5p) 
- Crear una solución que optimice el uso de la infraestructura. (2p) 
- Importancia de los datos (2p)

**PUNTO DE CONTROL - RA5**
- Evaluar la seguridad física de los datos (2,5p) 
- Evaluar la seguridad lógica de los datos (2,5p)

#### Bloque 1708 Sostenibilidad: 
**PUNTO DE CONTROL - RA3**
- Aplicar criterios de sostenibilidad del CPD (1,5p) 
- Argumentar los criterios de sostenibilidad del CPD aplicados (1,5p)

**PUNTO DE CONTROL - RA4**
- Proponer productos y servicios responsables para el CPD (1,5p) 
- Usar productos y servicios responsables para el CPD (1,5p)

**PUNTO DE CONTROL - RA5**
- Investigar la eficiencia energética del CPD (2p) 
- Comparar la eficiencia energética del CPD (2p)

#### Bloque 1709 IPO: 
**PUNTO DE CONTROL - RA3**
- Indicar los diferentes salarios para cada grupo-nivel pedido, sabiendo encontrar la información en el convenio dado como referencia (4p) 
- Identificar los diferentes períodos de prueba para los trabajadores/as escogidos (4p)
- Encontrar las vacaciones asignadas en el convenio para los trabajadores/as escogidos (2p)

#### Bloque Presentación y defensa 30 de mayo: 
**PUNTO DE CONTROL - Presentación y defensa**
- Calidad (2,5 p) 
- Exposición (2,5 p) 
- Participación equitativa (2,5 p) 
- Interacción y respuesta (2,5 p)

---

**Licencia:** Este documento está sujeto a la licencia de Reconocimiento de Creative Commons (CC-BY 4.0)
