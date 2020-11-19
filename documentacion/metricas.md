# Métricas

En esta sección se definen las métricas que serán procesados por la plataforma.​

Las métricas son aquellos datos expresados numéricamente que nos sirven para **analizar un evento** de una determinada configuración. Digamos que, gracias a las métricas, **podemos saber si se cumplen determinados criterios.**

‌

![](../.gitbook/assets/image%20%287%29.png)

Se accede por el menú superior. Se listan las métricas ya existentes.‌

### Crear o editar una Métrica <a id="crear-o-editar-una-definicion-de-evento"></a>

‌Los campos a completar son los siguientes

| Campo | Descripción |
| :--- | :--- |
| Nombre | Es el nombre que se le asigna a la definición para futura referencia |
| Definición de Evento | Una métrica aplica sobre una configuración específica de evento |
| Columna de Evento | Se establece a que columna del evento se aplicaran los filtros |
| Comparador | Se define cual será el comparador aplicado entre la columna y valor a comparar |
| Valor | Es el valor que será comparador con los criterios anteriores, por el cual se determinará cuando la métrica aplica al evento recibido. |
| Columna de Agrupamiento | Es la columna que se desea utilizar para agrupar valores, la misma será utilizada en la Alarma. Por ejemplo: Si queremos definir una alarma cuando se realicen N intentos de ingreso incorrectos por usuario, la columna de agrupamiento será el nombre de usuario. |
| Columna Numérica | Es un valor opcional que permite realizar funciones matematicas sobre ella, si no se define en la alarma solo se tendrá la opción de contar ocurrencias \(COUNT\) |
|  |  |

