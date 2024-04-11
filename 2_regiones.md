#   Una visión global: regiones y zonas de disponibilidad

a infraestructura de AWS está compuesta por regiones, zonas de disponibilidad, data centers y puntos de presencia. Además, se distribuye en diferentes regiones alrededor del mundo. Algunas de ellas son Ohio, Oregon, Norte de California, e incluso lugares exclusivos del gobierno de EE. UU. como GovCloud Este.

Si quieres conocer una lista completa con más sitios, puedes visitar esta página de AWS.

## Cómo escoger una región de AWS
Podemos escoger la región de nuestra aplicación basada en distintos aspectos que mencionaremos a continuación.

### Por ejemplo:

El cumplimiento de los requisitos legales y de gobernanza de datos, pues los datos nunca abandonan una región sin su permiso explícito

La proximidad con los clientes porque lanzan en una región cercana en donde estén para reducir latencia. Puedes revisar esta característica desde tu ubicación a cada región en cloudping.info.

Los servicios disponibles dentro de una región debido a que muchos no funcionan en todas partes. Algunos servicios globales o regionales son…

#### Globales
*   IAM
*   Route 53
*   Cloudfront
*   WAF

#### Regionales

*   EC2
*   Beanstalk
*   Lambda
*   Rekognition

**Los precios varían de región a región y son transparentes en la página de precios del servicio**

Zonas de disponibilidad
Una zona de disponibilidad es un grupo de data centers donde cada uno está lleno de servidores. Estos data centers poseen energía, redes y conectividad redundante, están separados entre sí, conectados con un gran ancho de banda y redes de latencia ultra baja.

Modelo de responsabilidad compartida
Ahora es crucial determinar las responsabilidades de AWS y del cliente dentro del servicio tecnológico que ofrece la compañía.

AWS se hace responsable de:

Hardware y la infraestructura global
Regiones
Zonas de disponibilidad
Ubicaciones de AWS Edge / puntos de presencia
Software
Cómputo
Almacenamiento
Bases de datos
Redes
El cliente se responsabiliza de:

Actualizaciones de S.O.
Protección de los datos que se almacenan
Manejo de aplicaciones
Accesos
Administración de usuarios y grupos
Contribución creada con los aportes de: Jesús Ignacio García Fernández y Ciro Villafraz.