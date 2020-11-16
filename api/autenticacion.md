# Autenticación

{% api-method method="get" host="https://monitor-api.fluenti.net" path="/api/authenticate" %}
{% api-method-summary %}
Authenticate
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to get free cakes.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-form-data-parameters %}
{% api-method-parameter name="password" type="string" required=true %}
API Secret asignado por la plataforma para acceso mediante API
{% endapi-method-parameter %}

{% api-method-parameter name="username" type="string" required=true %}
Nombre de usuario, usualmente el mail registrado en la cuenta
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Login correcto
{% endapi-method-response-example-description %}

```
{
    "token": "eyJ0eXAi....."
}
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=404 %}
{% api-method-response-example-description %}
Login incorrecto
{% endapi-method-response-example-description %}

```
{
    "timestamp": "2020-11-16T02:22:20.656+0000",
    "status": 401,
    "error": "Unauthorized",
    "message": "Unauthorized",
    "path": "/api/authenticate"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



