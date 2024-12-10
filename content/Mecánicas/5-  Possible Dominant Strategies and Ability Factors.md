---
title: Possible Dominant Strategies and Ability Factors
draft: false
tags:
---
# Estrategias Dominantes

Dada la amplia variedad de armas y habilidades a las que puede acceder un jugador, es importante analizar las posibles estrategias existentes para localizar las más efectivas y favorecedoras, y balancear el juego en consecuencia.
Los aspectos a considerar que más fácilmente podrían sobresalir sobre otros serían el uso de las transformaciones demoníacas y las armas adquiridas.

**Tranformaciones demoníacas:** Son muy poderosas y  proporcionan una ventaja considerable. En caso de no estar bien balanceadas, se puede abusar de ellas utilizándolas de manera más prolongada de la que se debería y combinándolas durante el combate y exploración.
Un ejemplo de posible estrategia dominante sería el uso prolongado de la transformación demoníaca al máximo priorizando los recursos para que se mantenga activa.

**Armas específicas:** Algunas de las armas existentes en el mundo podrían ofrecer ventajas importantes en según qué escenario, lo que llevaría al uso excesivo de esa arma en cuestión en lugar de alternar.
Por ejemplo, tenemos la *Corona Fragmentada* que permite lanzar ondas de energía destructivas. Si usamos esa arma para llevar a cabo un ataque a distancia resulta en una opción mucho más segura que un combate cuerpo a cuerpo.

Por otro lado, nos encontramos con la **Combinación de habilidades** que hace posible el cambio de arma durante el combate, así como usar habilidades de diferentes formas demoníacas. Esta capacidad extra puede generar combinaciones extremadamente fuertes (p. ej. la combinación de la forma demoníaca de Pereza, ralentizar el tiempo, con el ataque de la *Corona Fragmentada* de Soberbia). Se pueden crear estrategias dominantes si se priorizan ciertas sinergias y se maximizan combos que controlen el entorno (como el comentado previamente de ralentizar enemigos y atacar con ataques a distancia).

Por último, es importante tener en cuenta el factor de la Corrupción como riesgo calculado: si el sistema de Corrupción "recompensa" el uso de las transformaciones así como las decisiones arriesgadas sin poner ningún tipo de penalización inmediata, el jugador podría abusar del aumento de poder que se obtiene con ellas, sobre todo en las primeras etapas.

**Posibles Soluciones:**
Realizar una sesión de testing en la que se pueda confirmar la diferencia o no de dominancia de ciertas combinaciones o estrategias. 
Basándose en los resultados, implementar (o aumentar) una penalización gradual por el abuso de ciertas mecánicas. Un ejemplo podría ser una penalización inmediata por Corrupción Alta en combate, más limitaciones en la obtención de los recursos necesarios para usar formas demoníacas, entre otros.

# Factores de Habilidad

Dada la amplia variedad de opciones de ataque y defensa de las que dispone un jugador, si juega bien sus cartas y contando con el factor humano es totalmente posible la victoria de este contra un bot/enemigo con menor inteligencia (artificial).

Un jugador (humano) tiene diferentes técnicas a las que recurrir para lograr su victoria:
- El jugador tiene la capacidad de experimentar de forma creativa y encontrar **combinaciones de combos y armas** que quizás una IA menos avanzada no aprovecharía de la misma manera. Una situación de ejemplo la encontraríamos en medio de un combate en el que el jugador cambiase de arma para activar movimientos específicos y únicos.
- El jugador puede adaptar su estilo de juego al entorno y a los enemigos a tiempo real y **jugando de forma estratégica**, acción que sería más difícil para un enemigo programado con un número específico de patrones.
- El jugador humano tiene capacidad de observación, y dependiendo de su buena habilidad en ese aspecto, será capaz de **leer los patrones de ataque** de los enemigos, así como preverlos y explotar sus puntos débiles. 
- Parte de la capacidad estratégica del jugador puede gestionar y priorizar el uso de recursos de una manera más eficiente o conveniente, guardándolos para momentos clave del juego. Por ejemplo, no activar la forma demoníaca de Ira hasta llegar a una bossfight.

A pesar de todas las ventajas de las que dispone un jugador humano (mejores o peores según su ingenio y práctica), aún pueden darse situaciones en las que podría verse en desventaja frente a un enemigo. 
Si los bots tienen acceso a mejoras o ventajas estadísticas de las que pueden abusar (más daño, más salud, más vida) y no requieren que jueguen de forma estratégica o según el sistema de Corrupción/árbol de habilidades, podría producir una "sensación de desventaja o injusticia" al jugador humano.
Nuestro diseño de armas, ataques y mecánicas están concebidos y meditados para evitar esta clase desbalances entre enemigos y jugadores y ofrecer una experiencia buena e interesante. Mediante una combinación de habilidades y una pequeña estrategia el usuario consigue una ventaja frente al enemigo, lo que ayudaría en su victoria.
# Testing

En el momento de testear un combate se debe tener en cuenta varios factores que podrían influenciar el desarrollo del mismo: una pelea 1vs1 le daría mucha más ventaja al jugador que tener que luchar contra un grupo de enemigos; también podrían afectar al resultado del combate el conjunto de características del entorno, elementos interactuables con el jugador (plataformas, trampas, posibles salidas, etc.).

En estos casos añadiríamos particularidades al/los enemigos para que pudieran usar elementos del escenario a su favor, teniendo en cuenta que el jugador tiene la capacidad de razonamiento estratégico. Los enemigos también deberían tener unas habilidades y estadísticas más bien altas para compensar la ventaja que le da el "factor humano" al jugador e igualar el combate.

Teniendo esto en cuenta, en un combate ejemplo de **1vs1** el enemigo sería más poderoso que el jugador en cuanto a estadísticas (más salud/más daño...) así como utilizar algún elemento del entorno siempre y cuanto sea posible. Por ejemplo, la pelea podría desarrollarse cerca de una gran masa de agua (lago, océano, río) y el enemigo disponer de algunos ataques poderosos en los que utilizase el elemento de agua, o desarrollarse en un terreno rocoso tipo desierto y el enemigo usar defensas sólidas tipo roca, etc. El jugador debería tener estos factores en cuenta para poder hacer frente a tal enemigo: con el enemigo de "tipo roca" sería acertado usar la forma demoníaca de la Ira en la que aumenta el daño masivo y le posibilitaría destruir escudos enemigos de gran dureza como las defensas sólidas creadas con la roca.

Mediante una buena elección de ataques y la habilidad evasiva del jugador podría obtener la victoria. Con las mecánicas actuales al jugador le conviene más un procedimiento tipo ataque que le proporcionaría el triunfo de manera más rápida.