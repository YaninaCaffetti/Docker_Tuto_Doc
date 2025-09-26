# Docker_Tuto_Doc
--
A containerized version of the cognitive-affective intelligent tutor for easy deployment. This system provides personalized and empathetic support for people with disabilities in Argentina.
--
Tuto_Doc: Versión Dockerizada para Despliegue Sencillo
Este repositorio contiene la versión lista para producción y despliegue del proyecto Tuto_Doc, un tutor inteligente cognitivo-afectivo desarrollado como parte de una tesis doctoral en Informática en la Universidad Nacional de Misiones, Argentina.

El objetivo de este repositorio es proporcionar una manera sencilla y reproducible de ejecutar la aplicación completa utilizando Docker, eliminando la necesidad de configurar manualmente el entorno y las dependencias.

🧠 Sobre el Proyecto
Tuto_Doc es un agente inteligente que funciona como un tutor cognitivo. Su principal innovación es la capacidad de adaptar sus respuestas basándose tanto en el perfil del usuario como en su estado afectivo, el cual es inferido en tiempo real a partir del texto de sus consultas.

Características Principales
* Arquitectura Cognitivo-Afectiva: Utiliza una arquitectura Mixture of Experts (MoE) donde un componente cognitivo es modulado por un componente afectivo para generar una interacción más empática y efectiva.

* Modelo Cognitivo Basado en Arquetipos: Clasifica a los usuarios en uno de los seis arquetipos de vulnerabilidad laboral, construidos a partir de los microdatos del Estudio Nacional sobre el Perfil de las Personas con Discapacidad (ENDIS) de Argentina.

* Modelo Afectivo con Transformers: Emplea un modelo de lenguaje (BETO) ajustado para detectar siete emociones clave en las consultas del usuario en español.

* Interfaz Interactiva: Proporciona una interfaz de usuario desarrollada con Streamlit para una interacción en tiempo real.

📦 Este Repositorio

Este repositorio contiene:

El código fuente completo de la aplicación.

* Un Dockerfile para construir una imagen de contenedor con todas las dependencias.

* Un archivo .dockerignore para optimizar la construcción de la imagen.

* Instrucciones claras para construir y ejecutar la aplicación.

🔬 Repositorio Principal de Investigación
El código original, los notebooks experimentales y los papers asociados a esta investigación se encuentran en el repositorio principal:
YaninaCaffetti/Tuto_Doc

Este proyecto es el resultado de la Tesis Doctoral "Proceso para la integración de un tutor cognitivo de consultas referidas a la legislación argentina sobre discapacidad. Estudio de caso: Agente inteligente de connotaciones emocionales definidas por el usuario" de la Mgter. Ing. Yanina A. Caffetti.
