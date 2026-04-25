# Política de Privacidad — Feria de Albacete (fan app)

_Última actualización: 20 de abril de 2026_

Esta aplicación (en adelante, "la App") es un proyecto personal no oficial
creado por David Marco Moreno como homenaje a la Feria de Albacete. Esta
política explica de forma clara qué datos maneja la App y cómo lo hace.

## Resumen en una frase

**La App no recoge, no envía ni almacena en servidores externos ningún dato
personal.** Todo lo que tecleas, marcas o consultas vive únicamente en tu
dispositivo.

## Datos que la App NO recoge

- Nombre, email, teléfono, ubicación, identificadores únicos de dispositivo.
- Contactos, fotos, archivos, calendario.
- Cookies de seguimiento ni analítica de terceros (Google Analytics,
  Firebase, Meta, Mixpanel, etc.). No hay analítica en absoluto.
- Historial de navegación, comportamiento dentro de la App, tiempo de uso.

## Datos que la App SÍ almacena en tu dispositivo

Todos estos datos se guardan localmente usando AsyncStorage (almacenamiento
del sistema operativo, aislado por app). No salen del dispositivo salvo que
tú decidas compartirlos mediante el menú de compartir del sistema.

- **Eventos favoritos**: los eventos del programa que marcas con el
  corazón.
- **Identificadores internos de notificaciones**: IDs técnicos que permiten
  a la App cancelar el recordatorio 1h-antes cuando quitas un favorito.
- **Caché de noticias**: una copia local de las 4 últimas noticias
  descargadas de feria.albacete.es, para mostrarlas sin conexión.
- **Fecha de la última consulta de noticias**: timestamp que permite
  respetar el tope de 1 consulta diaria.
- **Preferencia de bienvenida**: una marca que recuerda si ya has visto el
  aviso inicial de "versión demo".

## Notificaciones

La App puede enviarte **notificaciones locales** 1 hora antes de cada evento
que marques como favorito. Estas notificaciones las programa tu propio
sistema operativo (iOS/Android) y **no requieren conexión a internet ni
servidor propio**. No usamos servicios de notificaciones push (APNs, FCM)
y nunca enviamos tokens a ningún servidor.

Puedes revocar el permiso de notificaciones en cualquier momento desde los
ajustes de tu dispositivo.

## Conexiones externas

La única conexión externa que realiza la App es una descarga del HTML
público de `feria.albacete.es/es/noticias`, como máximo **una vez al día**
y solo cuando:

- Abres la App después de más de 24 h desde la última consulta, o
- Deslizas hacia abajo en la pantalla de noticias para forzar una
  actualización (pull-to-refresh).

Esa conexión se realiza directamente desde tu dispositivo al sitio web del
Excmo. Ayuntamiento de Albacete. Tu dirección IP queda registrada en los
servidores de dicho sitio bajo su propia política, no la nuestra. La App no
ve, guarda ni transmite tu IP.

## Compartir

La App ofrece la opción de compartir un evento o tu "Plan de hoy" a través
del menú de compartir del sistema operativo (WhatsApp, Mail, Mensajes,
etc.). El contenido compartido es texto plano que tú eliges enviar. La App
no interviene en a quién ni cómo se lo mandas: lo hace el sistema.

## Enlaces a sitios de terceros

La App incluye enlaces directos a:

- `feria.albacete.es` (web oficial del Ayuntamiento).
- Perfil de LinkedIn del autor.
- Teléfonos útiles (112, 080, 092, 091, 967 50 43 36) a través del marcador
  del sistema.

Al tocar cualquiera de esos enlaces sales de la App. Lo que ocurra a partir
de ahí se rige por la política de privacidad del destino, no por ésta.

## Menores

La App no recoge datos, así que no recoge datos de menores. Es apta para
todos los públicos.

## Derechos del usuario

Como no almacenamos tus datos en ningún servidor, no hay datos personales
tuyos sobre los que ejercer derechos de acceso, rectificación o supresión
en sede del autor.

**Para borrar todos los datos locales**, basta con desinstalar la App.

## Cambios en esta política

Si esta política cambia de manera sustancial, la versión nueva se publicará
en esta misma URL y se actualizará la fecha de "Última actualización".

## Contacto

Para cualquier duda, reclamación o sugerencia sobre privacidad:

- Autor: David Marco Moreno
- LinkedIn: <https://www.linkedin.com/in/davidmarcomoreno/>
- Repositorio del proyecto: <https://github.com/jithub2024/ab2026>

---

_Aplicación no oficial. No está asociada, patrocinada ni avalada por el
Excmo. Ayuntamiento de Albacete. Los datos del programa proceden del
programa oficial publicado por el Ayuntamiento en feria.albacete.es._
