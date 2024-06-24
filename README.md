<a id="presentacion"></a>
# iot_essentials
Repositorio del [IoT](https://edu.codigoiot.com/course/view.php?id=1042 "Ir al curso")

Aqui se suben los ejercicios del curso IoT
| Modulo | Ejercicio |
|:------------:|-------------:|
| Utilizacion R Pi | Prender LED |
| Acceso Vehicular | RFID |

## Contenidos
* [Introduccion](#presentacion)
* [Ejercicios incluidos](#incluidos)
* [Advertencias de uso](#advertencias)
<a id="incluidos"></a>
## Ejecicios incluidos 
1. Parpadear LED
    * Circuito Sujerido
    * Codigo para prender LED desde Python:
    ```python
    #No olvides el import
    import RPi.GPIO as GPIO
    pin=19
    GPIO.setmode (BOARD)
    ```
1. Lectura de tarjerta RFID
    * Requiere crear un ambiente de trabajo con:
    ```shell
    python -m venv <nombre_de_ambiente>
    source <nombre_de_ambiente>/bin/activate
    ```
    * Requiere las bibliotecas spidev mfrc552
    ```shell
    python -m pip install spidev
    python -pip install mfrc522
    ```
    * Consulta [rfid.py](./RFID/rfid.py) para mas info

<a id="advertencias"></a>
## Advertencia de uso
**Este codigo es experomental y de fines educativos** **Uselo bajo su propio riesgo**

<a id="pendientes"></a>
## To Do
- [X] Iniciar documentaciom
- [ ] Incorporar codigo del LED
- [ ] Ver grabaciones de IoT
- [ ] Hacer practicas