# Low Poly Poker

Texas Hold'em en 3D con dinero ficticio, para navegador de PC.

- Juega solo contra 4 bots, eligiendo la personalidad de cada uno: prudente, tranquilo, equilibrado, agresivo o intenso.
- O crea una mesa online de hasta 5 jugadores y comparte el enlace de invitación: tus amigos entran sin cuenta.
- Puedes elegir tú las 5 cartas de tu jugada o dejar que el juego use siempre la mejor.
- Sin fichas no se juega: puedes pedir un préstamo al casino, y lo que ganes va primero a pagar la deuda.

La partida online usa un servidor público de mensajes MQTT (por WebSocket seguro): cada jugador solo se conecta a ese servidor, así que funciona aunque los routers bloqueen las conexiones directas. Si un servidor no responde se prueba otro. Las cartas de cada jugador viajan cifradas solo para él.
