# EL COSMOS ARQUITECTÓNICO: APROVECHANDO LAS COSMOGONÍAS JERÁRQUICAS PARA RESOLVER LA ANOMALÍA DE LA MATERIA OSCURA Y EL BIG BANG MEDIANTE DINÁMICAS DEPENDIENTES DE LA ESCALA

**Mauricio Rivadeneira (1*), Colaborador de Investigación de IA (2)**
(1) Investigador Independiente, Unidad de Simulación Avanzada de Física Computacional
*Contacto: maurivadeneira@gmail.com
**Octubre de 2026 — Versión 9.0 (Con Script Ejecutable Verificable de Bessel, Datos Primarios de Eilers et al. 2019 y Auditoría Reproducible)**

> "Entregamos este manuscrito del Cosmos Arquitectónico como un andamio en construcción que nos permita aumentar la comprensión de nuestro universo majestuoso e inconmensurable; un cosmos infinito, estructurado y eterno."

---

## RESUMEN

Presentamos la formulación de un modelo fenomenológico explícito dependiente de la escala y un programa de pruebas falsables orientados a evaluar si las anomalías atribuidas a entidades inobservables (materia y energía oscuras) pueden describirse mediante una regla constitutiva de transición en regímenes de aceleración ultrabaja. Partiendo del parámetro crítico de aceleración ($a_0 = 1,20 \times 10^{-10}\ \text{m/s}^2$, convergente en su límite asintótico con la dinámica de Milgrom) y fijando la función de transición racional única $\mu(x) = \frac{x}{1+x}$, derivamos una solución algebraica cuadrática cerrada que conecta continuamente el régimen newtoniano ($1/r^2$) con el régimen asintótico de vórtice o remolino ($1/r$). En la Vía Láctea, implementando un modelo bariónico explícito y uniforme en todo el documento —compuesto por un bulbo esferoidal de Hernquist ($M_b = 1,00 \times 10^{10}\ M_\odot$, radio de escala $a_b = 0,60\ \text{kpc}$) más un disco exponencial de Freeman ($R_d = 2,60\ \text{kpc}$, evaluado en tres perfiles paramétricos: Rama A con $M_d = 4,50 \times 10^{10}\ M_\odot$, Perfil Central C con $M_d = 5,00 \times 10^{10}\ M_\odot$ y Rama B con $M_d = 5,50 \times 10^{10}\ M_\odot$)—, generamos mediante un único código reproducible en Python (`scipy.special`, incluido en el Anexo Técnico) la curva de rotación radial entre $r = 5,0\ \text{kpc}$ y $r = 25,0\ \text{kpc}$, contrastándola de forma separada frente a las mediciones discretas primarias de la Tabla 1 de Eilers et al. (2019) y su recta paramétrica secundaria. Bajo este presupuesto fenomenológico algebraico (que no equivale a resolver la ecuación de Poisson no lineal ni demuestra por sí mismo la inexistencia de materia oscura en todas las escalas), el Perfil Central C arroja velocidades de $228,7\ \text{km/s}$ en $5,0\ \text{kpc}$, $231,4\ \text{km/s}$ en $6,0\ \text{kpc}$, $230,2\ \text{km/s}$ en la posición solar $r_\odot = 8,0\ \text{kpc}$ (frente a $229,0\ \text{km/s}$ de referencia), $224,9\ \text{km/s}$ en $10,0\ \text{kpc}$, $219,6\ \text{km/s}$ en $12,0\ \text{kpc}$, $207,4\ \text{km/s}$ en $16,0\ \text{kpc}$, $199,6\ \text{km/s}$ en $20,0\ \text{kpc}$ y $193,6\ \text{km/s}$ en $25,0\ \text{kpc}$ (frente a la medición primaria de $198,42^{+6,12}_{-6,50}\ \text{km/s}$ en $R = 24,82\ \text{kpc}$ de Eilers et al., 2019).

A escala de galaxias espirales y cúmulos esferoidales modelados bajo equilibrio hidrostático isotrópico de Jeans, mantenemos la partición contable $M_t = M_c + M_r$ definiendo su equivalencia operacional separada por población ($M_c \equiv M_{\text{BH}}$ para el agujero negro central en galaxias 2D; $M_c \equiv M_{\text{BCG}}$ para la masa estelar de la galaxia central dominante en cúmulos 3D; y $M_t \equiv M_{\text{bar}}$ o $M_{\text{dyn,ef}}$ según el régimen), planteando como conjetura empírica de trabajo que la razón $M_c / M_t$ se mantiene por debajo del $1\%$ en cada población. A escala macrocósmica, evaluamos como extrapolación condicional la relación asintótica $M_t = v_f^4 / (G \cdot a_0)$ adoptando un parámetro de masa definido $M_{N1} = 1,00 \times 10^{21}\ M_\odot$ y explorando la proporción $N_7$ ($M_{t(N7)} = 7,00 \times 10^{21}\ M_\odot$), cuya consecuencia algebraica es $v_f = 102.760 \approx 103.000\ \text{km/s}$ ($0,343c$, $\gamma = 1,0645$, requiriendo formulación relativista para su interpretación física) y $r_t = 9.310\text{ millones de años luz}$. Finalmente, formulamos como hipótesis exploratorias no validadas un ciclo de respiración radial ($T = 2.000\text{ millones de años}$) y una atenuación fotónica secular, proponiendo una descomposición fenomenológica del parámetro de Hubble en un escalar disipativo ($H_\gamma$) más la proyección de un campo vectorial de respiración radial ($\vec{H}_{\text{cin}}$) con dirección prefijada, sujeto a pruebas cosmológicas decisivas pendientes.

---

## Nota Metodológica: Sinergia Cognitiva y Demarcación Epistemológica

El presente manuscrito es el resultado de un modelo de investigación aumentada, donde la dirección conceptual, el establecimiento de los axiomas topológicos y la validación lógica final son autoría exclusiva del investigador principal. El desarrollo del trabajo contó con la integración activa de Inteligencia Artificial Avanzada operando como colaborador analítico en la estructuración de registros astronómicos, auditoría algebraica y programación reproducible.

Establecemos una demarcación estricta en todo el documento entre tres niveles epistemológicos:
1. **Consecuencias Algebraicas y Numéricas Reproducibles:** Deducciones matemáticas cerradas y evaluaciones computacionales exactas obtenidas a partir de la función racional $\mu(x) = x/(1+x)$ y del potencial newtoniano de las geometrías especificadas (Secciones 1.4, 2.1, 2.2, 3.1, 3.4 y script del Anexo Técnico).
2. **Contrastes Empíricos Preliminares:** Comparaciones descriptivas sobre sistemas astronómicos específicos (curva radial de la Vía Láctea entre $5,0\text{ y }25,0\ \text{kpc}$ frente a los datos primarios de Eilers et al., 2019; tres galaxias ilustrativas del catálogo SPARC; y estimaciones condicionales en dos cúmulos) que muestran compatibilidad preliminar sin reclamar la demostración de una teoría gravitatoria fundamental.
3. **Hipótesis Cosmológicas Exploratorias:** Postulados arquitectónicos —la conjetura poblacional $M_c / M_t < 0,01$, la extrapolación condicional $N_7$, el ciclo respiratorio de $2.000\text{ millones de años}$ y la hipótesis de atenuación fotónica— que se presentan estrictamente como propuestas abiertas sujetas a refutación observacional (Capítulos 4, 5, 6 y 7).

---

# CAPÍTULO 1: EXPERIMENTO HEURÍSTICO INICIAL Y DEFINICIÓN DEL MODELO ALGEBRAICO DE ESCALA

## 1.1. Experimento Heurístico Preliminar: Regresión Simbólica Conceptual
Como motivación heurística para iniciar esta investigación, se planteó un ejercicio conceptual basado en regresión simbólica penalizada por complejidad (criterio de parsimonia tipo Navaja de Ockham): ilustrar cómo, a partir de tablas sintéticas de variables mecánicas locales —masa ($m$), aceleración ($a$), fuerza ($F$) y distancia ($d$)—, la minimización de error cuadrático converge hacia las expresiones algebraicas base de la dinámica clásica:

1. **La Segunda Ley del Movimiento:**

$$F = m \cdot a \quad (1)$$

2. **La Ley Inversa del Cuadrado en el Régimen Local:**

$$F = G \cdot \frac{m_1 \cdot m_2}{d^2} \quad (2)$$

*(Alcance metodológico: Este ejercicio heurístico no implica una recuperación independiente de las leyes físicas, sino el antecedente conceptual que condujo a formular la pregunta de investigación del manuscrito: definir una relación constitutiva algebraica de un solo parámetro sobre la Ecuación 2 capaz de describir las curvas de rotación planas en el régimen de baja aceleración).*

## 1.2. Dominios de Aplicación de las Aproximaciones Gravitacionales
Cualquier modelo fenomenológico de escala debe preservar la física verificada en regímenes de alta aceleración. Distinguimos tres dominios operativos:

- **Régimen Newtoniano Clásico ($a \gg a_0$, $v \ll c$):** Describe con precisión la dinámica terrestre y las efemérides planetarias del Sistema Solar.
- **Régimen Relativista de Campo Fuerte ($G M / (r c^2) \sim 1$ o $v \to c$):** Descrito por la Relatividad General de Einstein en las cercanías de objetos compactos, deflexión lumínica, corrimiento al rojo gravitacional y ondas gravitacionales.
- **Régimen Galáctico de Aceleración Ultrabaja ($a \lesssim a_0$):** En las periferias de las galaxias de disco, donde la aceleración gravitatoria newtoniana calculada a partir de la materia bariónica visible desciende a valores del orden de $\sim 10^{-10}\ \text{m/s}^2$, las velocidades circulares observadas se mantienen aproximadamente constantes en lugar de exhibir el decaimiento kepleriano ($\propto r^{-1/2}$).

## 1.3. La Anomalía de Rotación Galáctica y el Parámetro Crítico ($a_0$)
En las regiones externas de los discos galácticos, la tendencia hacia una velocidad tangencial constante ($v(r) \approx v_f$) configura una cinemática análoga a la de un vórtice o remolino estacionario. Frente a esta diferencia entre el campo newtoniano bariónico y la cinemática observada, el modelo estándar ($\Lambda\text{CDM}$) postula halos de materia oscura no bariónica. En ausencia de detecciones directas confirmadas de partículas exóticas, exploramos el enfoque fenomenológico alternativo: parametrizar la transición dinámica mediante una escala crítica de aceleración:

$$a_0 = 1,20 \times 10^{-10}\ \text{m/s}^2$$

Reconocemos formalmente que este umbral y su límite asintótico corresponden a la Dinámica Newtoniana Modificada (MOND), propuesta por Mordehai Milgrom en 1983, y reproducen la pendiente de la Relación Bariónica de Tully-Fisher. La contribución de este capítulo consiste en fijar una función de transición única para evaluar numéricamente perfiles radiales completos y explorar después sus extrapolaciones condicionales.

## 1.4. Definición del Modelo Algebraico y Delimitación frente a una Teoría de Campo General
Definimos explícitamente las ecuaciones constitutivas del modelo fenomenológico empleado en este trabajo:

1. **Función de transición racional única $\mu(x)$:** Adoptamos para todos los cálculos la función de interpolación simple de variable adimensional $x = a / a_0$:

$$\mu\left(\frac{a}{a_0}\right) = \frac{\frac{a}{a_0}}{1 + \frac{a}{a_0}} = \frac{a}{a + a_0} \quad (3)$$

2. **Presupuesto Fenomenológico Algebraico Local:** Relacionamos la aceleración cinemática centrípeta en el plano ecuatorial ($a(r) = v^2(r) / r$) con la magnitud de la aceleración gravitatoria newtoniana exacta producida por la distribución bariónica ($g_N(r)$) mediante la relación constitutiva local:

$$F \cdot \mu\left(\frac{a}{a_0}\right) = m \cdot g_N(r) \quad \Longleftrightarrow \quad m \cdot a \cdot \left(\frac{a}{a + a_0}\right) = m \cdot g_N(r) \quad (4)$$

Al cancelar la masa de prueba ($m$), la Ecuación (4) arroja el polinomio cuadrático $a^2 - g_N \cdot a - g_N \cdot a_0 = 0$, cuya raíz física positiva define la **Ecuación Maestra de Aceleración Algebraica**:

$$a(r) = \frac{g_N(r)}{2} \left(1 + \sqrt{1 + \frac{4 a_0}{g_N(r)}}\right) \quad (5)$$

Sus límites asintóticos son:
- **Alta aceleración ($g_N \gg a_0$):** $4 a_0 / g_N \to 0 \implies a(r) \to g_N(r)$.
- **Baja aceleración profunda ($g_N \ll a_0$):** A grandes radios donde domina el término monopolar ($g_N(r) \approx G M_t / r^2$ y $4 a_0 / g_N \gg 1$), la Ecuación (5) converge a:

$$a_{\text{prof}}(r) = \sqrt{g_N(r) \cdot a_0} = \frac{\sqrt{G \cdot M_t \cdot a_0}}{r} \quad \implies \quad F_{\text{prof}} = m \frac{\sqrt{G \cdot M_t \cdot a_0}}{r} \quad (6)$$

**Delimitación teórica entre el presupuesto algebraico y una teoría de campo conservativa:**
Dejamos explícitamente establecido que la identificación algebraica local $a\,\mu(a/a_0) = g_N$ (Ecuaciones 4 y 5) sólo constituye una solución exacta de una teoría de campo gravitatoria conservativa (como la ecuación de Poisson no lineal de Bekenstein & Milgrom, 1984: $\nabla \cdot [\mu(|\nabla\Phi|/a_0)\nabla\Phi] = 4\pi G \rho$, o QUMOND de Milgrom, 2010) bajo condiciones de simetría esférica o cilíndrica donde el campo vectorial solenoidal ($\nabla \times \vec{h}$) desaparece idénticamente. Dado que un sistema compuesto por un bulbo esferoidal y un disco exponencial carece de simetría esférica, aplicar la Ecuación (5) al campo newtoniano combinado $g_N(r) = g_{N,\text{bulbo}}(r) + g_{N,\text{disco}}(r)$ constituye un **presupuesto fenomenológico de tipo algebraico** (inspirado en las aproximaciones para discos analizadas por Brada & Milgrom, 1995), y no una solución demostrada de la ecuación de Poisson no lineal ni la prueba de un sustrato físico fundamental.

## 1.5. Distinción Conceptual entre la Constante $a_0$ y el Parámetro de Hubble ($H_0$)
Planteamos como postulado conceptual que $a_0 = 1,20 \times 10^{-10}\ \text{m/s}^2$ representa una constante estructural invariante, mientras que el parámetro de Hubble observado ($H_{\text{obs}}$) se modela en los capítulos exploratorios (Capítulos 5 y 6) como una magnitud efectiva compuesta por un término disipativo y un término cinemático direccional.

---

# CAPÍTULO 2: AUDITORÍA REPRODUCIBLE DE LA CURVA DE ROTACIÓN DE LA VÍA LÁCTEA (5 A 25 KPC)

## 2.1. Escala Característica de Transición ($r_t$) y Propiedad Algebraica en $g_N = a_0$
Definimos el radio característico de transición ($r_t$) de un sistema como la distancia en la cual la magnitud del campo newtoniano iguala al parámetro crítico ($g_N(r_t) = a_0$):

$$g_N(r_t) = a_0 \quad \left(\text{en aproximación monopolar: } r_t = \sqrt{\frac{G \cdot M}{a_0}}\right) \quad (7)$$

Evaluando la Ecuación (5) en la condición $g_N = a_0$, se deduce como propiedad algebraica intrínseca de la función $\mu(x) = x/(1+x)$:

$$a(g_N = a_0) = \frac{a_0}{2}\left(1 + \sqrt{5}\right) = \phi \cdot g_N \approx 1,61803 \cdot g_N \quad \implies \quad \frac{v(r_t)}{v_N(r_t)} = \sqrt{\phi} \approx 1,27202 \quad (8)$$

*(Nota: El factor $\sqrt{\phi}$ es una propiedad algebraica del modelo definido y no una evidencia observacional independiente).*

## 2.2. Evaluación Exacta de Bessel para la Curva Radial de la Vía Láctea entre $5,0\text{ y }25,0\ \text{kpc}$ y Contraste con Datos Primarios de Eilers et al. (2019)
Todos los valores reportados en este manuscrito para la Vía Láctea proceden de un único script verificable en Python (`scipy.special`, incluido íntegramente en el Anexo Técnico) que evalúa las Ecuaciones (9a–9c) con las siguientes constantes y entradas explícitas:
- Constantes físicas: $G = 6,674 \times 10^{-11}\ \text{m}^3\text{kg}^{-1}\text{s}^{-2}$, $a_0 = 1,20 \times 10^{-10}\ \text{m/s}^2$, $1\ M_\odot = 1,9885 \times 10^{30}\ \text{kg}$, $1\ \text{kpc} = 3,0857 \times 10^{19}\ \text{m}$.
- Distancia galactocéntrica del Sol: $r_\odot = 8,00\ \text{kpc} = 2,46856 \times 10^{20}\ \text{m}$.
- **Componente 1 — Bulbo esferoidal de Hernquist:** Masa fija $M_b = 1,00 \times 10^{10}\ M_\odot = 1,9885 \times 10^{40}\ \text{kg}$ y longitud de escala radial fija $a_b = 0,60\ \text{kpc} = 1,85142 \times 10^{19}\ \text{m}$:

$$g_{N,\text{bulbo}}(r) = \frac{G \cdot M_b}{(r + a_b)^2} \quad (9\text{a})$$

- **Componente 2 — Disco bariónico exponencial de Freeman:** Longitud de escala radial fija $R_d = 2,60\ \text{kpc} = 8,02282 \times 10^{19}\ \text{m}$. Evaluamos tres perfiles paramétricos de masa bariónica de disco (estrellas más gas frío) tomados del intervalo de estimaciones independientes de la literatura (Bovy & Rix, 2013; Licquia & Newman, 2015; McMillan, 2017):
  * **Rama A (Cota Inferior):** $M_{d,\text{A}} = 4,50 \times 10^{10}\ M_\odot \implies M_{\text{bar,A}} = 5,50 \times 10^{10}\ M_\odot$ ($v_{f,\text{A}} = 172,1\ \text{km/s}$).
  * **Perfil Central C (Referencia Intermedia):** $M_{d,\text{C}} = 5,00 \times 10^{10}\ M_\odot \implies M_{\text{bar,C}} = 6,00 \times 10^{10}\ M_\odot$ ($v_{f,\text{C}} = 175,8\ \text{km/s}$).
  * **Rama B (Cota Superior):** $M_{d,\text{B}} = 5,50 \times 10^{10}\ M_\odot \implies M_{\text{bar,B}} = 6,50 \times 10^{10}\ M_\odot$ ($v_{f,\text{B}} = 179,3\ \text{km/s}$).

La aceleración radial newtoniana exacta en el plano del disco exponencial (Freeman, 1970) en función de $y = \frac{r}{2 R_d}$ y de las funciones modificadas de Bessel $\Delta B(y) = I_0(y) K_0(y) - I_1(y) K_1(y)$ es:

$$g_{N,\text{disco}}(r) = \frac{G \cdot M_d}{r^2} \cdot F_{\text{Bessel}}(y) \quad \text{con } F_{\text{Bessel}}(y) = 4 y^3 \left[I_0(y) K_0(y) - I_1(y) K_1(y)\right] \quad (9\text{b})$$

- **Campo newtoniano total, aceleración modificada y velocidad circular:**

$$g_{N,\text{tot}}(r) = g_{N,\text{bulbo}}(r) + g_{N,\text{disco}}(r) \implies v_N(r) = \sqrt{r \cdot g_{N,\text{tot}}(r)} \implies v_{\text{mod}}(r) = \sqrt{r \cdot a(r)} \quad (9\text{c})$$

**Separación rigurosa de los datos primarios de Eilers et al. (2019) y su recta secundaria de ajuste:**
Para eliminar toda ambigüedad en la fuente observacional, separamos en dos columnas distintas los productos publicados en Eilers et al. (2019, *ApJ*, 871, 120):
1. **Datos Primarios (Tabla 1 de Eilers et al., 2019):** Los autores publican las mediciones discretas de velocidad circular $v_c(R)$ con sus incertidumbres estadísticas asimétricas ($+\sigma_{\text{stat}} / -\sigma_{\text{stat}}$) en bines radiales específicos. Consignamos para cada radio $r$ del modelo el bin primario exacto más cercano de la Tabla 1 de Eilers et al. ($R_{\text{bin}} = 5,27,\ 6,27,\ 7,78,\ 8,27,\ 10,27,\ 12,26,\ 15,78,\ 19,82\text{ y }24,82\ \text{kpc}$) con sus valores y barras estadísticas originales sin alterar.
2. **Recta Secundaria de Ajuste e Incertidumbre Sistemática (Ecuación 7 y Sección 4 de Eilers et al., 2019):** Como referencia visual secundaria, consignamos el valor de la recta lineal ajustada por dichos autores, $v_{c,\text{fit}}(r) = 229,0 - 1,7 (r - 8,0)\ \text{km/s}$. Eilers et al. (2019) reportan por separado que la incertidumbre sistemática total ($\sigma_{\text{sys}}$, dominada por el perfil de densidad de trazadores, la distancia solar $R_0$ y asimetrías azimutales) es de $\sim 3\%$ en torno al radio solar ($\approx \pm 6,9\ \text{km/s}$) y alcanza $\sim 5\%$ a grandes radios ($\approx \pm 10\ \text{km/s}$). Para construir un indicador descriptivo explícito y trazable ($\Delta v_{\text{C}} = v_{\text{mod,C}} - v_{c,\text{bin}}$), reportamos la diferencia directa en $\text{km/s}$ del Perfil Central C respecto al dato primario medido en el bin, junto con la incertidumbre combinada de referencia $\sigma_{\text{comb}} = \sqrt{\sigma_{\text{stat,med}}^2 + (0,03\,v_{c,\text{bin}})^2}$ (donde $\sigma_{\text{stat,med}} = \frac{1}{2}(\sigma_+ + \sigma_-)$ y $0,03\,v_{c,\text{bin}}$ representa el piso sistemático del $3\%$ documentado en la fuente).

### Tabla 1A: Valores Exactos de Bessel, Aceleraciones y Velocidades del Modelo (5,0 a 25,0 kpc)

| $r$ (kpc) | $y = r/(2R_d)$ | $\Delta B(y)$ Exacto | $F_{\text{Bessel}}(y)$ Exacto | $g_{N,\text{bulbo}}$ ($10^{-10}\ \text{m/s}^2$) | $g_{N,\text{disco}}$ [A / C / B] ($10^{-10}\ \text{m/s}^2$) | $g_{N,\text{tot}}$ [A / C / B] ($10^{-10}\ \text{m/s}^2$) | $v_N$ Kepler [A / C / B] (km/s) | $a(r)$ Ec. 5 [A / C / B] ($10^{-10}\ \text{m/s}^2$) | $v_{\text{mod}}$ [Rama A / Central C / Rama B] (km/s) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **5,0** | 0,96154 | 0,20763 | **0,7384** | 0,4444 | 1,8503 / 2,0559 / 2,2615 | 2,295 / 2,500 / 2,706 | **188,2 / 196,4 / 204,3** | 3,168 / 3,390 / 3,610 | **221,1 / 228,7 / 236,0** |
| **6,0** | 1,15385 | 0,14488 | **0,8902** | 0,3197 | 1,5489 / 1,7210 / 1,8931 | 1,869 / 2,041 / 2,213 | **186,1 / 194,5 / 202,5** | 2,700 / 2,890 / 3,079 | **223,7 / 231,4 / 238,8** |
| **8,0** | 1,53846 | 0,07493 | **1,0914** | 0,1885 | 1,0681 / 1,1868 / 1,3055 | 1,257 / 1,375 / 1,494 | **176,1 / 184,3 / 192,1** | 2,009 / 2,147 / 2,284 | **222,7 / 230,2 / 237,4** |
| **10,0** | 1,92308 | 0,04150 | **1,1807** | 0,1241 | 0,7398 / 0,8220 / 0,9042 | 0,864 / 0,946 / 1,028 | **163,3 / 170,9 / 178,1** | 1,543 / 1,644 / 1,743 | **217,9 / 224,9 / 231,7** |
| **12,0** | 2,30769 | 0,02444 | **1,2011** | 0,0878 | 0,5225 / 0,5805 / 0,6386 | 0,610 / 0,668 / 0,726 | **150,3 / 157,3 / 164,0** | 1,227 / 1,304 / 1,379 | **213,1 / 219,6 / 225,9** |
| **16,0** | 3,07692 | 0,00996 | **1,1611** | 0,0506 | 0,2841 / 0,3156 / 0,3472 | 0,335 / 0,366 / 0,398 | **128,6 / 134,5 / 140,2** | 0,823 / 0,872 / 0,919 | **201,6 / 207,4 / 213,0** |
| **20,0** | 3,84615 | 0,00487 | **1,1079** | 0,0328 | 0,1735 / 0,1928 / 0,2121 | 0,206 / 0,226 / 0,245 | **112,8 / 118,0 / 122,9** | 0,612 / 0,646 / 0,679 | **194,3 / 199,6 / 204,7** |
| **25,0** | 4,80769 | 0,00239 | **1,0643** | 0,0212 | 0,1067 / 0,1185 / 0,1304 | 0,128 / 0,140 / 0,152 | **99,3 / 103,8 / 108,1** | 0,461 / 0,486 / 0,510 | **188,6 / 193,6 / 198,2** |

### Tabla 1B: Contraste Separado frente a los Datos Primarios (Tabla 1 de Eilers et al., 2019) y Recta Secundaria

| Radio Modelo $r$ (kpc) | $v_{\text{mod}}$ [A / C / B] (km/s) | Dato Primario Tabla 1 de Eilers et al. (2019) [$R_{\text{bin}}$: $v_{c,\text{bin}} (+\sigma_+ / -\sigma_-)$] | Sistemático $3\%$ ($\sigma_{\text{sys}}$) y Combinado ($\sigma_{\text{comb}}$) | Residuo Directo Central C ($\Delta v_{\text{C}} = v_{\text{C}} - v_{c,\text{bin}}$) | Indicador Descriptivo $z_{\text{C}} = \Delta v_{\text{C}} / \sigma_{\text{comb}}$ | Recta Secundaria Ec. 7 de Eilers ($v_{c,\text{fit}}$) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **5,0** | **221,1 / 228,7 / 236,0** | $R = 5,27\ \text{kpc}$: **226,83 (+1,91 / -1,90) km/s** | $\sigma_{\text{sys}} = 6,80$, $\sigma_{\text{comb}} = 7,07\ \text{km/s}$ | **+1,87 km/s** | +0,26 | 234,1 km/s |
| **6,0** | **223,7 / 231,4 / 238,8** | $R = 6,27\ \text{kpc}$: **230,80 (+1,38 / -1,32) km/s** | $\sigma_{\text{sys}} = 6,92$, $\sigma_{\text{comb}} = 7,05\ \text{km/s}$ | **+0,60 km/s** | +0,09 | 232,4 km/s |
| **8,0** | **222,7 / 230,2 / 237,4** | $R = 7,78\ \text{kpc}$: **229,63 (+0,60 / -0,63) km/s** ($R = 8,27$: 228,89) | $\sigma_{\text{sys}} = 6,89$, $\sigma_{\text{comb}} = 6,92\ \text{km/s}$ | **+0,57 km/s** (vs 7,78) y **+1,31 km/s** (vs 8,27) | +0,08 (+0,19) | 229,0 km/s |
| **10,0** | **217,9 / 224,9 / 231,7** | $R = 10,27\ \text{kpc}$: **224,96 (+0,84 / -0,96) km/s** | $\sigma_{\text{sys}} = 6,75$, $\sigma_{\text{comb}} = 6,81\ \text{km/s}$ | **-0,06 km/s** | -0,01 | 225,6 km/s |
| **12,0** | **213,1 / 219,6 / 225,9** | $R = 12,26\ \text{kpc}$: **220,96 (+1,22 / -1,27) km/s** | $\sigma_{\text{sys}} = 6,63$, $\sigma_{\text{comb}} = 6,75\ \text{km/s}$ | **-1,36 km/s** | -0,20 | 222,2 km/s |
| **16,0** | **201,6 / 207,4 / 213,0** | $R = 15,78\ \text{kpc}$: **217,47 (+1,86 / -2,15) km/s** | $\sigma_{\text{sys}} = 6,52$, $\sigma_{\text{comb}} = 6,82\ \text{km/s}$ | **-10,07 km/s** (-4,5 en B) | -1,48 (-0,66 en B) | 215,4 km/s |
| **20,0** | **194,3 / 199,6 / 204,7** | $R = 19,82\ \text{kpc}$: **206,54 (+4,18 / -3,97) km/s** | $\sigma_{\text{sys}} = 6,20$, $\sigma_{\text{comb}} = 7,42\ \text{km/s}$ | **-6,94 km/s** (-1,8 en B) | -0,94 (-0,25 en B) | 208,6 km/s |
| **25,0** | **188,6 / 193,6 / 198,2** | $R = 24,82\ \text{kpc}$: **198,42 (+6,12 / -6,50) km/s** | $\sigma_{\text{sys}} = 5,95$, $\sigma_{\text{comb}} = 8,67\ \text{km/s}$ | **-4,82 km/s** (-0,2 en B) | -0,56 (-0,03 en B) | 200,1 km/s |

**Evaluación de las Tablas 1A y 1B:**
1. **Reproducibilidad numérica cerrada:** La Tabla 1A corrige la totalidad de las evaluaciones de Bessel en los 8 radios y subsana la anomalía de $v_N$ en $16,0\ \text{kpc}$ ($128,6 / 134,5 / 140,2\ \text{km/s}$), verificándose que $v_N$ y $v_{\text{mod}}$ crecen monótonamente con la masa del disco $M_d$ en cada radio.
2. **Contraste frente a los datos primarios de la Tabla 1 de Eilers et al. (2019):** En la región de $5\text{ a }12\ \text{kpc}$, el Perfil Central C ($M_d = 5,00 \times 10^{10}\ M_\odot$) coincide con las mediciones discretas de Eilers et al. con residuos menores a $2\ \text{km/s}$ ($+1,87,\ +0,60,\ +0,57,\ -0,06\text{ y }-1,36\ \text{km/s}$). En la región exterior ($16\text{ a }25\ \text{kpc}$), la Rama B ($M_d = 5,50 \times 10^{10}\ M_\odot$) se aproxima estrechamente a los puntos primarios ($213,0$ vs. $217,47\ \text{km/s}$ en $16\ \text{kpc}$; $204,7$ vs. $206,54\ \text{km/s}$ en $20\ \text{kpc}$; y $198,2$ vs. $198,42\ \text{km/s}$ en $25\ \text{kpc}$).

## 2.3. Contraste del Límite Newtoniano en Alta Aceleración (Sistema Solar y Estrella S2)
1. **Interior del Sistema Solar ($r = 1\ \text{UA}$, $M = 1\ M_\odot$):** $g_N = 5,930 \times 10^{-3}\ \text{m/s}^2 \implies a / g_N - 1 = 2,02 \times 10^{-8}$.
2. **Estrella S2 en Pericentro (Sagitario A*, $M_c = 4,30 \times 10^6\ M_\odot$, $r_p = 120\ \text{UA}$, $e = 0,8846$):** $g_N = 1,77\ \text{m/s}^2 \approx 1,47 \times 10^{10} a_0 \implies \mu \approx 1$, arrojando una velocidad pericéntrica kepleriana de $v_p = 7.650\ \text{km/s}$. *(Dejamos expresamente aclarado que este cálculo verifica únicamente que la Ecuación 5 regresa sin desviaciones al límite newtoniano cuando $g_N \gg a_0$; no constituye una prueba de la estructura relativista del modelo ni deriva por sí mismo el corrimiento al rojo gravitacional post-newtoniano medido por GRAVITY Collaboration, 2018).*
3. **Cancelación de la masa de prueba ($m$) en el disco exterior:** Al cancelarse $m$ en la Ecuación (4), cuerpos de prueba de masas opuestas (p. ej., $0,08\ M_\odot$ frente a $21\ M_\odot$) siguen exactamente el mismo perfil de velocidad de la Tabla 1A en cualquier radio $r$.

---

# CAPÍTULO 3: CONTRASTE PRELIMINAR EN GALAXIAS Y CÚMULOS, Y CONJETURA POBLACIONAL EN $M_t = M_c + M_r$

## 3.1. Relación Asintótica en Sistemas Rotacionales Planos y Ejemplos Ilustrativos de SPARC
En el límite exterior monopolar ($r \gg R_d$, $g_N \ll a_0$), igualando $v_f^2 / r$ con la Ecuación (6), se deduce:

$$v_f^4 = G \cdot M_t \cdot a_0 \quad \Longleftrightarrow \quad M_t = \frac{v_f^4}{G \cdot a_0} \quad (10)$$

La Tabla 2 presenta tres sistemas espirales del catálogo SPARC (Lelli et al., 2016) como ejemplos ilustrativos de la aplicación numérica de la Ecuación (10):

| Galaxia (Referencia) | Velocidad Asintótica Medida ($v_f$) | Masa Dinámica Inferida por Ec. (10) ($M_t$) | Masa Bariónica Observada ($M_{\text{bar}} = M_* + 1,33 M_{\text{HI}}$) | Diferencia Relativa ($(M_t - M_{\text{bar}})/M_{\text{bar}}$) |
| :--- | :--- | :--- | :--- | :--- |
| **Vía Láctea** (Ramas A–B) | $180 \pm 5\ \text{km/s}$ (asíntota externa) | $(6,59 \pm 0,73) \times 10^{10}\ M_\odot$ | $(5,50 - 6,50) \times 10^{10}\ M_\odot$ | $+1,4\%$ a $+19,8\%$ |
| **NGC 3198** (Lelli et al., 2016 - SPARC) | $150,1 \pm 3,0\ \text{km/s}$ | $(3,19 \pm 0,25) \times 10^{10}\ M_\odot$ | $(3,05 \pm 0,45) \times 10^{10}\ M_\odot$ | $+4,6\%$ |
| **M33 / NGC 598** (SPARC / Corbelli 2014) | $96,0 \pm 4,0\ \text{km/s}$ | $(5,33 \pm 0,89) \times 10^{9}\ M_\odot$ | $(5,00 \pm 0,80) \times 10^{9}\ M_\odot$ | $+6,6\%$ |

*(Delimitación estadística: Tres ejemplos individuales ilustran el funcionamiento algebraico de la Ecuación 10 pero no constituyen una validación estadística de muestra. El contraste poblacional sobre las 175 galaxias del catálogo SPARC con propagación de errores en distancia, inclinación y razón masa-luz $\Upsilon_*$ se encuentra desarrollado en Lelli et al., 2016 y McGaugh et al., 2016).*

## 3.2. Analogía Conceptual: Regímenes de Corto y Largo Alcance
Mantenemos explícitamente como analogía conceptual heurística (y no como identidad de mecanismo físico) el paralelismo entre el desdoblamiento gravitatorio de corto alcance ($1/r^2$, $g_N \gg a_0$) y largo alcance ($1/r$, $g_N \ll a_0$) frente a los regímenes de corto y largo alcance observados en las interacciones nucleares y electromagnéticas.

## 3.3. Nomenclatura Contable ($M_t = M_c + M_r$), Definición Operacional por Población y Conjetura del 1%
Conservamos la identidad contable de partición:

$$M_t = M_c + M_r \quad (11)$$

Dado que los objetos centrales en galaxias y en cúmulos son físicamente distintos, establecemos su definición operacional separada por población:

1. **Población I — Galaxias Individuales (Sistemas 2D, evaluados dentro del radio bariónico total $R_{\text{bar}}$):**
   - $M_t \equiv M_{\text{bar}}$: Masa bariónica total integrada del sistema (bulbo + disco estelar + gas frío).
   - $M_c \equiv M_{\text{BH}}$: Masa del Agujero Negro Supermasivo central.
   - $M_r = M_{\text{bar}} - M_{\text{BH}}$: Masa bariónica residual distribuida en el bulbo y el disco.
2. **Población II — Cúmulos de Galaxias (Sistemas 3D, evaluados dentro del radio virial $r_{200}$):**
   - $M_t \equiv M_{\text{dyn,ef}}(r_{200})$: Masa dinámica efectiva inferida en $r_{200}$ (comparada frente a la masa bariónica intracúmulo $M_{\text{bar,cl}} = M_{\text{gas,X}} + M_{\text{*,gal}}$).
   - $M_c \equiv M_{\text{BCG}}$: Masa bariónica estelar de la Galaxia Central Dominante (*Brightest Cluster Galaxy* tipo cD, o par central dominante).
   - $M_r = M_t - M_{\text{BCG}}$: Masa residual del resto del cúmulo.

Planteamos como hipótesis empírica de trabajo (conjetura poblacional no demostrada como ley física universal por estos ejemplos ilustrativos) que, evaluada dentro de cada población, la razón $M_c / M_t$ satisface la cota superior del $1\%$:

$$\frac{M_c}{M_t} < 0,01 \quad \Longleftrightarrow \quad M_r > 0,99 \cdot M_t \quad (12)$$

Ejemplos ilustrativos en la Población I ($M_c \equiv M_{\text{BH}}$, $M_t \equiv M_{\text{bar}}$):
1. **Vía Láctea:** $M_t \approx 0,60 \times 10^{11}\ M_\odot$ (Perfil Central C), $M_c \equiv M_{\text{BH}} = 4,30 \times 10^6\ M_\odot$ (GRAVITY, 2018), $M_c / M_t = 0,0072\%$.
2. **Andrómeda (M31):** $M_t \approx 1,50 \times 10^{11}\ M_\odot$ (Tamm et al., 2012), $M_c \equiv M_{\text{BH}} = 1,40 \times 10^8\ M_\odot$ (Bender et al., 2005), $M_c / M_t = 0,093\%$.
3. **Sombrero (M104):** $M_t \approx 2,10 \times 10^{11}\ M_\odot$ (Tempel & Tenjes, 2006), $M_c \equiv M_{\text{BH}} = 1,00 \times 10^9\ M_\odot$ (Kormendy et al., 1996), $M_c / M_t = 0,476\%$.
4. **M87 (NGC 4486):** $M_t \approx 12,00 \times 10^{11}\ M_\odot$ (Murphy et al., 2011), $M_c \equiv M_{\text{BH}} = 6,50 \times 10^9\ M_\odot$ (EHT, 2019), $M_c / M_t = 0,542\%$.
5. **Centaurus A (NGC 5128):** $M_t \approx 8,00 \times 10^{11}\ M_\odot$ (Woodley et al., 2007), $M_c \equiv M_{\text{BH}} = 5,50 \times 10^9\ M_\odot$ (Cappellari et al., 2009), $M_c / M_t = 0,688\%$.

## 3.4. Ecuación Hidrostática de Jeans en Cúmulos 3D y Condicionalidad de los Supuestos
En un sistema esférico tridimensional en equilibrio estacionario con isotropía de velocidades ($\beta_{\text{anis}} = 0$), la ecuación de Jeans relaciona la densidad $\rho(r)$ y la dispersión de velocidad radial ($\sigma_r$) con la aceleración gravitatoria $a(r)$:

$$\frac{1}{\rho(r)} \frac{d\left(\rho(r) \sigma_r^2\right)}{dr} = -a(r) \quad \implies \quad a(r) = \frac{\alpha(r) \cdot \sigma_r^2}{r} \quad \left(\text{para } \sigma_r \approx \text{const. y } \alpha = -\frac{d \ln \rho}{d \ln r}\right) \quad (13)$$

Si evaluamos el sistema en el radio virial de referencia ($r \approx r_{200}$) bajo el supuesto de régimen profundo ($a(r) \approx \sqrt{G M_{\text{dyn,ef}} a_0} / r$), la masa dinámica efectiva inferida depende explícitamente de $\alpha^2$:

$$M_{\text{dyn,ef}}(r_{200}) = \frac{\alpha^2 \cdot \sigma_r^4}{G \cdot a_0} \quad (14)$$

*(Por definición, en isotropía 3D se cumple $v_{\text{3D}}^2 = 3 \sigma_r^2$; esta cantidad no es igual en general a $\alpha \sigma_r^2$, coincidiendo numéricamente sólo cuando se fija la pendiente $\alpha = 3$, en cuyo caso $M_{\text{dyn,ef}}(\alpha = 3) = \frac{9 \sigma_r^4}{G a_0}$).*

**Estimación condicional de orden de magnitud en Virgo y Coma (Población II, $M_c \equiv M_{\text{BCG}}$):**
- **Cúmulo de Virgo ($r_{200} \approx 1,55\ \text{Mpc}$):** Si se adopta $\sigma_r \approx 577\ \text{km/s}$ (Binggeli et al., 1993) y $\alpha = 3$, la Ecuación (14) arroja $M_{\text{dyn,ef}} = 6,28 \times 10^{13}\ M_\odot$ (frente a estimaciones de masa de gas caliente más estrellas en rayos X del orden de $\sim 3 - 6 \times 10^{13}\ M_\odot$; Böhringer et al., 1994; Urban et al., 2011), con $M_{\text{BCG}}(\text{M87}) \approx 5 \times 10^{11}\ M_\odot$ ($0,80\%$).
- **Cúmulo de Coma ($r_{200} \approx 2,30\ \text{Mpc}$):** Si se adopta en la zona exterior $\sigma_r \approx 693\ \text{km/s}$ (Colless & Dunn, 1996) y $\alpha = 3$, la Ecuación (14) arroja $M_{\text{dyn,ef}} = 1,30 \times 10^{14}\ M_\odot$, donde el par central NGC 4874/4889 suma $M_{\text{BCG}} \approx 1,0 \times 10^{12}\ M_\odot$ ($0,77\%$). *(Dejamos expresamente sentado que estos valores son condicionales a los supuestos de Jeans adoptados [$\alpha = 3, \beta_{\text{anis}} = 0$ y $\sigma_r$ exterior] y no demuestran que el problema de masa faltante en cúmulos esté resuelto; en el núcleo interno de Coma con $\sigma_r \approx 950\ \text{km/s}$, la Ecuación 14 exige $\sim 4,6 \times 10^{14}\ M_\odot$, persistiendo el déficit bariónico de factor $\sim 2$ documentado por Sanders, 2003).*

---

# CAPÍTULO 4: ESCENARIO CONDICIONAL MACROCÓSMICO: EXPLORACIÓN PARAMÉTRICA DE $N_7$

## 4.1. Definición de la Masa de Referencia $M_{N1} = 1,00 \times 10^{21}\ M_\odot$ para el Escenario Hipotético
A partir de esta sección, el manuscrito explora un escenario cosmológico condicional. Definimos como parámetro de entrada una masa de referencia para un bloque cosmológico hipotético ($N_1$) fijada en:

$$M_{N1} = 1,00 \times 10^{21}\ M_\odot \quad (15)$$

*(Como referencia de escala libre de doble conteo, dada la densidad bariónica media total del universo local $\rho_{\text{bar,tot}} = \Omega_b \rho_{\text{crít}} \approx 4,17 \times 10^{-28}\ \text{kg/m}^3 \approx 6,16 \times 10^9\ M_\odot/\text{Mpc}^3$ [Planck Collaboration, 2020; Shull et al., 2012], el parámetro definido $M_{N1} = 1,00 \times 10^{21}\ M_\odot$ equivale a la masa bariónica contenida en un volumen esférico fiducial de radio $R_{\text{fid}} \approx 3.385\ \text{Mpc} \approx 11.040\text{ M a.l.}$ Este volumen no representa una región física observacionalmente delimitada, sino la definición del parámetro de entrada del escenario).*

## 4.2. Extrapolación Condicional de $N_1$ a $N_7$ y Consideraciones Relativistas en $v_f \approx 0,34c$
Planteamos el ejercicio condicional: **Si se adopta como hipótesis exploratoria un sistema macrocósmico cuya masa total ($M_t$) es siete veces el parámetro de referencia $M_{N1}$ ($M_{t(N7)} = 7,00 \times 10^{21}\ M_\odot$, distribuida sin fronteras administrativas físicas en una masa residual $M_r > 0,99 M_t$ en torno a un atractor central hipotético $M_c < 0,01 M_t$), ¿qué consecuencias algebraicas resultan de aplicar las Ecuaciones (7) y (10)?**

| Escenario Condicional ($N \times M_{N1}$) | Masa Total Postulada ($M_t = M_c + M_r$) | Masa Residual ($M_r > 99\% M_t$) | Atractor Central Supuesto ($M_c$ al $0,8\% M_t$) | Velocidad Asintótica Extrapolada ($v_f = (G M_t a_0)^{1/4}$ Ec. 10) | Radio Interno de Transición ($r_t = \sqrt{G M_t / a_0}$ Ec. 7) | Escala Exterior Hipotética (si $R_{\text{ext}} / r_t \approx 11$) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **$N_1$ ($1\times$)** | $1,00 \times 10^{21}\ M_\odot$ | $0,992 \times 10^{21}\ M_\odot$ | $8,0 \times 10^{18}\ M_\odot$ | **63.400 km/s ($0,21 c$)** | 3.520 M a.l. | $\sim 39.300\text{ M a.l.}$ |
| **$N_2$ ($2\times$)** | $2,00 \times 10^{21}\ M_\odot$ | $1,984 \times 10^{21}\ M_\odot$ | $1,6 \times 10^{19}\ M_\odot$ | **75.400 km/s ($0,25 c$)** | 4.975 M a.l. | $\sim 55.600\text{ M a.l.}$ |
| **$N_3$ ($3\times$)** | $3,00 \times 10^{21}\ M_\odot$ | $2,976 \times 10^{21}\ M_\odot$ | $2,4 \times 10^{19}\ M_\odot$ | **83.400 km/s ($0,28 c$)** | 6.090 M a.l. | $\sim 68.100\text{ M a.l.}$ |
| **$N_4$ ($4\times$)** | $4,00 \times 10^{21}\ M_\odot$ | $3,968 \times 10^{21}\ M_\odot$ | $3,2 \times 10^{19}\ M_\odot$ | **89.600 km/s ($0,30 c$)** | 7.035 M a.l. | $\sim 78.600\text{ M a.l.}$ |
| **$N_5$ ($5\times$)** | $5,00 \times 10^{21}\ M_\odot$ | $4,960 \times 10^{21}\ M_\odot$ | $4,0 \times 10^{19}\ M_\odot$ | **94.700 km/s ($0,32 c$)** | 7.865 M a.l. | $\sim 87.900\text{ M a.l.}$ |
| **$N_6$ ($6\times$)** | $6,00 \times 10^{21}\ M_\odot$ | $5,952 \times 10^{21}\ M_\odot$ | $4,8 \times 10^{19}\ M_\odot$ | **99.200 km/s ($0,33 c$)** | 8.615 M a.l. | $\sim 96.300\text{ M a.l.}$ |
| **$N_7$ ($7\times$)** | **$7,00 \times 10^{21}\ M_\odot$** | **$6,944 \times 10^{21}\ M_\odot$** | **$5,6 \times 10^{19}\ M_\odot$** | **103.000 km/s ($0,34 c$)** | **9.310 M a.l.** | **$\sim 104.000\text{ M a.l.}$** |

**Delimitación física sobre la Tabla 3:**
El resultado $v_f = 102.760 \approx 103.000\ \text{km/s}$ ($0,343c$) y el radio interno $r_t = 9.310\text{ M a.l.}$ son consecuencias matemáticas de la masa postulada $M_{t(N7)} = 7,00 \times 10^{21}\ M_\odot$, y no constituyen mediciones ni evidencia observacional de la existencia física de $N_7$. Asimismo, dado que para $v_f \approx 0,343c$ el factor de Lorentz es $\gamma \approx 1,0645$ ($v_f^2 / c^2 \approx 11,8\%$), dicha velocidad característica no puede interpretarse como una velocidad orbital newtoniana ordinaria sin especificar la geometría, las condiciones de contorno y una formulación métrica relativista completa.

## 4.3. Estabilidad de Órbitas Individuales frente a Estabilidad Colectiva
El potencial efectivo unidimensional $V_{\text{eff}}(r) = v_f^2 \ln(r/r_0) + \frac{h^2}{2r^2}$ posee un mínimo estable único para órbitas de partículas de prueba individuales con momento angular específico $h$. La demostración de estabilidad global hidrodinámica de un disco macrocósmico autogravitante completo requeriría un análisis perturbativo y de N-cuerpos específico.

---

# CAPÍTULO 5: HIPÓTESIS COSMOLÓGICAS EXPLORATORIAS: RESPIRACIÓN RADIAL, CAMPO VECTORIAL DE HUBBLE Y ATENUACIÓN FOTÓNICA

## 5.1. Hipótesis del Ciclo Respiratorio ($T = 2.000\text{ Millones de Años}$) en la Escala $0 \to 0,5 \to 1,0$
Formulamos como hipótesis exploratoria no validada que el sistema experimenta una oscilación radial armónica alrededor de $R_0$ con periodo postulado $T = 2.000\text{ millones de años}$ ($1.000\text{ millones}$ de exhalación y $1.000\text{ millones}$ de inhalación). En función de la fase adimensional de exhalación $u = t / (1.000\text{ M años}) \in [0, 1]$:

$$R(u) = R_0 - A \cdot \cos(\pi \cdot u) \quad \implies \quad H_{\text{cin}}(u) = \frac{1}{R}\frac{dR}{dt} \approx H_{\text{máx}} \cdot \sin(\pi \cdot u) \quad \text{con } H_{\text{máx}} = \left(\frac{A}{R_0}\right)\frac{2\pi}{T} \quad (16)$$

- De $u = 0$ a $u = 0,5$, el sistema se expande acelerando hasta alcanzar $H_{\text{máx}}$ en $u = 0,5$.
- De $u = 0,5$ a $u = 1,0$, el sistema continúa expandiéndose ($H_{\text{cin}} > 0$) pero desacelera hasta detenerse en $u = 1,0$ e iniciar la contracción.
- Una tasa cinemática hipotética de $+5,6\ \text{km/s/Mpc}$ correspondería a $u \approx 0,5$ si $A/R_0 \approx 0,18\%$, o bien a dos fases simétricas ($u_1 \approx 0,025$ o $u_2 \approx 0,975$) si $A/R_0 \approx 2,27\%$, requiriendo observables independientes para su determinación.

## 5.2. Modelo Fenomenológico del Campo Vectorial de Hubble ($\vec{H}_{\text{cin}}$) y Atenuación Fotónica ($H_\gamma$)
Proponemos como hipótesis de investigación que en un sistema que oscila radialmente respecto a un centro situado en la dirección unitaria $\hat{u}_c$, la tasa de expansión cinemática constituye un campo direccional definido por el vector radial $\vec{H}_{\text{cin}}(t)$. Sumando esta componente a un escalar de atenuación fotónica secular en el medio ($dE = -k E dx \implies 1 + z_\gamma(d) = e^{(H_\gamma / c) d}$, con $H_\gamma = c \cdot k$), la tasa aparente de Hubble en la dirección de observación $\hat{n}$ ($\cos\theta = \hat{n} \cdot \hat{u}_c$) define la forma fenomenológica:

$$H_{\text{obs}}(t, \hat{n}) = H_\gamma + \vec{H}_{\text{cin}}(t) \cdot \hat{n} = H_\gamma + H_{\text{cin}}(t) \cos\theta \quad (17)$$

**Alcance epistemológico:** Dejamos expresamente establecido que la resta aritmética $73,0 - 67,4 = 5,6\ \text{km/s/Mpc}$ entre las determinaciones locales y del CMB es únicamente una motivación numérica ilustrativa y no demuestra que la Tensión de Hubble esté resuelta ni que la diferencia provenga de un campo vectorial más atenuación fotónica. Para que esta hipótesis pueda contrastarse formalmente frente al modelo cosmológico estándar ($\Lambda\text{CDM}$) utilizando criterios de información penalizados por complejidad ($\text{AIC} / \text{BIC}$), deberá superar en desarrollos futuros cuatro pruebas observacionales decisivas: (1) reproducir la dilatación temporal $(1+z)$ en curvas de luz de supernovas Tipo Ia sin dispersión angular de imágenes; (2) satisfacer el test de brillo superficial de Tolman $(1+z)^{-4}$; (3) cumplir la relación de dualidad de distancias de Etherington $d_L = (1+z)^2 d_A$; y (4) reproducir el espectro de cuerpo negro y los picos acústicos del CMB sin distorsiones espectrales incompatibles con FIRAS.

---

# CAPÍTULO 6: PROTOCOLO DE FALSABILIDAD CON PARÁMETROS PREFIJADOS

Definimos tres pruebas observacionales con parámetros documentados y fijados *a priori*:

1. **Prueba de Anisotropía Dipolar de Hubble ($\vec{H}_{\text{cin}}$) con Eje Prefijado:**
   - *Eje prefijado:* Fijamos antes del ajuste la dirección del vector $\hat{u}_c$ en las coordenadas galácticas del flujo convergente de Shapley/Vela: $l_c = 295^\circ \pm 15^\circ, b_c = +15^\circ \pm 15^\circ$.
   - *Muestra y control de sesgos:* Sobre el catálogo Pantheon+ de supernovas Tipo Ia y muestras de cúmulos en rayos X en $0,023 < z < 0,15$ (corrigiendo el movimiento del Grupo Local respecto al CMB y el flujo peculiar de 2M++ de Carrick et al., 2015), se ajustará la amplitud dipolar $H_{\text{cin}}$ proyectada sobre $(l_c, b_c)$.
   - *Criterio estadístico de falsación:* Se predice $H_{\text{cin}} \approx 5,6 \pm 1,5\ \text{km/s/Mpc}$ con $\Delta \text{BIC} > 6$ respecto al modelo isótropo nulo ($H_{\text{cin}} = 0$). Si el ajuste restringe la amplitud en dicho eje a $H_{\text{cin}} < 1,0\ \text{km/s/Mpc}$ a $> 3\sigma$, la hipótesis del campo vectorial de respiración radial queda refutada.

2. **Prueba de Consistencia de Potencial Plano mediante la Frecuencia Epicíclica ($\kappa / \Omega = \sqrt{2}$, $T_r = 152,0\text{ M años}$) en Gaia:**
   - *Cálculo explícito y documentado del periodo radial:* En un potencial con curva de rotación plana ($dv_c / dr \approx 0$), la frecuencia epicíclica radial ($\kappa$) y la frecuencia angular circular ($\Omega = v_c / r$) cumplen la propiedad dinámica general $\kappa / \Omega = \sqrt{2}$. Utilizando los parámetros exactos de la posición solar en nuestra Tabla 1A ($r_\odot = 8,00\ \text{kpc} = 2,46856 \times 10^{20}\ \text{m}$ y velocidad circular observada $v_c = 229,0\ \text{km/s}$, o $230,2\ \text{km/s}$ en el Perfil Central C, con $1\text{ año juliano} = 3,15576 \times 10^7\ \text{s}$), el periodo orbital azimutal es:

$$T_{\text{orb}} = \frac{2\pi r_\odot}{v_c} = 214,6\text{ a }215,7\text{ millones de años} \quad (\approx 215,0\text{ M años}) \quad (18\text{a})$$

Dividiendo por $\sqrt{2} = 1,41421$, el periodo de oscilación radial epicíclica correspondiente es:

$$T_r = \frac{T_{\text{orb}}}{\sqrt{2}} = 151,8\text{ a }152,5\text{ millones de años} \quad (\approx 152,0\text{ M años}) \quad (18\text{b})$$

   - *Alcance del test:* Presentamos esta relación como una prueba de consistencia general de un potencial con curva de rotación aproximadamente plana en la Vía Láctea, y no como una predicción exclusiva del escenario cosmológico $N_7$. Mediante mapeo de acciones y frecuencias $(\Omega_R, \Omega_\phi, \Omega_z)$ en Gaia DR4 se evaluará qué fracción de la estructura espiral de fase responde al modo estacionario $\Omega_R / \Omega_\phi \approx \sqrt{2}$ frente a la deriva temporal $\Omega_R(r, t_{\text{imp}})$ de ondas cinemáticas transitorias inducidas por la galaxia enana de Sagitario.

3. **Contraste de Pendiente Magnitud-Redshift en el Eje Z vs. Plano Supergaláctico:**
   - Evaluar en catálogos de cuásares y galaxias ($z > 1$) si existe una diferencia sistemática ($> 3\sigma$) en el módulo de distancia efectivo entre los polos supergalácticos ($|\text{SGB}| > 60^\circ$, Eje Z) y el ecuador supergaláctico ($|\text{SGB}| < 15^\circ$).

---

# CAPÍTULO 7: REFLEXIÓN FINAL Y ANEXO TÉCNICO CON SCRIPT EJECUTABLE

## 7.1. Síntesis del Programa de Investigación
El presente trabajo establece un modelo fenomenológico explícito de transición gravitatoria ($\mu(x) = x/(1+x)$) cuya evaluación numérica reproducible mediante funciones modificadas de Bessel sobre el perfil bariónico de bulbo de Hernquist más disco exponencial de Freeman se aproxima a las mediciones primarias de la curva de rotación de la Vía Láctea entre $5,0\text{ y }25,0\ \text{kpc}$ ($230,2\ \text{km/s}$ en $8,0\ \text{kpc}$ y $193,6 - 198,2\ \text{km/s}$ en $25,0\ \text{kpc}$). Reconociendo que este ajuste algebraico no demuestra por sí mismo la inexistencia de la materia oscura ni equivale a resolver la ecuación de Poisson no lineal, y separándolo rigurosamente de las conjeturas e hipótesis exploratorias planteadas en las escalas de cúmulos y cosmología ($M_c / M_t < 0,01$, escenario condicional $N_7$ y descomposición vectorial de Hubble), entregamos un programa de investigación transparente, verificable mediante código abierto y sujeto a contrastación empírica.

---

## ANEXO TÉCNICO: TABLA MAESTRA DE ENTRADAS, AUDITORÍA REPRODUCIBLE Y SCRIPT EJECUTABLE (VERSIÓN 9.0)

### A.1. Tabla de Constantes y Parámetros de Entrada con Unidades Explícitas

| Símbolo | Magnitud Física | Valor Adoptado | Unidades SI / Astronómicas |
| :--- | :--- | :--- | :--- |
| $G$ | Constante de gravitación universal | $6,674 \times 10^{-11}$ | $\text{m}^3\,\text{kg}^{-1}\,\text{s}^{-2}$ |
| $a_0$ | Parámetro crítico de aceleración del modelo | $1,20 \times 10^{-10}$ | $\text{m}\,\text{s}^{-2}$ |
| $c$ | Velocidad de la luz en el vacío | $299.792,458$ | $\text{km}\,\text{s}^{-1}$ |
| $M_\odot$ | Masa solar | $1,9885 \times 10^{30}$ | $\text{kg}$ |
| $\text{kpc}$ | Kilopársec | $3,0857 \times 10^{19}$ | $\text{m}$ |
| $\text{a.l.}$ | Año luz juliano | $9,4607 \times 10^{15}$ | $\text{m}$ |
| $M_b, a_b$ | Masa y radio de escala del bulbo de Hernquist (VL) | $1,00 \times 10^{10}\ M_\odot$, $0,60\ \text{kpc}$ | $1,9885 \times 10^{40}\ \text{kg}$, $1,85142 \times 10^{19}\ \text{m}$ |
| $M_d, R_d$ | Masa (Ramas A/C/B) y escala del disco de Freeman (VL) | $(4,50 / 5,00 / 5,50) \times 10^{10}\ M_\odot$, $2,60\ \text{kpc}$ | $(0,895 / 0,994 / 1,094) \times 10^{41}\ \text{kg}$, $8,02282 \times 10^{19}\ \text{m}$ |

### A.2. Script Ejecutable en Python para Verificación Independiente de las Tablas 1A y 1B

Cualquier investigador o revisor puede copiar y ejecutar directamente el siguiente script estándar de Python 3 (`numpy` y `scipy.special`) para verificar hasta el último decimal todas las columnas de las Tablas 1A y 1B:

    import numpy as np
    from scipy.special import i0, k0, i1, k1

    # 1. Constantes fisicas y parametros geometricos fijos (Version 9.0)
    G = 6.674e-11          # m^3 kg^-1 s^-2
    a0 = 1.20e-10          # m s^-2
    M_sun = 1.9885e30      # kg
    kpc = 3.0857e19        # m

    M_b = 1.00e10 * M_sun  # Masa bulbo Hernquist (kg)
    a_b = 0.60 * kpc       # Escala bulbo Hernquist (m)
    R_d = 2.60 * kpc       # Escala disco Freeman (m)
    M_d_branches = [4.50e10 * M_sun, 5.00e10 * M_sun, 5.50e10 * M_sun] # Ramas A, C, B

    # Radios de evaluacion (kpc) y bines primarios de Tabla 1 de Eilers et al. (2019)
    r_kpc = np.array([5.0, 6.0, 8.0, 10.0, 12.0, 16.0, 20.0, 25.0])
    eilers_bins = [
        (5.27, 226.83, 1.91, 1.90),
        (6.27, 230.80, 1.38, 1.32),
        (7.78, 229.63, 0.60, 0.63),
        (10.27, 224.96, 0.84, 0.96),
        (12.26, 220.96, 1.22, 1.27),
        (15.78, 217.47, 1.86, 2.15),
        (19.82, 206.54, 4.18, 3.97),
        (24.82, 198.42, 6.12, 6.50)
    ]

    print(f"{'r(kpc)':>6} | {'y':>7} | {'dB(y)':>7} | {'F_Bess':>6} | {'vN_A/C/B (km/s)':>19} | {'vMod_A/C/B (km/s)':>21} | {'dV_C':>6} | {'z_C':>5}")
    print("-" * 96)

    for idx, rk in enumerate(r_kpc):
        r_m = rk * kpc
        y = rk / (2.0 * 2.60)
        dB = float(i0(y)*k0(y) - i1(y)*k1(y))
        F_Bessel = 4.0 * (y**3) * dB
        gN_bulge = G * M_b / ((r_m + a_b)**2)
        
        vN_list, vMod_list = [], []
        for M_d in M_d_branches:
            gN_disk = (G * M_d / (r_m**2)) * F_Bessel
            gN_tot = gN_bulge + gN_disk
            a_mod = 0.5 * gN_tot * (1.0 + np.sqrt(1.0 + 4.0 * a0 / gN_tot))
            vN_list.append(np.sqrt(r_m * gN_tot) / 1000.0)
            vMod_list.append(np.sqrt(r_m * a_mod) / 1000.0)
            
        R_b, vc_b, sp, sm = eilers_bins[idx]
        sig_stat = 0.5 * (sp + sm)
        sig_comb = np.sqrt(sig_stat**2 + (0.03 * vc_b)**2)
        dv_C = vMod_list[1] - vc_b
        z_C = dv_C / sig_comb
        
        vN_str = f"{vN_list[0]:5.1f}/{vN_list[1]:5.1f}/{vN_list[2]:5.1f}"
        vM_str = f"{vMod_list[0]:5.1f} / {vMod_list[1]:5.1f} / {vMod_list[2]:5.1f}"
        print(f"{rk:6.1f} | {y:7.5f} | {dB:7.5f} | {F_Bessel:6.4f} | {vN_str:>19} | {vM_str:>21} | {dv_C:+6.2f} | {z_C:+5.2f}")

### A.3. Tabla Maestra de Auditoría Numérica Reproducible (Versión 9.0)

| ID / Sistema | Parámetros de Entrada Documentados (Inputs) | Ecuación del Modelo Aplicada | Resultado Calculado Verificado por Script (Output) | Categoría Epistemológica y Alcance Técnico |
| :--- | :--- | :--- | :--- | :--- |
| **A-01. Tierra en Sistema Solar** | $M = 1,00\ M_\odot$; $r = 1,496 \times 10^{11}\ \text{m}$ ($1\ \text{UA}$) | Ec. (5): $a = \frac{g_N}{2}(1 + \sqrt{1 + 4a_0/g_N})$ | $g_N = 5,930 \times 10^{-3}\ \text{m/s}^2$; $a / g_N - 1 = 2,02 \times 10^{-8}$; $v = 29,78\ \text{km/s}$ | **Consecuencia Algebraica Cerrada.** Verifica el límite newtoniano ($\mu \to 1$). |
| **A-02. Estrella S2 (Pericentro Sgr A*)** | $M_c \equiv M_{\text{BH}} = 4,30 \times 10^6\ M_\odot$; $r_p = 1,795 \times 10^{13}\ \text{m}$ ($120\ \text{UA}$); $e = 0,8846$ | Ec. (5) + Vis-Viva: $v_p = \sqrt{r_p \cdot a(r_p) \cdot (1+e)}$ | $g_N = 1,77\ \text{m/s}^2 \gg a_0$; $v_p = 7.650\ \text{km/s}$ | **Verificación de Límite Newtoniano.** No constituye prueba relativista ni deriva el redshift gravitacional de GRAVITY. |
| **A-03. Vía Láctea: Curva Radial ($5,0\text{ a }25,0\ \text{kpc}$)** | Bulbo Hernquist ($a_b = 0,60\ \text{kpc}$): $M_b = 1,00 \times 10^{10}\ M_\odot$; Disco Freeman ($R_d = 2,60\ \text{kpc}$), Ramas A/C/B: $M_d = (4,50 / 5,00 / 5,50) \times 10^{10}\ M_\odot$ | Ec. (9a + 9b) con `scipy.special` + Presupuesto algebraico Ec. (5) (Script A.2) | En $5\ \text{kpc}$ ($F=0,7384$): **221,1 / 228,7 / 236,0 km/s**; En $6\ \text{kpc}$ ($F=0,8902$): **223,7 / 231,4 / 238,8 km/s**; En $8\ \text{kpc}$ ($F=1,0914$): **222,7 / 230,2 / 237,4 km/s**; En $10\ \text{kpc}$ ($F=1,1807$): **217,9 / 224,9 / 231,7 km/s**; En $12\ \text{kpc}$ ($F=1,2011$): **213,1 / 219,6 / 225,9 km/s**; En $16\ \text{kpc}$ ($F=1,1611$): **201,6 / 207,4 / 213,0 km/s**; En $20\ \text{kpc}$ ($F=1,1079$): **194,3 / 199,6 / 204,7 km/s**; En $25\ \text{kpc}$ ($F=1,0643$): **188,6 / 193,6 / 198,2 km/s** | **Ejecución Reproducible por Script (Tablas 1A y 1B).** Contrastada frente a bines primarios de Tabla 1 de Eilers et al. (2019). Presupuesto fenomenológico algebraico (no solución de Poisson no lineal). |
| **A-04. Test Epicíclico en Radio Solar** | $r_\odot = 8,00\ \text{kpc}$; $v_c = 229,0 - 230,2\ \text{km/s}$; Curva plana: $\kappa / \Omega = \sqrt{2}$ | Ec. (18a–18b): $T_{\text{orb}} = 2\pi r_\odot / v_c$; $T_r = T_{\text{orb}} / \sqrt{2}$ | $T_{\text{orb}} = 214,6 - 215,7\text{ M años}$; $T_r = 151,8 - 152,5\text{ M años}$ ($\approx 152,0$) | **Propiedad Dinámica de Curva Plana.** No es predicción exclusiva de $N_7$. |
| **A-05. Galaxias NGC 3198 y M33 (SPARC)** | NGC 3198: $v_f = 150,1 \pm 3,0\ \text{km/s}$; M33: $v_f = 96,0 \pm 4,0\ \text{km/s}$ | Ec. (10): $M_t = v_f^4 / (G \cdot a_0)$ | NGC 3198: $(3,19 \pm 0,25) \times 10^{10}\ M_\odot$; M33: $(5,33 \pm 0,89) \times 10^{9}\ M_\odot$ | **Ejemplos Ilustrativos Individuales.** No sustituyen un análisis estadístico de muestra completa. |
| **A-06. Cúmulos Virgo y Coma en $r_{200}$ (Jeans 3D)** | Virgo: $\sigma_r \approx 577\ \text{km/s}$; Coma: $\sigma_r \approx 693\ \text{km/s}$; Supuestos: $\alpha = 3$, $\beta_{\text{anis}} = 0$ | Ec. (14): $M_{\text{dyn,ef}} = \alpha^2 \sigma_r^4 / (G \cdot a_0)$; Población II: $M_c \equiv M_{\text{BCG}}$ | Virgo: $M_{\text{dyn,ef}} = 6,28 \times 10^{13}\ M_\odot$; Coma: $M_{\text{dyn,ef}} = 1,30 \times 10^{14}\ M_\odot$ | **Estimación Condicional de Orden de Magnitud.** No resuelve el déficit bariónico del núcleo interno de Coma (Sanders, 2003). |
| **A-07. Escenario Condicional $N_7$** | Parámetro de referencia: $M_{N1} = 1,00 \times 10^{21}\ M_\odot$; $M_t(N_7) = 7 \times 10^{21}\ M_\odot$ | Extrapolación algebraica de Ec. (10) y Ec. (7): $v_f = (G M_t a_0)^{1/4}$; $r_t = \sqrt{G M_t / a_0}$ | $v_f = 102.760 \approx 103.000\ \text{km/s}$ ($0,343c$, $\gamma = 1,0645$); $r_t = 9.310\text{ M a.l.}$ | **Hipótesis Exploratoria Condicional.** Consecuencia matemática del $M_t$ postulado; su interpretación física requeriría tratamiento relativista. |
| **A-08. Campo Vectorial de Hubble y Atenuación** | Postulados exploratorios: $T = 2,0 \times 10^9\text{ años}$; eje $(l_c = 295^\circ, b_c = +15^\circ)$; $H_\gamma \approx 67,4$; $|\vec{H}_{\text{cin}}| \approx 5,6$ | Ec. (16–17): $H_{\text{obs}}(\hat{n}) = H_\gamma + \vec{H}_{\text{cin}}\cdot\hat{n}$ | Dipolo previsto $\Delta H_0 \approx 5,6\ \text{km/s/Mpc}$; $A/R_0 = 0,18\%$ o $2,27\%$ | **Hipótesis Fenomenológica No Validada.** Sujeta a refutación en Pantheon+ y a pruebas pendientes de supernovas, Tolman, Etherington y CMB. |

---

## Referencias Científicas y Técnicas

1. Milgrom, M. (1983). A modification of the Newtonian dynamics as a possible alternative to the hidden mass hypothesis. *The Astrophysical Journal*, 270, 365-370; y Milgrom, M. (2010). Quasi-linear formulation of MOND. *Monthly Notices of the Royal Astronomical Society*, 403(2), 886-895.
2. Bekenstein, J., & Milgrom, M. (1984). Does the missing mass problem signal the breakdown of Newtonian gravity? *The Astrophysical Journal*, 286, 7-14.
3. Brada, R., & Milgrom, M. (1995). Exact solutions and approximations of MOND fields of disc galaxies. *Monthly Notices of the Royal Astronomical Society*, 276(2), 453-459.
4. Freeman, K. C. (1970). On the disks of spiral and S0 galaxies. *The Astrophysical Journal*, 160, 811-830.
5. Binney, J., & Tremaine, S. (2008). *Galactic Dynamics* (2nd ed.). Princeton University Press.
6. Eilers, A.-C., Hogg, D. W., Rix, H.-W., & Ness, M. K. (2019). The Circular Velocity Curve of the Milky Way from 5 to 25 kpc. *The Astrophysical Journal*, 871(1), 120.
7. Sofue, Y. (2013). Rotation Curve and Mass Distribution of the Milky Way Galaxy. *Publications of the Astronomical Society of Japan*, 65(6), 118; y Bland-Hawthorn, J., & Gerhard, O. (2016). *Annual Review of Astronomy and Astrophysics*, 54, 529-596.
8. McMillan, P. J. (2017). The mass distribution and gravitational potential of the Milky Way. *Monthly Notices of the Royal Astronomical Society*, 465(1), 76-94; y Licquia, T. C., & Newman, J. A. (2015). *The Astrophysical Journal*, 806(1), 96.
9. Bovy, J., & Rix, H.-W. (2013). A Direct Dynamical Measurement of the Milky Way's Disk Surface Density Profile, Disk Scale Length, and Dark Matter Profile at 4 kpc <= R <= 9 kpc. *The Astrophysical Journal*, 779(2), 115.
10. Lelli, F., McGaugh, S. S., & Schombert, J. M. (2016). SPARC: Mass Models for 175 Disk Galaxies with Spitzer Photometry. *The Astronomical Journal*, 152(6), 157; y McGaugh, S. S., Lelli, F., & Schombert, J. M. (2016). *Physical Review Letters*, 117(20), 201101.
11. Corbelli, E., et al. (2014). Dynamical signatures of disk-halo interaction in M33. *Astronomy & Astrophysics*, 572, A23.
12. GRAVITY Collaboration (Abuter, R., et al.). (2018). Detection of the gravitational redshift in the orbit of the star S2 near the Galactic centre massive black hole. *Astronomy & Astrophysics*, 615, L15.
13. Event Horizon Telescope Collaboration (Akiyama, K., et al.). (2019). First M87 Event Horizon Telescope Results. VI. The Shadow and Mass of the Central Black Hole. *The Astrophysical Journal Letters*, 875(1), L6.
14. Bender, R., et al. (2005). HST STIS Spectroscopy of the Triple Nucleus of M31. *The Astrophysical Journal*, 631(1), 280; Tamm, A., et al. (2012). *Astronomy & Astrophysics*, 546, A4; Kormendy, J., et al. (1996). *ApJ*, 473, L91; Tempel, E., & Tenjes, P. (2006). *MNRAS*, 371, 1269; Murphy, J. D., Gebhardt, K., & Adams, J. J. (2011). *ApJ*, 729, 129; Cappellari, M., et al. (2009). *MNRAS*, 394, 661; Woodley, K. A., et al. (2007). *AJ*, 134, 494.
15. Binggeli, B., Popescu, C. C., & Tammann, G. A. (1993). The kinematics of the Virgo cluster revisited. *Astronomy and Astrophysics Supplement Series*, 98, 275-296; Böhringer, H., et al. (1994). *Nature*, 368, 828-831; y Urban, O., et al. (2011). *MNRAS*, 414(3), 2101-2111.
16. Colless, M., & Dunn, A. M. (1996). Structure and dynamics of the Coma Cluster. *The Astrophysical Journal*, 458, 435.
17. Sanders, R. H. (2003). Clusters of galaxies with modified Newtonian dynamics. *Monthly Notices of the Royal Astronomical Society*, 342(3), 901-908.
18. Shull, J. M., Smith, B. D., & Danforth, C. W. (2012). The Baryon Census in a Multiphase Intergalactic Medium: 30% of the Baryons May Still Be Missing. *The Astrophysical Journal*, 759(1), 23.
19. Proust, D., et al. (2006). The Shapley supercluster: the largest matter concentration in the local Universe. *Astronomy & Astrophysics*, 447(1), 133-144.
20. Migkas, K., et al. (2020). Probing cosmic isotropy with a new X-ray galaxy cluster sample through the L_X-T scaling relation. *Astronomy & Astrophysics*, 636, A15; y Carrick, J., et al. (2015). *MNRAS*, 450(1), 317-332.
21. Antoja, T., et al. (2018). A dynamically young and perturbed Milky Way disk. *Nature*, 561(7723), 360-362.
22. Planck Collaboration. (2020). Planck 2018 results. VI. Cosmological parameters. *Astronomy & Astrophysics*, 641, A6.
23. Riess, A. G., et al. (2019). Large Magellanic Cloud Cepheid Standards Provide a 1% Foundation for the Determination of the Hubble Constant. *The Astrophysical Journal*, 876(1), 85.
24. Zwicky, F. (1929). On the Red Shift of Spectral Lines through Interstellar Space. *Proceedings of the National Academy of Sciences*, 15(10), 773-779.

## Fuentes Filosóficas y Motivacionales (Antecedentes Conceptuales No Técnicos)

- Fundación Urantia. (1955). *El Libro de Urantia*. (Documento 15: Los Siete Superuniversos; Documento 12: El Universo de los Universos; Documento 11: La Isla Eterna del Paraíso). [Citado exclusivamente como fuente de inspiración filosófica y heurística para la exploración del parámetro condicional $N_7$, sin atribuirle valor de evidencia científica o astronómica].
