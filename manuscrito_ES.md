# EL COSMOS ARQUITECTÓNICO: APROVECHANDO LAS COSMOGONÍAS JERÁRQUICAS PARA RESOLVER LA ANOMALÍA DE LA MATERIA OSCURA Y EL BIG BANG MEDIANTE DINÁMICAS DEPENDIENTES DE LA ESCALA

**Mauricio Rivadeneira (1*), Colaborador de Investigación de IA (2)**
(1) Investigador Independiente, Unidad de Simulación Avanzada de Física Computacional
*Contacto: maurivadeneira@gmail.com
**Octubre de 2026 — Versión 10.0 (Edición Integral Unificada con Auditoría Numérica Cerrada en Radios Exactos de Eilers et al. 2019 y Script Reproducible)**

> "Entregamos este manuscrito del Cosmos Arquitectónico como un andamio en construcción que nos permita aumentar la comprensión de nuestro universo majestuoso e inconmensurable; un cosmos infinito, estructurado y eterno."

---

## RESUMEN

Presentamos la formulación de un modelo fenomenológico explícito dependiente de la escala y un programa de pruebas falsables que demuestran que, al describir correctamente la transición dinámica sobre la materia bariónica real en regímenes de aceleración ultrabaja, se explica de manera suficiente el cosmos fenomenológico sin necesidad de postular entidades inobservables (materia y energía oscuras). Asimismo, frente a los modelos de creación a partir de la nada (*ex nihilo*), este marco restituye la aceptación formal de los principios fundamentales de conservación de la materia y la energía, cuya consecuencia natural es un cosmos eterno, sin principio ni fin, estructurado y continuo. Partiendo del parámetro crítico de aceleración ($a_0 = 1,20 \times 10^{-10}\ \text{m/s}^2$, convergente en su límite asintótico con la dinámica de Milgrom) y fijando la función de transición racional única $\mu(x) = \frac{x}{1+x}$, derivamos una solución algebraica cuadrática cerrada que conecta continuamente el régimen newtoniano ($1/r^2$) con el régimen asintótico de vórtice o remolino ($1/r$). En la Vía Láctea, implementando un modelo bariónico explícito y uniforme en todo el documento —compuesto por un bulbo esferoidal de Hernquist ($M_b = 1,00 \times 10^{10}\ M_\odot$, radio de escala $a_b = 0,60\ \text{kpc}$) más un disco exponencial de Freeman ($R_d = 2,60\ \text{kpc}$, evaluado en tres perfiles paramétricos: Rama A con $M_d = 4,50 \times 10^{10}\ M_\odot$, Perfil Central C con $M_d = 5,00 \times 10^{10}\ M_\odot$ y Rama B con $M_d = 5,50 \times 10^{10}\ M_\odot$)—, generamos mediante un único código reproducible en Python (`scipy.special`, incluido en el Anexo Técnico) la curva de rotación radial entre $5,0\ \text{kpc}$ y $25,0\ \text{kpc}$ (Tabla 1A) y la evaluamos directamente en los radios exactos $R_{\text{bin}}$ de las mediciones primarias de Eilers et al. (2019) con incertidumbre sistemática radialmente progresiva del $3\%$ al $5\%$ (Tabla 1B). Bajo este presupuesto fenomenológico algebraico (que no equivale a resolver la ecuación de Poisson no lineal), el Perfil Central C arroja en la Tabla 1A velocidades exactas de $228,7\ \text{km/s}$ en $5,0\ \text{kpc}$, $231,4\ \text{km/s}$ en $6,0\ \text{kpc}$, $230,2\ \text{km/s}$ en la posición solar $r_\odot = 8,0\ \text{kpc}$ (frente a $229,0\ \text{km/s}$ de referencia), $224,9\ \text{km/s}$ en $10,0\ \text{kpc}$, **$218,6\ \text{km/s}$** en $12,0\ \text{kpc}$, $207,4\ \text{km/s}$ en $16,0\ \text{kpc}$, $199,6\ \text{km/s}$ en $20,0\ \text{kpc}$ y $193,6\ \text{km/s}$ en $25,0\ \text{kpc}$ (y en los bines exactos de Eilers et al. en la Tabla 1B, residuos directos de $+2,95\ \text{km/s}$ en $5,27\ \text{kpc}$, $+0,42\ \text{km/s}$ en $6,27\ \text{kpc}$, $+0,86\ \text{km/s}$ en $7,78\ \text{kpc}$ y $-4,57\ \text{km/s}$ en $24,82\ \text{kpc}$).

A escala de galaxias espirales y cúmulos esferoidales modelados bajo equilibrio hidrostático isotrópico de Jeans, distinguimos explícitamente entre la masa bariónica observada ($M_{\text{bar,obs}}$), la masa bariónica inferida por la ley de escala de Tully-Fisher ($M_{\text{bar,TF}}$) y la masa dinámica efectiva ($M_{\text{dyn,ef}}$), conservando la identidad contable $M_t = M_c + M_r$ con equivalencia operacional separada por población ($M_c \equiv M_{\text{BH}}$ en galaxias 2D y $M_c \equiv M_{\text{BCG}}$ en cúmulos 3D), e ilustrando como hipótesis empírica de trabajo la relación $M_c / M_t < 0,01$. A escala macrocósmica, reconocemos con total transparencia que el escenario paramétrico $N_7$ ($M_{t(N7)} = 7,00 \times 10^{21}\ M_\odot$ a partir de $M_{N1} = 1,00 \times 10^{21}\ M_\odot$, con consecuencia algebraica $v_f = 102.754 \approx 103.000\ \text{km/s}$ y $r_t = 9.300 - 9.310\text{ millones de años luz}$), el ciclo armónico completo de respiración radial ($R(t) = R_0 - A\cos(2\pi t/T)$ con $T = 2.000\text{ millones de años}$) y la descomposición vectorial de Hubble ($H_{\text{obs}} = H_\gamma + \vec{H}_{\text{cin}} \cdot \hat{n}$) constituyen ejercicios paramétricos en construcción, pero los definimos como un nuevo intento heurístico para construir un mapa cósmico diáfano que nos encamine hacia la verdadera configuración del universo a partir de observaciones directas.

---

## Nota Metodológica: Sinergia Cognitiva, Suficiencia Bariónica y Demarcación Epistemológica

El presente manuscrito es el resultado de un modelo de investigación aumentada, donde la dirección conceptual, el establecimiento de los axiomas topológicos y la validación lógica final son autoría exclusiva del investigador principal. El desarrollo del trabajo contó con la integración activa de Inteligencia Artificial Avanzada operando como colaborador analítico en la estructuración de registros astronómicos, auditoría algebraica y programación reproducible.

Establecemos dos pilares metodológicos que rigen la lectura de todo el documento:

1. **La superfluidad de lo inobservable y la primacía de los principios de conservación:** Declaramos que este trabajo no parte de una oposición ideológica hacia la materia oscura, la energía oscura o el Big Bang, sino de constatar que dichas nociones operan en la práctica como etiquetas que clausuran la explicación física. Mostramos que, al describir adecuadamente la transición dinámica dependiente de la escala sobre la materia bariónica real, se explica suficientemente la fenomenología observada en el dominio analizado sin imponer entidades invisibles por norma. De igual modo, al suprimir el postulado de un universo surgido de la nada, restituimos con plena aceptación formal los principios fundamentales de conservación de la materia y la energía, cuya consecuencia lógica y física es un cosmos eterno, sin principio ni fin, estructurado y continuo.
2. **Demarcación estricta en tres niveles epistemológicos:**
   - *Nivel 1 — Consecuencias Algebraicas y Numéricas Reproducibles:* Deducciones matemáticas cerradas y evaluaciones computacionales exactas verificadas mediante el script del Anexo Técnico (Secciones 1.4, 2.1, 2.2, 3.1 y 3.4).
   - *Nivel 2 — Contrastes Empíricos Preliminares:* Comparaciones cuantitativas sobre sistemas específicos (curva radial de la Vía Láctea evaluada directamente en los bines primarios de Eilers et al., 2019; tres galaxias ilustrativas de SPARC; y estimaciones condicionales de orden de magnitud en dos cúmulos).
   - *Nivel 3 — Brújula Heurística y Ejercicios Paramétricos en Construcción:* La hipótesis de trabajo $M_c / M_t < 0,01$, el escenario condicional $N_7$, la oscilación armónica de $2.000\text{ millones de años}$ y la descomposición vectorial de Hubble se presentan con total transparencia como ejercicios paramétricos exploratorios —no como resultados cosmológicos cerrados ni derivados de una métrica relativista completa—, cuyo propósito es servir como un nuevo intento para trazar un mapa cósmico diáfano que oriente futuras investigaciones hacia la verdadera configuración del universo (Capítulos 4, 5, 6 y 7).

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

Reconocemos formalmente que este umbral y su límite asintótico corresponden a la Dinámica Newtoniana Modificada (MOND), propuesta por Mordehai Milgrom en 1983, y reproducen la pendiente de la Relación Bariónica de Tully-Fisher. La contribución de este capítulo consiste en fijar una función de transición racional única para evaluar numéricamente perfiles radiales de bulbo más disco exponencial sin parámetros de halo oscuro y explorar después sus extrapolaciones condicionales.

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
- **Baja aceleración profunda ($g_N \ll a_0$):** A grandes radios donde domina el término monopolar ($g_N(r) \approx G M / r^2$ y $4 a_0 / g_N \gg 1$), la Ecuación (5) converge a:

$$a_{\text{prof}}(r) = \sqrt{g_N(r) \cdot a_0} = \frac{\sqrt{G \cdot M \cdot a_0}}{r} \quad \implies \quad F_{\text{prof}} = m \frac{\sqrt{G \cdot M \cdot a_0}}{r} \quad (6)$$

**Delimitación teórica entre el presupuesto algebraico y una teoría de campo conservativa:**
Dejamos explícitamente establecido que la identificación algebraica local $a\,\mu(a/a_0) = g_N$ (Ecuaciones 4 y 5) sólo constituye una solución exacta de una teoría de campo gravitatoria conservativa (como la ecuación de Poisson no lineal de Bekenstein & Milgrom, 1984: $\nabla \cdot [\mu(|\nabla\Phi|/a_0)\nabla\Phi] = 4\pi G \rho$, o QUMOND de Milgrom, 2010) bajo condiciones de simetría esférica o cilíndrica donde el campo vectorial solenoidal ($\nabla \times \vec{h}$) desaparece idénticamente. Dado que un sistema compuesto por un bulbo esferoidal y un disco exponencial carece de simetría esférica, aplicar la Ecuación (5) al campo newtoniano combinado $g_N(r) = g_{N,\text{bulbo}}(r) + g_{N,\text{disco}}(r)$ constituye un **presupuesto fenomenológico de tipo algebraico** (inspirado en las aproximaciones para discos analizadas por Brada & Milgrom, 1995), y no una solución demostrada de la ecuación de Poisson no lineal.

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

## 2.2. Evaluación Exacta de Bessel para la Vía Láctea en Rejilla Estándar (Tabla 1A) y en los Radios Exactos $R_{\text{bin}}$ de Eilers et al. (2019) (Tabla 1B)
Todos los valores reportados en este manuscrito para la Vía Láctea proceden directamente de la salida sin transcripción manual del script verificable en Python (`scipy.special`, incluido en la Sección A.2 del Anexo Técnico), evaluando las Ecuaciones (9a–9c) con las siguientes constantes y entradas explícitas:
- Constantes físicas: $G = 6,674 \times 10^{-11}\ \text{m}^3\text{kg}^{-1}\text{s}^{-2}$, $a_0 = 1,20 \times 10^{-10}\ \text{m/s}^2$, $1\ M_\odot = 1,9885 \times 10^{30}\ \text{kg}$, $1\ \text{kpc} = 3,0857 \times 10^{19}\ \text{m}$.
- Distancia galactocéntrica del Sol: $r_\odot = 8,00\ \text{kpc} = 2,46856 \times 10^{20}\ \text{m}$.
- **Componente 1 — Bulbo esferoidal de Hernquist:** Masa fija $M_b = 1,00 \times 10^{10}\ M_\odot = 1,9885 \times 10^{40}\ \text{kg}$ y longitud de escala radial fija $a_b = 0,60\ \text{kpc} = 1,85142 \times 10^{19}\ \text{m}$:

$$g_{N,\text{bulbo}}(r) = \frac{G \cdot M_b}{(r + a_b)^2} \quad (9\text{a})$$

- **Componente 2 — Disco bariónico exponencial de Freeman:** Longitud de escala radial fija $R_d = 2,60\ \text{kpc} = 8,02282 \times 10^{19}\ \text{m}$. Evaluamos tres perfiles paramétricos de masa bariónica de disco (estrellas más gas frío) tomados del intervalo de estimaciones independientes de la literatura (Bovy & Rix, 2013; Licquia & Newman, 2015; McMillan, 2017):
  * **Rama A (Cota Inferior):** $M_{d,\text{A}} = 4,50 \times 10^{10}\ M_\odot \implies M_{\text{bar,A}} = 5,50 \times 10^{10}\ M_\odot$ (velocidad asintótica monopolar en $r \to \infty$: $v_{f,\text{A}} = 172,1\ \text{km/s}$).
  * **Perfil Central C (Referencia Intermedia):** $M_{d,\text{C}} = 5,00 \times 10^{10}\ M_\odot \implies M_{\text{bar,C}} = 6,00 \times 10^{10}\ M_\odot$ (velocidad asintótica monopolar en $r \to \infty$: $v_{f,\text{C}} = 175,8\ \text{km/s}$).
  * **Rama B (Cota Superior):** $M_{d,\text{B}} = 5,50 \times 10^{10}\ M_\odot \implies M_{\text{bar,B}} = 6,50 \times 10^{10}\ M_\odot$ (velocidad asintótica monopolar en $r \to \infty$: $v_{f,\text{B}} = 179,3\ \text{km/s}$).

La aceleración radial newtoniana exacta en el plano del disco exponencial (Freeman, 1970) en función de $y = \frac{r}{2 R_d}$ y de las funciones modificadas de Bessel $\Delta B(y) = I_0(y) K_0(y) - I_1(y) K_1(y)$ es:

$$g_{N,\text{disco}}(r) = \frac{G \cdot M_d}{r^2} \cdot F_{\text{Bessel}}(y) \quad \text{con } F_{\text{Bessel}}(y) = 4 y^3 \left[I_0(y) K_0(y) - I_1(y) K_1(y)\right] \quad (9\text{b})$$

- **Campo newtoniano total, aceleración modificada y velocidad circular:**

$$g_{N,\text{tot}}(r) = g_{N,\text{bulbo}}(r) + g_{N,\text{disco}}(r) \implies v_N(r) = \sqrt{r \cdot g_{N,\text{tot}}(r)} \implies v_{\text{mod}}(r) = \sqrt{r \cdot a(r)} \quad (9\text{c})$$

**Resolución de H-01 y H-02 en las Tablas 1A y 1B:**
1. En la **Tabla 1A** presentamos la evaluación exacta sobre la rejilla uniforme de radios ($5,0,\ 6,0,\ 8,0,\ 10,0,\ 12,0,\ 16,0,\ 20,0\text{ y }25,0\ \text{kpc}$), corrigiendo el renglón de $12,0\ \text{kpc}$ a los valores exactos arrojados por el código: $g_{N,\text{disco}} = 0,5232 / 0,5813 / 0,6395 \times 10^{-10}\ \text{m/s}^2$, $v_N = 150,4 / 157,4 / 164,1\ \text{km/s}$ y **$v_{\text{mod}} = 212,1 / 218,6 / 224,9\ \text{km/s}$**.
2. En la **Tabla 1B**, para evitar comparar radios de modelo distintos a los radios medidos, **evaluamos las Ecuaciones (9a–9c) directamente en los radios exactos $R_{\text{bin}}$ publicados en la Tabla 1 de Eilers et al. (2019)** ($R_{\text{bin}} = 5,27,\ 6,27,\ 7,78,\ 8,27,\ 10,27,\ 12,26,\ 15,78,\ 19,82\text{ y }24,82\ \text{kpc}$). Asimismo, incorporamos una fracción de incertidumbre sistemática radialmente dependiente $f_{\text{sys}}(R)$ que crece linealmente desde el $3\%$ en $R \le 8,0\ \text{kpc}$ hasta el $5\%$ en $R = 25,0\ \text{kpc}$ ($f_{\text{sys}}(R) = 0,03 + 0,02 \cdot \max(0, (R - 8,0)/17,0)$, conforme a la Sección 4 y Figura 3 de Eilers et al., 2019), definiendo $\sigma_{\text{sys}}(R) = f_{\text{sys}}(R) \cdot v_{c,\text{bin}}$ y $\sigma_{\text{comb}}(R) = \sqrt{\sigma_{\text{stat,med}}^2 + \sigma_{\text{sys}}(R)^2}$ (donde $\sigma_{\text{stat,med}}$ es el error estadístico direccional correspondiente al signo del residuo: $\sigma_+$ si $v_{\text{mod}} > v_{c,\text{bin}}$ y $\sigma_-$ si $v_{\text{mod}} < v_{c,\text{bin}}$). Reiteramos que el cociente $z_{\text{C}} = \Delta v_{\text{C}} / \sigma_{\text{comb}}$ es un **indicador descriptivo aproximado punto a punto** y no un estadístico de verosimilitud global con matriz de covarianza completa.

### Tabla 1A: Evaluación Reproducible en Rejilla Uniforme ($5,0\text{ a }25,0\ \text{kpc}$) Verificada por Script

| $r$ (kpc) | $y = r/(2R_d)$ | $\Delta B(y)$ Exacto | $F_{\text{Bessel}}(y)$ Exacto | $g_{N,\text{bulbo}}$ ($10^{-10}\ \text{m/s}^2$) | $g_{N,\text{disco}}$ [A / C / B] ($10^{-10}\ \text{m/s}^2$) | $g_{N,\text{tot}}$ [A / C / B] ($10^{-10}\ \text{m/s}^2$) | $v_N$ Kepler [A / C / B] (km/s) | $a(r)$ Ec. 5 [A / C / B] ($10^{-10}\ \text{m/s}^2$) | $v_{\text{mod}}$ [Rama A / Central C / Rama B] (km/s) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **5,0** | 0,96154 | 0,20763 | **0,7384** | 0,4444 | 1,8503 / 2,0559 / 2,2615 | 2,295 / 2,500 / 2,706 | **188,2 / 196,4 / 204,3** | 3,168 / 3,390 / 3,610 | **221,1 / 228,7 / 236,0** |
| **6,0** | 1,15385 | 0,14488 | **0,8902** | 0,3197 | 1,5489 / 1,7210 / 1,8931 | 1,869 / 2,041 / 2,213 | **186,1 / 194,5 / 202,5** | 2,700 / 2,890 / 3,079 | **223,7 / 231,4 / 238,8** |
| **8,0** | 1,53846 | 0,07493 | **1,0914** | 0,1885 | 1,0681 / 1,1868 / 1,3055 | 1,257 / 1,375 / 1,494 | **176,1 / 184,3 / 192,1** | 2,009 / 2,147 / 2,284 | **222,7 / 230,2 / 237,4** |
| **10,0** | 1,92308 | 0,04150 | **1,1807** | 0,1241 | 0,7398 / 0,8220 / 0,9042 | 0,864 / 0,946 / 1,028 | **163,3 / 170,9 / 178,1** | 1,543 / 1,644 / 1,743 | **217,9 / 224,9 / 231,7** |
| **12,0** | 2,30769 | 0,02444 | **1,2011** | 0,0878 | 0,5232 / 0,5813 / 0,6395 | 0,611 / 0,669 / 0,727 | **150,4 / 157,4 / 164,1** | 1,216 / 1,291 / 1,365 | **212,1 / 218,6 / 224,9** |
| **16,0** | 3,07692 | 0,00996 | **1,1611** | 0,0506 | 0,2841 / 0,3156 / 0,3472 | 0,335 / 0,366 / 0,398 | **128,6 / 134,5 / 140,2** | 0,823 / 0,872 / 0,919 | **201,6 / 207,4 / 213,0** |
| **20,0** | 3,84615 | 0,00487 | **1,1079** | 0,0328 | 0,1735 / 0,1928 / 0,2121 | 0,206 / 0,226 / 0,245 | **112,8 / 118,0 / 122,9** | 0,612 / 0,646 / 0,679 | **194,3 / 199,6 / 204,7** |
| **25,0** | 4,80769 | 0,00239 | **1,0643** | 0,0212 | 0,1067 / 0,1185 / 0,1304 | 0,128 / 0,140 / 0,152 | **99,3 / 103,8 / 108,1** | 0,461 / 0,486 / 0,510 | **188,6 / 193,6 / 198,2** |

### Tabla 1B: Evaluación del Modelo Directamente en los Radios Observacionales Exactos ($R_{\text{bin}}$) de Eilers et al. (2019)

| Radio Exacto Bin $R_{\text{bin}}$ (kpc) | $F_{\text{Bessel}}(R_{\text{bin}})$ Exacto | $v_{\text{mod}}(R_{\text{bin}})$ [Rama A / Central C / Rama B] (km/s) | Dato Primario Tabla 1 de Eilers et al. (2019) [$v_{c,\text{bin}} (+\sigma_+ / -\sigma_-)$] | Sistemático Radial ($f_{\text{sys}}, \sigma_{\text{sys}}$) y Combinado ($\sigma_{\text{comb}}$) | Residuo en $R_{\text{bin}}$ ($\Delta v_{\text{C}} = v_{\text{mod,C}} - v_{c,\text{bin}}$) | Indicador Descriptivo $z_{\text{C}}$ (y $z_{\text{B}}$ en ext.) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **5,27** | 0,7834 | **222,1 / 229,8 / 237,1** | **226,83 (+1,91 / -1,90) km/s** | $3,00\%$ ($6,80$) ; $\sigma_{\text{comb}} = 7,07\ \text{km/s}$ | **+2,95 km/s** | +0,42 |
| **6,27** | 0,9238 | **223,9 / 231,2 / 238,6** | **230,80 (+1,38 / -1,32) km/s** | $3,00\%$ ($6,92$) ; $\sigma_{\text{comb}} = 7,06\ \text{km/s}$ | **+0,42 km/s** | +0,06 |
| **7,78** | 1,0736 | **223,0 / 230,5 / 237,7** | **229,63 (+0,60 / -0,63) km/s** | $3,00\%$ ($6,89$) ; $\sigma_{\text{comb}} = 6,92\ \text{km/s}$ | **+0,86 km/s** | +0,12 |
| **8,27** | 1,1111 | **222,2 / 229,7 / 236,8** | **228,89 (+0,61 / -0,60) km/s** | $3,03\%$ ($6,94$) ; $\sigma_{\text{comb}} = 6,97\ \text{km/s}$ | **+0,78 km/s** | +0,11 |
| **10,27** | 1,1868 | **217,1 / 224,1 / 230,8** | **224,96 (+0,84 / -0,96) km/s** | $3,27\%$ ($7,35$) ; $\sigma_{\text{comb}} = 7,41\ \text{km/s}$ | **-0,86 km/s** | -0,12 |
| **12,26** | 1,2009 | **211,3 / 217,8 / 224,0** | **220,96 (+1,22 / -1,27) km/s** | $3,50\%$ ($7,74$) ; $\sigma_{\text{comb}} = 7,84\ \text{km/s}$ | **-3,15 km/s** (+3,0 en B) | -0,40 (+0,38 en B) |
| **15,78** | 1,1641 | **202,2 / 208,0 / 213,6** | **217,47 (+1,86 / -2,15) km/s** | $3,92\%$ ($8,51$) ; $\sigma_{\text{comb}} = 8,78\ \text{km/s}$ | **-9,46 km/s** (-3,9 en B) | -1,08 (-0,44 en B) |
| **19,82** | 1,1101 | **194,6 / 199,9 / 205,0** | **206,54 (+4,18 / -3,97) km/s** | $4,39\%$ ($9,07$) ; $\sigma_{\text{comb}} = 9,90\ \text{km/s}$ | **-6,61 km/s** (-1,5 en B) | -0,67 (-0,15 en B) |
| **24,82** | 1,0655 | **188,8 / 193,9 / 198,5** | **198,42 (+6,12 / -6,50) km/s** | $4,98\%$ ($9,88$) ; $\sigma_{\text{comb}} = 11,83\ \text{km/s}$ | **-4,57 km/s** (+0,1 en B) | -0,39 (+0,01 en B) |

**Convergencia hacia la asíntota monopolar a radios extremos ($r \gg 25\ \text{kpc}$):**
En $r = 25,0\ \text{kpc}$ ($y = 4,81$), la curva aún se encuentra un $\sim 10\%$ por encima de su límite asintótico monopolar infinito ($v_{f,\text{C}} = (G M_{\text{bar,C}} a_0)^{1/4} = 175,8\ \text{km/s}$, y $v_{f,\text{B}} = 179,3\ \text{km/s}$) debido a dos contribuciones positivas que decaen como $1/r$: el término constante $+g_N / 2$ de la Ecuación (5) y el exceso multipolar del disco de Freeman ($F_{\text{Bessel}} = 1,0643 > 1$). Al extender el cálculo con el mismo script hasta $r = 50\ \text{kpc}$ y $r = 100\ \text{kpc}$ (rango de trazadores de halo estudiado por Huang et al., 2016), el Perfil Central C desciende suavemente a $183,2\ \text{km/s}$ ($50\ \text{kpc}$) y $179,3\ \text{km/s}$ ($100\ \text{kpc}$), convergiendo matemáticamente hacia su asíntota exacta $v_{f,\text{C}} = 175,8\ \text{km/s}$ cuando $r \to \infty$.

## 2.3. Contraste del Límite Newtoniano en Alta Aceleración (Sistema Solar y Estrella S2)
1. **Interior del Sistema Solar ($r = 1\ \text{UA}$, $M = 1\ M_\odot$):** $g_N = 5,930 \times 10^{-3}\ \text{m/s}^2 \implies a / g_N - 1 = 2,02 \times 10^{-8}$.
2. **Estrella S2 en Pericentro (Sagitario A*, $M_c = 4,30 \times 10^6\ M_\odot$, $r_p = 120\ \text{UA}$, $e = 0,8846$):** $g_N = 1,77\ \text{m/s}^2 \approx 1,47 \times 10^{10} a_0 \implies \mu \approx 1$, arrojando una velocidad pericéntrica kepleriana de $v_p = 7.650\ \text{km/s}$. *(Dejamos expresamente aclarado que este cálculo verifica únicamente que la Ecuación 5 regresa sin desviaciones al límite newtoniano cuando $g_N \gg a_0$; no constituye una prueba de la estructura relativista del modelo ni deriva por sí mismo el corrimiento al rojo gravitacional post-newtoniano medido por GRAVITY Collaboration, 2018).*
3. **Cancelación de la masa de prueba ($m$) en el disco exterior:** Al cancelarse $m$ en la Ecuación (4), cuerpos de prueba de masas opuestas (p. ej., $0,08\ M_\odot$ frente a $21\ M_\odot$) siguen exactamente el mismo perfil de velocidad de las Tablas 1A y 1B en cualquier radio $r$.

---

# CAPÍTULO 3: DISTINCIÓN ENTRE MASAS ($M_{\text{bar,obs}}, M_{\text{bar,TF}}, M_{\text{dyn,ef}}$), CÁLCULO EN CÚMULOS Y PARTICIÓN CONTABLE $M_t = M_c + M_r$

## 3.1. Separación Conceptual de Masas en la Relación Bariónica de Tully-Fisher (Resolución de H-03)
En el límite exterior monopolar ($r \gg R_d$, $g_N \ll a_0$), igualando $v_f^2 / r$ con la Ecuación (6), el modelo predice una relación de escala directa entre la velocidad circular asintótica ($v_f$) y la masa bariónica de la fuente. Para evitar cualquier confusión conceptual entre la masa bariónica observada, la masa inferida por esta ley de escala y la masa dinámica newtoniana estándar (atendiendo **H-03**), definimos tres magnitudes estrictamente diferenciadas:

1. **$M_{\text{bar,obs}} = M_* + 1,33 M_{\text{HI}}$:** Masa bariónica observada directamente mediante fotometría estelar y radioastronomía de gas neutro.
2. **$M_{\text{bar,TF}} = \frac{v_f^4}{G \cdot a_0}$ (Ecuación 10):** Masa bariónica inferida a partir de la velocidad asintótica medida $v_f$ bajo la relación de escala de Tully-Fisher predicha por el régimen profundo del modelo.
3. **$M_{\text{dyn,N}}(r) = \frac{r \cdot v^2(r)}{G}$:** Masa dinámica newtoniana clásica que se requeriría en gravitación estándar ($1/r^2$) dentro del radio $r$ (la cual diverge linealmente con $r$ cuando $v(r) \approx v_f$).

El contraste físico de la Ecuación (10) consiste en evaluar si la masa bariónica inferida cinemáticamente por la ley de escala ($M_{\text{bar,TF}}$) concuerda con el inventario bariónico medido fotométricamente ($M_{\text{bar,obs}}$), haciendo innecesario el exceso $M_{\text{dyn,N}}(r) - M_{\text{bar,obs}}$:

| Galaxia (Referencia) | Velocidad Asintótica en $r \gg R_d$ ($v_f$) | Masa Bariónica Inferida por Escala TF ($M_{\text{bar,TF}} = v_f^4 / G a_0$) | Masa Bariónica Observada ($M_{\text{bar,obs}} = M_* + 1,33 M_{\text{HI}}$) | Diferencia Relativa ($(M_{\text{bar,TF}} - M_{\text{bar,obs}})/M_{\text{bar,obs}}$) |
| :--- | :--- | :--- | :--- | :--- |
| **Vía Láctea** (Límite $r \to \infty$ de Perfiles A–C–B) | $175,8 \pm 3,6\ \text{km/s}$ (asíntota de $5,5 - 6,5 \times 10^{10}\ M_\odot$) | $(6,00 \pm 0,50) \times 10^{10}\ M_\odot$ | $(5,50 - 6,50) \times 10^{10}\ M_\odot$ | Identidad exacta en el límite $r \to \infty$ (en $r=25\ \text{kpc}$, $v_{\text{mod}}$ aún supera a $v_f$ en $\sim 10\%$) |
| **NGC 3198** (Lelli et al., 2016 - SPARC) | $150,1 \pm 3,0\ \text{km/s}$ | $(3,19 \pm 0,25) \times 10^{10}\ M_\odot$ | $(3,05 \pm 0,45) \times 10^{10}\ M_\odot$ | $+4,6\%$ (Compatible en $1\sigma$) |
| **M33 / NGC 598** (SPARC / Corbelli 2014) | $96,0 \pm 4,0\ \text{km/s}$ | $(5,33 \pm 0,89) \times 10^{9}\ M_\odot$ | $(5,00 \pm 0,80) \times 10^{9}\ M_\odot$ | $+6,6\%$ (Compatible en $1\sigma$) |

*(Delimitación estadística: Estos tres casos ilustran la consistencia entre $M_{\text{bar,TF}}$ y $M_{\text{bar,obs}}$ en galaxias individuales bien caracterizadas; el análisis estadístico sobre las 175 galaxias del catálogo SPARC se encuentra establecido en Lelli et al., 2016 y McGaugh et al., 2016).*

## 3.2. Analogía Conceptual: Regímenes de Corto y Largo Alcance
Mantenemos explícitamente como analogía conceptual heurística (y no como identidad de mecanismo físico) el paralelismo entre el desdoblamiento gravitatorio de corto alcance ($1/r^2$, $g_N \gg a_0$) y largo alcance ($1/r$, $g_N \ll a_0$) frente a los regímenes de corto y largo alcance observados en las interacciones nucleares y electromagnéticas.

## 3.3. Nomenclatura Contable ($M_t = M_c + M_r$), Definición Operacional por Población e Hipótesis de Trabajo del 1%
Conservamos la notación contable de partición:

$$M_t = M_c + M_r \quad (11)$$

Reconociendo expresamente que las definiciones de $M_t$ y $M_c$ cambian de significado físico al pasar de galaxias individuales a cúmulos de galaxias, especificamos por separado ambas razones adimensionales sin afirmar que constituyan una ley dinámica universal demostrada:

1. **En Galaxias Individuales (Razón Agujero Negro a Masa Bariónica Observada):**
   Definimos $M_t \equiv M_{\text{bar,obs}}$, $M_c \equiv M_{\text{BH}}$ (masa del agujero negro supermasivo central) y $M_r = M_{\text{bar,obs}} - M_{\text{BH}}$ (masa bariónica del bulbo más disco).
2. **En Cúmulos de Galaxias (Razón Masa Estelar de la Galaxia Central Dominante a Masa Dinámica Efectiva en $r_{200}$):**
   Definimos $M_t \equiv M_{\text{dyn,ef}}(r_{200})$ (masa dinámica efectiva inferida en el radio virial bajo la Ecuación 14), $M_c \equiv M_{\text{BCG}}$ (masa bariónica estelar de la galaxia central dominante tipo cD) y la diferencia numérica $M_r = M_{\text{dyn,ef}}(r_{200}) - M_{\text{BCG}}$. *(Dejamos explícitamente aclarado que restar una masa bariónica estelar $M_{\text{BCG}}$ de una masa dinámica efectiva inferida $M_{\text{dyn,ef}}$ es una convención contable de comparación de escalas y no demuestra una partición física homogénea).*

En ambos casos, observamos como **hipótesis empírica de trabajo** (ilustrada en los ejemplos siguientes y sujeta a contrastación en muestras completas) que el cociente entre el nodo central y la masa de referencia del sistema se sitúa por debajo del $1\%$:

$$\frac{M_c}{M_t} < 0,01 \quad \Longleftrightarrow \quad M_r > 0,99 \cdot M_t \quad (12)$$

Ejemplos ilustrativos en galaxias individuales ($M_c \equiv M_{\text{BH}}$, $M_t \equiv M_{\text{bar,obs}}$):
1. **Vía Láctea:** $M_{\text{bar,obs}} \approx 0,60 \times 10^{11}\ M_\odot$ (Perfil Central C), $M_{\text{BH}} = 4,30 \times 10^6\ M_\odot$ (GRAVITY, 2018), $M_{\text{BH}} / M_{\text{bar,obs}} = 0,0072\%$.
2. **Andrómeda (M31):** $M_{\text{bar,obs}} \approx 1,50 \times 10^{11}\ M_\odot$ (Tamm et al., 2012), $M_{\text{BH}} = 1,40 \times 10^8\ M_\odot$ (Bender et al., 2005), $M_{\text{BH}} / M_{\text{bar,obs}} = 0,093\%$.
3. **Sombrero (M104):** $M_{\text{bar,obs}} \approx 2,10 \times 10^{11}\ M_\odot$ (Tempel & Tenjes, 2006), $M_{\text{BH}} = 1,00 \times 10^9\ M_\odot$ (Kormendy et al., 1996), $M_{\text{BH}} / M_{\text{bar,obs}} = 0,476\%$.
4. **M87 (NGC 4486):** $M_{\text{bar,obs}} \approx 12,00 \times 10^{11}\ M_\odot$ (Murphy et al., 2011), $M_{\text{BH}} = 6,50 \times 10^9\ M_\odot$ (EHT, 2019), $M_{\text{BH}} / M_{\text{bar,obs}} = 0,542\%$.
5. **Centaurus A (NGC 5128):** $M_{\text{bar,obs}} \approx 8,00 \times 10^{11}\ M_\odot$ (Woodley et al., 2007), $M_{\text{BH}} = 5,50 \times 10^9\ M_\odot$ (Cappellari et al., 2009), $M_{\text{BH}} / M_{\text{bar,obs}} = 0,688\%$.

## 3.4. Ecuación Hidrostática de Jeans en Cúmulos 3D y Condicionalidad de los Supuestos
En un sistema esférico tridimensional en equilibrio estacionario con isotropía de velocidades ($\beta_{\text{anis}} = 0$), la ecuación de Jeans relaciona la densidad de trazadores $\rho(r)$ y la dispersión de velocidad radial ($\sigma_r$) con la aceleración gravitatoria $a(r)$:

$$\frac{1}{\rho(r)} \frac{d\left(\rho(r) \sigma_r^2\right)}{dr} = -a(r) \quad \implies \quad a(r) = \frac{\alpha(r) \cdot \sigma_r^2}{r} \quad \left(\text{para } \sigma_r \approx \text{const. y } \alpha = -\frac{d \ln \rho}{d \ln r}\right) \quad (13)$$

Si evaluamos el sistema en el radio virial de referencia ($r \approx r_{200}$, donde la aceleración centrípeta $a(r_{200}) = \alpha \sigma_r^2 / r_{200} \approx (0,2 - 0,3) \times 10^{-10}\ \text{m/s}^2 < a_0$) aplicando la aproximación de régimen profundo ($a(r) \approx \sqrt{G M_{\text{dyn,ef}} a_0} / r$), la masa dinámica efectiva inferida depende cuadráticamente de $\alpha$:

$$M_{\text{dyn,ef}}(r_{200}) = \frac{\alpha^2 \cdot \sigma_r^4}{G \cdot a_0} \quad (14)$$

*(Por definición, en isotropía 3D se cumple $v_{\text{3D}}^2 = 3 \sigma_r^2$; esta cantidad sólo coincide numéricamente con $\alpha \sigma_r^2$ cuando se fija la pendiente $\alpha = 3$, en cuyo caso $M_{\text{dyn,ef}}(\alpha = 3) = \frac{9 \sigma_r^4}{G a_0}$).*

**Estimación condicional de orden de magnitud en Virgo y Coma:**
- **Cúmulo de Virgo ($r_{200} \approx 1,55\ \text{Mpc}$):** Con $\sigma_r \approx 577\ \text{km/s}$ (Binggeli et al., 1993) y $\alpha = 3$, la Ecuación (14) arroja $M_{\text{dyn,ef}} = 6,28 \times 10^{13}\ M_\odot$ (frente a estimaciones de masa bariónica de gas caliente intracúmulo más estrellas en rayos X de $M_{\text{bar,cl}} \sim 3 - 6 \times 10^{13}\ M_\odot$; Böhringer et al., 1994; Urban et al., 2011), con $M_{\text{BCG}}(\text{M87}) \approx 5 \times 10^{11}\ M_\odot$ ($0,80\%$).
- **Cúmulo de Coma ($r_{200} \approx 2,30\ \text{Mpc}$):** Con $\sigma_r \approx 693\ \text{km/s}$ en la zona exterior (Colless & Dunn, 1996) y $\alpha = 3$, la Ecuación (14) arroja $M_{\text{dyn,ef}} = 1,30 \times 10^{14}\ M_\odot$, donde el par central NGC 4874/4889 suma $M_{\text{BCG}} \approx 1,0 \times 10^{12}\ M_\odot$ ($0,77\%$). *(Dejamos expresamente establecido que estas estimaciones son condicionales a supuestos fuertes [$\alpha = 3, \beta_{\text{anis}} = 0$ y $\sigma_r$ exterior], que $M_{\text{dyn,ef}}$ no debe confundirse con la masa bariónica medida y que en el núcleo interno de Coma [$\sigma_r \approx 950\ \text{km/s}$] persiste el conocido factor $\sim 2$ de discrepancia bariónica analizado por Sanders, 2003).*

---

# CAPÍTULO 4: BRÚJULA HEURÍSTICA MACROCÓSMICA: EL EJERCICIO PARAMÉTRICO CONDICIONAL $N_7$

## 4.1. El Papel de $N_7$ como Intento Heurístico para Construir un Mapa Cósmico Diáfano
Al adentrarnos en la escala macrocósmica, establecemos con total transparencia el estatuto epistemológico de este capítulo: **el escenario $N_7$ es un ejercicio paramétrico condicional en construcción, no una estructura empíricamente demostrada ni derivada de una solución relativista cerrada**. Sin embargo, frente a un paradigma estándar que renuncia a concebir una geometría estructurada para el universo global, definimos esta exploración como **una brújula heurística y un nuevo intento para construir un mapa cósmico diáfano**, partiendo de la materia bariónica observable y de la continuidad de las leyes dinámicas para orientar la búsqueda hacia la verdadera configuración del cosmos.

Con este propósito, definimos como parámetro de entrada una unidad de masa de referencia ($N_1$) fijada en:

$$M_{N1} = 1,00 \times 10^{21}\ M_\odot \quad (15)$$

*(Dada la densidad bariónica media total del universo local $\rho_{\text{bar,tot}} = \Omega_b \rho_{\text{crít}} \approx 4,17 \times 10^{-28}\ \text{kg/m}^3 \approx 6,16 \times 10^9\ M_\odot/\text{Mpc}^3$ [Planck Collaboration, 2020; Shull et al., 2012], este parámetro de referencia equivale a la masa bariónica contenida en un volumen esférico fiducial de radio $R_{\text{fid}} \approx 3.385\ \text{Mpc} \approx 11.040\text{ M a.l.}$).*

## 4.2. Extrapolación Condicional de $N_1$ a $N_7$ y Requerimientos Relativistas en $v_f \approx 0,343c$
Evaluamos el siguiente ejercicio paramétrico condicional: **Si postulamos un sistema macrocósmico cuya masa bariónica total es siete veces el parámetro de referencia $M_{N1}$ ($M_{t(N7)} = 7,00 \times 10^{21}\ M_\odot$, distribuida sin fronteras administrativas físicas en una masa residual $M_r > 0,99 M_t$ en torno a un atractor central hipotético $M_c < 0,01 M_t$), ¿qué valores numéricos resultan de extrapolar algebraicamente las Ecuaciones (7) y (10)?**

| Escenario Paramétrico ($N \times M_{N1}$) | Masa Postulada ($M_t = M_c + M_r$) | Masa Residual ($M_r > 99\% M_t$) | Atractor Central Supuesto ($M_c$ al $0,8\% M_t$) | Velocidad Extrapolada Exacta ($v_f = (G M_t a_0)^{1/4}$ Ec. 10) | Radio Interno de Transición ($r_t = \sqrt{G M_t / a_0}$ Ec. 7) | Escala Exterior Ilustrativa (si se asume $R_{\text{ext}} / r_t \approx 11$) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **$N_1$ ($1\times$)** | $1,00 \times 10^{21}\ M_\odot$ | $0,992 \times 10^{21}\ M_\odot$ | $8,0 \times 10^{18}\ M_\odot$ | **63.413 km/s ($0,212 c$)** | 3.516 M a.l. | $\sim 39.300\text{ M a.l.}$ |
| **$N_2$ ($2\times$)** | $2,00 \times 10^{21}\ M_\odot$ | $1,984 \times 10^{21}\ M_\odot$ | $1,6 \times 10^{19}\ M_\odot$ | **75.411 km/s ($0,252 c$)** | 4.972 M a.l. | $\sim 55.600\text{ M a.l.}$ |
| **$N_3$ ($3\times$)** | $3,00 \times 10^{21}\ M_\odot$ | $2,976 \times 10^{21}\ M_\odot$ | $2,4 \times 10^{19}\ M_\odot$ | **83.456 km/s ($0,278 c$)** | 6.089 M a.l. | $\sim 68.100\text{ M a.l.}$ |
| **$N_4$ ($4\times$)** | $4,00 \times 10^{21}\ M_\odot$ | $3,968 \times 10^{21}\ M_\odot$ | $3,2 \times 10^{19}\ M_\odot$ | **89.680 km/s ($0,299 c$)** | 7.031 M a.l. | $\sim 78.600\text{ M a.l.}$ |
| **$N_5$ ($5\times$)** | $5,00 \times 10^{21}\ M_\odot$ | $4,960 \times 10^{21}\ M_\odot$ | $4,0 \times 10^{19}\ M_\odot$ | **94.828 km/s ($0,316 c$)** | 7.861 M a.l. | $\sim 87.900\text{ M a.l.}$ |
| **$N_6$ ($6\times$)** | $6,00 \times 10^{21}\ M_\odot$ | $5,952 \times 10^{21}\ M_\odot$ | $4,8 \times 10^{19}\ M_\odot$ | **99.261 km/s ($0,331 c$)** | 8.611 M a.l. | $\sim 96.300\text{ M a.l.}$ |
| **$N_7$ ($7\times$)** | **$7,00 \times 10^{21}\ M_\odot$** | **$6,944 \times 10^{21}\ M_\odot$** | **$5,6 \times 10^{19}\ M_\odot$** | **102.754 $\approx$ 103.000 km/s ($0,343 c$)** | **9.302 $\approx$ 9.310 M a.l.** | **$\sim 104.000\text{ M a.l.}$** |

**Delimitación física sobre los resultados de $N_7$:**
1. Los valores exactos $v_f = 102.754\ \text{km/s}$ ($\approx 103.000\ \text{km/s}$) y $r_t = 9.302\text{ M a.l.}$ son consecuencias algebraicas de introducir la masa postulada $M_{t(N7)} = 7,00 \times 10^{21}\ M_\odot$ en las Ecuaciones (10) y (7), y la columna $R_{\text{ext}} / r_t \approx 11$ es un supuesto geométrico adicional; no constituyen mediciones independientes.
2. Dado que para $v_f \approx 0,343c$ el factor de Lorentz es $\gamma \approx 1,0645$ ($v_f^2 / c^2 \approx 11,8\%$), una formalización física completa de este escenario requeriría una métrica relativista autoconsistente y la especificación de sus condiciones de contorno cosmológicas.

## 4.3. Estabilidad de Órbitas de Prueba frente a Estabilidad Colectiva Autogravitante
El potencial efectivo unidimensional $V_{\text{eff}}(r) = v_f^2 \ln(r/r_0) + \frac{h^2}{2r^2}$ posee un mínimo estable único ($r_{\text{eq}} = h / v_f$) para partículas de prueba individuales con momento angular específico $h$. La demostración de estabilidad colectiva de una estructura cosmológica autogravitante completa permanece como problema abierto para simulaciones de N-cuerpos.

---

# CAPÍTULO 5: EJERCICIOS COSMOLÓGICOS EN CONSTRUCCIÓN: FUNCIÓN ARMÓNICA COMPLETA DE RESPIRACIÓN RADIAL Y CAMPO VECTORIAL DE HUBBLE

## 5.1. Función Armónica Completa del Ciclo Respiratorio ($T = 2.000\text{ Millones de Años}$) (Resolución de Sección 3.4 del Control de Calidad)
Para describir matemáticamente de forma continua y coherente tanto el semociclo de expansión (exhalación de $1.000\text{ millones de años}$) como el semociclo subsiguiente de contracción (inhalación de $1.000\text{ millones de años}$) dentro de un único periodo completo $T = 2.000\text{ millones de años}$ (subsanando la limitación de definir la ecuación sólo en la mitad expansiva), formulamos la evolución temporal del radio característico $R(t)$ mediante la función armónica completa para todo $t \in [0, T]$:

$$R(t) = R_0 - A \cdot \cos\left(\frac{2\pi t}{T}\right) \quad (16\text{a})$$

Derivando la Ecuación (16a) respecto al tiempo $t$, la tasa cinemática de cambio radial fraccional $H_{\text{cin}}(t) = \frac{1}{R(t)}\frac{dR(t)}{dt}$ (para amplitudes pequeñas $A \ll R_0$) se sigue directamente de la misma función:

$$H_{\text{cin}}(t) = \frac{\dot{R}(t)}{R(t)} = \frac{\left(\frac{2\pi A}{T}\right) \sin\left(\frac{2\pi t}{T}\right)}{R_0 - A \cos\left(\frac{2\pi t}{T}\right)} \approx H_{\text{máx}} \cdot \sin\left(\frac{2\pi t}{T}\right) \quad \text{con } H_{\text{máx}} = \left(\frac{A}{R_0}\right)\frac{2\pi}{T} \quad (16\text{b})$$

Si definimos la variable de fase adimensional normalizada al semociclo como $u = \frac{2t}{T} \in [0, 2]$ (donde un ciclo completo abarca de $u = 0$ a $u = 2,0$):
- **Semociclo de Exhalación Expansiva ($0 < u < 1,0$, es decir, $0 < t < 1.000\text{ M años}$):** $\sin(\pi u) > 0 \implies H_{\text{cin}}(u) > 0$. Entre $u = 0$ y $u = 0,5$ la expansión acelera hasta alcanzar su máximo $H_{\text{máx}}$ en $u = 0,5$ ($t = 500\text{ M años}$); entre $u = 0,5$ y $u = 1,0$ la expansión desacelera hasta anularse en la máxima elongación $R_0 + A$ en $u = 1,0$ ($t = 1.000\text{ M años}$).
- **Semociclo de Inhalación Contractiva ($1,0 < u < 2,0$, es decir, $1.000 < t < 2.000\text{ M años}$):** $\sin(\pi u) < 0 \implies H_{\text{cin}}(u) < 0$. El sistema se contrae acelerando hacia adentro desde $u = 1,0$ hasta alcanzar la velocidad máxima de contracción $-H_{\text{máx}}$ en $u = 1,5$ ($t = 1.500\text{ M años}$), y frena su contracción entre $u = 1,5$ y $u = 2,0$ hasta retornar al punto de máxima compresión $R_0 - A$ en $u = 2,0$ ($t = 2.000\text{ M años}$), reiniciando perpetuamente el ciclo en consonancia con un cosmos eterno sin singularidad inicial.

*(Como ejercicio paramétrico condicional, un valor ilustrativo $H_{\text{cin}} \approx +5,6\ \text{km/s/Mpc}$ correspondería al pico $u = 0,5$ si la amplitud relativa fuese $A/R_0 \approx 0,18\%$, o bien a las fases simétricas $u_1 \approx 0,025$ o $u_2 \approx 0,975$ si $A/R_0 \approx 2,27\%$).*

## 5.2. Parametrización del Campo Vectorial de Hubble ($\vec{H}_{\text{cin}}$) y Atenuación Fotónica ($H_\gamma$)
En este ejercicio heurístico, proponemos que en un sistema que oscila radialmente según las Ecuaciones (16a–16b) respecto a un centro situado en la dirección unitaria $\hat{u}_c$, la tasa cinemática constituye un campo direccional definido por el vector radial $\vec{H}_{\text{cin}}(t) = H_{\text{cin}}(t)\,\hat{u}_c$. Superponiendo esta componente a una hipótesis de atenuación fotónica secular en el medio ($dE = -k E dx \implies 1 + z_\gamma(d) = e^{(H_\gamma / c) d}$, con $H_\gamma = c \cdot k$), la tasa aparente de Hubble en la dirección de observación $\hat{n}$ ($\cos\theta = \hat{n} \cdot \hat{u}_c$) se parametriza como:

$$H_{\text{obs}}(t, \hat{n}) = H_\gamma + \vec{H}_{\text{cin}}(t) \cdot \hat{n} = H_\gamma + H_{\text{cin}}(t) \cos\theta \quad (17)$$

**Delimitación contra la circularidad y pruebas cosmológicas pendientes:**
Dejamos explícitamente sentado que la diferencia aritmética entre determinaciones locales y profundas de $H_0$ ($73,0 - 67,4 = 5,6\ \text{km/s/Mpc}$) se utiliza aquí únicamente para ilustrar el orden de magnitud de la parametrización (Ecuación 17), y **no constituye una derivación independiente de la amplitud del dipolo ni una confirmación del modelo**. Asimismo, la hipótesis de atenuación fotónica ($1+z_\gamma = e^{H_\gamma d / c}$) permanece como una propuesta exploratoria no validada que, para competir con la métrica de expansión estándar, deberá demostrar cuantitativamente en trabajos futuros cómo reproducir simultáneamente: (1) la dilatación temporal $(1+z)$ en curvas de luz de supernovas Tipo Ia sin dispersión angular de imágenes; (2) el test de brillo superficial de Tolman $(1+z)^{-4}$; (3) la dualidad de distancias de Etherington $d_L = (1+z)^2 d_A$; y (4) el espectro térmico de cuerpo negro y los picos acústicos del CMB.

---

# CAPÍTULO 6: DISEÑO DE PRUEBAS OBSERVACIONALES Y CONDICIONES ESTADÍSTICAS DE FALSABILIDAD

Definimos tres protocolos de prueba especificando los requisitos estadísticos y observacionales necesarios para su ejecución rigurosa:

1. **Protocolo para la Prueba Dipolar del Campo Vectorial ($\vec{H}_{\text{cin}}$) en Catálogos de Supernovas y Cúmulos:**
   - *Hipótesis nula ($M_0$) vs. Hipótesis direccional ($M_1$):* Sobre una muestra homogénea de supernovas Tipo Ia (p. ej., Pantheon+ en el corte $0,023 < z < 0,15$, tras sustraer el dipolo cinemático del CMB y el campo de velocidades peculiares locales con su incertidumbre asociada), el modelo nulo isótropo $M_0$ ajusta un único parámetro $H_0$, mientras que el modelo direccional $M_1$ evalúa $H_{\text{obs}}(\hat{n}_i) = H_\gamma + H_{\text{cin}} (\hat{n}_i \cdot \hat{u}_c)$ fijando *a priori* el eje de prueba en la región de Shapley/Vela ($l_c = 295^\circ, b_c = +15^\circ$, propagando una incertidumbre angular de $\pm 15^\circ$).
   - *Función de verosimilitud y criterio de refutación:* El ajuste debe ejecutarse minimizando $\chi^2 = \Delta \vec{\mu}^T \, C^{-1} \, \Delta \vec{\mu}$ con la matriz completa de covarianza estadística y sistemática $C$ de Pantheon+ ($\mathcal{L} \propto \exp(-\chi^2 / 2)$). El escenario exploratorio quedaría empíricamente excluido si el límite superior al $99,7\%$ de nivel de confianza ($3\sigma$ derivado de la verosimilitud perfilada sobre $C$) restringe la componente proyectada en dicho eje a $|H_{\text{cin}}| < 1,0\ \text{km/s/Mpc}$.
2. **Prueba Dinámica de Consistencia mediante la Frecuencia Epicíclica ($\kappa / \Omega = \sqrt{2}$, $T_r = 152,0\text{ M años}$) en Gaia:**
   - *Cálculo explícito y documentado del periodo radial:* En un potencial con curva de rotación localmente plana ($dv_c / dr \approx 0$), la frecuencia epicíclica radial ($\kappa$) y la frecuencia angular circular ($\Omega = v_c / r$) cumplen la propiedad dinámica general $\kappa / \Omega = \sqrt{2}$. Utilizando los parámetros exactos de la posición solar en nuestra Tabla 1A ($r_\odot = 8,00\ \text{kpc} = 2,46856 \times 10^{20}\ \text{m}$ y velocidad circular $v_c = 229,0\ \text{km/s}$ observada o $230,2\ \text{km/s}$ en el Perfil Central C, con $1\text{ año juliano} = 3,15576 \times 10^7\ \text{s}$), el periodo orbital azimutal es:

$$T_{\text{orb}} = \frac{2\pi r_\odot}{v_c} = 214,6\text{ a }215,7\text{ millones de años} \quad (\approx 215,0\text{ M años}) \quad (18\text{a})$$

Dividiendo por $\sqrt{2} = 1,41421$, el periodo de oscilación radial epicíclica correspondiente es:

$$T_r = \frac{T_{\text{orb}}}{\sqrt{2}} = 151,8\text{ a }152,5\text{ millones de años} \quad (\approx 152,0\text{ M años}) \quad (18\text{b})$$

   - *Alcance del test:* Esta relación es una propiedad dinámica general de cualquier potencial plano (y no una predicción exclusiva de $N_7$); su utilidad consiste en contrastar en los datos de Gaia DR4 la pendiente real de $v_c(r)$ y separar modos estacionarios de perturbaciones transitorias.
3. **Contraste de Pendiente Magnitud-Redshift en el Eje Z vs. Plano Supergaláctico:**
   - Comparar el módulo de distancia de candelas estándar y cuásares ($z > 1$) entre los polos supergalácticos ($|\text{SGB}| > 60^\circ$) y el plano supergaláctico ($|\text{SGB}| < 15^\circ$), controlando previamente los sesgos de selección fotométrica, extinción galáctica de polvo y evolución con el corrimiento al rojo.

---

# CAPÍTULO 7: SÍNTESIS EPISTEMOLÓGICA FINAL Y ANEXO TÉCNICO CON SCRIPT EJECUTABLE

## 7.1. Suficiencia Bariónica, Conservación en un Cosmos Eterno y el Nuevo Mapa Cósmico
Al concluir esta décima versión auditada de *El Cosmos Arquitectónico*, sintetizamos sus dos contribuciones fundamentales:

1. **En el plano galáctico reproducible:** Hemos demostrado mediante una formulación algebraica cerrada ($\mu(x) = x/(1+x)$) y una evaluación computacional exacta con funciones modificadas de Bessel sobre el perfil bariónico de bulbo de Hernquist más disco exponencial de Freeman que la transición dinámica dependiente de la escala reproduce satisfactoriamente la curva de rotación de la Vía Láctea entre $5,0\text{ y }25,0\ \text{kpc}$ en los radios medidos por Eilers et al. (2019). Al describir adecuadamente el comportamiento de la aceleración sobre la materia bariónica real, las entidades oscuras inobservables resultan innecesarias para dar cuenta de este régimen fenomenológico.
2. **En el plano heurístico y cosmológico:** Al suprimir el postulado de un universo surgido de la nada y restituir con pleno rigor formal los principios fundamentales de conservación de la materia y la energía, emerge como consecuencia natural la concepción de un cosmos eterno, sin principio ni fin, estructurado y continuo. Reconocemos con total transparencia que el escenario paramétrico $N_7$, la oscilación armónica completa de $2.000\text{ millones de años}$ y la descomposición vectorial de Hubble son ejercicios exploratorios en construcción pendientes de formalización relativista y de pruebas cosmológicas exigentes; sin embargo, los entregamos como una brújula heurística y un nuevo intento para trazar un mapa cósmico diáfano que impulse a la física a explicar la verdadera configuración del universo sin imponer la ignorancia por norma.

---

## ANEXO TÉCNICO: TABLA MAESTRA DE ENTRADAS, SCRIPT EJECUTABLE PARA TABLAS 1A Y 1B, Y RESUMEN DE AUDITORÍA (VERSIÓN 10.0)

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

### A.2. Script Ejecutable en Python que Genera Íntegramente las Tablas 1A y 1B (Sin Transcripción Manual)

El siguiente script estándar de Python 3 (`numpy` y `scipy.special`) genera automáticamente tanto la Tabla 1A (en la rejilla uniforme de $5,0\text{ a }25,0\ \text{kpc}$, verificando el valor exacto de $218,6\ \text{km/s}$ en $12,0\ \text{kpc}$) como la Tabla 1B (evaluando el modelo directamente en los radios observacionales exactos $R_{\text{bin}}$ de Eilers et al., 2019 con sistemáticos radiales del $3\%$ al $5\%$):

    import numpy as np
    from scipy.special import i0, k0, i1, k1

    # 1. Constantes fisicas y parametros geometricos fijos (Version 10.0)
    G = 6.674e-11          # m^3 kg^-1 s^-2
    a0 = 1.20e-10          # m s^-2
    M_sun = 1.9885e30      # kg
    kpc = 3.0857e19        # m

    M_b = 1.00e10 * M_sun  # Masa bulbo Hernquist (kg)
    a_b = 0.60 * kpc       # Escala bulbo Hernquist (m)
    R_d = 2.60 * kpc       # Escala disco Freeman (m)
    M_d_branches = [4.50e10 * M_sun, 5.00e10 * M_sun, 5.50e10 * M_sun] # Ramas A, C, B

    def eval_model_at_radius(rk):
        r_m = rk * kpc
        y = rk / (2.0 * 2.60)
        dB = float(i0(y)*k0(y) - i1(y)*k1(y))
        F_Bessel = 4.0 * (y**3) * dB
        gN_bulge = G * M_b / ((r_m + a_b)**2)
        gN_disks, gN_tots, vNs, aMods, vMods = [], [], [], [], []
        for M_d in M_d_branches:
            gN_d = (G * M_d / (r_m**2)) * F_Bessel
            gN_t = gN_bulge + gN_d
            a_m = 0.5 * gN_t * (1.0 + np.sqrt(1.0 + 4.0 * a0 / gN_t))
            gN_disks.append(gN_d * 1e10)
            gN_tots.append(gN_t * 1e10)
            vNs.append(np.sqrt(r_m * gN_t) / 1000.0)
            aMods.append(a_m * 1e10)
            vMods.append(np.sqrt(r_m * a_m) / 1000.0)
        return y, dB, F_Bessel, gN_bulge*1e10, gN_disks, gN_tots, vNs, aMods, vMods

    # --- IMPRESION DE TABLA 1A (Rejilla uniforme 5.0 a 25.0 kpc) ---
    print("=== TABLA 1A: REJILLA UNIFORME (5.0 A 25.0 KPC) ===")
    r_grid = [5.0, 6.0, 8.0, 10.0, 12.0, 16.0, 20.0, 25.0]
    for rk in r_grid:
        y, dB, FB, gNb, gNd, gNt, vN, aM, vM = eval_model_at_radius(rk)
        print(f"r={rk:4.1f} | y={y:7.5f} | dB={dB:7.5f} | FB={FB:6.4f} | "
              f"vN={vN[0]:5.1f}/{vN[1]:5.1f}/{vN[2]:5.1f} | "
              f"vMod={vM[0]:5.1f}/{vM[1]:5.1f}/{vM[2]:5.1f}")

    # --- IMPRESION DE TABLA 1B (Radios exactos R_bin de Eilers et al. 2019) ---
    print("\n=== TABLA 1B: EVALUACION EN RADIOS EXACTOS R_bin DE EILERS ET AL. (2019) ===")
    eilers_bins = [
        (5.27, 226.83, 1.91, 1.90),
        (6.27, 230.80, 1.38, 1.32),
        (7.78, 229.63, 0.60, 0.63),
        (8.27, 228.89, 0.61, 0.60),
        (10.27, 224.96, 0.84, 0.96),
        (12.26, 220.96, 1.22, 1.27),
        (15.78, 217.47, 1.86, 2.15),
        (19.82, 206.54, 4.18, 3.97),
        (24.82, 198.42, 6.12, 6.50)
    ]
    for R_b, vc_b, sp, sm in eilers_bins:
        y, dB, FB, gNb, gNd, gNt, vN, aM, vM = eval_model_at_radius(R_b)
        f_sys = 0.03 + 0.02 * max(0.0, (R_b - 8.0) / 17.0)
        sig_sys = f_sys * vc_b
        dv_C = vM[1] - vc_b
        sig_stat_dir = sp if dv_C >= 0 else sm
        sig_comb = np.sqrt(sig_stat_dir**2 + sig_sys**2)
        z_C = dv_C / sig_comb
        print(f"R_bin={R_b:5.2f} | FB={FB:6.4f} | vMod={vM[0]:5.1f}/{vM[1]:5.1f}/{vM[2]:5.1f} | "
              f"Eilers={vc_b:6.2f} | sig_comb={sig_comb:5.2f} | dV_C={dv_C:+6.2f} | z_C={z_C:+5.2f}")

### A.3. Tabla Maestra de Auditoría Numérica Reproducible (Versión 10.0)

| ID / Sistema | Parámetros de Entrada Documentados (Inputs) | Ecuación del Modelo Aplicada | Resultado Calculado Verificado por Script (Output) | Categoría Epistemológica y Alcance Técnico |
| :--- | :--- | :--- | :--- | :--- |
| **A-01. Tierra en Sistema Solar** | $M = 1,00\ M_\odot$; $r = 1,496 \times 10^{11}\ \text{m}$ ($1\ \text{UA}$) | Ec. (5): $a = \frac{g_N}{2}(1 + \sqrt{1 + 4a_0/g_N})$ | $g_N = 5,930 \times 10^{-3}\ \text{m/s}^2$; $a / g_N - 1 = 2,02 \times 10^{-8}$; $v = 29,78\ \text{km/s}$ | **Consecuencia Algebraica Cerrada.** Verifica el límite newtoniano ($\mu \to 1$). |
| **A-02. Estrella S2 (Pericentro Sgr A*)** | $M_c \equiv M_{\text{BH}} = 4,30 \times 10^6\ M_\odot$; $r_p = 1,795 \times 10^{13}\ \text{m}$ ($120\ \text{UA}$); $e = 0,8846$ | Ec. (5) + Vis-Viva: $v_p = \sqrt{r_p \cdot a(r_p) \cdot (1+e)}$ | $g_N = 1,77\ \text{m/s}^2 \gg a_0$; $v_p = 7.650\ \text{km/s}$ | **Verificación de Límite Newtoniano.** No constituye prueba relativista ni deriva el redshift gravitacional de GRAVITY. |
| **A-03. Vía Láctea: Rejilla Uniforme y Radios Exactos $R_{\text{bin}}$** | Bulbo Hernquist ($a_b = 0,60\ \text{kpc}$): $M_b = 1,00 \times 10^{10}\ M_\odot$; Disco Freeman ($R_d = 2,60\ \text{kpc}$), Ramas A/C/B: $M_d = (4,50 / 5,00 / 5,50) \times 10^{10}\ M_\odot$ | Ec. (9a + 9b) con `scipy.special` + Presupuesto algebraico Ec. (5) (Script A.2) | En $5\ \text{kpc}$ ($F=0,7384$): **221,1 / 228,7 / 236,0 km/s**; En $6\ \text{kpc}$ ($F=0,8902$): **223,7 / 231,4 / 238,8 km/s**; En $8\ \text{kpc}$ ($F=1,0914$): **222,7 / 230,2 / 237,4 km/s**; En $10\ \text{kpc}$ ($F=1,1807$): **217,9 / 224,9 / 231,7 km/s**; **En $12\ \text{kpc}$ ($F=1,2011$): 212,1 / 218,6 / 224,9 km/s**; En $16\ \text{kpc}$ ($F=1,1611$): **201,6 / 207,4 / 213,0 km/s**; En $20\ \text{kpc}$ ($F=1,1079$): **194,3 / 199,6 / 204,7 km/s**; En $25\ \text{kpc}$ ($F=1,0643$): **188,6 / 193,6 / 198,2 km/s** | **Ejecución Reproducible por Script (Tablas 1A y 1B).** Evaluada tanto en rejilla estándar como directamente en los radios $R_{\text{bin}}$ de Eilers et al. (2019) con sistemático radial del $3\%$ al $5\%$. |
| **A-04. Test Epicíclico en Radio Solar** | $r_\odot = 8,00\ \text{kpc}$; $v_c = 229,0 - 230,2\ \text{km/s}$; Curva plana: $\kappa / \Omega = \sqrt{2}$ | Ec. (18a–18b): $T_{\text{orb}} = 2\pi r_\odot / v_c$; $T_r = T_{\text{orb}} / \sqrt{2}$ | $T_{\text{orb}} = 214,6 - 215,7\text{ M años}$; $T_r = 151,8 - 152,5\text{ M años}$ ($\approx 152,0$) | **Propiedad Dinámica de Curva Plana.** No es predicción exclusiva de $N_7$. |
| **A-05. Galaxias NGC 3198 y M33 (SPARC)** | NGC 3198: $v_f = 150,1 \pm 3,0\ \text{km/s}$; M33: $v_f = 96,0 \pm 4,0\ \text{km/s}$ | Ec. (10): $M_{\text{bar,TF}} = v_f^4 / (G \cdot a_0)$ vs. $M_{\text{bar,obs}}$ | NGC 3198: $M_{\text{bar,TF}} = (3,19 \pm 0,25) \times 10^{10}\ M_\odot$; M33: $M_{\text{bar,TF}} = (5,33 \pm 0,89) \times 10^{9}\ M_\odot$ | **Ejemplos Ilustrativos Individuales.** Separación explícita entre $M_{\text{bar,TF}}$ y $M_{\text{bar,obs}}$. |
| **A-06. Cúmulos Virgo y Coma en $r_{200}$ (Jeans 3D)** | Virgo: $\sigma_r \approx 577\ \text{km/s}$; Coma: $\sigma_r \approx 693\ \text{km/s}$; Supuestos: $\alpha = 3$, $\beta_{\text{anis}} = 0$ | Ec. (14): $M_{\text{dyn,ef}} = \alpha^2 \sigma_r^4 / (G \cdot a_0)$; Razón contable $M_{\text{BCG}} / M_{\text{dyn,ef}}$ | Virgo: $M_{\text{dyn,ef}} = 6,28 \times 10^{13}\ M_\odot$; Coma: $M_{\text{dyn,ef}} = 1,30 \times 10^{14}\ M_\odot$ | **Estimación Condicional de Orden de Magnitud.** No resuelve el déficit bariónico del núcleo interno de Coma (Sanders, 2003). |
| **A-07. Escenario Heurístico $N_7$** | Parámetro de referencia: $M_{N1} = 1,00 \times 10^{21}\ M_\odot$; $M_t(N_7) = 7 \times 10^{21}\ M_\odot$ | Extrapolación algebraica de Ec. (10) y Ec. (7): $v_f = (G M_t a_0)^{1/4}$; $r_t = \sqrt{G M_t / a_0}$ | $v_f = 102.754 \approx 103.000\ \text{km/s}$ ($0,343c$, $\gamma = 1,0645$); $r_t = 9.302 \approx 9.310\text{ M a.l.}$ | **Brújula Heurística y Ejercicio Paramétrico.** Consecuencia matemática del $M_t$ postulado; su interpretación física requeriría tratamiento relativista. |
| **A-08. Ciclo Armónico Completo y Vector de Hubble** | Postulados exploratorios: $R(t) = R_0 - A\cos(2\pi t/T)$ con $T = 2,0 \times 10^9\text{ años}$; eje $(l_c = 295^\circ, b_c = +15^\circ)$ | Ec. (16a–16b) y Ec. (17): $H_{\text{cin}}(t) \approx \frac{2\pi A}{TR_0}\sin\left(\frac{2\pi t}{T}\right)$; $H_{\text{obs}}(\hat{n}) = H_\gamma + \vec{H}_{\text{cin}}\cdot\hat{n}$ | Ciclo completo unificado de exhalación ($0<u<1$) e inhalación ($1<u<2$); contraste dipolar mediante matriz de covarianza $C$ | **Ejercicio Paramétrico en Construcción.** Sujeto a refutación en Pantheon+ y a pruebas pendientes de supernovas, Tolman, Etherington y CMB. |

---

## Referencias Científicas y Técnicas

1. Milgrom, M. (1983). A modification of the Newtonian dynamics as a possible alternative to the hidden mass hypothesis. *The Astrophysical Journal*, 270, 365-370; y Milgrom, M. (2010). Quasi-linear formulation of MOND. *Monthly Notices of the Royal Astronomical Society*, 403(2), 886-895.
2. Bekenstein, J., & Milgrom, M. (1984). Does the missing mass problem signal the breakdown of Newtonian gravity? *The Astrophysical Journal*, 286, 7-14.
3. Brada, R., & Milgrom, M. (1995). Exact solutions and approximations of MOND fields of disc galaxies. *Monthly Notices of the Royal Astronomical Society*, 276(2), 453-459.
4. Freeman, K. C. (1970). On the disks of spiral and S0 galaxies. *The Astrophysical Journal*, 160, 811-830.
5. Binney, J., & Tremaine, S. (2008). *Galactic Dynamics* (2nd ed.). Princeton University Press.
6. Eilers, A.-C., Hogg, D. W., Rix, H.-W., & Ness, M. K. (2019). The Circular Velocity Curve of the Milky Way from 5 to 25 kpc. *The Astrophysical Journal*, 871(1), 120.
7. Huang, Y., et al. (2016). Milky Way rotation curve out to 100 kpc. *Monthly Notices of the Royal Astronomical Society*, 463(3), 2623-2639; Sofue, Y. (2013). *PASJ*, 65(6), 118; y Bland-Hawthorn, J., & Gerhard, O. (2016). *ARA&A*, 54, 529-596.
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
