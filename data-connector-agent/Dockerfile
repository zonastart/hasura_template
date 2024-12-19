# Imagen base del conector
FROM hasura/graphql-data-connector:v2.42.0

# Exponer el puerto del conector
EXPOSE 8081

# Variables de entorno (asegúrate de configurarlas en Railway)
ENV QUARKUS_LOG_LEVEL=ERROR
ENV QUARKUS_OPENTELEMETRY_ENABLED="false"

# Comando para ejecutar el servicio
CMD ["quarkus-run"]