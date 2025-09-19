![image_alt](https://github.com/DogoTalei/AndroidSecurityAnalyzer-/blob/c9a34d45a975054fb8a6c798692abf10ac60a628/dogo.png)
A continuación se detallan las funciones principales de la herramienta Android Security Analyzer:

1 Análisis de Integridad del Sistema: Verifica el modelo del dispositivo, la versión de Android y el estado de root y bootloader para detectar posibles modificaciones.

2 Escaneo de Kernel: Identifica vulnerabilidades conocidas (CVEs) en el kernel del dispositivo para evaluar su seguridad.

3 Análisis de SELinux: Revisa si SELinux está en modo Enforcing, lo que garantiza una política de seguridad estricta.

4 Verificación de Particiones: Comprueba si las particiones críticas están montadas como de solo lectura (RO) para prevenir escrituras no autorizadas.

5 Enumeración de Servicios Críticos: Lista los servicios del sistema importantes para la seguridad, como el keystore, para su posterior revisión.

6 Análisis de Parches de Seguridad: Evalúa la fecha del último parche de seguridad para determinar si el dispositivo está desactualizado y vulnerable.

7 Detección de Exploits Públicos: Busca vulnerabilidades con exploits conocidos que podrían ser utilizados para comprometer el dispositivo.

8 El programa está diseñado para diagnosticar una situación de emergencia de almacenamiento. La sobrecarga en las particiones del sistema es una condición crítica que puede llevar a fallos operativos,

9 Análisis de Puertos Abiertos: Escanea los puertos TCP/UDP para identificar conexiones activas y, si se usa una base de datos GeoIP, muestra la compañía propietaria de la IP.

10 Análisis de Batería: Extrae y muestra información útil sobre el estado de la batería del dispositivo.

11 Generación de Reporte: Compila todos los hallazgos en un informe detallado y lo guarda en un archivo de texto.
