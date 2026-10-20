# Política de Privacidad y Condiciones de Uso — FindMyPet 🐾

**Última actualización:** 19 de octubre de 2026

En **FindMyPet**, valoramos y respetamos la privacidad y la seguridad de nuestra comunidad. Este documento describe cómo recopilamos, utilizamos, almacenamos y protegemos la información cuando utilizás nuestra aplicación móvil **FindMyPet** (en adelante, la "Aplicación"), así como las normas sobre publicidad y prohibición de recompensas.

---

## 1. Público Objetivo (+16 años)
La Aplicación está destinada exclusivamente a personas de **16 años de edad o más**. No recopilamos intencionalmente información personal de niños ni de menores de 16 años, y la Aplicación no está diseñada para atraer involuntariamente a niños. Si sos padre, madre o tutor y tomás conocimiento de que un menor de 16 años nos ha proporcionado datos personales, escribinos a **soporte.findmypet@gmail.com** para proceder a su eliminación inmediata.

---

## 2. Información que Recopilamos y su Finalidad

Nuestra Aplicación ofrece un **Modo de Acceso Libre (Invitado)** que permite explorar mascotas reportadas sin necesidad de crear una cuenta. Solo recopilamos datos adicionales cuando el usuario decide voluntariamente registrarse, iniciar sesión con Google o correo electrónico, publicar un reporte de mascota perdida/encontrada, crear un pasaporte/chapita QR o utilizar el chat interno.

### 2.1. Información Personal y de Cuenta
* **Datos recopilados:** Nombre y apellido, dirección de correo electrónico, foto de perfil (opcional o provista mediante inicio de sesión con Google) y teléfono de contacto (opcional para chapitas QR o reportes). En caso de validación adicional de seguridad, documento de identidad (DNI) y selfie de verificación.
* **Finalidad:** Autenticación de usuarios (mediante Firebase Authentication y Google Sign-In), gestión de la cuenta, prevención de fraudes, seguridad de la comunidad y comunicación entre usuarios para el reencuentro de mascotas.

### 2.2. Datos de Ubicación (Precisa y Aproximada)
* **Datos recopilados:** Coordenadas GPS de ubicación precisa y aproximada del dispositivo.
* **Finalidad:** Mostrar en el mapa interactivo y en el listado los casos de mascotas perdidas y encontradas cercanas al usuario, y asociar la zona o barrio aproximado (con ofuscación de seguridad de 1 a 2 cuadras para proteger la privacidad del domicilio) al publicar un reporte.

### 2.3. Fotos, Cámara e Imágenes
* **Datos recopilados:** Fotografías de las mascotas tomadas con la cámara o seleccionadas de la galería del dispositivo, y lectura de códigos QR mediante la cámara.
* **Finalidad:** Publicar avisos de mascotas perdidas o encontradas, realizar búsqueda y coincidencia visual asistida por Inteligencia Artificial (Google Gemini AI), generar afiches imprimibles en formato PDF y chapitas QR identificatorias.

### 2.4. Mensajes y Notificaciones Push
* **Datos recopilados:** Mensajes enviados a través del canal de chat interno de la Aplicación y tokens de notificaciones push del dispositivo (Expo / Firebase Cloud Messaging).
* **Finalidad:** Permitir la comunicación en tiempo real entre el reportante y el dueño de la mascota, y enviar alertas sobre mensajes recibidos o novedades de reportes.

---

## 3. Política de No Recompensas y Prevención de Fraudes

Con el objetivo de proteger a las familias y evitar estafas, extorsiones o retenciones indebidas de mascotas:
* **FindMyPet no ofrece, gestiona ni intermedia recompensas económicas** de ningún tipo.
* **No está permitido ofrecer ni exigir dinero o recompensas públicas** dentro de las descripciones de los reportes, afiches PDF ni chats de la Aplicación como condición para brindar información o restituir una mascota.
* La Aplicación cuenta con filtros automáticos de seguridad que bloquean la publicación de montos de dinero o menciones a recompensas públicas, fomentando una red 100% solidaria y gratuita entre vecinos.
* Solo se permite reportar animales vivos; cualquier contenido sensible, falso o extorsivo será eliminado y la cuenta responsable será bloqueada.

---

## 4. Publicidad y Uso de Google Ads (Google AdMob)

Para sostener el funcionamiento gratuito de la plataforma, nuestra Aplicación muestra anuncios publicitarios de terceros a través de **Google Ads / Google AdMob** (`react-native-google-mobile-ads`).
* **ID de publicidad y datos del dispositivo:** El SDK de Google Mobile Ads puede recopilar y compartir automáticamente identificadores de dispositivo (como el **ID de publicidad de Android / Advertising ID**), dirección IP aproximada, datos de diagnóstico e interacciones con los anuncios.
* **Finalidad:** Mostrar anuncios publicitarios (por ejemplo, banners o anuncios al generar chapitas QR y exportar afiches en PDF), medir el rendimiento de las campañas publicitarias, realizar análisis estadísticos y prevenir el fraude publicitario.
* Podés restablecer o limitar el uso del ID de publicidad en cualquier momento desde los ajustes de tu teléfono Android (*Configuración > Google > Anuncios*).
* Para más información sobre cómo Google procesa los datos en servicios publicitarios, consultá: [Cómo utiliza Google la información de sitios o aplicaciones que usan nuestros servicios](https://policies.google.com/technologies/partner-sites).

---

## 5. Seguridad y Almacenamiento de los Datos

* **Cifrado en tránsito:** Todos los datos transmitidos entre la Aplicación y nuestros servidores en la nube (**Google Firebase Authentication, Cloud Firestore y Firebase Storage**) viajan cifrados mediante protocolos seguros (**HTTPS / TLS**).
* **No comercialización de datos personales:** Bajo ninguna circunstancia vendemos ni alquilamos tus datos personales (nombre, correo, teléfono o DNI) a terceros.

---

## 6. Eliminación de Cuenta y de Datos Personales

Cumpliendo con las políticas de Google Play y normativas de protección de datos, podés eliminar tu cuenta y todos tus datos asociados en cualquier momento:

1. **Desde la propia Aplicación (Eliminación inmediata):** Ingresando a la pestaña **Mi Cuenta (Perfil) > Eliminar cuenta definitivamente**, lo que borra de forma automática e irreversible tus credenciales en Firebase Auth, tu perfil, tus chats y tus reportes en Firestore.
2. **Por correo electrónico (Sin abrir la Aplicación):** Enviando un correo a **soporte.findmypet@gmail.com** con el asunto *"Eliminar mi cuenta y datos"* indicando el correo electrónico con el que te registraste. Procesaremos la baja definitiva en un plazo máximo de 7 días hábiles.

---

## 7. Cambios en esta Política de Privacidad

Podemos actualizar esta Política de Privacidad ocasionalmente para reflejar mejoras en la Aplicación o cambios normativos. Publicaremos cualquier actualización en este mismo enlace indicando la fecha de vigencia.

---

## 8. Contacto

Si tenés consultas o solicitudes relacionadas con esta Política de Privacidad o el tratamiento de tus datos en **FindMyPet**, escribinos a:
* **Correo electrónico de soporte:** [soporte.findmypet@gmail.com](mailto:soporte.findmypet@gmail.com)
* **Repositorio oficial:** [https://github.com/dsacomani/pet-finder-app](https://github.com/dsacomani/pet-finder-app)
