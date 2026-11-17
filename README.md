# 📚 Guía Maestra Interactiva: Gestión de Desarrollo de Software

Plataforma educativa web interactiva y responsiva para el estudio y preparación de exámenes de la materia **Gestión de Desarrollo de Software** (Tecnicatura Universitaria en Programación - basada en Roger S. Pressman, *Ingeniería del Software: Un Enfoque Práctico*, 7ª Edición).

---

## 🚀 Contenido del Repositorio

- **`index.html`**: Portal Central con resumen ejecutivo, 4 calculadoras interactivas (AVG / EVM, PERT, ERD, VSM), buscador dinámico y simulador de preguntas de examen.
- **`unidad1.html`**: El Personal y el Proceso (Las 4 P, MOI, Equipos de alto rendimiento vs. Ambientes tóxicos, Paradigma Ágil y TP 1).
- **`unidad2.html`**: El Producto, el Proceso y el Proyecto (Ámbito, Matriz de Fusión Producto-Proceso, Principio W5-HH de Barry Boehm).
- **`unidad3.html`**: Métricas de Proceso, Proyecto y Producto (Medida vs Medición vs Métrica, Factores de McCall, Eficacia de Eliminación de Defectos $ERD$).
- **`unidad4.html`**: Estimación de Proyectos de Software (Personal, EIS, Reutilización, Estimación a 3 puntos PERT, Puntos de Función).
- **`unidad5.html`**: Calendario del Proyecto y Valor Ganado (Ley de Brooks, Ruta Crítica, Análisis de Valor Ganado $AVG/EVM$, Ejercicio 5 resuelto).
- **`unidad6.html`**: Administración del Riesgo (Incertidumbre + Pérdida, Matriz $5 \times 5$, Hoja HIR, Exposición al Riesgo $ER$).
- **`unidad7.html`**: Mantenimiento y Reingeniería (Regla 70/30, Ciclo de 6 fases, Ingeniería Inversa vs Adelante, Refactorización).
- **`unidad8.html`**: Mejoramiento del Proceso de Software (MPS, CMMI Niveles 1-5, Niveles de Inmadurez, Value Stream Mapping $VSM$).
- **`mobile.css`**: Hoja de estilos optimizada con Media Queries para visualización y uso táctil en celulares y tablets.
- **`server.js`**: Servidor estático local en Node.js (puerto 8080).
- **`GUIA_ESTUDIO_GESTION_DE_SOFTWARE.md`**: Guía teórica exhaustiva en formato Markdown.

---

## 📱 Diseño Responsivo para Celulares

- Adaptación automática para pantallas móviles (`max-width: 768px` y `max-width: 400px`).
- Soporte para deslizamiento táctil horizontal sin romper el ancho de pantalla en fórmulas KaTeX y diagramas Mermaid.
- Menú flotante y barras de navegación adaptadas al alcance del pulgar.

---

## 🛠️ Ejecución Local

Puedes abrir directamente `index.html` en cualquier navegador web moderno, o ejecutar el servidor Node.js incluido:

```bash
node server.js
```

Luego accede a: `http://localhost:8080`
