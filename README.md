# Taller Empleados

PWA operativa conectada al mismo backend de Taller Admin.

## Funciones conectadas
- Login individual
- Órdenes asignadas
- Cambio de estado
- Diagnósticos
- Trabajo en equipo
- Piezas utilizadas
- Evidencias (fotos/PDF)
- Actualización en tiempo real

## Acceso
El usuario del empleado se crea desde **Taller Admin > Empleados**. No existe registro público de empleados.

## Seguridad
Supabase Auth + Row Level Security. Cada técnico recibe únicamente las órdenes que tenga asignadas, salvo perfiles administrativos.
