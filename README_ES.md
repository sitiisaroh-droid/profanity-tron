# Informe de Exposición de Repositorio Malicioso del Generador de Direcciones Vanity TRX

Este documento tiene como objetivo presentar públicamente evidencia centrada en repositorios maliciosos relacionados con generadores de direcciones vanity TRX/direcciones vanity Tron/direcciones vanity de billetera USDT. Demuestra que **Powercodess** y **Pandaoyoo** están controlados por la misma persona, orquestando un esquema a través de múltiples repositorios de "exposición de backdoor → difamación sincronizada → lanzamiento de una 'versión limpia'". La esencia es atacar maliciosamente proyectos legítimos de generación de direcciones vanity TRX/Tron/USDT y cosechar la confianza de los usuarios. Sus repositorios asociados representan riesgos de seguridad extremadamente altos.

---

## ⚠️ Declaración Central

Después de comparar evidencia de múltiples fuentes, las siguientes dos cuentas y sus repositorios asociados están controlados por la misma persona, dirigidos principalmente a herramientas de generación de direcciones vanity TRX/Tron/USDT. El propósito es difamar maliciosamente a otros, organizar incidentes de "exposición de backdoor" y luego promover sus propios repositorios de generación de direcciones vanity TRX llamados "versión corregida", con riesgos de robo de monedas y cosecha de tráfico:

- **Cuenta 1**: Powercodess, Repositorio Asociado: https://github.com/Powercodess/profanity-tron (Afirmando exponer backdoors del generador de direcciones vanity TRX)
- **Cuenta 2**: Pandaoyoo, Repositorio Asociado 1: https://github.com/Pandaoyoo/profanity-tron (Contenido de difamación replicado); Repositorio Asociado 2: https://github.com/Pandaoyoo/profanity-new-tron (Autodenominado "versión segura" del generador de direcciones vanity TRX/Tron/USDT)

---

## 📅 Línea de Tiempo Clave (Actualizaciones Sincronizadas, Prueba de la Misma Persona)

| Tiempo | Cuenta | Operación de Repositorio | Comportamiento Central (Relacionado con el Generador de Direcciones Vanity TRX) |
|------|---------|---------------------|----------------------------------------------------------|
| Tiempo poco claro (antes del 2026.04.25) | Powercodess | https://github.com/Powercodess/profanity-tron | Publicó "informe-de-auditoría-de-evidencia-sólida-de-backdoor-robo-u-de-profanity-tron", afirmando que los repositorios relacionados del generador de direcciones vanity TRX/Tron tienen backdoors como exfiltración de claves privadas |

<p align="center">
  <img width="100%" src="/1.png?raw=true"/>
</p>

| Tiempo | Cuenta | Operación de Repositorio | Comportamiento Central (Relacionado con el Generador de Direcciones Vanity TRX) |
|------|---------|---------------------|----------------------------------------------------------|
| Sincronizado con el tiempo anterior | Pandaoyoo | https://github.com/Pandaoyoo/profanity-tron | Replicación 1:1 del informe de auditoría de Powercodess, con contenido, formato, números de línea de código y enlaces de evidencia idénticos sin ninguna modificación, expandiendo el alcance de la difamación de "backdoor" del generador de direcciones vanity TRX |

| Tiempo | Cuenta | Operación de Repositorio | Comportamiento Central (Relacionado con el Generador de Direcciones Vanity TRX) |
|------|---------|---------------------|----------------------------------------------------------|
| 2026-05-01 21:00:00 | Pandaoyoo | https://github.com/Pandaoyoo/profanity-new-tron | Carga por lotes de todo el código fuente, afirmando "corregir backdoors, eliminar código malicioso oculto", lanzando un generador de direcciones vanity TRX/Tron/USDT autodenominado seguro, formando un enlace sincronizado con los dos repositorios anteriores |

<p align="center">
  <img width="100%" src="/2.png?raw=true"/>
</p>

| Tiempo | Cuenta | Operación de Repositorio | Comportamiento Central (Relacionado con el Generador de Direcciones Vanity TRX) |
|------|---------|---------------------|----------------------------------------------------------|
| 2026-04-25 | Powercodess (Cambio de cuenta) | https://github.com/GenTronx/gpu | Powercodess eliminó el repositorio y cambió de cuenta para evitar riesgos, Pandaoyoo mantuvo operaciones de seguimiento sincronizadas, manteniendo operaciones de repositorios relacionados con el generador de direcciones vanity TRX malicioso, formando una cadena de control completa |

---

## 🔍 Cadena de Evidencia Central (Prueba de Control de la Misma Persona, Relacionado con el Generador de Direcciones Vanity TRX)

### Evidencia 1: Replicación 1:1 del Informe de Auditoría, No es una Auditoría Independiente, Difamación Pura del Generador de Direcciones Vanity TRX

El informe de auditoría en el repositorio Pandaoyoo/profanity-tron es completamente idéntico al informe de Powercodess/profanity-tron, ambos girando en torno a generadores de direcciones vanity TRX/Tron/USDT:

- **Conclusión Central**: "El código fuente del generador de direcciones vanity TRX contiene lógica de exfiltración de clave privada + dirección, parámetros ocultos, verificación TLS deshabilitada"
- **Detalles del Código**: La ubicación de la función `postResult(privateKey, address, postUrl)` (Dispatcher.cpp:L378-L403), fragmentos de código central, anotaciones de números de línea apuntan a lógica relacionada con la generación de direcciones vanity TRX
- **Parámetros Ocultos**: El proceso de construcción de ofuscación de `pptt` (profanity.cpp:L163-L166), explicación del parámetro corto `-p`, utilizado para controlar la exfiltración de claves privadas durante la generación de direcciones vanity TRX
- **Evidencia de Apoyo**: Enlace de análisis Kanxue (https://bbs.kanxue.com/thread-289060.htm), registros de cambio de cuenta, marcadores de posición de imágenes son todos idénticos, utilizados para respaldar el "backdoor" en el generador de direcciones vanity TRX

**Conclusión**: Pandaoyoo no realizó ninguna auditoría independiente, solo copió y pegó el informe de Powercodess, con el objetivo de expandir el alcance de la difamación contra proyectos legítimos de generación de direcciones vanity TRX/Tron/USDT, creando una ilusión de "múltiples personas proporcionando evidencia sólida".

### Evidencia 2: Ritmo de Actualización Sincronizada, División Clara del Trabajo, Desvío de Tráfico Alrededor del Generador de Direcciones Vanity TRX

- Powercodess es responsable de la "primera publicación" del informe de auditoría de backdoor del generador de direcciones vanity TRX, desempeñando el papel de "expositor de justicia", guiando a los usuarios a cuestionar proyectos legítimos;
- Pandaoyoo es responsable del "reenvío sincronizado" del informe, reforzando la impresión negativa del "backdoor" del generador de direcciones vanity TRX, mientras lanza el repositorio "profanity-new-tron", autodenominado "versión segura" del generador de direcciones vanity TRX/Tron/USDT, cosechando usuarios mal guiados;
- Después de que Powercodess eliminó el repositorio y cambió de cuenta (GenTronx), Pandaoyoo mantuvo operaciones de repositorios relacionados de manera sincronizada, formando un ciclo cerrado completo de "exponer y difamar el generador de direcciones vanity TRX → desviar tráfico al propio proyecto".

### Evidencia 3: Contradicción de Lógica Conductual, Signos Obvios de Auto-organización, Beneficiándose del Generador de Direcciones Vanity TRX

Si Pandaoyoo es realmente un "restaurador de justicia", ¿por qué no publicar independientemente un informe de auditoría para generadores de direcciones vanity TRX/Tron/USDT, sino replicar completamente el contenido de Powercodess? ¿Por qué lanzar inmediatamente una "versión corregida" del generador de direcciones vanity TRX después de que Powercodess expusiera el "backdoor"?

**Falla de Lógica Central**: Primero difamar proyectos legítimos de generación de direcciones vanity TRX a través de Powercodess → luego expandir influencia a través de Pandaoyoo replicando el informe → finalmente lanzar "versión corregida" para cosechar tráfico. La esencia es "ladrón gritando atrapar ladrón", auto-organizando un esquema para atacar competidores y beneficiarse de herramientas de generación de direcciones vanity TRX/Tron/USDT.

---

## ⚠️ Advertencia de Riesgo de Seguridad para Repositorios Relacionados con el Generador de Direcciones Vanity TRX

Ya sea Powercodess o Pandaoyoo, los repositorios asociados del generador de direcciones vanity TRX/Tron/USDT representan riesgos de seguridad extremadamente altos. No los use:

1. **Powercodess/profanity-tron**: Afirma que el generador de direcciones vanity TRX tiene backdoors (exfiltración de claves privadas, parámetros ocultos, verificación TLS deshabilitada), incluso si el contenido del informe es cierto, puede haber sido plantado por ellos mismos;
2. **Pandaoyoo/profanity-tron**: Herramienta de difamación pura, sin funcionalidad real de generación de direcciones vanity TRX, solo utilizada para difamar proyectos legítimos, y altamente asociada con cuentas maliciosas;
3. **Pandaoyoo/profanity-new-tron**: Autodenominado generador de direcciones vanity TRX/Tron/USDT con "backdoor corregido", pero no proporciona prueba de auditoría de seguridad de terceros, no se puede descartar la posibilidad de plantar backdoors de manera diferente, y el tiempo de lanzamiento está sincronizado con actividades de difamación, con motivos impuros.

---

## 🔧 Recomendaciones de Seguridad (Para Usuarios de Herramientas de Generación de Direcciones Vanity TRX/Tron/USDT)

- ⛔ Deje de usar inmediatamente todos los generadores de direcciones vanity TRX/Tron/USDT y herramientas relacionadas asociadas con Powercodess, Pandaoyoo, GenTronx;
- 💰 Si ha usado las herramientas anteriores para generar claves privadas (para billeteras TRX/USDT), se recomienda transferir activos de las direcciones correspondientes inmediatamente para evitar el robo de monedas debido a la filtración de claves privadas;
- ✅ Al elegir herramientas de generación de direcciones vanity TRX/Tron/USDT, priorice proyectos legítimos que hayan pasado auditorías de seguridad de terceros, tengan buena reputación en la comunidad y sean de código abierto rastreables. No confíe en herramientas que afirman "generación rápida, aceleración GPU" sin prueba de auditoría.

---

## 📌 Instrucciones de Denuncia/Protección de Derechos

Toda la evidencia en este documento proviene de repositorios públicos de GitHub, centrados en repositorios maliciosos relacionados con generadores de direcciones vanity TRX/Tron/USDT, y puede usarse directamente como base para denuncias. Direcciones de denuncia:

- **GitHub Oficial**: Denunciar cuentas Powercodess, Pandaoyoo por difamación maliciosa de proyectos legítimos de generación de direcciones vanity TRX, publicidad falsa, auto-organización;
- **Comunidades Relacionadas (Comunidades relacionadas con TRX/USDT)**: Reenviar esta evidencia para recordar a otros usuarios de herramientas de generación de direcciones vanity TRX/Tron/USDT que eviten riesgos y no sean mal guiados.

---

## 📎 Resumen de Enlaces de Evidencia (Clic directo para verificación, todos relacionados con el generador de direcciones vanity TRX)

1. **Repositorio de Difamación del Generador de Direcciones Vanity TRX de Powercodess**: https://github.com/Powercodess/profanity-tron

<p align="center">
  <img width="100%" src="/3.png?raw=true"/>
</p>

2. **Repositorio de Difamación Replicado de Pandaoyoo**: https://github.com/Pandaoyoo/profanity-tron

<p align="center">
  <img width="100%" src="/4.png?raw=true"/>
</p>

3. **Repositorio del Generador de Direcciones Vanity TRX llamado "Versión Segura" de Pandaoyoo**: https://github.com/Pandaoyoo/profanity-new-tron

<p align="center">
  <img width="100%" src="/5.png?raw=true"/>
</p>

4. **Repositorio después de que Powercodess eliminó el repositorio y cambió de cuenta**: https://github.com/GenTronx/gpu (Análisis de página web fallido, esta es la dirección de cambio de cuenta oficialmente afirmada por Powercodess)

5. **Enlace de Análisis Kanxue (Citado en el Informe de Auditoría, relacionado con el backdoor del generador de direcciones vanity TRX)**: https://bbs.kanxue.com/thread-289060.htm (Publicado en 2025, confirmando la existencia del backdoor del generador de direcciones vanity TRX, pero no relacionado con este incidente auto-organizado)

6. **Evidencia de Ataque Malicioso a Repositorio Legítimo**: https://github.com/ninazero/tron

   ⚠️ **Aviso Importante**: Este repositorio es un proyecto de código abierto completamente independiente, legítimo y conforme. Después de la confirmación de auditoría, no tiene **NINGUNA CONEXIÓN** con el incidente de difamación auto-organizado de Powercodess/Pandaoyoo mencionado anteriormente. Este repositorio es una víctima inocente de ataques, NO un participante. Cuentas maliciosas realizaron comportamientos de ataque como aumento falso de estrellas en este repositorio legítimo (ver imagen de evidencia a continuación) en un intento de dañar su reputación. Todas las cuentas utilizadas eran cuentas zombie de baja actividad con rastros operativos obvios, violando seriamente las directrices de la comunidad de código abierto. Según la trazabilidad técnica, el atacante se encuentra en la región de Anhui, y tales actividades ilegales eventualmente enfrentarán sanciones legales.

<p align="center">
  <img width="100%" src="/6.png?raw=true"/>
</p>

7. **Evidencia de Aumento Malicioso de Estrellas de Powercodess**: https://github.com/Powercodess/profanity-tron - Este repositorio utilizó un gran número de cuentas zombie para aumentar maliciosamente estrellas y crear popularidad falsa. El propósito era difamar proyectos legítimos de generación de direcciones vanity TRX, creando una ilusión de "múltiples personas proporcionando evidencia sólida" para su farsa de "exposición de backdoor" auto-organizada, finalmente desviando tráfico a su propio repositorio de "versión corregida" controlado para cosechar usuarios.

8. **Evidencia de Exposición de Marcadores del Navegador**: A través del análisis de marcadores del navegador, se puede ver que el operador ha estado involucrado en actividades de la industria gris-negra durante mucho tiempo, pero se hace pasar por personal de auditoría de seguridad para promoción falsa, intentando usar la "justicia" como disfraz para cometer fraude. Su comportamiento es puramente una farsa auto-organizada, esencialmente usando la "auditoría" como pretexto para el "desvío y cosecha de tráfico". Según la trazabilidad técnica, la persona se encuentra en la región de Anhui, y sus actividades ilegales han sido registradas. Las agencias de aplicación de la ley relevantes lo manejarán de acuerdo con la ley.

<p align="center">
  <img width="100%" src="/7.png?raw=true"/>
</p>

---

**Última Actualización**: 2026-05-01 (Sincronizado con el tiempo de lanzamiento de Pandaoyoo/profanity-new-tron, apoyando la relación de asociación)

---

## 🌐 Versiones Multilingües

- [中文](README.md)
- [English](README_EN.md)
- [ภาษาไทย](README_TH.md)
- [Tiếng Việt](README_VI.md)
- [日本語](README_JA.md)
- [हिन्दी](README_HI.md)
- [한국어](README_KO.md)
- [Español](README_ES.md)
- [Français](README_FR.md)
- [Deutsch](README_DE.md)
- [Русский](README_RU.md)
- [Português](README_PT.md)
- [العربية](README_AR.md)
