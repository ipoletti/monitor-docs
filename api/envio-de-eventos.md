# Envío de Eventos

{% api-method method="post" host="https://monitor-api.fluenti.net" path="/api/event" %}
{% api-method-summary %}
Event
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to get free cakes.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-headers %}
{% api-method-parameter name="Authorization" type="string" required=true %}
Token obtenido en la etapa de autenticación con el formato: "Bearer &lt;token&gt;".
{% endapi-method-parameter %}
{% endapi-method-headers %}

{% api-method-body-parameters %}
{% api-method-parameter name="event" type="string" required=true %}
Evento completo como un texto, si se envía un JSON se debe incluir como un string realizando el escapeado de caracteres reservados, como ser comillas, etc.
{% endapi-method-parameter %}

{% api-method-parameter name="eventDefinitionId" type="integer" required=true %}
Id que define la configuración del evento que se está enviando.
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Cake successfully retrieved.
{% endapi-method-response-example-description %}

```
{    "name": "Cake's name",    "recipe": "Cake's recipe name",    "cake": "Binary cake"}
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=404 %}
{% api-method-response-example-description %}
Could not find a cake matching this query.
{% endapi-method-response-example-description %}

```
{    "message": "Ain't no cake like that."}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



