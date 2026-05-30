# Análisis de Patrones de Éxito en Videojuegos para la Tienda Online Ice

El objetivo principal de este proyecto fue identificar patrones y factores que permitan determinar si un videojuego tiene éxito o no dentro de la tienda online Ice. A través del análisis de datos históricos de ventas, plataformas, géneros y calificaciones de usuarios y críticos, se buscó obtener información valiosa que facilite la toma de decisiones estratégicas relacionadas con la comercialización y promoción de videojuegos.

### Limpieza y preparación de los datos
1. Se detectaron inconsistencias en los nombres de las columnas, incluyendo mayúsculas, espacios y formatos poco uniformes.
Solución: se estandarizaron los nombres utilizando minúsculas y formatos más legibles para facilitar el análisis.
2. El conjunto de datos contenía valores faltantes en algunas columnas importantes.
Solución: dependiendo del caso, los valores ausentes fueron reemplazados, eliminados o tratados cuidadosamente para evitar afectar el análisis.
3. Algunas columnas numéricas y de fechas estaban almacenadas como texto.
Solución: se corrigieron los tipos de datos para garantizar cálculos y visualizaciones precisas.

### Análisis exploratorio de datos
1. Se observó que los años con mayor cantidad de lanzamientos de videojuegos fueron: 2008 y 2009. Esto indica un período de alta producción y crecimiento dentro de la industria de los videojuegos.
2. Durante el análisis histórico de ventas y lanzamientos se identificaron los períodos de mayor popularidad de distintas plataformas:
  * PS2: auge entre 2001 y 2003, con un pequeño declive en 2002.
  * DS: auge entre 2005 y 2008, aunque presentó una disminución temporal en 2006.
  * PS3: auge en 2012.
  * WII: auge en 2009.
  * X360: auge en 2010.
Además, se determinó que la vida promedio de una plataforma es de aproximadamente 16 años.
3. Se realizaron gráficas comparativas para identificar las plataformas más rentables del mercado actual.
#### Plataformas más rentables del mercado actual:
![Ventas totales por plataformas](imagen/plataformas_rentables.png)

Los resultados muestran que PS4 es actualmente una de las plataformas más rentables.

4. Los géneros más rentables por región:
   ![Géneros más rentables](imagen/generos_rentables_region.png)

8. En Norteamérica las plataformas más importantes fueron: X360, PS2, WII, PS3 y Ds. Añadiendo que, los géneros más rentables fueron: Action, Sports, Shooter, Platform y Misc.
9. En Europa las plataformas más importantes fueron: PS2, PS3, X360, WII y DS; donde los géneros más rentables fueron: Action, Sports, Shooter, Rancing y Misc.
10. En Japón las plataformas más importantes fueron: DS, PS, PS2, SNES y DS y los géneros más rentables fueron: Role-Playing Action, Sports, Platform y Misc.
