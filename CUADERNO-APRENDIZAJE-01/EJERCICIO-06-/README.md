# Ejercicio 06 - Dashboard de métricas

## Qué he aprendido
- A crear un dashboard con varias tarjetas de métricas reutilizando un componente Metric
- A distribuir tarjetas en varias filas con flexDirection: 'row', flexWrap: 'wrap' y gap

## Respuesta a la pregunta de comprensión
¿Por qué un ancho del 48% puede ser más práctico que 50% cuando además existe separación entre tarjetas?

Respuesta: Porque el espacio de separación también ocupa parte del ancho disponible. Si cada tarjeta midiera exactamente el 50%, el espacio adicional podría hacer que no cupieran dos en la misma fila. Con un 48% se deja margen para la separación y que ambas tarjetas encajen

## Qué he modificado
- He modificado App.tsx para mostrar: ventas, clientes, pedidos y conversión
- He creado el componente Metric para presentar cada dato con el mismo diseño y he organizado las tarjetas en una cuadrícula

## Resultado
La interfaz presenta el título Dashboard y el subtítulo Resumen del negocio, seguidos de cuatro tarjetas blancas en dos columnas. Cada tarjeta muestra una métrica, su valor y un indicador de cambio en verde