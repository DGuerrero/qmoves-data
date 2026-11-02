# Política de privacidad de Rutalo

[Read in English](PRIVACY.md)

*Última actualización: 25 de octubre de 2026*

Rutalo es una app de transporte público para Bilbao y Bizkaia. Está diseñada para recopilar lo mínimo
posible: sin cuentas, sin publicidad y sin nada que te identifique.

## Qué recopilamos

Solo dos cosas, ambas a través de Google Firebase, y ambas bajo tu control en **Ajustes → Privacidad**:

**Informes de errores (Firebase Crashlytics).** Si la app falla, envía un informe para que podamos corregir el
problema: qué falló en el código, la versión de la app, el modelo del teléfono y la versión de Android, la memoria
y el almacenamiento libres en ese momento, y un identificador de instalación aleatorio creado por Crashlytics. Los
informes de errores están activados por defecto; puedes desactivarlos en cualquier momento. Se conservan 90 días.

**Estadísticas de uso (Google Analytics for Firebase), solo si aceptas.** La primera vez que usas Rutalo te
preguntamos si quieres compartir estadísticas de uso anónimas. Si dices que sí, la app envía qué pantallas abres y
qué funciones usas (por ejemplo, «planificó un viaje desde un acceso directo» o «abrió el horario de una línea»),
junto con la versión de la app, el modelo del teléfono, la versión de Android, el idioma, la ubicación aproximada
(ciudad o región), que Google deduce de la dirección IP sin conservar la dirección, y un identificador aleatorio de
la instancia de la app. Si dices que no, no se envía nada. Puedes cambiar tu respuesta en cualquier momento en
Ajustes; al desactivar las estadísticas también se borra lo recogido en el teléfono y se restablece el
identificador. Las estadísticas se conservan 2 meses.

Nunca enviamos tu ubicación, los lugares o paradas que buscas, tus lugares de casa o trabajo, ni tus favoritos. No
se recopilan identificadores publicitarios y las funciones de publicidad están desactivadas. No vendemos datos ni
los compartimos con nadie más. Google trata estos datos por cuenta nuestra, tal como se describe en la
[información de privacidad de Firebase](https://firebase.google.com/support/privacy).

No usamos ningún servidor propio que reciba datos de la app.

## Tu ubicación

Si lo permites, Rutalo usa la ubicación de tu dispositivo para mostrar las paradas cercanas y planificar viajes
desde donde estás. La ubicación se usa solo en tu dispositivo. Nunca se nos envía ni a nosotros ni a nadie más, y
no se guarda después de cerrar la app. Puedes usar Rutalo sin acceso a la ubicación buscando lugares o eligiendo un
punto en el mapa.

En Android, la ubicación la proporcionan los servicios de Google Play. El tratamiento de esos datos por parte de
Google se rige por la [política de privacidad de Google](https://policies.google.com/privacy).

## Favoritos y lugares guardados

Las paradas que guardas como favoritas y los lugares que fijas como casa y trabajo se almacenan solo en tu
dispositivo. Al desinstalar la app o borrar sus datos, se eliminan.

## Solicitudes de red de la app

Para funcionar, Rutalo descarga datos públicos. Estas solicitudes no contienen datos personales, pero, como en
cualquier solicitud por internet, el servidor ve tu dirección IP y datos técnicos básicos:

| Qué | De dónde | Cuándo |
| :--- | :--- | :--- |
| Horarios, paradas y lugares | GitHub (github.com) | En el primer arranque y cuando hay una versión más reciente |
| Horas de salida en directo | Datos abiertos del Gobierno Vasco (opendata.euskadi.eus) y Renfe (gtfsrt.renfe.com) | Mientras consultas salidas o viajes |
| Teselas del mapa | OpenFreeMap (tiles.openfreemap.org) | Mientras el mapa está en pantalla |
| Informes de errores y, si aceptaste, estadísticas de uso | Google Firebase | Como se describe arriba |

Las teselas se solicitan para la zona que muestra el mapa, que puede ser la que te rodea. Ninguna solicitud envía
coordenadas de ubicación, y solo las de Firebase llevan un identificador.

## Menores

Rutalo es apto para todas las edades. No está dirigida a menores de 13 años y no recopila conscientemente sus datos
personales.

## Tus derechos

Puedes desactivar los informes de errores y las estadísticas de uso en cualquier momento en Ajustes. Para pedir que
se borren los datos ya enviados, o para cualquier otra solicitud conforme a la normativa de protección de datos
(como el RGPD), escribe a la dirección que aparece abajo.

## Cambios

Si esta política cambia, la nueva versión se publicará en esta dirección con una nueva fecha.

## Contacto

Preguntas sobre esta política: [david@quoders.com](mailto:david@quoders.com)
