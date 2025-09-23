# Análisis de Archivo con VirusTotal

-Este workflow **automatiza el análisis de archivos** recibidos por correo en Gmail:

1. **Toma el archivo** adjunto del último **correo recibido**.  
2. Lo envía a **VirusTotal** para su análisis.  
3. **Espera 20 segundos** para obtener los resultados.  
4. **Envía un correo** con un **resumen del análisis**:  
   - Si algún motor lo marca como **malicioso**, el informe incluye:  
     - **Nombre de los motores** que lo detectaron  
     - **Tipo de malware** identificado  
     - **Categoría** (ej. 'malicious')
   <img width="376" height="56" alt="image" src="https://github.com/user-attachments/assets/42daeed8-7cce-44bb-ab0c-98c764e33243" />
   
   **-NOTA:** El **nodo 'Code'** contiene un **script en Python** que **organiza la información recibida de VirusTotal** para hacer el resumen que se envía por correo.

    - **Si ningún motor lo detecta como malicioso**, recibiremos el mensaje:  --> 'Ningún motor marcó el archivo como malicious'.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Requisitos
- Credenciales de VirusTotal (API key)
- Cuenta de Gmail configurada en n8n
