Aquí está el caso de uso en formato Markdown:

# CASO DE USO: Eliminar pacientes
## ACTORES: Usuario
## PRECONDICIONES: un paciente fue consultado.
## REQUERIMIENTOS:
### NORMAL
1. El sistema muestra en pantalla nombre, apellido, DNI, teléfono del paciente consultado.
2. El usuario selecciona el paciente y hace clic en eliminar.
3. El sistema muestra una advertencia de si está seguro de eliminar.
4. Si el usuario hace clic en Sí, los datos son eliminados.

### ALTERNATIVO
3.1. Si el usuario hace clic en no, vuelve al punto 1.

## POSTCONDICIONES: un paciente fue eliminado.
