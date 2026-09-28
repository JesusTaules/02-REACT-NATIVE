# Ejercicio 07 - Feed de noticias

## Qué he aprendido
- A reutilizar un componente de tarjeta para representar varias noticias
- A pasar información a un componente mediante props y a permitir el desplazamiento vertical con ScrollView

## Respuesta a la pregunta de comprensión
¿Qué parte debe cambiar entre una noticia y otra y qué parte debería permanecer igual?

Respuesta: Deben cambiar los datos de cada noticia, como su categoría y su título. La estructura y los estilos de la tarjeta deberían permanecer iguales para que todas se muestren de forma coherente

## Qué he modificado
- He modificado App.tsx para mostrar tres noticias de tecnología, móvil y cloud
- He creado el componente NewsCard, que recibe la categoría y el título mediante props y mantiene una estructura común para cada noticia

## Resultado
La interfaz muestra el encabezado Noticias y tres tarjetas apiladas verticalmente. Cada tarjeta incluye una categoría, un titular y la fecha Hace 2 horas