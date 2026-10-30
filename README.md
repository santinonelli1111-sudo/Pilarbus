# Pilarbus: ecosistema móvil de transporte publico 
Proyecto Pilarbus: Planificación con Scrum, gestión de tareas y control de versiones para una aplicación de transporte publico de Pilar

## Integrantes 
- Juan Vizgarra
- Lautaro Olmedo
- Vanesa Pavia
- 

## Descripción del proyecto 
Pilarbus es una propuesta de aplicación móvil y plataforma web para consultar recorridos y la ubicación de los colectivos en tiempo real. tambien contempla funcionalidades como alertas de desvíos y envio de reclamos.

## Justificación metodológica 
El proyecto "Pilarbus" presenta características que hacen que un enfoque tradicional, no sea el más adecuado, ya que existe alta incertidumbre sobre los requisitos: las funcionalidades se irán definiendo y modificando según la retroalimentación de los usuarios beta. En este contexto, Scrum resulta la metodología ideal, porque trabaja en ciclos cortos e iterativos llamados Sprints, lo que permite incorporar cambios en cualquier momento sin alterar todo el proyecto.
A diferencia de los modelos tradicionales, donde se intenta definir todo desde el inicio y los cambios tienen costos adicionales, el flujo de trabajo continuo que propone Scrum permite entregar valor de forma progresiva, recibir comentarios y mejorar el producto paso a paso. Este se ajusta perfectamente a las necesidades del proyecto, ya que además requiere actualizaciones constantes sin interrumpir el servicio.

## Trabajo en ramas y pull requests
La rama principal del repositorio denominada **`Main`**, contendría los cambio revisados y validados del proyecto.
Para poder desarrollar una funcionalidad o corregir un error, el encargado de la tarea creara una rama independiente para trabajar en ella. por ejemplo: se crea la rama `feature/alertas-desvíos` y en esta se desarrollaran las notificaciones sobre cambios de recorrido para luego agregarlas a la rama principal.
Estos avances se registraran mediante commits (registros de los cambios del proyecto) con mensajes claros que describan las modificaciones realizadas.
Una vez preparado el cambio, el integrante abrirá un **Pull requests** para solicitar la incorporación al **`Main`**. este PR incluirá: 
- Una descripción del cambio y su objetivo.
- La tarjeta de trello relacionada.
- Las pruebas realizadas.
Con este mecanismo se puede hacer una revisión del trabajo antes de incorporarlo de la versión principal y mantener un registro de las deciciones que toma el equipo.

## revisión y aprobación de cambios  
Cada pull requests debe ser revisado por al menos un integrante del grupo, diferente a quien hizo el cambio. Esta persona tiene que comprobar que el cambio responda a la tarea planteada y cuente con las pruebas necesarias, en caso de encontrar errores se deben solicitar correcciones y dejar comentarios.
la incorporación a `Main` denominada **Marge** (la incorporacion de una rama a la rama principal) se permite cuando: 
- El cambio cumpla con los criterios que pide la tarea
- Las observaciones de la revisión estén resueltas
- Exista una aprobacion de otro integrante
- Los controles automaticos de build y test finalicen correctamente
