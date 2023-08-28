up:: [[Pentesting]]
tags:: #pentesting 

# CEH | Module 1

## Section 01 - Information Security

### Attack Classification
- **Passive Atacks**
	- No manipulan la informacion, Interceptan y monitorean *network traffic* y *flujo de data* en la red.
	- *sniffing*, *eavesdropping*, *footprinting, network traffic analysis, decryption of weakly encrypted traffic*

- **Active Attacks**
	- Manipulan la informacion en transito para lograr un *bypass* o break a los sistemas de seguridad.
	- *DoS*, *Main-in-the-Middle*, *session hijacking*, *SQL injection*

-  **Close-in Attacks**
	- Ocurren cuando el atacante esta próximo físicamente al sistema a atacar.
	- *Eavesdropping*, *shoulder surfing*, *dumpster diving*

-  **Insider Attacks**
	- Ocurren cuando el ataque proviene desde adentro, usando acceso privilegiado para violar reglas o causar algun tipo de daño.
	- *keyloggers, backdoors, malware*

-  **Distribution Attacks**
	- Ocurren al alterar *hardware o software* previos a sus instalaciones.

### Information Warfare

Este termino se refiere al uso de las **ICT**(*information and communication technologies*) para ganar ventaja competitiva sobre un oponente.
![[ceh1.png]]
## Section 02 - Hacking Methodology

### Metodologias de Hacking y Frameworks

Aprender las metodologias y frameworks ayuda a entender las fases involucradas al momento de vulnerar un sistema.
Este conocimiento ayuda a dar mejorar la *infraestructura de seguridad* de la organizacion.
![[ceh2.png]]
Esta metodologia muestra el paso a paso para hacer un *ethical hacking*
Se siguen los mismos pasos que un atacante.

### Cyber Kill Chain Methodology
![[ceh3.png]]
**Desarrollado por Lockheed Martin**, el marco de trabajo _Cyber Kill Chain®_ es parte del modelo de _Defensa Impulsada por Inteligencia®_ para la identificación y prevención de la actividad de intrusiones cibernéticas. El modelo identifica lo que los adversarios deben completar para lograr su objetivo. La cadena se compone de:

1. **Reconocimiento**
    - Recopilación de direcciones de correo electrónico, información de conferencias, etc.
2. **Weaponización**
    - Combinación de un _exploit_ con una puerta trasera en una carga entregable.
3. **Entrega**
    - Entrega del paquete weaponizado a la víctima a través de correo electrónico, web, USB, etc.
4. **Explotación**
    - Aprovechamiento de una vulnerabilidad para ejecutar código en el sistema de la víctima.
5. **Instalación**
    - Instalación de malware en el recurso.
6. **Control y comando (C2)**
    - Canal de comando para la manipulación remota de la víctima.
7. **Acción en los objetivos**
    - Los intrusos logran sus objetivos.

### Tactics, Techniques and Procedures (TTPs)
![[ceh4.png]]
**Tactics, Techniques, and Procedures (TTPs)** es un concepto esencial en los estudios de terrorismo y seguridad cibernética. El papel de los TTPs en el análisis del terrorismo es identificar patrones individuales de comportamiento de una actividad terrorista específica o de una organización terrorista en particular, y examinar y categorizar tácticas y armas más generales utilizadas por esa actividad terrorista específica o esa organización terrorista en particular.

### Indicators of Compromise (IoC)
**Indicator of Compromise (IoC)** en la informática forense es un artefacto observado en una red o en un sistema operativo que, con alta confianza, indica una intrusión informática. Los IoCs típicos son firmas de virus y direcciones IP, hashes MD5 de archivos de malware, o URL o nombres de dominio de servidores de control y comando de botnets. Después de que los IoCs han sido identificados a través de un proceso de respuesta a incidentes e informática forense, se pueden utilizar para la detección temprana de futuros intentos de ataque mediante sistemas de detección de intrusiones y software antivirus.

### MITRE ATT&CK Framework
![[ceh5.png]]
**MITRE ATT&CK®** es una base de conocimiento globalmente accesible de tácticas y técnicas de adversarios basadas en observaciones del mundo real. La base de conocimiento ATT&CK se utiliza como base para el desarrollo de modelos y metodologías de amenazas específicas en el sector privado, en el gobierno y en la comunidad de productos y servicios de ciberseguridad.

### Diamond Model of Intrusion Analysis
![[ceh6.png]]
El **modelo diamante de análisis de intrusiones** es un modelo utilizado por profesionales de seguridad de la información para autenticar y rastrear amenazas cibernéticas. Consta de 4 partes: adversario, infraestructura, capacidad y objetivo. Proporciona a los analistas una vista integral de los ataques cibernéticos.

## Section 03 - Hacking Concepts
**Hacker**
Un **hacker** es una persona con habilidades en tecnología de la información que utiliza su conocimiento técnico para lograr un objetivo o superar un obstáculo dentro de un sistema computarizado mediante medios no convencionales.

- **White hat hacker**: Los _white hats_ son hackers que trabajan para mantener seguros los datos de otros hackers al encontrar vulnerabilidades en sistemas que pueden ser mitigadas.
- **Black hat hacker**: Los _black hats_ o _crackers_ son hackers con intenciones maliciosas. Suelen robar, explotar y vender datos, y generalmente están motivados por ganancias personales.
- **Grey hat**: Un _grey hat_ es un hacker informático o experto en seguridad informática que a veces puede violar leyes o estándares éticos típicos, pero no tiene la intención maliciosa típica de un _black hat_ hacker.


## Section 04 - Information Security Controls
### Defensa en Profundidad (Defense in Depth)
La **defensa en profundidad** es un concepto utilizado en la seguridad de la información en el cual se implementan múltiples capas de controles de seguridad a lo largo de un sistema de tecnología de la información (TI). Su objetivo es proporcionar redundancia en caso de que un control de seguridad falle o se explote una vulnerabilidad, y puede cubrir aspectos relacionados con la seguridad de personal, procedimientos, tecnología y física durante todo el ciclo de vida del sistema.

### Skills of an Ethical Hacker

![[ceh7.png]]
### Riesgo de Seguridad de la Información (Information Security Risk)
El **riesgo de seguridad de la información** se refiere al riesgo que enfrentan las operaciones de una organización (incluyendo su misión, funciones, imagen y reputación), sus activos, individuos, otras organizaciones y la nación en general debido a la posibilidad de acceso no autorizado, uso, divulgación, interrupción, modificación o destrucción de la información y/o sistemas de información.

### Defense-in-depth
![[ceh8.png]]
### Matriz de Riesgo (Risk Matrix)
Una **matriz de riesgo** es una herramienta utilizada durante la evaluación de riesgos para definir el nivel de riesgo al considerar la categoría de probabilidad o probabilidad contra la categoría de severidad de las consecuencias.

### Gestión de Riesgos (Risk Management)
La **gestión de riesgos** es el proceso de identificación, evaluación y priorización de riesgos (definidos en ISO 31000 como el efecto de la incertidumbre en los objetivos), seguido de la aplicación coordinada y económica de recursos para minimizar, monitorear y controlar la probabilidad o el impacto de eventos desafortunados o maximizar la realización de oportunidades.
![[ceh10.png]]

### Inteligencia de Amenazas Cibernéticas (Cyber Threat Intelligence)
La **inteligencia de amenazas cibernéticas (CTI)** es información basada en conocimientos, habilidades y experiencias relacionadas con la ocurrencia y evaluación de amenazas tanto cibernéticas como físicas, así como actores de amenazas. Su objetivo es ayudar a mitigar posibles ataques y eventos dañinos que ocurran en el ciberespacio.

### Inteligencia de Amenazas Cibernéticas - Táctica (Cyber Threat Intelligence - Tactical)
![[ceh12.png]]
Táctica: inteligencia técnica que incluye Indicadores de Compromiso (IoC) como direcciones IP, nombres de archivos o hash, que pueden utilizarse para ayudar en la identificación de actores de amenazas.

### Inteligencia de Amenazas Cibernéticas - Operativa (Cyber Threat Intelligence - Operational)
Operativa: detalles sobre la motivación o capacidades de los actores de amenazas, incluyendo sus herramientas, técnicas y procedimientos.

### Inteligencia de Amenazas Cibernéticas - Estratégica (Cyber Threat Intelligence - Strategic)
Estratégica: inteligencia sobre los riesgos generales asociados con las amenazas cibernéticas que pueden utilizarse para orientar la estrategia organizativa de alto nivel.

### Modelado de Amenazas (Threat Modeling)
El **modelado de amenazas** es un proceso mediante el cual se pueden identificar y enumerar amenazas potenciales, como vulnerabilidades estructurales o la ausencia de salvaguardias adecuadas, y se pueden priorizar las contramedidas.
![[ceh13.png]]

### Gestión de Incidentes (Incident Management)
Un **incidente** es un evento que podría llevar a la pérdida o interrupción de las operaciones, servicios o funciones de una organización. La **gestión de incidentes (IcM)** es un término que describe las actividades de una organización para identificar, analizar y corregir peligros con el fin de prevenir futuras recurrencias.
![[ceh14.png]]
![[ceh15.png]]
### Inteligencia Artificial (Artificial Intelligence)
La **inteligencia artificial (IA)** es la inteligencia demostrada por máquinas, en contraposición a la inteligencia natural mostrada por animales y humanos. La investigación en IA se ha definido como el campo de estudio de agentes inteligentes, lo que se refiere a cualquier sistema que percibe su entorno y toma acciones que maximizan sus posibilidades de lograr sus objetivos.
![[ceh16.png]]
