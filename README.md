Este es un servidor dedicado modificado de Counter-Strike 2 (CS2) que te permite cambiar el mod activo desde el chat o la consola del servidor. Los mapas están preconfigurados según el modo de juego y cambian automáticamente cuando este se modifica.

Cada modo de juego incluye mapas preestablecidos para que comiences de inmediato, y es fácil añadir más.

En la consola del servidor, ejecuta estos comandos:

meta list → Deberías ver CounterStrikeSharp en la salida.
css_plugins list → Deberías ver algunos plugins en la salida.
Si ambos comandos muestran contenido, todo está funcionando correctamente.

El uso de RCON mientras estás conectado al servidor no funciona. 
Consulta la discusión aquí https://www.reddit.com/r/GlobalOffensive/comments/167spzi/cs2_rcon/ .
Soluciones actuales:
Usa CS2Rcon para que los administradores puedan usar !rcon en el chat.
Desconéctate del servidor y usa rcon_address IP:PORT en la consola.
Utiliza un programa RCON externo compatible, como este https://github.com/fpaezf/CS2-RCON-Tool-V2.



Pruebas utilizadas solo config chile
