# Sangam Digital Twin

Executive dashboard for Alcove's Sangam project: an interactive 3D digital twin (Three.js) with floor-wise status, budget vs committed vs actual cost, S-curve progress, procurement and cash-flow pipelines, and an auto-generated executive summary.

Runs on **demo data** shaped like the ERP master database (tower → floor → budget / committed / actual / status), until the ERP export is loaded.

Open `index.html` in a browser. It needs internet access for the CDN libraries (Three.js, ECharts, GSAP) and WebGL for the 3D view.
