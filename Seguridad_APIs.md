Seguridad en APIs:

- Hay que tener controladas las APIs que hay (se pueden tener en un repositorio central).
- Hay que tener actualizadas las versiones de las APIs en este repositorio.
- Casi nunca se da de baja una API obsoleta y, aunque no se utiliza, sigue estando y puede ser vulnerable.
- Hay una continua lucha entre servicio vs seguridad.
- Cada vez que se actualiza, tiene que pasar unos tests de seguridad de manera automática.
- Los WAFs tradicionales no manejan bien las APIs.
- Analizador estático de código específico del Framework.
- Tener buenas definiciones de las APIs -> Se pueden generar con Postman, HAR o ChatGPT.
- Con las definiciones, se pueden automatizar test de seguridad de APIs con Schematesis (opensource).
- En el IDE se puede meter en VSCode con un addon en tiempo real: De Crunch (Opensource) -> SwaggerHUB.
