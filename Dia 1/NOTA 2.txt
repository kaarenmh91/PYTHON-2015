import numpy as np
print 'NumPy version: ', np.__version__

import matplotlib as mlib
print'Matplotlib version:', mlib.__version__

import sympy as sp
print 'SymPy version:', sp.__version__

import panda
s as pd
print 'Pandas version:', pd.__version__

import Android
from android import Android
android=Android()
android.ttsSpeak('hola')

https://github.com/kuri65536/python-for-android/releases

descargar el r26 
--EN SECCION DE DOWNLOAD
instalar el apk en el telefono


configurar una variable de entorno
agregar el sdk-adb
C:\Users\KMENDEZ.SEFIPLAN\AppData\Local\Android\sdk\platform-tools
cerrar todo
en una nueva notebook-
--!adb devices
--debe mostrar el nombre de mi dispositivo
!adb forward tcp:9999 tcp:43909 (puerto que tenemos en script monitor en el celular, barra de notificaciones, miguel)

descargar 
sl4a android.py poner esto en google y descargar primera linea
guardar archivo en el mismo directorio donte tengo la libreta de pytthon maestria. app de android python...

import android
!adb forward tcp:9999 tcp:39990
 
en el anaconda --
cd ruta de la carpetaa donde guarde mis archivos

set AP_PORT =9999
ipython notebook


en el celular
interpretes
start server
hacerlo publico
cheack pytthon

-------------------------------------------------------------

--EN LA CONSOLA anaconda

set AP_PORT=9999
ipython notebook

---------------------------------------------------------
EN EL CELULAR

ABRIR sl4a
START SERVER-
-PRIVADO
IR A NOTIFICACION DE QUE SE INICIO EL SERVIDOR
VER EL PUERTO.. ES EL PRIMERO
VERIFICAR QUE EL AP_PORT ESTA HABILIATDO EN EL NOTBOOOK
!echo  %AP_PORT%
debe salir 9999

!adb forward tcp:9999 tcp:39393
import android
doird=android.Android()
doird.makeToast("lania")
doird.ttsSpeak("HOLA BUENOS DIAS")

------

PARA CREAR LA VARIABLE DE ENTORNO ESTATICA Y NO TENER QUE ESTARLA CARGANDO

CREAR UNA NUEVA VARIABLE DE ENTORNO

--VERIFICAR QUE EL PUERTO ESTA DISPONIBLE
!echo %AP_PORT%





