# Guía del usuario de GitHub para MCT

Los servicios en la nube, como Microsoft Azure, se actualizan con frecuencia, lo que lleva a desafíos para los Microsoft Certified Trainer (MCT) a medida que enseñan cursos y los pasos de los laboratorios ya no coinciden con nuestros servicios en la nube. . Debido a la frecuencia de los cambios y al hecho de que podría no haber ninguna notificación cuando se produzcan cambios, es difícil que el equipo de desarrollo del curso identifique y ajuste rápidamente los cambios del laboratorio.

Para solucionar estos problemas, se usa GitHub para publicar los pasos y scripts de laboratorio para cursos que cubran servicios en la nube, como Azure. El uso de GitHub permite a los autores y MCT del curso mantener el contenido del laboratorio actualizado con los cambios del servicio en la nube. El uso de GitHub permite a los MCT proporcionar comentarios y sugerencias sobre cambios en el laboratorio y, a continuación, los autores del curso podrán actualizar rápidamente los pasos de laboratorio y los scripts.

Al prepararse para enseñar estos cursos, asegúrese de usar los pasos y scripts de laboratorio más recientes descargando los archivos adecuados de GitHub.

Esta guía de usuario es para los MCT que no están familiarizados con GitHub. Proporciona pasos para conectarse a GitHub, descargar e imprimir materiales del curso, actualizar los scripts que usan los alumnos en laboratorios y explicar cómo ayudar a garantizar que el contenido de un curso permanezca actualizado.

> **Nota**: El soporte técnico de Microsoft Learning para acceder a los archivos en GitHub y el soporte para la navegación del sitio de GitHub se limita solo a los MCT que imparten este curso.

GitHub no se debería usar para analizar el contenido técnico de cursos o cómo prepararse para cursos o sus laboratorios. Es específicamente para abordar cambios en los laboratorios.

 
> **Nota**: Para abordar comentarios generales sobre cursos y demostraciones, o cómo prepararse para cursos, use los foros de MCT.

## Secciones

- [Terminología de GitHub](https://microsoftlearning.github.io/MCT-User-Guide/terminology/)

- [Recibir notificaciones de actualización y colaborar en proyectos](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/)

- Sugerir cambios o enviar un problema sobre instrucciones de laboratorios

## Terminología de GitHub

GitHub presenta terminología que podría ser nueva para usted. En la lista siguiente, se incluyen términos y conceptos usados en este documento. Sin embargo, para obtener una lista completa de los términos de GitHub, consulte el [Glosario de GitHub](https://docs.github.com/en/get-started/quickstart/github-glossary).

| Término| Explicación |
| - | - |
| Git y GitHub| Git es un programa de seguimiento de cambios de código abierto y GitHub es un sitio o solución creado en Git. Hay otros sitios web y soluciones que usan Git como back-end. Usaría GitHub principalmente para proyectos de desarrollo de código abierto (públicos) y es gratuito para esos proyectos. Sin embargo, si desea usar GitHub para proyectos privados que no sean de código abierto, deberá registrarse para obtener una versión de pago. |
| Repo o repositorio| Cada proyecto de GitHub se encuentra en un repositorio o repo. Un repositorio contiene todos los archivos de un proyecto, incluyendo la documentación, y admite el historial de revisiones. Un repositorio puede ser público o privado. Se puede tener una copia local del repositorio en el disco duro del equipo o usar el repositorio en GitHub. |
| Markdown| Se trata de un formato de archivo de texto que se puede usar para crear documentación. Se basa en texto y es muy sencillo de actualizar, lo que facilita el uso durante la colaboración. A continuación, GitHub lo representa como HTML. |
| GitHub Flavored Markdown (GFM)| Hay muchas variaciones o tipos del formato de archivo Markdown. La versión de GitHub, comúnmente conocida como GFM, es una de las variaciones más comunes de Markdown. Para obtener más información sobre GFM y cómo usar el formato de marcado para los documentos GFM, consulte "Introducción a la escritura y al formato en GitHub" en https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github/. |
| Bifurcar| Se trata de una copia de otro repositorio que reside en la cuenta de GitHub, en comparación con una rama, que reside en el repositorio original. Consulte "Rama" directamente más abajo. |
| Rama| Se trata de una copia de un repositorio que reside en el mismo repositorio que el original. Es posible combinar una rama con el original. |
| Capturar| Este es el proceso de recuperar una copia de los cambios más recientes de un repositorio en línea. Sin embargo, una recuperación no combina los cambios. |
| Extraer (pull)| Este es el proceso de capturar los cambios más recientes de un repositorio en línea y combinarlos con cambios locales. |
| Merge| Este es el proceso de capturar cambios de una rama y aplicarlos a otra. Esto incluye recuperar los cambios de un repositorio en línea y, a continuación, aplicarlos a la versión local de ese repositorio. |
| Solicitud de incorporación de cambios| Se trata de un conjunto de cambios propuestos a un repositorio que un usuario envía y, a continuación, los propietarios o colaboradores de un repositorio pueden aceptar o rechazar la solicitud de extracción. |
| Push| Este es el proceso de enviar los cambios locales al repositorio en línea. |
| Colaborador| Se trata de un usuario de GitHub que tiene permisos para agregar, eliminar o cambiar el contenido de un repositorio. |

## Recibir notificaciones de actualización, sugerir cambios y colaborar en proyectos

Configure la experiencia de GitHub para recibir notificaciones cuando se produzcan actualizaciones en un repositorio de GitHub. Hay varias maneras en las que es posible registrarse para recibir notificaciones y muchas de ellas se relacionan con las muchas maneras de colaborar en un proyecto. Para recibir notificaciones, realice las siguientes acciones.

| Acción| Descripción |
| - | - |
| [Inspección de repositorios](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/watching/)| Al ver un repositorio, GitHub le suscribe automáticamente a las notificaciones de las nuevas solicitudes de incorporación de cambios o problemas creados para ese repositorio específico. Verá automáticamente cualquier repositorio que cree o del que sea colaborador. |
| [Solicitud de incorporación de cambios](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/pullrequest/)| Al crear solicitudes de incorporación de cambios y proponer a los propietarios de un repositorio que acepten un cambio que realizó, se suscribirá de forma automática para recibir notificaciones de los debates relacionados con la solicitud de extracción. Para crear una solicitud de incorporación de cambios, primero se debe crear una rama. |
| [Comentarios](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/comment/)| Al hacer comentarios sobre la solicitud de incorporación de cambios de otra persona, GitHub le suscribirá automáticamente al foro al que pertenezca a ese comentario, o bien suscríbase manualmente al foro. |
| [Problemas](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/issue/)| Un problema es una sugerencia, pregunta o solicitud que pertenezca a un repositorio. Cada problema tiene su propia discusión y puede suscribirse a problemas, o bien GitHub le suscribirá automáticamente a los problemas que cree. |
| [Menciones](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/mention/)| Cuando otro usuario le mencione en una conversación con el nombre de usuario de GitHub ([@username](https://github.com/username)), GitHub le suscribirá automáticamente a la discusión. |

> **Nota**: Modifique cómo y cuándo recibir notificaciones y cancele la suscripción a cualquiera o a todas las discusiones.

## Envíe incidencias o sugiera cambios sobre instrucciones de laboratorios

Si tiene sugerencias o encuentra errores en laboratorios, envíe una solicitud de incorporación de cambios y registre una incidencia. Si ya conoce la corrección del error, se recomienda enviar una solicitud de incorporación de cambios, de lo contrario, envíe una incidencia.

| Acción| Descripción |
| - | - |
| [Solicitud de incorporación de cambios](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/pullrequest/)| Al crear solicitudes de incorporación de cambios y proponer a los propietarios de un repositorio que acepten un cambio realizado, se suscribirá de forma automática para recibir notificaciones sobre los debates relacionados con la solicitud de extracción. Para crear una solicitud de incorporación de cambios, primero se debe crear una rama. |
| [Comentarios](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/comment/)| Al hacer comentarios sobre la solicitud de incorporación de cambios de otra persona, GitHub le suscribirá automáticamente al foro al que pertenezca a ese comentario, o bien suscríbase manualmente al foro. |
| [Problemas](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/issue/)| Un problema es una sugerencia, pregunta o solicitud que pertenezca a un repositorio. Cada incidencia tiene su propia discusión. Suscríbase a incidencias o GitHub le suscribirá automáticamente a los problemas que cree. |
