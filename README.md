#git clone#
Con este comando puedes obtener una copia de un repositorio existente. Con éste recibes una copia de casi todos los datos que tiene el servidor, cada versión de cada archivo de la historia del proyecto es descargada por defecto cuando ejecutas *git clone*.

#git pull#
Incorpora los cambios de un repositorio remoto a la rama actual. El comando *git pull* es básicamente una combinación de los comandos *git fetch* y *git merge*, donde Git descargará desde el repositorio remoto especificado y a continuación, de forma inmediata intentará combinarlo en la rama en la que te encuentres.

#git fetch#
El comando *git fetch* comunica con un repositorio remoto y obtiene toda la información que se encuentra en ese repositorio que no está en el tuyo actual y la almacena en tu base de datos local.

#Diferencia entre git fetch y git pull#
La diferencia clave entre git fetch y pull es que git pull copia los cambios desde un repositorio remoto directamente a su directorio de trabajo, mientras que git fetch no lo hace. El comando git fetch solo copia los cambios en su repositorio de Git local. El comando git pull hace ambas cosas.
Si su espacio de trabajo no tiene archivos no confirmados y desea copiar los últimos cambios desde un repositorio remoto directamente a su directorio de trabajo, ejecute el comando git pull .
Si desea extraer los últimos cambios de un repositorio remoto sin sobrescribir nada en su directorio de trabajo, utilice git fetch y luego realice un git merge cuando sea el momento adecuado.