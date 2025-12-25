# Términos y Condiciones de ViralNexus

Fecha de última actualización: 17 de noviembre de 2025

Bienvenido a ViralNexus ("la App", "nosotros"). Al descargar, instalar o utilizar nuestra aplicación móvil, usted ("el Usuario") acepta estar sujeto a los siguientes Términos y Condiciones ("Términos").

**1. Descripción del Servicio**

ViralNexus es una aplicación móvil diseñada para ayudar a los creadores de contenido de TikTok a analizar su rendimiento y obtener ideas estratégicas. El servicio requiere una conexión a su cuenta de TikTok para descargar las métricas de sus videos y proporcionar análisis y recomendaciones generadas por inteligencia artificial (IA).

**2. Conexión a TikTok y Fuente de Datos**

Para utilizar la App, usted debe autorizar a ViralNexus a acceder a su cuenta de TikTok a través del SDK oficial de TikTok. Los permisos solicitados se limitan a userInfoBasic (para verificar su cuenta) y videoList (para acceder a la lista de sus videos públicos y sus métricas).

ViralNexus actúa únicamente como un cliente que interactúa con la API oficial de TikTok. No estamos afiliados, asociados, autorizados, respaldados ni conectados de ninguna manera oficial con TikTok Inc.

**3. Arquitectura de Datos y Privacidad**

Nuestra arquitectura está diseñada con la privacidad como pilar fundamental, combinando el almacenamiento local seguro con el procesamiento inteligente en la nube.

*3.1. Almacenamiento 100% Local (Sus Datos Personales)*

Los siguientes datos de su cuenta se descargan y almacenan exclusiva y permanentemente en la base de datos local de su dispositivo (viralnexus_db.sqlite). Estos datos nunca abandonan su dispositivo:

Tokens de Autenticación: Sus tokens de acceso y actualización de TikTok (AuthTokens).

Datos de Video: La lista completa de sus videos sincronizados, incluyendo URL de miniaturas, recuentos de vistas, "me gusta", comentarios y compartidos (UserVideos).

*3.2. Procesamiento de IA en la Nube (Datos de Rendimiento)*

Para proporcionar las funciones avanzadas de recomendación de IA (como la "Idea del Día", el análisis de video individual y las recomendaciones de pantalla), la App envía datos de rendimiento anonimizados y no identificables a nuestros servicios seguros en la nube (Google Cloud Functions).

Estos datos de rendimiento pueden incluir:

Títulos o descripciones de videos.

Métricas de rendimiento (ej. "me gusta", vistas).

Hashtags utilizados.

Promedios de rendimiento de su cuenta.

Nunca enviamos sus tokens de autenticación, información de perfil de usuario ni archivos de video a nuestros servidores de IA. El único propósito de enviar estos datos de rendimiento es para que nuestros modelos de IA puedan generar los valiosos insights que se le devuelven y se almacenan en su caché local.

**4. Control del Usuario sobre sus Datos**

Usted mantiene el control total sobre sus datos de las siguientes maneras:

Eliminación de Datos: En la pantalla de "Configuración", usted puede usar la opción "Reiniciar Datos de Tiktok". Esta acción revocará permanentemente el acceso de la App a su cuenta de TikTok y borrará de forma irreversible toda la base de datos local de su dispositivo (clearAllData).

Control de Conectividad:

La sincronización inicial de videos requiere una conexión Wi-Fi para proteger su plan de datos móviles.

Usted puede deshabilitar el uso de datos móviles para las funciones de IA en cualquier momento desde el menú de "Configuración".

**5. Uso Aceptable**

Usted acepta no utilizar la App para ningún propósito ilegal o no autorizado. Se prohíbe intentar realizar ingeniería inversa, descompilar la App, interferir con nuestros servicios en la nube o utilizar la App de cualquier manera que pueda dañar, deshabilitar o sobrecargar nuestros sistemas.

**6. Limitación de Responsabilidad**

La App se proporciona "tal cual". Si bien nos esforzamos por proporcionar análisis precisos y útiles, las recomendaciones generadas por la IA son sugerencias y no garantizan el éxito, el crecimiento de seguidores ni la viralidad del contenido.

ViralNexus no será responsable de ninguna pérdida de datos, interrupción del servicio (incluidas las fallas de la API de TikTok) o cualquier daño directo o indirecto que surja del uso o la incapacidad de usar la App.

**7. Modificaciones a los Términos**

Nos reservamos el derecho de modificar estos Términos en cualquier momento. La fecha de "última actualización" en la parte superior de este documento indicará cuándo se realizaron los últimos cambios. Su uso continuado de la App después de cualquier modificación constituye su aceptación de los nuevos Términos.

**8. Contacto**

Si tiene alguna pregunta sobre estos Términos, próximamente tendremos línea de comunicación vía soporte.
