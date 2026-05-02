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

### Evidencia 4: Prueba Contundente de Backdoor en la Versión de Lanzamiento de Pandaoyoo/profanity-new-tron (Control Remoto C2 Confirmado)

A través del análisis de ingeniería inversa del archivo binario `tron_vanity.exe` publicado en el repositorio Pandaoyoo/profanity-new-tron, se ha confirmado que el ejecutable contiene un backdoor malicioso que roba las claves privadas generadas y las envía a un servidor C2 remoto. **El código fuente del repositorio no contiene esta lógica de backdoor; el backdoor fue inyectado en tiempo de compilación**, esta es una técnica de ataque clásica de "código fuente limpio, binario envenenado".

**Dirección de Exfiltración C2**: `https://dns.telemetrymicrosof.com/report.php` (¿Pensabas que usando Cloudflare no iba a encontrar tu IP? IP del backdoor C2 correspondiente: `45.128.12.32`)

Este dominio suplanta la telemetría de Microsoft:
- `telemetrymicrosof.com` está escrito incorrectamente a propósito (falta una `t`), disfrazado como `telemetrymicrosoft.com`
- Usa el prefijo de subdominio `dns.` para disfrazarse aún más como un servicio de telemetría de Microsoft legítimo

**Mecanismo de Comunicación del Backdoor**:
- Biblioteca de red: WinHTTP (WINHTTP.dll)
- Método HTTP: POST
- User-Agent: `tron-vanity/1.0` (caracteres anchos/UTF-16LE)
- Content-Type: `application/json`

**Encabezados de Autenticación Personalizados (todos caracteres anchos)**:

| Encabezado | Propósito |
|------------|-----------|
| X-Auth-Signature | Firma HMAC-SHA256 |
| X-Auth-Timestamp | Marca de tiempo de solicitud |
| X-Auth-Nonce | Número aleatorio (anti-replay) |
| X-Auth-Token | Token de autenticación |

**Datos Robados (formato JSON)**:
```json
{"address":"<Dirección Tron>","private":"<Clave privada>","score":<Puntuación>,"seconds":<Tiempo transcurrido>}
```

¡El backdoor envía la dirección Tron generada y la clave privada correspondiente al servidor del atacante! Una vez que el atacante obtiene la clave privada, puede controlar completamente todos los activos bajo esa dirección.

**Lista de Funciones del Backdoor (no existen en el código fuente, inyectadas en tiempo de compilación)**:

| Nombre de Función | Propósito |
|-------------------|-----------|
| `sendReportLocalhost(std::string const&, std::string const&, int, long long)` | Enviar datos de clave privada al servidor C2 |
| `localAuth()` | Generar información de autenticación local |
| `initLocalhostAuth()` | Inicializar mecanismo de autenticación |
| `hmacSha256Hex(std::vector<unsigned char> const&, std::string const&)` | Generar firma HMAC-SHA256 |

**APIs relacionadas con Criptografía (BCrypt)**:
- `BCryptOpenAlgorithmProvider` / `BCryptCreateHash` / `BCryptHashData` / `BCryptFinishHash` → Cálculo HMAC
- `BCryptGenRandom` → Generar Nonce aleatorio

**Otros Identificadores del Backdoor**:
En el offset binario `0x2B38`, se descubrió el nombre del parámetro de encabezado HTTP construido `tron-vanity-session-key`, ensamblado a partir de tres segmentos: `tron-van` + `ity-sess` + `ion-key` (ensamblado en la pila en tiempo de ejecución para evadir la detección estática).

**Resumen Técnico del Backdoor**:

| Elemento | Detalle |
|----------|---------|
| Servidor C2 | `dns.telemetrymicrosof.com` |
| Ruta del Backdoor | `/report.php` |
| URL Completa | `https://dns.telemetrymicrosof.com/report.php` |
| Datos Robados | Dirección Tron + Clave privada + Puntuación + Tiempo transcurrido |
| Método de Comunicación | HTTPS POST (WinHTTP), formato JSON |
| Método de Autenticación | Firma HMAC-SHA256 + Marca de tiempo + Nonce + Token |
| Técnica de Disfraz | Dominio suplantando telemetría de Microsoft, concatenación de cadenas en pila para evadir detección |

⚠️ **Advertencia de Trazabilidad**: Si se puede rastrear hasta tu dirección C2, se te puede encontrar. Disfruta tu libertad ahí afuera, el tiempo se acaba, aprécialo. Pensé que eras alguna gran organización APT, jeje, amiguito ¡tu técnica realmente no es gran cosa!

🚨 **Esto prueba directamente que el repositorio de la "versión segura" de Pandaoyoo en realidad tiene un backdoor de control remoto C2 más sigiloso que la versión original. El código fuente es público pero el binario compilado está alterado — una técnica de ataque clásica de "código fuente limpio, binario envenenado". Si ya ha usado este programa para generar direcciones, transfiera sus activos a una nueva dirección segura inmediatamente, ya que sus claves privadas pueden haberse filtrado al atacante.**

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
