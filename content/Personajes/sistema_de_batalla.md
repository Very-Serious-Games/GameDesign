---
title: 1. Sistema de Batalla
draft: false
tags:
---
# Estructura del combate
- Fluidez y ritmo:
	El combate está diseñado para que el jugador pueda alternar rápidamente entre ataques, defensas y transformaciones, fomentando el uso continuo de combos y variaciones en el estilo de lucha.
- Encadenamiento de combos:
	Los ataques ligeros y pesados pueden encadenarse en secuencias específicas.
	Cambiar de arma en medio de un combo reinicia la secuencia, otorgando acceso a ataques únicos y elevando la puntuación de estilo.
- Entorno interactivo:
	Algunos entornos de la arena pueden ser utilizados estratégicamente como por ejemplo unos pilares que pueden derrumbarse sobre enemigos.

# Recursos del jugador
- Salud:
	Representa la vida del jugador y se muestra como una barra verde en la interfaz.
	Puede regenerarse con un arma específica o mediante consumibles limitados.
- Energía Demoníaca:
	Recurso principal para el uso de las transformaciones.
	Se recarga mediante ejecución de combos y al derrotar enemigos.

# Condiciones de combate
- Victoria:
	Derrotar a todos los enemigos en la arena o completar algún objetivo secundario como proteger a un aliado.
- Derrota:
	El jugador pierde si su salud llega a 0 o si no es capaz de cumplir las condiciones del objetivo principal.

# Acciones del jugador
- Ataques ligeros:
	Ataques de alta velocidad utilizados principalmente para iniciar combos y ganar Energía demoníaca rápidamente.
	Daño moderado pero inefectivos contra enemigos con escudo.
- Ataques pesados:
	Ataques mucho más lentos que son capaces de romper defensas, aplicar efectos de impacto como aturdimientos o derribos y causar mayor daño.
	Estos ataques dejarán vulnerable momentáneamente al jugador si falla.
- Cambios de arma:
	Cambiar de arma en medio de un combo genera un ataque de cambio, el cual es un ataque único de cada arma que mejora la puntuación de combo.
- Transformaciones demoníacas:
	Cada transformación tiene una duración limitada basada en la energía disponible.
- Esquiva:
	Realiza un movimiento rápido para evitar ataques enemigos.
- Bloqueo:
	Reduce significativamente el daño recibido, dependiendo del arma equipada.
- Parry:
	Si se realiza con precisión, anula el ataque enemigo y abre una ventana para un golpe crítico.
	Si se falla, dejará al jugador vulnerable por un corto periodo de tiempo.
# Interacción con enemigos
Tipos de Enemigos:
- Menores:
	Débiles y numerosos.
	Sirven para construir combos y recargar energía.
	Atacan en grupo.
	Algunos tienen ataques a distancia para obligar al jugador a moverse.
- Élite:
	Más resistentes, con ataques potentes y patrones específicos.
	Suelen tener una mecánica especial, como escudos que el jugador debe romper.
	Se mueven de manera más calculada, bloqueando o esquivando ataques.
- Jefes:
	Son el núcleo del sistema de combate avanzado, con varias fases y patrones únicos que evolucionan durante la pelea.
	Cada jefe representa un pecado capital y emplea mecánicas que reflejan su temática.
	Sus ataques cambian según la fase, obligando al jugador a adaptarse continuamente.