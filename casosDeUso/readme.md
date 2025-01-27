[![Inicio](https://img.shields.io/badge/Inicio-blue?style=for-the-badge)](https://github.com/srgiom/24-25-IdSw1-SDR/tree/main)
[![Modelo de Dominio](https://img.shields.io/badge/Modelo%20de%20Dominio-blue?style=for-the-badge)](https://github.com/srgiom/24-25-IdSw1-SDR/tree/main/modeloDelDominio)
[![Prototipos](https://img.shields.io/badge/Prototipos-blue?style=for-the-badge)](https://github.com/srgiom/24-25-IdSw1-SDR/tree/main/prototipos)

## 🛠️ **Actores, Casos de Uso y Diagrama de Contexto**

### Actores
![Actores](https://github.com/srgiom/24-25-IdSw1-SDR/raw/main/casosDeUso/actores/actores.png)
> 🗂️ **Detalles:**
> Este diagrama muestra al actor principal del sistema: **el administrador**. Este rol incluye tareas clave como:
> - Gestionar aulas, asignaturas, profesores y estudiantes.
> - Control total sobre el sistema para garantizar su correcto funcionamiento.

---

### Casos de Uso
<table>
  <tr>
    <td align="center">
      <img src="https://github.com/ikercelaya/24-25-IdSw1-SDR/blob/main/casosDeUso/imagenes/CasosDeUso1.svg" width="600"/>
      <br/>
    </td>
    <td align="center">
      <img src="https://github.com/ikercelaya/24-25-IdSw1-SDR/blob/main/casosDeUso/imagenes/CasosDeUso2.svg" width="1000"/>
      <br/>
    </td>
  </tr>
</table>

> 🌐 **Casos de Uso:**
> Este diagrama presenta una vista general de todos los casos de uso que encontramos en nuestro Sistema.

---

## Diagramas de Contexto

#### Diagrama de Contexto Principal
![Diagrama de Contexto Principal](/casosDeUso/diagramaDeContexto/imagenes/DiagramaDeContextoPrincipal.svg)
> 🌐 **Contexto del Sistema:**
> Este diagrama presenta una vista general de las interacciones entre el sistema y los diferentes menús, resaltando el flujo principal y las transiciones al menú principal.

---

#### MENU_GRADO
![Diagrama MENU_GRADO](/casosDeUso/diagramaDeContexto/imagenes/DiagramaMenuGrado.svg)
> 📚 **Menú de Grado:**
> En este diagrama se detallan las funcionalidades relacionadas con la gestión de grados, incluyendo registrar, actualizar, consultar y eliminar grados.

---

#### MENU_AULA
![Diagrama MENU_AULA](/casosDeUso/diagramaDeContexto/imagenes/DiagramaMenuAula.svg)
> 🏫 **Menú de Aula:**
> Este diagrama representa las operaciones disponibles para la gestión de aulas, como registrar, actualizar, consultar y eliminar aulas.

---

#### MENU_ASIGNATURA
![Diagrama MENU_ASIGNATURA](/casosDeUso/diagramaDeContexto/imagenes/DiagramaMenuAsignatura.svg)
> 📘 **Menú de Asignatura:**
> Este diagrama ilustra las funcionalidades relacionadas con la gestión de asignaturas, incluyendo registrar, actualizar, consultar y eliminar asignaturas.

---

#### MENU_PROFESOR
![Diagrama MENU_PROFESOR](/casosDeUso/diagramaDeContexto/imagenes/DiagramaMenuProfesor.svg)
> 👩‍🏫 **Menú de Profesor:**
> Este diagrama detalla las operaciones disponibles para la gestión de profesores, como registrar, actualizar, consultar y eliminar profesores.

---

#### MENU_ASIGNATURAGRADO
![Diagrama MENU_ASIGNATURAGRADO](/casosDeUso/diagramaDeContexto/imagenes/DiagramaMenuAsignaturaGrado.svg)
> 📚 **Menú de Asignatura-Grado:**
> En este diagrama se describen las operaciones para gestionar la relación entre asignaturas y grados, incluyendo crear, actualizar, consultar y eliminar estas relaciones.

---

#### MENU_ASIGNATURAGRADOPROFESOR
![Diagrama MENU_ASIGNATURAGRADOPROFESOR](/casosDeUso/diagramaDeContexto/imagenes/DiagramaMenuAsignaturaGradoProfesor.svg)
> 🧑‍🏫 **Menú de Asignatura-Grado-Profesor:**
> Este diagrama ilustra la gestión de relaciones entre asignaturas, grados y profesores, permitiendo crear, actualizar, consultar y eliminar estas asociaciones.

---

#### MENU_HORARIOASIGNATURAAULA
![Diagrama MENU_HORARIOASIGNATURAAULA](/casosDeUso/diagramaDeContexto/imagenes/DiagramaHorarioAsignaturaAula.svg)
> ⏰ **Menú de Horario-Asignatura-Aula:**
> Este diagrama muestra las operaciones disponibles para gestionar horarios en relación con asignaturas y aulas, incluyendo registrar, actualizar, consultar y eliminar.

---

#### MENU_HORARIO
![Diagrama MENU_HORARIO](/casosDeUso/diagramaDeContexto/imagenes/DiagramaMenuHorario.svg)
> 🕒 **Menú de Horario:**
> En este diagrama se representan las funcionalidades de gestión de horarios, como registrar, actualizar, consultar y eliminar horarios.

---

#### MENU_CASOSADICIONALES
![Diagrama MENU_CASOSADICIONALES](/casosDeUso/diagramaDeContexto/imagenes/DiagramaMenuCasosAdicionales.svg)
> ➕ **Menú de Casos Adicionales:**
> Este diagrama incluye las funcionalidades adicionales del sistema, como asignar profesores, consultar horarios de profesores, editar asignaciones y elegir grados.

---

## 🛠️ Casos de Uso Detallados

### Inicio de Sesión
![Inicio de Sesión](/casosDeUso/imagenes/IniciarSesión.svg)
> 🔒 **Ingreso:**
> Este diagrama ilustra el flujo de inicio de sesión:
> - El usuario ingresa sus credenciales.
> - El sistema valida la información:
>   - Si es válida, se muestra un mensaje de bienvenida.
>   - Si no, se notifica un error de "Credenciales incorrectas".

---

### Ver Menú
![Ver Menú](/casosDeUso/imagenes/VerMenu.svg)
> 📋 **Visualización del Menú:**
> Muestra las opciones principales del sistema:
> - El usuario puede navegar hacia las diferentes funcionalidades.

---

### Grado
#### Registrar Grado
![Registrar Grado](/casosDeUso/imagenes/Grado/RegistrarGrado.svg)
> 🎓 **Registro de Grado:**
> Permite al usuario registrar un nuevo grado:
> - Introducción manual de datos.
> - Confirmación de creación.

#### Consultar Grado
![Consultar Grado](/casosDeUso/imagenes/Grado/ConsultarGrado.svg)
> 📘 **Consulta de Grados:**
> Presenta una lista de grados disponibles:
> - Permite seleccionar un grado específico para ver sus detalles.

#### Actualizar Grado
![Actualizar Grado](/casosDeUso/imagenes/Grado/ActualizarGrado.svg)
> ✏️ **Edición de Grados:**
> Permite modificar los datos de un grado existente:
> - Validación de datos y confirmación.

#### Eliminar Grado
![Eliminar Grado](/casosDeUso/imagenes/Grado/EliminarGrado.svg)
> ❌ **Eliminación de Grado:**
> Elimina un grado seleccionado tras confirmación del usuario.

---

### Aula
#### Registrar Aula
![Registrar Aula](/casosDeUso/imagenes/Aula/RegistrarAula.svg)
> 🏫 **Registro de Aulas:**
> Permite agregar nuevas aulas al sistema:
> - Introducción de datos como nombre, capacidad, y ubicación.

#### Consultar Aula
![Consultar Aula](/casosDeUso/imagenes/Aula/ConsultarAula.svg)
> 📋 **Consulta de Aulas:**
> Muestra las aulas disponibles con filtros por ubicación y capacidad.

#### Actualizar Aula
![Actualizar Aula](/casosDeUso/imagenes/Aula/ActualizarAula.svg)
> ✏️ **Edición de Aulas:**
> Permite modificar los datos de una aula específica.

#### Eliminar Aula
![Eliminar Aula](/casosDeUso/imagenes/Aula/EliminarAula.svg)
> ❌ **Eliminación de Aulas:**
> Proceso para eliminar un aula tras confirmación del usuario.

---

### Asignatura
#### Registrar Asignatura
![Registrar Asignatura](/casosDeUso/imagenes/Asignatura/RegistrarAsignatura.svg)
> 📝 **Registro de Asignaturas:**
> Permite registrar nuevas asignaturas mediante:
> - Introducción manual o carga de archivo.

#### Consultar Asignatura
![Consultar Asignatura](/casosDeUso/imagenes/Asignatura/ConsultarAsignatura.svg)
> 📋 **Consulta de Asignaturas:**
> Muestra una lista de asignaturas disponibles.

#### Actualizar Asignatura
![Actualizar Asignatura](/casosDeUso/imagenes/Asignatura/ActualizarAsignatura.svg)
> ✏️ **Edición de Asignaturas:**
> Modifica los datos de una asignatura existente.

#### Eliminar Asignatura
![Eliminar Asignatura](/casosDeUso/imagenes/Asignatura/EliminarAsignatura.svg)
> ❌ **Eliminación de Asignaturas:**
> Permite eliminar asignaturas tras confirmación del usuario.

---

### Profesor
#### Registrar Profesor
![Registrar Profesor](/casosDeUso/imagenes/Profesor/RegistrarProfesor.svg)
> 👨‍🏫 **Registro de Profesores:**
> Agrega nuevos profesores al sistema mediante datos manuales.

#### Consultar Profesor
![Consultar Profesor](/casosDeUso/imagenes/Profesor/ConsultarProfesor.svg)
> 📘 **Consulta de Profesores:**
> Permite ver una lista de profesores registrados.

#### Actualizar Profesor
![Actualizar Profesor](/casosDeUso/imagenes/Profesor/ActualizarProfesor.svg)
> ✏️ **Edición de Profesores:**
> Modifica información sobre profesores existentes.

#### Eliminar Profesor
![Eliminar Profesor](/casosDeUso/imagenes/Profesor/EliminarProfesor.svg)
> ❌ **Eliminación de Profesores:**
> Elimina registros de profesores tras validación.

---

### Asignatura-Grado
#### Registrar Asignatura-Grado
![Registrar Asignatura-Grado](/casosDeUso/imagenes/AsignaturaGrado/RegistrarAsignaturaGrado.svg)
> 🔗 **Vinculación:**
> Permite vincular asignaturas específicas a grados académicos.

#### Consultar Asignatura-Grado
![Consultar Asignatura-Grado](/casosDeUso/imagenes/AsignaturaGrado/ConsultarAsignaturaGrado.svg)
> 📘 **Consulta de Vinculaciones:**
> Permite visualizar las asignaturas vinculadas a un grado.

#### Actualizar Asignatura-Grado
![Actualizar Asignatura-Grado](/casosDeUso/imagenes/AsignaturaGrado/ActualizarAsignaturaGrado.svg)
> ✏️ **Edición de Vinculaciones:**
> Modifica asignaturas asociadas a un grado.

#### Eliminar Asignatura-Grado
![Eliminar Asignatura-Grado](/casosDeUso/imagenes/AsignaturaGrado/EliminarAsignaturaGrado.svg)
> ❌ **Eliminación de Vinculaciones:**
> Permite eliminar la relación entre asignaturas y grados.

---

### Asignatura-Grado-Profesor
#### Registrar Asignatura-Grado-Profesor
![Registrar Asignatura-Grado-Profesor](/casosDeUso/imagenes/AsignaturaGradoProfesor/RegistrarAsignaturaGradoProfesor.svg)
> 🔗 **Registro Vinculación:**
> Permite asociar asignaturas con grados y profesores.

#### Consultar Asignatura-Grado-Profesor
![Consultar Asignatura-Grado-Profesor](/casosDeUso/imagenes/AsignaturaGradoProfesor/ConsultarAsignaturaGradoProfesor.svg)
> 📘 **Consulta de Vinculaciones:**
> Muestra detalles de las asociaciones existentes.

#### Actualizar Asignatura-Grado-Profesor
![Actualizar Asignatura-Grado-Profesor](/casosDeUso/imagenes/AsignaturaGradoProfesor/ActualizarAsignaturaGradoProfesor.svg)
> ✏️ **Edición de Asociaciones:**
> Permite modificar las relaciones ya registradas.

#### Eliminar Asignatura-Grado-Profesor
![Eliminar Asignatura-Grado-Profesor](/casosDeUso/imagenes/AsignaturaGradoProfesor/EliminarAsignaturaGradoProfesor.svg)
> ❌ **Eliminación de Vinculaciones:**
> Elimina las asociaciones tras validación.

---

### Horario-Asignatura-Aula
#### Registrar Horario-Asignatura-Aula
![Registrar Horario-Asignatura-Aula](/casosDeUso/imagenes/HorarioAsignaturaAula/RegistrarHorarioAsignaturaAula.svg)
> 🏫 **Registro Vinculaciones:**
> Permite crear horarios vinculados a aulas y asociaciones específicas.

#### Consultar Horario-Asignatura-Aula
![Consultar Horario-Asignatura-Aula](/casosDeUso/imagenes/HorarioAsignaturaAula/ConsultarHorarioAsignaturaAula.svg)
> 📋 **Consulta de Vinculaciones:**
> Permite revisar asociaciones entre horarios y aulas.

#### Actualizar Horario-Asignatura-Aula
![Actualizar Horario-Asignatura-Aula](/casosDeUso/imagenes/HorarioAsignaturaAula/ActualizarHorarioAsignaturaAula.svg)
> ✏️ **Edición de Vinculaciones:**
> Permite modificar registros ya existentes.

#### Eliminar Horario-Asignatura-Aula
![Eliminar Horario-Asignatura-Aula](/casosDeUso/imagenes/HorarioAsignaturaAula/EliminarHorarioAsignaturaAula.svg)
> ❌ **Eliminación de Vinculaciones:**
> Borra registros tras validación.

---

### Horario
#### Registrar Horario
![Registrar Horario](/casosDeUso/imagenes/Horario/RegistrarHorario.svg)
> 📅 **Registro de Horarios:**
> Permite crear horarios personalizados para asignaturas y profesores.

#### Consultar Horario
![Consultar Horario](/casosDeUso/imagenes/Horario/ConsultarHorario.svg)
> 📋 **Consulta de Horarios:**
> Muestra horarios existentes por asignatura o profesor.

#### Actualizar Horario
![Actualizar Horario](/casosDeUso/imagenes/Horario/ActualizarHorario.svg)
> ✏️ **Edición de Horarios:**
> Permite ajustar detalles en horarios registrados.

#### Eliminar Horario
![Eliminar Horario](/casosDeUso/imagenes/Horario/EliminarHorario.svg)
> ❌ **Eliminación de Horarios:**
> Permite borrar horarios del sistema.

---

### Casos Adicionales
#### Asignar Profesor
![Asignar Profesor](/casosDeUso/imagenes/AsignarProfesor.svg)
> 👨‍🏫 **Asignación de Profesor:**
> Permite asignar profesores a asignaturas específicas.

#### Consultar Horario de Profesor
![Consultar Horario de Profesor](/casosDeUso/imagenes/ConsultarHorarioProfesor.svg)
> 📅 **Consulta del Horario:**
> Muestra horarios completos para un profesor.

#### Editar Asignación
![Editar Asignación](/casosDeUso/imagenes/EditarAsignación.svg)
> ✏️ **Edición de Asignaciones:**
> Modifica detalles en asignaciones ya creadas.

#### Seleccionar Aula Automáticamente
![Seleccionar Aula Automáticamente](/casosDeUso/imagenes/SeleccionarAulaAutomaticamente.svg)
> 🤖 **Automatización:**
> Selecciona automáticamente aulas basadas en disponibilidad y preferencias.

#### Elegir Grado
![Elegir Grado](/casosDeUso/imagenes/ElegirGrado.svg)
> 🎓 **Selección de Grado:**
> Permite al usuario elegir un grado y visualizar sus opciones asociadas.

---
