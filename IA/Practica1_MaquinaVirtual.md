# Maquina Virtual
--- 
### Objetivo
- Crear dos maquinas virtuales, una dentro de la otra
### Caracteristicas de una maquina virtuales
![Caracteristicas de una Maquina Virtual]()
### Procedimiento
1. Ingresar a la pagina de los [Servicios de Azure](https://portal.azure.com/#home) 
2. Buscar el servicio de Maquinas Virtuales
3. Crear una Maquina Virtual de Azure
    ![Maquina Virtual de Azure]()
4. Llenar los datos solicitados y crear 
    ![Crear Maquina Virtual]()
5. Crear otra maquina virtual con las mismas caracteristicas pero con diferente nombre (asegurarse que esten en la misma Red virtual y de preferencia que el grupo de seguridad sea basico). 
    ![Maquinas Virtuales]()
6. Conectar una de las maquinas virtuales a RDP
    ![Conectar RDP]()
    Descargar el archivo RDP
    ![Descargar archivo RDP]()
7. Abrir el archivo RDP con el programa Escritorio remoto de Microsoft (nombre y usuario el que se utilizo al crear el recurso).
![Maquina Virtual en Escritorio remoto de Microsoft]()
8. Abrir el progrmaa PowerShell como administrador en la primera maquina virtual. 
9. Ingresar el siguiente comando mstsc /v:10.0.0.7 
La version se obtuvo de la maquina virtual secundaria en la parte Direccion de IP Privada 
![Direccion de IP Privada]()
Nos pedira el usuario y contraseña que ingresamos al crear la maquina virtual
10. Se abrira la seguanda maquina virtual en la maquina virtual es decir que tenemos una maquina virtual dentro de una maquina virtual.
![Maquina Virtual dentro de una maquina virtual]()