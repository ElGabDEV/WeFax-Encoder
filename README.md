@'

\# WEFAX Encoder (120/576)



Este es un script en Python diseñado para convertir cualquier imagen (PNG, JPEG) en un archivo de audio `.wav` codificado bajo el estándar internacional \*\*WEFAX 120 / IOC 576\*\* (Radiofacsimile de HF). 



El archivo de audio generado simula una transmisión real de onda corta y puede ser decodificado por software de radioafición como \*Fldigi\*, \*MultiFAX\*, \*JVComm32\* o aplicaciones móviles de HF-FAX mediante acoplamiento acústico.



\## Estructura del Proyecto



Para que el script funcione correctamente, se recomienda mantener la siguiente organización de archivos en la carpeta de tu proyecto:

(por cierto si tienes pereza solo escribe python wefaxencoder.py imeages\ACAELNOMBREDELAFOTO, aguanta png y jpg los demas no recuerdo jeje) 

para funcionar requiere estos aca te dejo el comando:
pip install pillow numpy scipy

```text

wefaxencoder/

&#x20; ├── wefaxencoder.py     # Script principal del codificador

&#x20; ├── README.md           # Instrucciones de uso

&#x20; ├── LICENSE             # Licencia del proyecto (MIT)

&#x20; └── imeages/            # Carpeta para almacenar las imágenes a codificar

&#x20;       └── test.png      # Imagen de muestra

