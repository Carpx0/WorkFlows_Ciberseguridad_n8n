# WorkFlows_Ciberseguridad_n8n
-Este repositorio está destinado a compartir **workflows de n8n** enfocados en:

- **Respuesta ante incidentes de seguridad**  
- **Automatización de tareas repetitivas** en procesos de ciberseguridad  
- **Integración con APIs de seguridad** (VirusTotal, AbuseIPDB, MISP, etc.)  
- **Análisis de indicadores de compromiso (IoCs)** como direcciones IP, dominios, URLs o hashes de archivos  

-El objetivo es proporcionar ejemplos prácticos y reutilizables que faciliten la construcción de entornos de **automatización de seguridad (SOAR)** utilizando n8n.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Instrucciones
1. Tener instalado **n8n** ([Repositorio_Oficial](https://github.com/n8n-io/n8n))
2. Descargar el **archivo.json** que quieras utilizar.
3. En n8n: **Import from File**.
4. Configura tu **API Key** de **VirusTotal** en el nodo HTTP Request (Para los flujos que utilicen VirusTotal).
5. Configura tu **email** en los nodos de Email (Para los flujos que utilicen Email).
