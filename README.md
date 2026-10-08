DTech Launcher Ligero
Características
Comunidad: burbuja de chat flotante, chat general y chats privados entre usuarios. Acceso con la cuenta de Google, sin contraseñas.
Cifrado de extremo a extremo en los chats privados (ECDH P-256 + AES-256-GCM). Las claves privadas nunca salen del teléfono.
Escritorio: cuadrícula y páginas configurables, dock, carpetas, escritorio libre, widgets, packs de iconos y apps ocultas.
Gestos: deslizar, doble toque y gestos dibujados con un dedo.
Red: cortafuegos local por app (WiFi y datos), acceso a VPN e indicador flotante de velocidad.
Extras: puntos de notificación, bloqueo con doble toque y copia de seguridad de ajustes.
Descarga
Descarga el APK desde Releases e instálalo (tendrás que permitir instalar apps de orígenes desconocidos).
Requiere Android 7.0 (API 24) o superior.
Privacidad
Las funciones del launcher funcionan sin cuenta y sin enviar datos. Lee la política de privacidad.
Compilar tú mismo
El proyecto se abre con NanoIDE (.caproj) o se puede importar como módulo Android (Java 8, compileSdk 34).
La comunidad usa Supabase. Para tener tu propio servidor:
Crea un proyecto en Supabase y ejecuta supabase/schema_v2.sql y después supabase/schema_v3_e2e.sql.
Activa el proveedor Google en Authentication y añade com.example.launcher://auth en Redirect URLs.
Cambia URL_BASE y PUBLISHABLE_KEY en Supa.java por los de tu proyecto, y el correo del administrador en el SQL.
La clave publicable es pública por diseño. Nunca pongas la service_role ni el secreto de Google en la app.
Contacto
arielscisnero@gmail.com