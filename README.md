# ¡Hola! Soy Matías Zúñiga 👋

**Ingeniero Civil Metalúrgico** y estudiante del **Magíster en Ciencia de Datos (Universidad de Chile)**.
Investigador en **ALGES–AMTC (U. de Chile)**, donde trabajo en modelamiento avanzado de variables para minería.

Me muevo en la intersección entre **procesos mineros, sensores y modelos probabilísticos**.

---

## 🔬 Líneas de trabajo

### Estimación probabilística en baterías de litio *(tesis de magíster)*
Estimación de **estado de carga (SoC)** y **estado de salud (SoH)** a partir solo de voltaje, corriente y temperatura, donde ambas son variables latentes.
El foco es la **transferibilidad entre químicas** (NMC, LFP, LCO) con incertidumbre calibrada, usando modelos electroquímicamente informados:

- **EKF** sobre modelo de circuito equivalente (ECM) con curva OCV fija por química.
- **SMC / filtro de partículas** con química latente y OCV adaptativa.
- Validación **LOCO** (*leave-one-chemistry-out*) para medir el costo real de la universalidad.

### Visión hiperespectral en minería del cobre
- **Seguimiento de minerales sobre correas transportadoras** con cámaras hiperespectrales y **aprendizaje no supervisado** (clustering, métricas de teoría de la información).
- **Generación de imágenes hiperespectrales sintéticas** (mezclas Dirichlet, modelo de *dead leaves*) para evaluar la robustez de los modelos.
- **Información mutua espacial (SMI)** vía interpolación por ensamble y procesos de Mondrian, aplicada a selección de bandas y clasificación espectral-espacial.
- Análisis de **rareza de muestras** comparando distribuciones de píxeles con divergencia de **Jensen–Shannon**.

### Modelamiento de procesos y prototipado
- **Modelos predictivos de variables metalúrgicas** y de *throughput* de planta a partir de variables geometalúrgicas (F80, granulometría, dureza AxB, Bond work index).
- Desarrollo de **prototipos completos**: mecánica, electrónica y software, con documentación técnica (Onshape, BOM, guías de armado).

---

## 🧪 Proyectos destacados

**Stochastic Imaging Spectroscopy (SIS)** — línea de espectroscopía estocástica desarrollada por nuestro equipo en ALGES–AMTC.

**Sample Auditor** — herramienta para comparar distribuciones de píxeles y detectar muestras atípicas mediante Jensen–Shannon.

**Scanner hiperespectral para correa transportadora** — diseño e integración de un equipo de medición en línea sobre cinta, pensado para operar en condiciones de faena y permitir mantención sin detener la producción.

**Maqueta instrumentada de equipos LHD** — sistema en escala con control de movimiento, sensores de posición y lógica de operación programada, usado como banco de pruebas.

---

## 🛠️ Stack

**Lenguajes** · Python, C/C++ (Arduino), Git

**ML / DS** · NumPy, Pandas, Scikit-learn, SVM, árboles y *boosting*, validación cruzada, SHAP, UMAP / t-SNE / Isomap, Matplotlib, Plotly

**Métodos probabilísticos** · Filtro de Kalman extendido (EKF), Monte Carlo secuencial, teoría de la información (entropía, información mutua, Jensen–Shannon)

**Visión hiperespectral** · Segmentación, vectorización de parches, *Spectral Angle Mapper* (SAM), selección de bandas

**Mecatrónica** · Servos y motores paso a paso, sensores, integración con PLC / ESP / Arduino

**CAD y fabricación** · Onshape, impresión 3D (Bambu Lab, Orca Slicer), flujo DXF → CAD, BOM y guías de armado

---

## 📫 Contacto

- 📧 **Email:** mzuniga@alges.cl
- 💼 **LinkedIn:** [linkedin.com/in/mizv](https://www.linkedin.com/in/mizv)
- 🐙 **GitHub:** [@mzuniga10](https://github.com/mzuniga10)
