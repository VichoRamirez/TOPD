✅❌
Revisar y refinar la pregunta de investigación✅
- ¿Es clara y medible? ¿Requiere ajustes tras la primera exploración?✅
    ¿Cuáles son las variables clave que permiten construir un modelo predictivo de la duración de la estancia hospitalaria de un paciente, y con qué precisión dicho modelo puede estimar ese tiempo de estancia?

Seleccionar al menos 3 variables clave del dataset y analizarlas:✅✅✅✅
    Variable objetivo: "DIAS_ESTANCIA"
    Variables Independientes Tentativas: "HOSPITAL", "IR_29301_MORTALIDAD", "IR_29301_SEVERIDAD"
- Medidas de tendencia central y dispersión (mean(), median(), std(), etc.).✅✅✅✅
- Distribuciones (histogramas, boxplots).✅✅✅✅
- Correlación entre variables numéricas (.corr() o np.corrcoef).✅✅✅✅

Realizar comparaciones por subgrupo:✅
- Ejemplo: sexo, grupo etario, servicio de salud, tipo de ingreso.✅
- Tablas agregadas (groupby().agg()) y visualizaciones con matplotlib.✅

Interpretar hallazgos preliminares:✅
- Hipótesis refinadas basadas en patrones observados.✅

Selección justificada de variable objetivo (ej: DIAS_ESTANCIA limpio, TIPOALTA, subconjunto por diagnóstico)✅

Ingeniería de variables y selección de features:✅
- Justificar por qué ciertas variables podrían ser útiles para predecir la variable objetivo.✅
- Identificar correlaciones, redundancias o valores extremos.✅

Preparación de datos:✅
- Limpieza, tratamiento de nulos, codificación categórica si corresponde (get_dummies, etc.).✅
- Generación de nuevas variables si son relevantes para el fenómeno (edad categorizada, ratios, etc.).✅

Exploración visual y justificación del enfoque:❌
- Visualizaciones multivariadas para entender relaciones clave.✅
- Reflexión sobre qué modelo sería apropiado y por qué, sin implementarlo aún.❌
