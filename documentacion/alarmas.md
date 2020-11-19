# Alarmas

En esta sección se definen las alarmas que serán procesados por la plataforma.​

Las alarmas permiten trabajar sobre las métricas definidas anteriormente, estableciendo umbrales para los cuales la alarma será activada y disparada la notificación correspondiente.

![](../.gitbook/assets/image%20%288%29.png)

Se accede por el menú superior. Se listan las alarmas ya existentes.‌

### Crear o editar una Alarma <a id="crear-o-editar-una-definicion-de-evento"></a>

‌Los campos a completar son los siguientes

| Campo | Descripción |
| :--- | :--- |
| Nombre | Es el nombre que se le asigna a la definición para futura referencia |
| Métrica | Una alarma aplica sobre una métrica específica |
| Función | Se establece cual será la función a utilizar sobre el valor de "Columna Numérica" definida en la métrica, en caso de no haberse definido solo se podrá utilizar la función de contar elementos \(COUNT\) |
| Valor Umbral | Se define el valor máximo numérico a partir del cual se activará la alarma aplicado sobre el resultado de la función definida en el campo anterior |
| Rango de Tiempo | Es el tiempo que se define durante el cual se aplica la función anteriormente definida |
| Notificador | Es el notificador que será disparador en caso de activarse la Alarma |

