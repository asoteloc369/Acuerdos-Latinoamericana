# Acuerdos-Latinoamericana
Sistema con Inteligencia Artificial para extracción automática de datos de formatos de acuerdos funerarios.
# 🏛️ Sistema de Acuerdos y Expedientes - Latinoamericana Recinto Funeral

Sistema con Inteligencia Artificial para extracción automática de datos de formatos de acuerdos funerarios.

---

## 🚀 GUÍA DE CONFIGURACIÓN EN GITHUB PAGES

Esta guía te llevará paso a paso para configurar tu sistema en GitHub Pages. El proceso completo toma aproximadamente quince minutos y una vez configurado, tu sistema estará disponible en línea de forma permanente.

---

## PASO 1: Crear una Cuenta en GitHub

Primero necesitas crear una cuenta gratuita en GitHub si aún no tienes una. GitHub es una plataforma de Microsoft que ofrece servicios de hosting gratuito para aplicaciones web como esta.

1. Abre tu navegador web (Chrome, Firefox, Edge, o Safari)
2. Ve a la página: **https://github.com**
3. Verás un botón grande que dice **"Sign up"** (Registrarse). Haz clic en él
4. Completa el formulario de registro con:
   - Tu correo electrónico (puede ser personal o de trabajo)
   - Una contraseña segura que puedas recordar
   - Un nombre de usuario (puede ser tu nombre o el de tu empresa)
5. GitHub te pedirá que verifiques que eres humano con un pequeño acertijo o captcha
6. Haz clic en **"Create account"** (Crear cuenta)
7. GitHub te enviará un código de verificación a tu correo electrónico
8. Revisa tu bandeja de entrada y copia el código de seis dígitos
9. Pégalo en la página de GitHub donde te lo solicitan
10. GitHub te hará algunas preguntas opcionales sobre cómo planeas usar la plataforma. Puedes saltarlas haciendo clic en **"Skip"** o responderlas si lo prefieres

¡Listo! Ya tienes tu cuenta de GitHub creada y estás en tu página principal.

---

## PASO 2: Crear un Nuevo Repositorio

Un repositorio es como una carpeta especial en GitHub donde guardarás los archivos de tu sistema. Piensa en él como un contenedor organizado para tu proyecto.

1. En la esquina superior derecha de la pantalla, verás un símbolo de **más (+)**. Haz clic en él
2. En el menú que aparece, selecciona **"New repository"** (Nuevo repositorio)
3. Te llevará a una página para configurar tu nuevo repositorio. Completa la información:

   **Repository name** (Nombre del repositorio):
   - Escribe: `sistema-latinoamericana`
   - Este nombre será parte de la URL de tu sistema, así que usa algo descriptivo
   - No uses espacios, solo guiones o guiones bajos
   
   **Description** (Descripción) - Opcional:
   - Puedes escribir: "Sistema de gestión de acuerdos con IA para Latinoamericana Recinto Funeral"
   - O dejar este campo vacío
   
   **Public/Private** (Público/Privado):
   - **IMPORTANTE:** Selecciona **"Public"** (Público)
   - Aunque se llame "público", esto no significa que cualquiera pueda encontrar tu sistema
   - Es necesario para que GitHub Pages funcione en la versión gratuita
   - La URL que se genere será aleatoria y no aparecerá en buscadores
   
   **Initialize this repository with**:
   - ✅ Marca la casilla **"Add a README file"** (Agregar archivo README)
   - Esto inicializa el repositorio correctamente y te facilitará el siguiente paso

4. Haz clic en el botón verde **"Create repository"** (Crear repositorio) en la parte inferior

¡Excelente! Ahora tienes tu repositorio creado. Verás una página con tu nuevo repositorio que contiene un archivo README inicial.

---

## PASO 3: Subir el Archivo HTML del Sistema

Ahora es momento de subir el archivo principal de tu sistema a GitHub. Este archivo contiene toda la interfaz, la lógica de procesamiento, y las integraciones con las APIs de Google.

1. En la página de tu repositorio, busca el botón **"Add file"** (Agregar archivo) en la parte superior derecha
2. Haz clic en él y selecciona **"Upload files"** (Subir archivos)
3. Verás una página con un área grande que dice "Drag files here" (Arrastra archivos aquí)

4. **Preparar el archivo para subir:**
   - Descarga el archivo `index.html` que te proporcioné (este es el sistema con IA integrada)
   - Asegúrate de que el archivo se llame exactamente **`index.html`** (no `sistema_latinoamericana_con_ia.html`)
   - Esto es importante porque GitHub Pages busca automáticamente un archivo llamado `index.html` como página principal

5. **Subir el archivo:**
   - Arrastra el archivo `index.html` desde tu carpeta de descargas hasta el área indicada en GitHub
   - O haz clic en **"choose your files"** para seleccionarlo manualmente desde tu computadora
   - Verás el nombre del archivo aparecer en la lista de archivos a subir

6. **Confirmar la subida:**
   - En la parte inferior de la página hay un cuadro de texto con el título "Commit changes"
   - Puedes dejar el mensaje por defecto que dice "Add files via upload"
   - O cambiarlo por algo más descriptivo como "Subir sistema de acuerdos v1.0"
   - Haz clic en el botón verde **"Commit changes"** (Confirmar cambios)

GitHub procesará el archivo (toma solo unos segundos) y te regresará a la página principal de tu repositorio. Ahora deberías ver dos archivos listados: el README y tu index.html.

---

## PASO 4: Activar GitHub Pages

Ahora viene el paso crucial que convierte tu repositorio en un sitio web accesible. GitHub Pages es el servicio que tomará tu archivo HTML y lo publicará en línea con una URL permanente.

1. En la página de tu repositorio, busca las pestañas en la parte superior
2. Verás pestañas como: Code, Issues, Pull requests, Actions, Projects, Wiki, Security, Insights, y **Settings**
3. Haz clic en la pestaña **"Settings"** (Configuración) - es la última a la derecha

4. En la página de configuración, mira el menú lateral izquierdo
5. Desplázate hacia abajo hasta encontrar la sección **"Code and automation"**
6. Dentro de esa sección, haz clic en **"Pages"**

7. En la página de GitHub Pages, verás varias opciones:

   **Source** (Fuente):
   - Hay un menú desplegable que probablemente dice **"None"** (Ninguno)
   - Haz clic en ese menú desplegable
   - Selecciona **"main"** o **"master"** (el nombre de tu rama principal)
   - Esto le dice a GitHub que quieres publicar los archivos de tu rama principal

   **Folder** (Carpeta):
   - Déjalo en **"/ (root)"** (raíz)
   - Esto significa que GitHub buscará tu index.html en la raíz del repositorio

8. Haz clic en el botón **"Save"** (Guardar)

GitHub comenzará a procesar y publicar tu sitio. Verás un mensaje que dice "GitHub Pages source saved" (Fuente de GitHub Pages guardada). La página se refrescará automáticamente y después de uno o dos minutos, verás un cuadro verde o azul en la parte superior con un mensaje como:

**"Your site is published at https://tu-usuario.github.io/sistema-latinoamericana/"**

Esta es la URL permanente de tu sistema. Cópiala completa.

---

## PASO 5: Acceder y Probar tu Sistema

Ahora que tu sistema está publicado en GitHub Pages, es momento de accederlo y verificar que todo funcione correctamente.

1. **Acceder al sistema:**
   - Copia la URL que GitHub te proporcionó (algo como https://tu-usuario.github.io/sistema-latinoamericana/)
   - Pégala en una nueva pestaña de tu navegador
   - Presiona Enter

2. **Primera carga:**
   - El sistema puede tardar entre treinta segundos y dos minutos en estar disponible la primera vez
   - Si ves un error cuatrocientos cuatro (404 - Page Not Found), espera un minuto más y refresca la página
   - Una vez que cargue, verás la interfaz completa de tu Sistema de Acuerdos y Expedientes

3. **Verificar que está funcionando:**
   - Deberías ver el título "Sistema de Acuerdos y Expedientes" en grande
   - El subtítulo "Latinoamericana Recinto Funeral"
   - Un badge verde que dice "IA Activada - Extracción Automática"
   - Dos opciones para seleccionar tipo de servicio: Necesidad Inmediata y Servicio PABS

4. **Probar con un documento real:**
   - Selecciona el tipo de servicio apropiado
   - Haz clic en la zona de carga o arrastra un formato de acuerdos
   - Una vez cargado, haz clic en "Extraer Datos con IA"
   - El sistema debería procesar sin errores de "Failed to fetch"
   - Verás los pasos de procesamiento iluminarse uno por uno
   - Después de diez a treinta segundos, el formulario debería aparecer con los datos extraídos

5. **Guardar la URL:**
   - Si todo funcionó correctamente, guarda esta URL en tus favoritos
   - Puedes crear un acceso directo en tu escritorio que abra directamente esta dirección
   - Comparte la URL solo con miembros de confianza de tu equipo en Latinoamericana

---

## ⚠️ CONSIDERACIONES DE SEGURIDAD

Es importante que entiendas algunos aspectos sobre la seguridad de tu sistema ahora que está hospedado en línea.

**La URL es privada pero no secreta:**
Tu sistema tiene una URL única que GitHub generó automáticamente. Esta URL no está indexada en motores de búsqueda como Google, Bing, o Yahoo. Nadie puede encontrar tu sistema buscando términos relacionados con servicios funerarios o Latinoamericana. Sin embargo, cualquier persona que conozca la URL exacta puede acceder al sistema. Por esta razón, comparte la URL solo con personas de confianza dentro de tu organización.

**Las API Keys están en el código:**
Las claves de Google Cloud Vision y Gemini AI están incluidas en el archivo HTML. Cualquier persona con conocimientos técnicos que acceda a tu sistema podría abrir el inspector de código del navegador y ver estas claves. Para la mayoría de los casos de uso interno, esto no representa un problema significativo, especialmente porque puedes monitorear el uso de las claves desde Google Cloud Console y detectar cualquier actividad inusual.

**Monitoreo de uso:**
Te recomiendo que revises periódicamente el uso de tus API Keys en Google Cloud Console. Puedes ver cuántas llamadas se han hecho a cada servicio y detectar si hay uso anormal que pudiera indicar que alguien está usando tus claves sin autorización. Si alguna vez sospechas que las claves fueron comprometidas, puedes deshabilitarlas inmediatamente desde Google Cloud y generar nuevas.

**Mejoras de seguridad futuras:**
Si en el futuro necesitas un nivel de seguridad más robusto, podríamos implementar varias mejoras como agregar autenticación con contraseña, mover las API Keys a un backend separado, o usar servicios de autenticación como Auth0 o Firebase Authentication. Por ahora, para comenzar y probar el sistema, la configuración actual es adecuada para uso interno.

---

## 🔄 CÓMO ACTUALIZAR EL SISTEMA

Cuando necesites actualizar el sistema en el futuro con nuevas funcionalidades o correcciones, el proceso es muy sencillo.

1. Ve a tu repositorio en GitHub
2. Haz clic en el archivo `index.html` existente
3. Haz clic en el ícono del lápiz que dice "Edit this file" (Editar este archivo)
4. Borra todo el contenido actual
5. Pega el contenido del nuevo archivo HTML actualizado
6. Haz clic en "Commit changes" (Confirmar cambios)
7. Espera uno o dos minutos y refresca tu sitio web

Todos los usuarios que accedan a la URL verán automáticamente la versión actualizada sin necesidad de que descarguen nada nuevo.

---

## 📊 PRÓXIMOS PASOS

Una vez que tu sistema esté funcionando correctamente en GitHub Pages y hayas probado con varios documentos reales, podemos avanzar a las siguientes fases del proyecto:

**Integración con Google Sheets:**
Configuraremos una conexión automática usando Make o Zapier para que cuando guardes un expediente, los datos se envíen automáticamente a tu hoja de cálculo. Esto eliminará completamente la necesidad de exportar y copiar manualmente.

**Sistema de Notificaciones WhatsApp:**
Implementaremos notificaciones automáticas por WhatsApp que se envíen cuando se procese un servicio nuevo, alertando a los miembros relevantes del equipo con la información del servicio.

**Dashboard de Reportes y Analíticas:**
Crearemos un panel de control donde podrás ver estadísticas de tus servicios, tendencias mensuales, tipos de servicio más comunes, análisis comparativo entre servicios PABS y de necesidad inmediata, y otros reportes que te ayuden en la toma de decisiones.

**Integración con Calendario de Capillas:**
Desarrollaremos una vista de calendario que muestre la ocupación de las capillas en tiempo real y permita verificar disponibilidad antes de asignar horarios.

---

## 🆘 SOLUCIÓN DE PROBLEMAS

**Problema: La página muestra error 404 después de activar GitHub Pages**
Solución: GitHub Pages puede tardar hasta diez minutos en publicar el sitio la primera vez. Espera unos minutos y refresca la página. Si el problema persiste después de quince minutos, verifica que el archivo se llame exactamente `index.html` y esté en la raíz del repositorio.

**Problema: El sistema carga pero muestra errores al procesar documentos**
Solución: Abre las herramientas de desarrollo del navegador presionando F12 y revisa la consola en busca de mensajes de error específicos. Los errores más comunes están relacionados con las API Keys. Verifica que las claves estén correctas y activas en Google Cloud Console.

**Problema: La extracción de datos no es precisa**
Solución: La precisión depende de la calidad de la imagen del documento. Asegúrate de que las fotos tengan buena iluminación, estén enfocadas, y el documento esté completamente visible. Si la extracción es consistentemente imprecisa en ciertos campos, podemos ajustar las instrucciones para Gemini AI.

**Problema: No puedo encontrar mi repositorio**
Solución: Inicia sesión en GitHub y haz clic en tu foto de perfil en la esquina superior derecha. Selecciona "Your repositories" (Tus repositorios) y verás una lista de todos los repositorios que has creado.

---

## 📞 SOPORTE

Si encuentras problemas durante la configuración o el uso del sistema, documenta el error específico que estás viendo, toma capturas de pantalla si es posible, y estaré disponible para ayudarte a resolverlo.

---

**Creado para:** Latinoamericana Recinto Funeral  
**Fecha:** Noviembre 2024  
**Versión:** 1.0  
**Tecnologías:** Google Cloud Vision API, Gemini AI, GitHub Pages

¡Tu sistema de extracción automática con IA está listo para usar!
