# Análisis de Salud Mundial

**Autor:** Angel David Diaz Pinilla

---

## Descripción del Dataset

El dataset `salud_mundial.csv` contiene indicadores de salud de **159 países** alrededor del mundo, incluyendo esperanza de vida, gasto en salud, mortalidad infantil y cobertura de vacunación.

| Columna | Descripción |
|---|---|
| `pais` | Nombre del país |
| `region` | Continente o región geográfica |
| `nivel_ingresos` | Nivel económico: Low, Medium, High, Very High |
| `esperanza_vida` | Esperanza de vida al nacer (años) |
| `gasto_salud_usd` | Gasto per cápita en salud (USD/año) |
| `mortalidad_infantil` | Muertes por cada 1,000 nacidos vivos |
| `medicos_por_1000` | Médicos por cada 1,000 habitantes |
| `poblacion_urbana_pct` | % de población que vive en zonas urbanas |
| `obesidad_pct` | % de la población con obesidad |
| `diabetes_pct` | % de la población con diabetes |
| `tabaquismo_pct` | % de fumadores |
| `camas_hospital_por_1000` | Camas hospitalarias por 1,000 hab. |
| `vacunacion_pct` | % de cobertura de vacunación |

**Fuente:** Indicadores del Banco Mundial / OMS.

---

## Cómo ejecutar el notebook

1. Clona el repositorio
```bash
git clone https://github.com/Angel-D28/Taller_integrador1..git
```


3. Instala las dependencias
```bash
pip install pandas numpy matplotlib seaborn jupyter
```



---

##  Hallazgos principales

1. **Brecha por ingresos** — los países con nivel de ingresos *Very High* tienen una esperanza de vida promedio superior a 80 años, mientras que los países *Low* no superan los 60 años.

2. **Europa lidera** en esperanza de vida promedio por región, mientras que África registra los valores más bajos junto con la mayor mortalidad infantil.

3. **El gasto en salud no garantiza buenos resultados** — algunos países con gasto medio tienen mejores indicadores de vacunación que países con gasto alto, sugiriendo que la eficiencia importa tanto como la inversión.

---

## Tecnologías usadas

![Python]
![Pandas]
![Jupyter]
![Git]

| Tecnología | Uso |
|---|---|
| Python | lenguaje principal |
| Pandas | limpieza y análisis de datos |
| Jupyter Notebook | desarrollo interactivo |
| Git / GitHub | control de versiones |

---

##  Estructura del proyecto
```
taller_integrador/
│
├── salud_mundial.csv
├── taller_modulo1.ipynb
└── README.md
```
