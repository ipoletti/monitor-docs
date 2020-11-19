# Notificadores

En esta sección se definen los notificadores que serán procesados por la plataforma.​

Los notificadores definidos podrán ser asignados a las Alarmas para enviar alertas ante la activación de las mismas.

![](../.gitbook/assets/image%20%285%29.png)

Se accede por el menú superior. Se listan las alarmas ya existentes.‌

### Crear o editar un Notificador <a id="crear-o-editar-una-definicion-de-evento"></a>

‌Los campos a completar son los siguientes

| Campo | Descripción |
| :--- | :--- |
| Tipo de Notificador | Es el tipo de Notificador, actualmente se soporta el envió de Mail e invocación de API |
| Nombre | Es el nombre que se le asigna al notifcador para futura referencia |

#### Para Notificar tipo Mail

| Campo | Descripción |
| :--- | :--- |
| Correo Electrónico | Correo electrónico del destinatario |
| Asunto | Es el asunto que se enviará en el correo |

#### Para Notificar tipo API

| Campo | Descripción |
| :--- | :--- |
| Endpoint \(URL\) | Es la URL del servicio tipo REST que recibirá la invocación |

