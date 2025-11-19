Componentes:

Objetivo: Asegurar compatibilidad con cambios en servicios externos (SMTP, OAuth), cumplimiento legal (protección datos) y actualizaciones de bibliotecas.

Alcance: Módulos de autenticación, integración de correo, validaciones, dependencias del servidor.

Actividades:

Monitoreo de librerías con vulnerabilidades (mensual).

Actualizaciones de adaptadores SMTP / OAuth (cuando proveedores cambien API).

Ajustes a requisitos legales (ej. conservación de datos, políticas de privacidad).

Frecuencia: Revisión mensual + adaptaciones bajo demanda.

Prioridades y SLA:

Crítico (rotura de autenticación/seguridad): 24h.

Alto (integración correo rota): 72h.

Medio (mejora menor por cambio de proveedor): 1-2 semanas.

Proceso: ticket → evaluación → implementación → pruebas → despliegue.

Registro: changelog en repo y nota en DRS_v2.

Recursos: 1 dev full-stack + 1 QA (part-time).

Métrica: tiempo medio de resolución (MTTR), número de incidentes mensuales.
