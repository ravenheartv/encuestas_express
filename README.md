# encuestas_NDT

Necesitamos crear un backend con las siguientes caracteristicas:

- servir archivos estaticos (index, login, visualizaciones)
- SQlite
- valoraciones 
- almecenar valoraciones
- almacenar usuarios 

## base de datos 

- utilizaremos SQlire, con dos tablas, `users` y `rating`

- password
- review
- rating 
- message


## api

## POST api/reviews?rating="good"&message="ta flama"

endpoint para recibir los datos del usuario, los mandaremos por el body en formato json

```json
{
    "rating": "good",
    "message": "lo que sea"
}

en rating puede recibir 
- good 
- neutral
- bad




