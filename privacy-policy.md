# Política de Privacidad de ViralNexus

Fecha de última actualización: 17 de noviembre de 2025

En ViralNexus, su privacidad es nuestro pilar fundamental. Esta política explica qué información manejamos, cómo la almacenamos y cómo la utilizamos para potenciar su crecimiento como creador.

Nuestra filosofía es simple: Sus datos personales y credenciales de acceso se quedan en su dispositivo. Los datos de rendimiento de sus videos se utilizan para generar análisis, tanto localmente como en la nube, pero nunca se venden ni se comparten.

**1. La Arquitectura Híbrida: Local y Nube**

ViralNexus utiliza una arquitectura híbrida para equilibrar la máxima privacidad con el poder de la inteligencia artificial avanzada.

*A. Lo que se Almacena 100% Localmente en su Dispositivo*

La siguiente información se descarga desde la API oficial de TikTok y se almacena en una base de datos segura (tiknexus_db.sqlite) exclusivamente en su dispositivo. Esta información nunca se envía a nuestros servidores:

Credenciales de Acceso: Sus tokens de acceso y actualización de TikTok (AuthTokens). Estos son esenciales para que la app pueda comunicarse con TikTok en su nombre.

Datos de Videos y Métricas: La lista completa de sus videos sincronizados, incluyendo sus métricas (vistas, "me gusta", comentarios, compartidos), miniaturas y fechas de creación (UserVideos).

*B. Lo que se Procesa Localmente en su Dispositivo*

Ciertos análisis que no requieren IA avanzada se realizan directamente en su teléfono utilizando los datos locales mencionados anteriormente. Esto incluye:

Análisis de Hashtags: El cálculo de vistas totales y videos usados por hashtag.

Análisis de Horarios: La generación del "mapa de calor" para encontrar sus mejores horas para publicar.

*C. Lo que se Procesa en la Nube (Para la IA)*

Para ofrecerle recomendaciones de IA potentes y personalizadas (como la "Idea del Día", el análisis por video y las recomendaciones de contenido), la app envía datos de rendimiento anonimizados a nuestros servicios seguros en la nube (Google Cloud Functions) para su procesamiento.

Los datos de rendimiento que enviamos para analizar pueden incluir:

Títulos o descripciones de sus videos recientes o más populares.

Métricas agregadas (ej. "vistas promedio", "me gusta promedio").

Hashtags que más utiliza.

Para ser claros: Nunca enviamos sus credenciales (Tokens) ni información de su perfil personal a nuestros servidores de IA. El único propósito de este procesamiento en la nube es generar los insights que se le devuelven y se guardan en la caché local de su app.

**2. Su Control Total sobre sus Datos**

Usted siempre tiene el control sobre su información.

Eliminación Total de Datos: En cualquier momento, puede ir a Configuración y seleccionar "Reiniciar Datos de Tiktok". Esta acción realiza dos cosas:

Revoca el acceso de la app a su cuenta de TikTok.

Borra permanentemente toda la base de datos local de su dispositivo (clearAllData), eliminando todos sus tokens, videos y caché de análisis.

Control de Datos Móviles: Entendemos que el procesamiento de IA puede consumir datos. Por eso, puede deshabilitar el uso de IA cuando esté en una red móvil desde el menú de Configuración. La app verificará esto antes de realizar cualquier llamada a la nube.

**3. Uso de la Información**

No recopilamos datos personales para venderlos, compartirlos con terceros ni para fines publicitarios.

Datos Locales: Se usan para que usted pueda ver sus métricas y para los análisis locales (hashtags, horarios).

Datos de Rendimiento (en la Nube): Se usan únicamente para entrenar y ejecutar los modelos de IA que le devuelven recomendaciones de contenido. Los datos se procesan y no se almacenan a largo plazo asociados a su identidad.

Caché Local de IA: Los resultados de los análisis de IA se guardan en su base de datos local para que la app cargue rápido y no tenga que solicitar el mismo análisis repetidamente.

**4. Seguridad**

Tomamos medidas razonables para proteger la integridad de su información. El almacenamiento de sus tokens de acceso en la base de datos local de su dispositivo es una práctica estándar de la industria.

**5. Cambios a esta Política**

Podemos actualizar esta Política de Privacidad periódicamente. Le notificaremos de cualquier cambio publicando la nueva política en esta página y actualizando la "Fecha de última actualización" en la parte superior.

**6. Contacto**

Si tiene alguna pregunta sobre esta Política, próximamente tendremos línea de comunicación vía soporte.
