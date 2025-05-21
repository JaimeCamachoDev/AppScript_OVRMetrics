<header>


![image](https://github.com/user-attachments/assets/609fd8b8-58a6-4535-8905-492fdabf8666)

![AppScriptOVRMetrics-HojasdeclculodeGoogle-GoogleChrome2025-05-2114-21-06-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/907cf7bc-2a85-4ac0-8b9b-406ed122abf2)

# Tool_AppScript_OVRMetrics

_Script for OVR Metrics_

[Plantilla Google](https://docs.google.com/spreadsheets/d/1h8ZbjseN19Wsh2SDeQPGN5gP2F9hPnXVY85pLLXE1xw/copy)

---

## Descripción

Este proyecto permite analizar y visualizar de forma sencilla las métricas de rendimiento capturadas con la herramienta OVR Metrics en dispositivos Meta Quest. El flujo consiste en extraer los datos del visor, transferirlos al PC y luego analizarlos automáticamente en Google Sheets mediante un script de Apps Script, generando gráficas y resúmenes útiles.

## ¿Qué es OVR Metrics?

**OVR Metrics** es una herramienta para dispositivos Oculus/Meta Quest que registra información relevante sobre el rendimiento del visor, como el uso de CPU, GPU, tasa de frames, temperatura, entre otros. Este tipo de datos es esencial para desarrolladores de aplicaciones de realidad virtual que buscan optimizar el rendimiento de sus proyectos.

## Flujo de trabajo

1. **Captura de datos en Quest**  
   Utiliza la app OVR Metrics para registrar las métricas de tu visor. Los datos se guardan en:
   ```
   sdcard/Android/data/com.oculus.ovrmonitormetricsservice/files/CapturedMetrics/
   ```

2. **Transferencia al PC**  
   Conecta el Quest al PC y copia los archivos de métricas utilizando una herramienta como SideQuest.

3. **Importación en Google Sheets**  
   Sube el archivo de métricas (generalmente en formato CSV o similar) a una hoja de cálculo de Google.

4. **Aplicación del Apps Script**  
   Añade el script de este repositorio a tu hoja de Google Sheets. El script:
   - Limpia y organiza los datos automáticamente.
   - Analiza las métricas recogidas.
   - Genera gráficas y resúmenes visuales para facilitar el análisis.

## ¿Cómo usar este repositorio?

1. Extrae tus métricas siguiendo los pasos anteriores.
2. Sube el archivo a Google Sheets.
3. Copia el Apps Script de este repositorio y pégalo en el editor de Apps Script de tu hoja.
4. Ejecuta el script para limpiar, analizar y visualizar los datos.

---

¿Quieres que añada instrucciones más detalladas (por ejemplo, cómo pegar el script en Google Sheets) o lo dejo así de conciso?
