# Azure Virtual Network 
--- 
### Objetivo
- Crear dos redes virtuales y conectarlas entre si a partir de una maquina virtual.
### Caracteristicas
![]()
### Procedimiento
1. Abrir Microsoft Azure y abrimos el servicio de redes virtuales
2. Crear un grupo de recursos
![]()
3. Llenamos los datos solicitados y creamos
![]()
4. Ahora nos dirigimos a nuestro grupo de recursos
![]()
5. Creamos una red virtual la cual la tenemos en Azure como Redes Virtuales
![]()
6. A continuacion, creamos la red en este caso tenemos que agregarlo al grupo de recusos que creamos e ingresamos un nombre y la region.
![]()
7. En la pestaña de "Direcciones IP" verificamos que el "Espacio de direcciones IPv4" sea 10.0.0.0/16.
A continuacion, agregamos una "subred" y la llenamos con los datos como se muestra en la siguiente imagen donde tenemos que agregar en el "Intervalo de direccion de subred " la siguiente direccion 10.0.0.0/24.
Finalmente creamos la red virtual.
![]()
8. Ahora creamos otra red virtual que este en el mismo grupo de recursos y creamos una subred. Este caso es difiere ya que tenemos que agregar la siguiente direccion 10.1.0.0/24 en el "Intervalo de direccion de subred". De igual forma se muestra en la siguiente imagen.
![]() 
9. Ahora creamos una Maquina Virtual Azure en este caso tenemos que agregarla al grupo de recursos que hemos creado anteriormente y en la maquina virtual es linux. 
![]()
10. Ahora nos dirigimos a la pestaña de Redes y el la parte de Red Virtual seleccionamos la primera red virtual
![]()
11. Creamos otra red virtual con las mismas caracteristicas que la anterior pero en la pestaña de Redes la conectamos a la segunda Red Virtual.
12. Nos dirigimos a la maquina virtual 1, nos dirigimos a Conectar SSH y copiamos el punto 4 (JoseGuadalupe@20.70.28.35), como se muestra en la imagen.
![]()
13. Presionamos el icono de Azure Cloud Shell que esta en la barra azul en la parte superior, si nos marca que no tenemos un espacio de almacenamiento lo creamos.
![]()
14. En el Azure Cloud Sheel ingresamos los siguientes comandos:
- ssh  JoseGuadalupe@20.70.28.35 
- yes 
- Ingresamos la contraseña 
Para este caso ya estamos dentro de la maquina virtual 1 (MV1).
Para confirmar que ya estamos en la maquina virtual ingresamos el siguiente codigo "sudo apt-get moo" y nos debera de aparecer una vaca
![]()
15. Ingresamos a la Red virtual (RV0) y nos dirigimos al apartado de "Emparejamiento" y agregamos un emparejamiento.
![]()
16. Llenamos los datos como se muestra en la siguiente imagen y agregamos.
![]()
17. Esperamos que el "Estado del emparejamiento" nos aparesca conectado.
![]()
18. Ingresamos al Azure Cloud Sheel e ingresamos el siguiente comando "ping 10.0.0.5", con este comando ya tenemos la conexion de las dos redes.
![]()

Esto nos sirve para conectar las redes de diferentes empresas 

Ahora nos dirigimos la red virtual 1 para conectar las dos redes virtuales

###### Nota: en caso de no poder hacer la conexion entre las maquinas virtuales y las redes verificar pertenescan a la misma region

 


