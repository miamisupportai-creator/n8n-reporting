# Guia de Setup — Reportes Automatizados

## Descripcion
Reporte semanal automatico con metricas del CRM. Corre cada lunes a las 8 AM, agrega datos de la semana, genera HTML profesional, y lo envia por email al cliente.

## Pasos
1. Importar `workflow.json` en n8n
2. Configurar credencial de Zoho CRM (OAuth)
3. Configurar credencial de Email (SMTP)
4. Reemplazar `${CLIENT_EMAIL}` con el email real del cliente
5. Activar el workflow

## Variables Configuradas
| Variable | Valor |
|----------|-------|
| CLIENT_ID | ${CLIENT_ID} |
| CLIENT_NAME | ${CLIENT_NAME} |
| CLIENT_EMAIL | ${CLIENT_EMAIL} |
| BUDGET | ${BUDGET} |

## Metricas del Reporte
- Total leads de la semana
- Leads calificados y convertidos
- Tasas de calificacion y conversion
- Fuente principal de leads
- Desglose por fuente

## Schedule
Cada **lunes a las 8:00 AM**.

## Soporte
contact@ai50m.com | ai50m.com
