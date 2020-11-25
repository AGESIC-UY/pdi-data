# pdi-data

## Introducción
La plataforma de interoperabilidad de AGESIC es una solución que brinda capacidades de integración y middleware entre proveedores y consumidores de servicios. Entre otras, provee la funcionalidad de ruteo de invocaciones a servicios, esto permite ocultar los endpoints a los consumidores y aplicar maniobras sobre los mismos de forma transparente para los consumidores. Todas las invocaciones a servicios a través de la plataforma serán redireccionadas por medio del servicio de ruteo.

## Descripción de la solución
Como se indica en la descripción del proyecto ![pdi-ruteo](https://github.com/AGESIC-UY/pdi-ruteo), está diseñado para guardar su información en un repositorio Git. Este repositorio sigue la estructura representada por este proyecto (pdi-data). Como se puede identificar, consta de dos archivos, _rutas_ y _usuarios_. El primero contiene las rutas que se registran en el sistema indicando si es degradable o no y en caso de serlo los valores asociados, mientras que el segundo tiene los usuarios registrados en el sistema junto con sus permisos.

## Ejecución
Para que este proyecto sea utilizado por el sistema de ruteo, se tiene que crear el repositorio con estos archivos en un Git el cual tenga conectividad con el sistema de ruteo. Para que el ruteo utilice ese repositorio, se deberán configurar los valores de conexión necesarios en el archivo de configuración correspondiente que se encuentra dentro del proyecto ![pdi-config](https://github.com/AGESIC-UY/pdi-config).

## Contacto
Por cualquier duda o consulta, puede comunicarse a arquitectura@agesic.gub.uy

---

## Introduction
AGESIC's interoperability platform is a solution that provides integration and middleware capabilities between service providers and consumers. It provides the functionality of routing of invocations to services, among others, allowing to hide endpoints from consumers and operate transparently with them. All invocations to services through the platform will be redirected through the routing service.

## Solution description
As stated in the ![pdi-ruteo](https://github.com/AGESIC-UY/pdi-ruteo) project description, it is designed to save the information in a Git repository. This repository follows the structure represented by this project (pdi-data). As can be identified, it consists of two files, _rutas_ and _usuarios_. The first contains the routes that are registered in the system indicating whether it is degradable or not and, if so, the associated values, while the second has the users registered in the system along with their permissions.

## Execution
In order to be used by the routing system, you must create a Git repository with these files, and obviously must have connectivity between the routing system and the repository. Finally, the repository connection values must be configured in the corresponding configuration file, found within the project ![pdi-config](https://github.com/AGESIC-UY/pdi-config).

## Contact
If you require any further information, please contact arquitectura@agesic.gub.uy


