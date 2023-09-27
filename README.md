# Proyecto H1N1 and Seasonal Flu Vaccines

Proyecto para el curso Inteligencia Artificial para las Ciencias e Ingenierías.

En este proyecto, abordaremos el desafío de prever la probabilidad de que las personas sean vacunadas contra el virus H1N1 y la gripe estacional, lo cual es crucial en el ámbito de la salud pública para combatir enfermedades infecciosas y prevenir su propagación. 

## Desarrollado por:
Marisol Correa Gutiérrez - 1007223653 - Bioingeniería

Manuela Ospina Giraldo - 1007232820 - Bioingeniería

Eliana Salas Villa - 1193579584 - Bioingeniería

## Enlace a la fuente de los datos usados: 
https://www.kaggle.com/datasets/arashnic/flu-data

## Datos:
Para acceder al dataset desde Google colab, siga los siguientes pasos:

1.Ingrese al enlace de la fuente de datos.

2.Pulse el botón 'Download' de la derecha.

3.Cargue el archivo zip al entorno de Colab, ya sea arrastrándolo al visor de archivos (deberá repetirlo cada vez que acceda al notebook) o guardándolo en su Drive y cargándolo mediante la ruta. Para cualquiera de las opciones, ejecute los comandos:

! unzip path/to/data.zip .

Eso descomprimirá el archivo csv en la carpeta actual. Para leerlo ejecute el comando:

import pandas as pd

df = pd.read_csv('path/to/data.csv')

Ahora puede trabajar con el DataFrame 'df' en su notebook
