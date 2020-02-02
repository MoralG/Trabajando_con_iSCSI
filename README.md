# Trabajando con iSCSI

![iSCSI](image/iSCSI.jpg)

#### Vamos a configurar un sistema que exporte algunos targets por iSCSI y los conecte a diversos clientes.

### [Tarea1](https://github.com/MoralG/Trabajando_con_iSCSI/blob/master/Trabajando_con_iSCSI.md#tarea-1)
Crearemos un target con una LUN y lo conectaremos a un cliente GNU/Linux. ¿Cómo escaneamos desde el cliente buscando los targets disponibles y utilizando la unidad lógica proporcionada?, formateándola si es necesario y montándola.

### [Tarea2](https://github.com/MoralG/Trabajando_con_iSCSI/blob/master/Trabajando_con_iSCSI.md#tarea-2)
Vamos a utilizar systemd mount para que el target se monte automáticamente al arrancar el cliente.

### [Tarea3](https://github.com/MoralG/Trabajando_con_iSCSI/blob/master/Trabajando_con_iSCSI.md#tarea-3)
Crearemos un target con 2 LUN y autenticación por CHAP y la conectaremos a un cliente windows. ¿Cómo se escanea la red en windows y cómo se utilizan las unidades nuevas (formateándolas con NTFS)?
