# Desarrollo

Voy a usar las mismas tecnologías que he usado en las prácticas de empresa:

- Lenguaje de programación: [php](https://www.php.net).
- Editor de texto: [Visual Studio Code](https://code.visualstudio.com).
- Gestor de base de datos: [HeidiSQL](https://www.heidisql.com).
- Cliente SFTP: [WinSCP]([WinSCP :: Official Site :: Download](https://winscp.net/eng/download.php)).
- Servicio de dominio y alojamiento web: [Hostalia](https://www.hostalia.com).

Además he desarrollado una api en php desde cero (ya que no hay ninguna funcional por el momento), se puede acceder mediante el siguiente enlace:
https://lolesportswiki.info/api/handler.php/{nombre modulo}/{nombre acción}?{variables, si procede}.

Actualmente existen 10 módulos:
 - coach/{list | delete}
 - country/{list}
 - game/{list | delete}
 - league/{list}
 - player/{list | listAll | one | byteam | byteamandsplit | delete}
 - position/{list}
 - rol/{list}
 - split/{list}
 - splitleague/{list | one | delete}
 - team/{list | one | bysplit | delete}

y las variables que necesitan cada accion son:
 - delete?id=* (id del registro que se desea eliminar)
 - listAll (no requiere variables)
 - one?id=* (id del registro que se desea consultar)
 - byteam?teamId=* (id del equipo cuyos jugadores se desean consultar)
 - byteamandsplit?teamId=*&splitleagueId=* (id del equipo y del splitleague en orden)
 - bysplit?id=*
 - list?name=* (sólo para team, splitleague, player, coach)
