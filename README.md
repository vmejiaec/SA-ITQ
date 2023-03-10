# Ejercicios para la prueba del equipo del Sistema Académico

## Contenido

1. [Periodos académicos](#periodos-académicos)
2. [Asignaturas](#asignaturas)
3. [Días para la matrícula](#días-para-la-matrícula)
4. [Registro en línea de la matrícula de inglés](#registro-en-línea-de-la-matrícula-de-inglés)
5. [Profesor nuevo](#profesor-nuevo)


# Acceso a la base de datos de pruebas

Server name: SQL8002.site4now.net

Login: db_a93eed_itq_admin

Password: Itq_2023

# Acceso al repositorio del código

Sitio GitHub con el código: <https://github.com/vmejiaec/SA-ITQ>

# Ejecución del código en Visual Studio 2015

Para ejecutar el código localmente en tu computadora, debes clonar el repositorio y 
luego buscar el archivo "sistema.sln". Al abrir el archivo el VS2015 presentará todas 
las pantallas del proyecto. Con pulsar en el botón "run" se inicia la ejecución de la
aplicación web

![VS2015 Open](media/VSOpen.png)

![VS2015 Run](media/VSRun.png)

# Usuario del Sistema Académico para pruebas

usuario: desa
password: desa

![Usuario para pruebas](media/SA-ITQ-Login.png)

# Creación de periodos académicos

## Pantalla: PeriodosAcademicos.aspx

![Interfaz de usuario gráfica, Tabla Descripción generada automáticamente con confianza media](media/5b451309ba8912232d7bed64e3649372.png)

Agregar los campos de  fecha de inicio y final del período de matrículas, para guardar el período de matriculación permitido. Hay que tomar en cuenta que debemos almacenar esta información en la base de datos. Los campos en la base se llamarán:

Fecha_Inicio_Matriculas, Fecha_Fin_Matriculas

# Creación de Asignaturas

## Pantalla: IngresarMaterias.aspx

![](media/a981b127bc2c7a5413d746d20751f54c.png)

Agregar la opción de añadir el número de horas a elegir entre los valores de 36 o 64, y el cálculo del valor del crédito, como resultado de la operación con los datos del valor hora y el número de horas.

# Crear días para la matrícula

## Pantalla: IngresoDiasMatricula.aspx

![Tabla Descripción generada automáticamente](media/389ea91a658cc6bd2ebf1688402ab77a.png)

Permitir elegir los estados entre una lista desplegable que tenga las opciones A – Activo, P – Pasivo

# Registro en línea de la matrícula de inglés

## Pantalla: inscripcion.aspx

![](media/fafea90fd7299249a844cb6b0e7c9581.png)

Esta pantalla debe consulta a la base, a la tabla de períodos académicos, para saber si existe un período de matrículas vigente a la fecha actual, si es así, debe permitir continuar con un mensaje que indique las fechas de inicio y fin del período de matrículas; y, caso contrario, que presente la información de las fechas, pero con el aviso que el período a vencido y no permita utilizar la pantalla.

# Creación de un profesor nuevo

## Pantalla: IngNuevoDocente.aspx

![](media/02776b7cb4d656274b967f37d4e23bb0.png)

El logo debe ser actualizado con el nuevo logo.

Antes de grabar hay que validar que el correo sea el correo institucional, esto es, que termine con @itq.edu.ec. Hay que presentar un mensaje de error adecuado que avise al usuario que el correo no es institucional.
