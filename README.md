# Building-IA
<!-- Esta es la plantilla de rebajas para el proyecto final del curso Building AI, 
Creado por Reaktor Innovations y la Universidad de Helsinki. -->

# Proyecto Anahi

Proyecto final del curso **Building AI**

## Resumen

Este proyecto aplica inteligencia artificial para detectar eventos críticos mediante sensores, con el fin de mejorar la seguridad en el hogar y en comunidades vulnerables. Utiliza modelos simples y eficientes para procesar datos en tiempo real y generar alertas automáticas.

## Fondo

El proyecto surge ante la necesidad de contar con herramientas accesibles que permitan la detección oportuna de incendios y el monitoreo de la calidad del agua. Estos problemas afectan tanto a zonas urbanas como rurales, especialmente en contextos donde no existen sistemas avanzados de prevención.

Este desarrollo busca:
* Reducir los riesgos por incendios domésticos mediante sensores de humo inteligentes
* Alertar sobre cambios anómalos en la calidad del agua en tiempo real
* Democratizar el acceso a soluciones tecnológicas de bajo costo y fácil implementación

La motivación principal es contribuir con una solución que tenga impacto social directo, utilizando inteligencia artificial de manera responsable y útil.

## ¿Cómo se utiliza?

La solución funciona mediante sensores conectados a una unidad central que recopila datos constantemente. Estos datos se procesan utilizando modelos de IA que identifican patrones de riesgo. En caso de detección, se emite una alerta local y/o remota para que el usuario pueda actuar a tiempo.

El sistema está pensado para hogares, centros comunitarios y pequeños establecimientos. Los usuarios no requieren conocimientos técnicos, ya que la interfaz es automática y las alertas son claras.


## Fuentes de datos y métodos de IA

Los datos provienen de sensores de bajo costo que recolectan información sobre humo, temperatura, turbidez del agua, pH, entre otros parámetros ambientales. El modelo de IA utiliza algoritmos de clasificación supervisada para identificar situaciones anómalas.

Fuentes utilizadas:
* Datos recolectados en pruebas de campo
* Dataset de referencia sobre calidad del agua de organismos públicos
* Umbrales definidos por normativas sanitarias

| Tipo de dato     | Descripción                        |
| ---------------- | ---------------------------------- |
| Sensor de humo   | Detecta partículas en el aire      |
| Sensor de agua   | Mide turbidez, pH y conductividad  |
| Salida del sistema | Alerta visual, sonora o remota     |

## Desafíos

* La calibración precisa de los sensores puede ser compleja en entornos variables.
* Los modelos deben ser lo suficientemente livianos para funcionar en hardware de bajo consumo.
* Se deben tener en cuenta consideraciones éticas como el uso responsable de los datos y la transparencia del sistema.

No todos los tipos de contaminación o riesgo son detectables con sensores simples, por lo que hay que mantener expectativas realistas sobre el alcance del sistema.

## ¿Qué sigue?

El proyecto puede escalar hacia:
* Una versión comercial para viviendas de interés social
* Integración con aplicaciones móviles y sistemas de notificación por internet
* Colaboración con autoridades locales para implementaciones comunitarias

Para continuar se requerirá:
* Apoyo en manufactura de hardware
* Desarrollo de interfaces accesibles
* Validación en entornos reales con usuarios finales

