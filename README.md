# Api-Karate-Serenity-restcountries.com
Ejercicio API https://restcountries.com/v3.1/
Ejercicio API
Susana, es una QA apasionada por la Calidad, ella siempre está aprendiendo sobre las últimas tecnologías y cómo es de esperar en cuanto a automatización no se ha querido quedar atrás. Empezó a ver videos, tutoriales sobre karate y serenity para pruebas Apis, sin embargo, una vez enfrentada a un proyecto real se ha encontrado con varias casuísticas que no le han permitido avanzar. Ella le pide ayuda a su compañero/a (Tu) que revise su código porque por si sola no logra encontrar los errores que tiene. ¿Te atreves a ayudar a susana?

Descripción de los scenarios implementados:
1- Navega a la url https://restcountries.com/v3.1/name/<pais> y Consulta datos por país, en este caso "Ecuador". Se envía el tipo de método Get y la respuesta que sea un 200, se guarda en una variable temporal la response del scenario 1 para más adelante utilizarla.
2- Luego en la 2da url https://restcountries.com/v3.1/capital/ se consultan los datos por capital, para ello utilizaremos la variable temporal con los resultados almacenados de la primera ejecución donde le concatenaremos a la url antes mencionada dicha capital y obtendremos los valores esperados como el fifa que para el caso de Ecuador deberá ser "ECU", por lo que se deberá validar que el fifa de la respuesta coincida con el enviado por el csv. Así como el método sea Get y el code 200.
3- Finalmente en la url https://restcountries.com/v3.1/lang/spanish se deberá validar que Ecuador este en la lista de habla hispana, que pertenezca a la región "Americas" y que la lista devuelva 24 registros. Así como el método sea Get y el code 200.

Consideración a tener en cuenta para la la resolución del ejercicio:
- validar que hay máx 7 errores que deben ser corregidos, para que funcione la automatización.
- Se deben eliminar Header que no se utilicen dentro de los métodos.
- En el scenario 1 debemos agregar la validación que sea la capital enviada en la data e imprimirla
- Explicar con comentarios que hace esta línea de código And
