Las personas cotidianamente tienen que guardar documentos diarios, académicos y personales; tanto de salud, estudios, trabajo y de la familia. Un caso típico es el de personas (desde jóvenes universitarios hasta adultos mayores) que tienen sus documentos importantes dispersos y desordenados entre Google Drive, el correo electrónico y WhatsApp, lo que les hace perder tiempo buscando y, a menudo, olvidar fechas de vencimiento o citas importantes relacionadas a esos trámites.

# Proyecto: Listoco

# Rol
Eres un Arquitecto de Software y Diseñador UX/UI Senior con 20 años de experiencia, especializado en frameworks modernos (React, Next.js, Tailwind CSS) y componentes de alta calidad (Shadcn UI), con un fuerte enfoque en Accesibilidad (A11y) para interfaces multigeneracionales.

# Logros
Al finalizar, el prototipo de **Listoco** debe permitir que el usuario:
- Reduzca el tiempo de búsqueda y organización de documentos de horas a minutos al unificar fuentes.
- Centralice archivos dispersos (Drive, Correo, WhatsApp) y permita la digitalización rápida de documentos físicos usando la cámara.
- Mantenga el control de sus documentos recibiendo alertas proactivas antes de que un documento caduque (sistema de semáforo).
- Pueda agendar citas médicas, académicas o de trámites directamente vinculadas a los documentos guardados.
- Disfrute de una experiencia completamente personalizada mediante el inicio de sesión.

# Contexto
Ayudo a personas de todas las edades a organizar su vida documental mediante una aplicación inteligente llamada **Listoco**, la cual centraliza archivos de múltiples plataformas, automatiza la clasificación, gestiona alertas de vencimiento y facilita el agendamiento de citas relacionadas a dichos documentos.

# Usuario y problema
**Persona:** Público amplio (desde estudiantes universitarios de 20 años hasta adultos mayores de +70 años).
**Problema:** Tienen su información fragmentada en Drive, correo y WhatsApp. Pierden tiempo buscando archivos importantes, olvidan renovar documentos y tienen problemas gestionando las citas asociadas a estos.
**Trabajo a realizar (JTBD):** "Necesito un solo lugar donde pueda encontrar todos mis documentos fácilmente, que me avise cuando estén por vencer y que me permita agendar y recordar mis citas sin que la tecnología sea una barrera."

# Desafío
Construye un prototipo interactivo (escritorio y móvil) para **Listoco**, altamente accesible y fácil de usar, que soporte las siguientes historias:

### Historia 1: Integración y Centralización Omnicanal
Como usuario, quiero conectar mi Google Drive, mi correo y mi WhatsApp para importar documentos directamente a una sola bóveda central.
- **Criterios:** El sistema debe permitir sincronizar o importar archivos de estas 3 fuentes y mostrarlos en un panel unificado con vista previa.

### Historia 2: Gestión de Vigencia (Semáforo)
Como usuario, quiero que el sistema detecte o me permita ingresar la fecha de vencimiento de mis documentos para recibir alertas.
- **Criterios:** Sistema de semáforo visual (Verde: vigente, Amarillo: próximo a vencer, Rojo: vencido) en el panel principal. Notificaciones claras y fáciles de entender.

### Historia 3: Agendamiento de Citas Integrado
Como usuario, quiero poder agendar una cita vinculada a un documento específico (ej. agendar cita en la embajada ligada al pasaporte vencido, o cita médica ligada a unos análisis).
- **Criterios:** Un módulo de calendario integrado donde se pueda crear un evento, asignarle fecha/hora y adjuntar/vincular el documento correspondiente.

### Historia 4: Accesibilidad Multigeneracional
Como usuario (especialmente si soy adulto mayor), quiero navegar por la aplicación sin perderme, con textos legibles y botones claros.
- **Criterios:** Diseño de alto contraste, tipografía grande ajustable, y flujos de acción de máximo 3 clics sin menús ocultos complejos.

# Flujo principal
1. Inicio de Sesión y Personalización: Login para una experiencia adaptada al usuario y conexión inicial de canales (Drive, WhatsApp, Correo).
2. Pantalla principal (Dashboard) unificada que muestre las diferentes categorías de documentos y el estado (semáforo) de vencimiento.
3. Importación/Carga de archivo: Seleccionando fuentes digitales o usando la cámara para escanear y subir documentos al instante.
4. Asignación de categoría y fecha de vencimiento.
5. Opción de "Agendar Cita" desde la vista del documento.
6. Recepción de alertas por vencimiento o citas próximas.

# Estilo y tono
**Profesional y Accesible:** Azul degradado (#040042 a #0D00C2) para transmitir seguridad, con fondos beige o blancos cálidos para facilitar la lectura.
**Diseño:** Minimalista, botones grandes, tipografía muy clara, estilo "boceteado" (wireframe de alta fidelidad), responsivo (prioridad móvil).

# Criterios de aceptación
**Característica:** Centralización de documentos
* **Escenario:** Importar desde Drive o WhatsApp
* **Dado** que estoy en la pantalla de inicio
* **Cuando** selecciono importar un PDF desde mi Drive o un chat de WhatsApp
* **Entonces** el sistema lo descarga a mi bóveda, muestra una vista previa y me pide confirmar su fecha de vencimiento.

**Característica:** Agendamiento de citas
* **Escenario:** Crear cita desde un documento
* **Dado** que estoy visualizando un documento (ej. receta médica)
* **Cuando** presiono el botón "Agendar Cita"
* **Entonces** se abre un formulario simple de fecha y hora, y al guardar, la cita queda vinculada al documento en mi calendario.

# Dudas
* **Integraciones:** ¿Cómo manejaremos la privacidad y los permisos al conectar Drive, Correo y especialmente WhatsApp en Listoco?
* **Accesibilidad:** ¿Se incluirá un modo de lectura por voz o iconos descriptivos grandes para los adultos mayores?
* **Notificaciones:** Para las alertas de vencimiento y citas, ¿serán notificaciones push en el celular, correos electrónicos, o mensajes de WhatsApp automatizados?

Hazme todas las dudas que tengas sobre la arquitectura técnica antes de empezar y solo cuando estés claro te lanzas a desarrollar.
