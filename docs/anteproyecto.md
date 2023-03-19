# Anteproyecto

> NOTA: Incluir diagramas donde proceda (diagramas de clases, casos de uso, entidad relación, ...).

## OBJETIVOS

*Quiero hacer una aplicación de información y estadísticas deportivas orientadas a los esports, en este caso el lol o league of legends. En un principio se abarcarán las principales ligas de las mayores regiones, en este caso son cuatro: China (LPL), Corea (LCK), Norte América (LCS) y Europa (LEC).*

*La idea es que al finalizar el proyecto se haya logrado crear una aplicación en la que puedas consultar resultados y fechas de los partidos, qué jugadores conforman cada equipo, cuál es el resultado del equipo en la liga, así como modificar el estado de los jugadores, es decir, dar de alta, baja o modificar el estado de los jugadores en la base de datos (a esto último sólo tendrían acceso un grupo reducido de personas de confianza, por supuesto).*

## ANÁLISIS DEL SOFTWARE

**Requisitos:**

- Debe ofrecer información y estadísticas deportivas orientadas a los esports de forma "amigable".

- El usuario podría consultar toda la información que le interese de cualquier competición.

- Opción de modificar cualquier dato si se registra con cuenta de administrador.

#### CASOS DE USO:

![alt text](https://github.com/KarimElKharrat/integracion-dam/blob/main/docs/doc_images/casosdeuso.png?raw=true)

## DISEÑO DEL SOFTWARE

#### DIAGRAMA DE FLUJO DE DATOS:

*Nivel 0 o de contexto:*

![alt text](https://github.com/KarimElKharrat/integracion-dam/blob/main/docs/doc_images/dfdnivel0.png?raw=true)

*Nivel 1:*

![alt text](https://github.com/KarimElKharrat/integracion-dam/blob/main/docs/doc_images/dfdnivel1.png?raw=true)

<sub>**=primitivo</sub>

*Nivel 2 (Registro):*

![alt text](https://github.com/KarimElKharrat/integracion-dam/blob/main/docs/doc_images/dfdnivel2.1.png?raw=true)

<sub>**=primitivo</sub>

*Nivel 2 (Gestionar consulta):

![alt text](https://github.com/KarimElKharrat/integracion-dam/blob/main/docs/doc_images/dfdnivel2.2.png?raw=true)

<sub>**=primitivo</sub>

*Nivel 3 (Registro):

![alt text](https://github.com/KarimElKharrat/integracion-dam/blob/main/docs/doc_images/dfdnivel3.png?raw=true)

<sub>**=primitivo</sub>



#### DIAGRAMA ENTIDAD-RELACIÓN TRANSFORMADO:

![alt text](https://github.com/KarimElKharrat/integracion-dam/blob/main/docs/doc_images/bdprincipal.png?raw=true)

## ESTIMACIÓN DE COSTES

*En un principio, este proyecto se desarrollará en mi tiempo libre, que quitando prácticas y horas de descanso son unas 3-4 horas al dia sin contar fines de semana, ésto sería hasta el 30 de mayo (fecha límite de entrega del proyecto). Suponiendo que empiezo el 20 de marzo esto daría un total de 20 días a 3-4 horas al día dan en total unas 60-80 horas.*

*En un principio.*
