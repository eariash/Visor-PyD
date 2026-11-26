# Visor de riesgo agroclimático de enfermedades (SENAMHI · SPA)

Página estática: `index.html` + `datos.json` + `departamentos.geojson`.
Se regenera en cada corrida con `Rscript R/04_correr.R` y `bash visor/publicar_github.sh`
desde la carpeta `operativo/` del proyecto Pest_Disease_Models5Km.

- Observado: API SENAMHI hasta las 14:00. Pronóstico: ETA 5 km, 4 días.
- Recomendaciones en borrador, pendientes de validación por la SPA.
