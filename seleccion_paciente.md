# CASO DE USO: selección de pacientes
## ACTORES: Usuario
## PRECONDICIONES: el usuario debe estar logueado en el sistema y dentro del módulo gestión de pacientes.
## REQUERIMIENTOS:
### NORMAL
1. El usuario hace clic en "Consultar paciente"
2. El sistema muestra en pantalla un listado con los pacientes cargados y un filtro para buscar pacientes por su nombre o DNI.
3. El usuario tipea el nombre o el DNI del paciente.
4. El sistema va haciendo el filtro de manera automática, mientras el usuario va tipeando y muestra los resultados obtenidos.

### ALTERNATIVO
1.* Si el usuario hace clic en "Cancel", el sistema vuelve al punto 1.
3.1. Si el usuario no completa correctamente sus datos, el sistema vuelve al punto 2.
4.1. El sistema va haciendo el filtro de manera automática, mientras el usuario va tipeando y muestra un mensaje al usuario de que no encontró coincidencias con el filtro ingresado.

## POSTCONDICIONES: El usuario accede a la información correspondiente de la opción seleccionada.
