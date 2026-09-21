# Laboratorio 3: Automatización de procesos de devolución con n8n
**Asignatura:** ICN-292 Sistemas de Información para la Gestión  
**Estudiante:** Michelle Medina Barra  
**RUT:** 21.832.400-2  
**Rol USM:** 202360506-9  
---
## Parámetros Asignados (Semilla S=400)
- **Umbral de monto (U):** $30.000 CLP  
- **Plazo máximo (D):** 7 días corridos  
---
## Estructura del Repositorio
- `ICN292-Lab3-Medina-Barra-triage.json`: Workflow principal de clasificación y triage de devoluciones (Parte A).
- `ICN292-Lab3-Medina-Barra-emisor.json`: Workflow secundario para emisión e iteración de solicitudes de prueba.
- `ICN292-Lab3-Medina-Barra-resumen.json`: Workflow programado (Schedule) para consolidación diaria de métricas (Parte B).
- `ICN292-Lab3-Medina-Michelle.pdf`: Informe final del laboratorio en formato PDF.
- `ICN292-Lab3-Medina-Michelle.docx`: Documento editable del informe final.
---
## Instrucciones de Reproducción
1. Importar los tres archivos `.json` en una instancia de n8n.
2. Activar el workflow de triage para habilitar la URL de producción del Webhook.
3. Actualizar la URL de destino en el flujo Emisor si corresponde.
4. Ejecutar el flujo Emisor para enviar el lote de 15 solicitudes de prueba.
