# Presupuestos de imprenta

App web de un solo archivo (`index.html`) para calcular y entregar presupuestos de una imprenta.

## Qué calcula

- Papel (precio por resma y hojas por resma) y otros materiales, con porcentaje de desperdicio
- Mano de obra: costo semanal y horas por semana de cada empleado, convertido a costo por hora
- Luz de cada máquina (kW × horas × precio del kWh)
- Consumibles: toner, tinta, film o grapas, por página
- Gastos fijos prorrateados por hora de trabajo
- Ganancia sobre el costo e IVA
- Presupuesto para el cliente en PDF, con el logo y los colores de la imprenta

## Cómo usarla

1. Abrí `index.html` en el navegador (o publicá el repositorio con GitHub Pages).
2. Cargá los costos del negocio en las pestañas Equipo, Papel, Máquinas y Gastos.
3. Armá cada presupuesto en la pestaña Presupuesto, paso a paso.
4. Guardalo, mandalo por WhatsApp o usá "Imprimir / PDF" y elegí "Guardar como PDF".

## Datos

Los datos se guardan en el navegador de cada dispositivo (`localStorage`). No se comparten entre equipos y se pierden si se borran los datos del sitio.
