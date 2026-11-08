# Calendario de Mantención HTO-HTP

Página web que muestra el calendario de mantención (vista Calendario, Carta Gantt y Lista, con feriados).

## Cómo se actualiza
La página lee directamente el archivo `Calendario_Mantencion_2026_plantilla.xlsx` de este repositorio.
Para actualizarla, sube la nueva versión del Excel **con el mismo nombre**. GitHub Pages publica el cambio en 1 a 2 minutos.

## Reglas del Excel
- Hoja `Calendario 2026`: cada día tiene la celda de la actividad y, al lado, el código de área (TTMM, MMPP, GUAR, EYS, BOD, LOC, ELEC).
- Hoja `Feriados`: fecha, día, nombre y tipo (Nacional / Irrenunciable).
- No cambiar el nombre del archivo ni de las hojas.
