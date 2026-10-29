### Hacer network test

1. Abrir servidor: ```supertuxkart --server-config=config_24p.xml --lan-server="San Alberto 2026" --network-console```

Los archivos de configuracion que acaban en un numero indica el numero maximo de jugadores que permite. Usa esos para testear.
**No uses el config ia_test. No lo he conseguido hacer funcionar**

2. Metete tu al servidor

3. Mete a los bots (ejecuta este comando desde otra terminal en la misma maquina o en otra, lo que prefieras): ```supertuxkart --connect-now=localhost --network-ai=23 --no-graphics```

4. A disfrutar probando si el servidor se suicida o no. Puedes ajustar el numero de bots introducidos en el comando anterior, en `--network-ai=`
