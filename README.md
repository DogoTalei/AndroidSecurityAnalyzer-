![image_alt](https://github.com/DogoTalei/AndroidSecurityAnalyzer-/blob/c9a34d45a975054fb8a6c798692abf10ac60a628/dogo.png)
A continuación se detallan las funciones principales de la herramienta Android Security Analyzer:

1 Análisis de Integridad del Sistema: Verifica el modelo del dispositivo, la versión de Android y el estado de root y bootloader para detectar posibles modificaciones.
![image_alt](https://github.com/DogoTalei/AndroidSecurityAnalyzer-/blob/e931a377efa19f52abda8dd23ad28bf3e1507289/Screenshot_91.png)

2 Escaneo de Kernel: Identifica vulnerabilidades conocidas (CVEs) en el kernel del dispositivo para evaluar su seguridad.
![image_alt](https://github.com/DogoTalei/AndroidSecurityAnalyzer-/blob/e931a377efa19f52abda8dd23ad28bf3e1507289/Screenshot_92.png)

3 Análisis de SELinux: Revisa si SELinux está en modo Enforcing, lo que garantiza una política de seguridad estricta.

4 Verificación de Particiones: Comprueba si las particiones críticas están montadas como de solo lectura (RO) para prevenir escrituras no autorizadas.

5 Enumeración de Servicios Críticos: Lista los servicios del sistema importantes para la seguridad, como el keystore, para su posterior revisión.
![image_alt](https://github.com/DogoTalei/AndroidSecurityAnalyzer-/blob/4d2e002d2a2f89235cf95cd252ace5062ac41bbb/Screenshot_93.png)

6 Análisis de Parches de Seguridad: Evalúa la fecha del último parche de seguridad para determinar si el dispositivo está desactualizado y vulnerable.

7 Detección de Exploits Públicos: Busca vulnerabilidades con exploits conocidos que podrían ser utilizados para comprometer el dispositivo.
![image_alt](https://github.com/DogoTalei/AndroidSecurityAnalyzer-/blob/4d2e002d2a2f89235cf95cd252ace5062ac41bbb/Screenshot_94.png)

8 El programa está diseñado para diagnosticar una situación de emergencia de almacenamiento. La sobrecarga en las particiones del sistema es una condición crítica que puede llevar a fallos 
operativos,
![image_alt](https://github.com/DogoTalei/AndroidSecurityAnalyzer-/blob/4d2e002d2a2f89235cf95cd252ace5062ac41bbb/Screenshot_95.png)

9 Análisis de Puertos Abiertos: Escanea los puertos TCP/UDP para identificar conexiones activas y, si se usa una base de datos GeoIP, muestra la compañía propietaria de la IP.
![image_alt](https://github.com/DogoTalei/AndroidSecurityAnalyzer-/blob/4d2e002d2a2f89235cf95cd252ace5062ac41bbb/Screenshot_96.png)
![image_alt](https://github.com/DogoTalei/AndroidSecurityAnalyzer-/blob/4d2e002d2a2f89235cf95cd252ace5062ac41bbb/Screenshot_97.png)

10 Análisis de Batería: Extrae y muestra información útil sobre el estado de la batería del dispositivo.

11 Generación de Reporte: Compila todos los hallazgos en un informe detallado y lo guarda en un archivo de texto.
![image_alt](https://github.com/DogoTalei/AndroidSecurityAnalyzer-/blob/4d2e002d2a2f89235cf95cd252ace5062ac41bbb/Screenshot_98.png)

Uso
Para usar el programa, simplemente ejecuta el archivo AndroidSecurityAnalyzer desde la carpeta portable. La herramienta se encargará del resto del proceso.

Pasos para Activar la Depuración USB en Android

1. Activar el Modo de Desarrollador
Primero, deben ir a los Ajustes del dispositivo y encontrar la sección "Acerca del teléfono" o "Acerca del dispositivo". Una vez allí, buscarán un apartado llamado "Número de compilación" o "Versión de MIUI" (dependiendo de la marca del teléfono). Deben presionar sobre esta opción siete veces seguidas hasta que aparezca un mensaje indicando que el "Modo de desarrollador" está activado.
![image_alt](https://github.com/DogoTalei/Droid_X/blob/12faac3cdb1ea156827634fa4669a2f35f3920af/como-activar-opciones-desarrollador-movil-android-1958761.png)

2. Activar la Depuración USB
Después de activar el modo de desarrollador, regresarán al menú principal de Ajustes y buscarán una nueva opción llamada "Opciones de desarrollador". Dentro de este menú, deberán desplazarse hasta encontrar y activar la opción "Depuración USB".

![image_alt](https://github.com/DogoTalei/Droid_X/blob/7ceb0c3d94e7578f5cf2559ef12f277d4efdf0b4/samsung-activar-depuracion-usb.png)

Una vez que estos pasos estén completos, el usuario puede conectar su dispositivo a la computadora y ejecutar tu programa. Si aparece una ventana en el teléfono pidiendo autorización para la depuración USB, deberán aceptarla.
                ![image_alt](https://github.com/DogoTalei/Droid_X/blob/a89e15ac14776ca1c060a73500fe51396663c5b6/450_1000.png)

Demostración 




https://github.com/user-attachments/assets/f27666e3-480b-44cf-b549-31a59fc377de


