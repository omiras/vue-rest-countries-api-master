# Reto Front End Mentor con Vue

## Iterción 0

- Visita la documentación de la [API Rest Countries v3](https://restcountries.com/)
- Esta API ha cambiado mucho durante el tiempo. Antes, podías hacer una petición y obtenías todos los paises de golpe, pero ahora ya no se puede. Investiga como podemos hacer una petición para obtener toda la información de los paises que necesitamos (para la Iteración 1)
- Es decir, construye la URL de manera que al hacer una petición GET obtengamos algo similar a esto:

<img  src="https://oscarm.tinytake.com/media/1797c22?filename=1753873401817_TinyTake30-07-2025-01-03-01_638894702014364010.png&sub_type=thumbnail_preview&type=attachment&width=1200&height=634" title="Powered by TinyTake Screen Capture"/><br>

- Para la primera iteración necesitamos:
  - nombre páis
  - URL de la imagen de la bandera
  - Población
  - Continente



## Iteración 1

- Permite que Vue3 gobierne todo el HTML
- Declara una variable de estado para almacenar todos los paises
- Nada más cargar la app, haz un fetch para obtener todos los paises del a api usando el hook [onMounted](https://vuejs.org/api/composition-api-lifecycle#onmounted)
- Utiliza adecuadamente la directiva v-for para generar tantos `<div class="country-info-box">` como paises hemos recuperado de la API

