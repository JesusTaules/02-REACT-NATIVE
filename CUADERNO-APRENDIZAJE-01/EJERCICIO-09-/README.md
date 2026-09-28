# Ejercicio 09 - Interfaz bancaria

## Qué he aprendido
- A organizar en una pantalla desplazable el saldo de una cuenta y sus movimientos
- A reutilizar el componente Movement y pasarle los datos de cada movimiento

## Respuesta a la pregunta de comprensión
¿Qué partes de esta pantalla convertirías en componentes y cuáles dejarías directamente en App? Justifica.

Respuesta: Convertiría cada movimiento en un componente porque todos comparten la misma estructura y solo cambian el concepto, la fecha y el importe. Dejaría en App la presentación general y el saldo

## Qué he modificado
- App.tsx para mostrar el saludo, su saldo disponible y cuatro movimientos bancarios
- He creado el componente reutilizable Movement y he dispuesto cada movimiento en una fila

## Resultado
La interfaz presenta un saludo, una tarjeta oscura con el saldo y una lista desplazable de cuatro movimientos, en cada movimiento aparecen el concepto y la fecha a la izquierda, y el importe a la derecha.