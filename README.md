# Arbol_Binomial_Opciones
Modelo Cox-Ross-Rubenstein vs Montecarlo para valuar opciones



Simulación Monte Carlo y Valoración de Opciones Europeas con Black-Scholes-Merton

Este proyecto implementa, de forma clara y aplicada, dos de las herramientas más importantes en las finanzas cuantitativas modernas:

Simulación Monte Carlo de trayectorias de precios bajo el modelo
Geometric Brownian Motion (GBM).

Valoración de opciones europeas (call y put) mediante:

Monte Carlo bajo medida neutral al riesgo,

el modelo analítico Black-Scholes-Merton.

El objetivo es mostrar cómo la simulación aleatoria y la teoría matemática convergen a un mismo resultado cuando se modela un activo financiero bajo un GBM.

Las opciones son contratos derivados cuyo valor depende del precio futuro de un activo. Pero ese precio es incierto.
Para modelar esa incertidumbre, usamos el Movimiento Browniano Geométrico, uno de los modelos más usados en finanzas.

Monte Carlo nos permite:

generar cientos o miles de trayectorias posibles del precio del activo,

evaluar el payoff de la opción en cada escenario,

obtener un precio justo promediando todos los payoffs descontados.

Black-Scholes-Merton es la solución cerrada exacta del mismo modelo que simula Monte Carlo.
