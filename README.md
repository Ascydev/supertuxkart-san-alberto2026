# INFO IMPORTANTE PARA PARTICIPANTES

**Es importantisimo que cada jugador se lleve su propio PC para jugar al juego.** El juego esta disponible para Linux, Windows y MacOS en https://supertuxkart.net/es/Download
- Por favor, asegurate tambien de que tu juego funciona correctamente antes del torneo (y asi aprovechas para aprenderte los controles básicos).
- No te preocupes de posibles problemas de conexión que puedan haber el dia del torneo; eso se resolvera en el mismo momento. (Ya sabemos que pueden haber algunos problemas con el firewall, pero sabemos resolverlos) (`sudo ufw allow 2759`).

POSIBLES EXCEPCIONES: Si por lo que sea no tienes ordenador, puede ser que se pueda usar alguno de un aula para jugar, pero NO te lo puedo asegurar con certeza.

Se permite jugar **con mando**.

## Hacer network test (Ignora esto si eres un participante)

1. Abrir servidor: ```supertuxkart --server-config=config_24p.xml --lan-server="San Alberto 2026" --network-console```

Los archivos de configuracion que acaban en un numero indica el numero maximo de jugadores que permite. Usa esos para testear.
**No uses el config ia_test. No lo he conseguido hacer funcionar**

2. Metete tu al servidor

3. Mete a los bots (ejecuta este comando desde otra terminal en la misma maquina o en otra, lo que prefieras): ```supertuxkart --connect-now=IP_SERVIDOR --network-ai=23 --no-graphics```

3.5: **ESPERA A QUE EN LA LISTA DE JUGADORES LOS BOTS APAREZCAN CON PING.** Es por si acaso.

4. A disfrutar probando si el servidor se suicida o no (osea, que ya puedes darle a jugar). Puedes ajustar el numero de bots introducidos en el comando anterior, en `--network-ai=N`
