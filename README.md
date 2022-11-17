
# Description

Este repositorio contiene un ejemplo de instrumentacion Flask de OpenTelemetry, incluye injeccion de Trace ID en logs formato JSON.

Using docker:
```
make build
make run

# Enviar solicitudes HTTP a  localhost:8000/rolldice
# Exameniar los logs donde podremos ver el trace ID.
```


