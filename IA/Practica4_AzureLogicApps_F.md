# Azure Logic Apps
---
### Objetivo
- Implementar el servicio de Azure Logic Apps
### Caracteristicas

![Caracteristicas de Azure Logic Apps](https://github.com/sanchezJose07/InteligenciaArtificial/blob/main/imagenes/LA5.png)

### Procedimiento
1. Abrimos Microsorft Azure
2. Abrir Aplicacion logica y agregar

![Aplicacion logica](https://github.com/sanchezJose07/InteligenciaArtificial/blob/main/imagenes/LA4.png)

3. Llenamos los datos necesarios para el recurso y creamos

![Recurso](https://github.com/sanchezJose07/InteligenciaArtificial/blob/main/imagenes/LA3.png)
4. Ahora nos dirigimos a Ir al recurso 

![Ir al recurso](https://github.com/sanchezJose07/InteligenciaArtificial/blob/main/imagenes/LA7.png)
5. Nos dirigimos a Diseñador de aplicacion logica 

![Diseñador de aplicacion logica](https://github.com/sanchezJose07/InteligenciaArtificial/blob/main/imagenes/LA6.png)
6. Creamos una aplicacion en blanco 

![Aplicacion en blanco](https://github.com/sanchezJose07/InteligenciaArtificial/blob/main/imagenes/LA1.png)
7. Una vez dentro buscamos twitter y agregamos un desencadenador para twitter

![Desencadenador para twitter](https://github.com/sanchezJose07/InteligenciaArtificial/blob/main/imagenes/LA2.png)
8. Colocamos un texto en el primer recuadro e iniciamos secion en twiter

![twiter]()
9. Colocar los datos en el cuadro de Cuando se publica un tweet nuevo

![Datos para twitter]()
10. Crear un archivo de exel en la nuve para llenar la hoja con los tweets

![Exel]()
11. Agregar un segundo paso y agregamos el servicio de lenguaje 

![Segundo paso del desencadenador]()

12. Ahora abrimos otro recurso llamado Cognitive Services

![Cognitive Services]()

13. Creamos un Servicio de Lenguaje

![Reconocimiento del lenguaje](https://github.com/sanchezJose07/InteligenciaArtificial/blob/main/imagenes/LA0.png)
14. Ahora llenamos la informacion necesaria y creamos

![Crear servicio de lenguaje]()
14. Ahora nos dirigimos al recurso
![]()
15. Nos dirigimos a la parte de claves y punto de conexion y compiamos la Clave 1 y el Extremo
![]()
16. Lo anterior lo pegamos en la parte del segundo desencadenador del punto 11, colocamos el nombre y creamos
![]()
17. En el recuadro ingresamos el Document ID e ingresamos que texto se va a analizaren el tweet
18. Ahora creamos otro paso y buscamos google sheet para la hoja de calculo del paso 10 e iniciamos sesion con nuestra cuenta de google. En archivo tenemos que ingresar la hoja de calculo que esta en la nube y despues la hoja de calculo y añadimos los parametros del tweet
 ![]()
20. En caso de que no funcione tenemos que eliminar el paso y crearlo de nuevo y llenarlo de nuevo 
21. Ahora ingresamos los parametros que van a llenar nuestra hoja de calculo como se muestra en la imagen 
![]()
22. Ahora en el mismo paso de "para cada uno" creamos un paso para teams para publicar un mensaje en un canal e iniciamos sesion
23. Del paso anterior llenamos los datos solicitados como se muestra en la imagen siguiente y guardamos
![]()
24. Finalmente twiteamos con el hashtag designado y vemso que nuestra hoja de calculo se esta llenando
![]()

