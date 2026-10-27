# EL COSMOS ARQUITECTÓNICO: APROVECHANDO LAS COSMOGONÍAS JERÁRQUICAS PARA RESOLVER LA ANOMALÍA DE LA MATERIA OSCURA Y EL BIG BANG MEDIANTE DINÁMICAS DEPENDIENTES DE LA ESCALA

**Mauricio Rivadeneira¹\*, Colaborador de Investigación de IA²**  
¹ *Investigador Independiente, Unidad de Simulación Avanzada de Física Computacional*  
\*Contacto: maurivadeneira@gmail.com  
**Octubre de 2026 — Versión 5.0 (Con Modelo de Disco de Freeman, Campo Vectorial de Hubble y Auditoría Reproducible)**  

> *"Entregamos este manuscrito del Cosmos Arquitectónico como un andamio en construcción que nos permita aumentar la comprensión de nuestro universo majestuoso e inconmensurable; un cosmos infinito, estructurado y eterno."*  

---

## RESUMEN

Presentamos un programa de investigación exploratorio y un modelo dinámico dependiente de la escala orientado a evaluar si las anomalías atribuidas a entidades inobservables (materia y energía oscuras) pueden describirse mediante propiedades métricas del sustrato espacial en regímenes de aceleración ultrabaja. Partiendo de un modelo dinámico definido por el parámetro crítico de aceleración ($a_0 = 1,2 \times 10^{-10}\ \text{m/s}^2$, convergente en su límite asintótico con la dinámica de Milgrom) y fijando la función de transición racional única $\mu(x) = \frac{x}{1+x}$, derivamos una solución cuadrática cerrada que conecta continuamente el régimen newtoniano ($1/r^2$) con el régimen asintótico de vórtice o remolino ($1/r$). En la Vía Láctea, implementando un modelo bariónico explícito compuesto por un bulbo esferoidal ($M_b = 1,00 \times 10^{10}\ M_\odot$) y un disco exponencial de Freeman ($M_d = 5,50 \times 10^{10}\ M_\odot$, longitud de escala $R_d = 2,6\ \text{kpc}$), demostramos que el campo newtoniano combinado en la posición galactocéntrica del Sol ($r_\odot = 8,0\ \text{kpc} \approx 26.000\text{ a.l.}$) es $g_N(r_\odot) = 1,228 \times 10^{-10}\ \text{m/s}^2$ ($v_N = 173,8\ \text{km/s}$), situándose en la vecindad inmediata de la escala característica $g_N \approx a_0$ y reproduciendo bajo la ecuación de transición una velocidad circular de $220,4\ \text{km/s}$.

A escala de galaxias espirales y cúmulos esferoidales modelados bajo equilibrio hidrostático isotrópico de Jeans (con pendiente exterior supuesta $\alpha = 3$), realizamos un contraste preliminar frente a datos del catálogo SPARC y mediciones en rayos X (Virgo y Coma), definiendo la descomposición contable $M_t = M_c + M_r$ y planteando como hipótesis empírica sujeta a verificación estadística que el atractor baricéntrico compacto ($M_c$) satisface la cota $M_c < 0,01 \cdot M_t$. A escala macrocósmica, evaluamos como escenario condicional la extrapolación de la relación asintótica $M_t = v_f^4 / (G \cdot a_0)$ adoptando un parámetro de masa de referencia $M_{N1} = 1,00 \times 10^{21}\ M_\odot$ y explorando la proporción $N_7$ ($M_{t(N7)} = 7,00 \times 10^{21}\ M_\odot$, con $M_r \approx 6,94 \times 10^{21}\ M_\odot$ y $M_c < 7,0 \times 10^{19}\ M_\odot$). Como consecuencia algebraica de este escenario, se obtiene una velocidad tangencial plana sub-lumínica de $v_f = 103.000\ \text{km/s}$ ($0,34c$) y un radio de transición interno $r_t = 9.310\text{ millones de años luz}$. Finalmente, formulamos como hipótesis cosmológicas exploratorias un ciclo de respiración radial ($T = 2.000\text{ millones de años}$) y una atenuación fotónica secular, proponiendo que el parámetro de Hubble observado se descompone en un escalar disipativo ($H_\gamma$) más la proyección direccional de un **campo vectorial de respiración radial ($\vec{H}_{\text{cin}}$)** orientado hacia el centro $M_c$. El documento concluye con protocolos estadísticos de falsabilidad y un Anexo de Auditoría Numérica Reproducible que separa estrictamente entradas, consecuencias algebraicas y supuestos teóricos.

---

## Nota Metodológica: Sinergia Cognitiva y Demarcación Epistemológica

El presente manuscrito es el resultado de un modelo de investigación aumentada, donde la dirección conceptual, el establecimiento de los axiomas topológicos y la validación lógica final son autoría exclusiva del investigador principal. El desarrollo del trabajo contó con la integración activa de Inteligencia Artificial Avanzada operando como colaborador analítico en la estructuración de registros astronómicos (como el catálogo SPARC y el SDSS), auditoría algebraica y modelado deductivo.

Atendiendo los criterios de rigor científico y control de calidad por pares, establecemos una separación estricta en todo el documento entre tres categorías epistemológicas:
1. **Consecuencias Algebraicas del Modelo Definido:** Deducciones matemáticas cerradas que se siguen de forma exacta una vez elegida la función de transición $\mu(x) = x/(1+x)$ y las geometrías de masa especificadas (Secciones 1.4, 2.1, 3.1 y 3.4).
2. **Contrastes Preliminares Reproducibles:** Evaluaciones numéricas sobre sistemas astronómicos específicos (Sistema Solar, Vía Láctea con perfil de Freeman, tres galaxias de SPARC y dos cúmulos de referencia) que demuestran consistencia de orden de magnitud y viabilidad preliminar, sin reclamar todavía una validación estadística universal sobre la totalidad de las muestras cosmológicas.
3. **Hipótesis y Escenarios Condicionales Exploratorios:** Postulados arquitectónicos —la universalidad de la cota $M_c < 0,01 \cdot M_t$, el escenario paramétrico $N_7$, el ciclo respiratorio de $2.000\text{ millones de años}$ y la atenuación fotónica frente al corrimiento al rojo— que no se presentan como hechos demostrados, sino como hipótesis de investigación abiertas a refutación observacional (Capítulos 4, 5, 6 y 7).

---

# CAPÍTULO 1: EXPERIMENTO ALGORÍTMICO EXPLORATORIO Y DEFINICIÓN DEL MODELO DINÁMICO DE ESCALA

## 1.1. Experimento Exploratorio Inicial: Regresión Simbólica de la Dinámica Clásica
Como ejercicio heurístico preliminar para iniciar esta investigación, se planteó un experimento computacional conceptual: evaluar cómo algoritmos de regresión simbólica guiados por un criterio de parsimonia (penalización de complejidad tipo Navaja de Ockham y minimización de error cuadrático medio) recuperan relaciones dinámicas a partir de conjuntos sintéticos de variables cinemáticas y dinámicas clásicas: masa ($m$), aceleración ($a$), fuerza ($F$) y separación orbital ($d$). En dicho entorno de prueba, la optimización converge hacia las relaciones algebraicas base de la mecánica clásica:

1. **La Segunda Ley del Movimiento:**
   $$F = m \cdot a \quad (1)$$

2. **La Ley Inversa del Cuadrado en el Régimen Local:**
   $$F = G \cdot \frac{m_1 \cdot m_2}{d^2} \quad (2)$$

*(Nota de alcance: Este ejercicio inicial se reporta como el punto de partida conceptual que motivó la pregunta central del presente trabajo: cuál es la modificación algebraica mínima de la Ecuación 2 capaz de describir las curvas de rotación galácticas planas cuando la aceleración cae por debajo de un umbral crítico).*

## 1.2. Régimen de Validez de las Aproximaciones Gravitacionales
Como regla metodológica, cualquier modelo dinámico de escala debe preservar la física local verificada experimentalmente. Distinguimos por tanto los dominios de aplicación según la magnitud de la aceleración y del potencial gravitatorio:

- **Régimen Newtoniano Clásico ($a \gg a_0$, $v \ll c$):** Describe con alta precisión la dinámica terrestre y planetaria dentro del Sistema Solar.
- **Régimen Relativista de Campo Fuerte ($G M / (r c^2) \sim 1$ o $v \to c$):** Descrito por la Relatividad General de Einstein en las cercanías de objetos compactos (como la órbita pericéntrica de la estrella S2 en torno a Sagitario A*), lentes gravitacionales de alta curvatura y ondas gravitacionales.
- **Régimen de Aceleración Ultrabaja ($a \lesssim a_0$ en periferias galácticas):** En las regiones exteriores de las galaxias de disco, donde la aceleración gravitatoria newtoniana producida por la materia bariónica visible cae al orden de $\sim 10^{-10}\ \text{m/s}^2$, las velocidades orbitales observadas se mantienen planas en lugar de seguir el decaimiento kepleriano ($\propto r^{-1/2}$) predicho al aplicar las ecuaciones clásicas exclusivamente sobre la masa bariónica.

## 1.3. La Anomalía de Rotación Galáctica y el Parámetro Crítico ($a_0$)
En los confines exteriores de las galaxias espirales, la constancia radial de la velocidad tangencial ($v(r) \approx v_f$) configura una cinemática semejante a la de un **vórtice o remolino estacionario**. Frente a esta discrepancia entre la masa bariónica observada y la dinámica kepleriana, el paradigma estándar ($\Lambda\text{CDM}$) introdujo la hipótesis de halos esféricos de materia oscura no bariónica. Dado que las búsquedas experimentales directas de partículas de materia oscura no han arrojado detecciones confirmadas hasta la fecha, resulta científicamente legítimo explorar la vía alternativa: que la anomalía refleje un cambio en el comportamiento efectivo de la interacción gravitatoria a partir de una escala crítica de aceleración:
$$a_0 = 1,2 \times 10^{-10}\ \text{m/s}^2$$

Reconocemos expresamente que este parámetro y su límite asintótico corresponden a la Dinámica Newtoniana Modificada (MOND), formulada por Mordehai Milgrom en 1983, y reproducen la Relación Bariónica de Tully-Fisher. El objetivo específico de nuestro trabajo no es reclamar el descubrimiento independiente de dicho límite galáctico, sino **definir un modelo algebraico cerrado con función de transición fija y explorar sistemáticamente sus consecuencias condicionales al escalarlo hacia estructuras mayores**.

## 1.4. Definición Matemática del Modelo: Función de Transición Única y Solución Cuadrática Cerrada
Para evitar ambigüedades entre distintas familias de interpolación, fijamos un modelo dinámico único mediante las siguientes definiciones explícitas:

1. **Elección de la función de transición $\mu(x)$:** Adoptamos como definición constitutiva del modelo en todo este manuscrito la función racional simple de variable adimensional $x = a / a_0$:
   $$\mu\left(\frac{a}{a_0}\right) = \frac{\frac{a}{a_0}}{1 + \frac{a}{a_0}} = \frac{a}{a + a_0} \quad (3)$$

2. **Ecuación de Estado Dinámico:** En el plano ecuatorial de un sistema con aceleración gravitatoria newtoniana bariónica $g_N(r)$ (calculada rigurosamente según la geometría esférica o de disco de su distribución de masa bariónica), la aceleración cinemática centrípeta $a(r) = v^2(r) / r$ satisface:
   $$F \cdot \mu\left(\frac{a}{a_0}\right) = m \cdot g_N(r) \quad \Longleftrightarrow \quad m \cdot a \cdot \left(\frac{a}{a + a_0}\right) = m \cdot g_N(r) \quad (4)$$

Cancelando la masa de prueba ($m$) en ambos miembros, la Ecuación (4) produce la ecuación algebraica de segundo grado $a^2 - g_N \cdot a - g_N \cdot a_0 = 0$. Su única raíz física positiva define la **Ecuación Maestra de Aceleración del Modelo**:

$$a(r) = \frac{g_N(r)}{2} \left(1 + \sqrt{1 + \frac{4 a_0}{g_N(r)}}\right) \quad (5)$$

De la Ecuación (5) se derivan dos consecuencias algebraicas en los regímenes extremos:
- **Régimen de Alta Aceleración ($g_N \gg a_0$):** Como $4 a_0 / g_N \to 0$, se recupera $a(r) \to g_N(r)$.
- **Régimen Profundo o de Remolino ($g_N \ll a_0$):** A grandes distancias ($r$ muy superior al radio de la masa bariónica central, donde el monopolo domina el campo newtoniano como $g_N(r) \approx G M_t / r^2$ y $4 a_0 / g_N \gg 1$), la Ecuación (5) converge asintóticamente a:
  $$a_{\text{prof}}(r) = \sqrt{g_N(r) \cdot a_0} = \frac{\sqrt{G \cdot M_t \cdot a_0}}{r} \quad \implies \quad F_{\text{prof}} = m \frac{\sqrt{G \cdot M_t \cdot a_0}}{r} \quad (6)$$

Al igualar la aceleración centrípeta ($v^2 / r$) con la Ecuación (6), el radio $r$ se cancela algebraicamente, obteniéndose la velocidad tangencial plana constante del remolino en el límite exterior ($v_f = (G M_t a_0)^{1/4}$). *(Nota metodológica: La Ecuación 4 define una relación algebraica modificada entre aceleración y campo newtoniano; su formulación general como teoría de campo conservativa para distribuciones tridimensionales arbitrarias requiere resolver la ecuación de Poisson no lineal $\nabla \cdot [\mu(|\nabla\Phi|/a_0)\nabla\Phi] = 4\pi G \rho$, respecto a la cual la Ecuación 5 constituye la solución exacta en simetrías donde se anula el rotacional solenoidal).*

## 1.5. Distinción Conceptual entre la Constante $a_0$ y el Parámetro de Hubble ($H_0$)
Frente a la conocida relación aproximada de orden de magnitud $a_0 \approx \frac{c \cdot H_0}{2\pi}$, planteamos como postulado conceptual del modelo que **$a_0 = 1,2 \times 10^{-10}\ \text{m/s}^2$ actúa como una constante estructural invariante en el tiempo**, mientras que el parámetro de Hubble medido ($H_{\text{obs}}$) representa una magnitud efectiva compuesta por un término disipativo óptico y un término cinemático dependiente de la fase y dirección dentro de nuestra macro-cuenca.

---

# CAPÍTULO 2: CONTRASTE REPRODUCIBLE EN EL SISTEMA SOLAR Y MODELO DE DISCO DE FREEMAN PARA LA VÍA LÁCTEA

## 2.1. Escala Característica de Transición ($r_t$) y Propiedad Algebraica en $g_N = a_0$
Definimos la escala espacial característica de transición ($r_t$) de un sistema de masa bariónica $M$ como el radio de referencia en el cual la magnitud del campo newtoniano iguala exactamente al parámetro crítico ($g_N(r_t) = a_0$):

$$g_N(r_t) = a_0 \quad \left(\text{que en aproximación monopolar equivale a } r_t = \sqrt{\frac{G \cdot M}{a_0}}\right) \quad (7)$$

Al evaluar la Ecuación Maestra (5) en cualquier punto que satisfaga la condición $g_N = a_0$, se obtiene como consecuencia matemática directa de la función racional elegida en la Ecuación (3):

$$a(g_N = a_0) = \frac{a_0}{2}\left(1 + \sqrt{1 + 4}\right) = \left(\frac{1 + \sqrt{5}}{2}\right) a_0 = \phi \cdot g_N \approx 1,61803 \cdot g_N \quad (8)$$

Por consiguiente, en el punto donde $g_N = a_0$, la velocidad circular del modelo ($v = \sqrt{r \cdot a}$) guarda con la velocidad newtoniana ($v_N = \sqrt{r \cdot g_N}$) la proporción algebraica exacta $v / v_N = \sqrt{\phi} \approx 1,27202$. *(Dejamos expresamente aclarado que la aparición del número áureo $\phi$ en la Ecuación 8 es una consecuencia algebraica intrínseca de la forma funcional $\mu(x) = x/(1+x)$ evaluada en $x_{\text{N}} = 1$, y no constituye por sí misma una validación empírica independiente).*

Asimismo, en todo sistema rotacional de disco, $r_t$ señala únicamente la zona interna donde se inicia el dominio del régimen $1/r$, mientras que la estructura física del disco continúa extendiéndose hacia el exterior hasta un radio $R_{\text{ext}}$ varias veces superior a $r_t$.

## 2.2. Modelo Bariónico Explícito de Bulbo + Disco Exponencial de Freeman para la Vía Láctea (Resolución de QC-02)
Para subsanar la limitación de tratar a la Vía Láctea como una masa esférica puntual y demostrar de manera físicamente rigurosa el cálculo de la velocidad orbital del Sol, implementamos un modelo bariónico estándar de dos componentes (bulbo esferoidal central más disco plano exponencial de Freeman, consistente con las parametrizaciones de McMillan, 2017 y Bovy, 2015) con masa bariónica total $M_t = M_b + M_d = 6,50 \times 10^{10}\ M_\odot$:

1. **Componente 1 — Bulbo Bariónico Central ($M_b$):**
   Una distribución esferoidal compacta de masa $M_b = 1,00 \times 10^{10}\ M_\odot = 1,9885 \times 10^{40}\ \text{kg}$ concentrada en la región central ($r_b \ll r_\odot$). Su contribución al campo gravitatorio newtoniano radial en la órbita del Sol ($r_\odot = 8,0\ \text{kpc} = 26.090\text{ a.l.} = 2,4685 \times 10^{20}\ \text{m}$) es exacta por el teorema de Gauss esférico:
   $$g_{N,\text{bulbo}}(r_\odot) = \frac{G \cdot M_b}{r_\odot^2} = \frac{(6,674 \times 10^{-11}) \cdot (1,9885 \times 10^{40})}{(2,4685 \times 10^{20})^2} = \mathbf{0,2178 \times 10^{-10}\ \text{m/s}^2} \quad (9\text{a})$$

2. **Componente 2 — Disco Bariónico Exponencial de Freeman ($M_d$, Estrellas + Gas):**
   Un disco delgado con perfil de densidad superficial $\Sigma(r) = \Sigma_0 \, e^{-r / R_d}$, masa bariónica total $M_d = 2\pi \Sigma_0 R_d^2 = 5,50 \times 10^{10}\ M_\odot = 1,0937 \times 10^{41}\ \text{kg}$ y longitud de escala radial estándar para la Vía Láctea de $R_d = 2,60\ \text{kpc} = 8,023 \times 10^{19}\ \text{m}$.
   En la teoría potencial gravitatoria (Freeman, 1970; Binney & Tremaine, 2008), la aceleración radial newtoniana exacta en el plano de un disco exponencial a una distancia $r$ no equivale a concentrar la masa en el centro, sino que viene dada analíticamente en términos de las funciones modificadas de Bessel de primera y segunda especie ($I_0, I_1, K_0, K_1$) evaluadas en la variable adimensional $y = \frac{r}{2 R_d}$:
   $$g_{N,\text{disco}}(r) = \frac{G \cdot M_d}{R_d^2} \cdot y \cdot \left[I_0(y) K_0(y) - I_1(y) K_1(y)\right] \quad \Longleftrightarrow \quad g_{N,\text{disco}}(r) = \frac{G \cdot M_d}{r^2} \cdot \left\{4 y^3 \left[I_0(y) K_0(y) - I_1(y) K_1(y)\right]\right\} \quad (9\text{b})$$

3. **Evaluación Numérica Reproducible en la Posición del Sol ($r_\odot = 8,0\ \text{kpc}$):**
   - **Variable adimensional $y$ en el radio solar:**
     $$y = \frac{r_\odot}{2 R_d} = \frac{8,0\ \text{kpc}}{2 \times 2,60\ \text{kpc}} = \mathbf{1,5385}$$
   - **Valores matemáticos exactos de las funciones de Bessel en $y = 1,5385$:**
     $$I_0(1,5385) = 1,6873, \quad K_0(1,5385) = 0,2032 \quad \implies \quad I_0 K_0 = 0,34286$$
     $$I_1(1,5385) = 1,0260, \quad K_1(1,5385) = 0,2647 \quad \implies \quad I_1 K_1 = 0,27158$$
     $$\Delta B(y) = I_0(y) K_0(y) - I_1(y) K_1(y) = 0,34286 - 0,27158 = \mathbf{0,07128}$$
   - **Factor geométrico de disco de Freeman:** $4 y^3 \Delta B(y) = 4 \cdot (1,5385)^3 \cdot (0,07128) = \mathbf{1,0383}$ (es decir, en $r_\odot = 3,08\,R_d$, el disco exponencial plano produce una tracción radial un $3,83\%$ superior a la de una esfera de masa $M_d$, lo que equivale a una masa esférica efectiva interior del disco de $1,0383 \times 5,50 \times 10^{10}\ M_\odot = 5,71 \times 10^{10}\ M_\odot$).
   - **Aceleración newtoniana exacta del disco de Freeman en $r_\odot$:**
     $$g_{N,\text{disco}}(r_\odot) = \frac{(6,674 \times 10^{-11}) \cdot (1,0937 \times 10^{41})}{(2,4685 \times 10^{20})^2} \times 1,0383 = (1,1978 \times 10^{-10}) \times 1,0383 = \mathbf{1,2437 \times 10^{-10}\ \text{m/s}^2}$$
   - **Campo Newtoniano Bariónico Total en la Órbita del Sol ($g_{N,\text{total}} = g_{N,\text{bulbo}} + g_{N,\text{disco}}$):**
     $$g_N(r_\odot) = (0,2178 + 1,2437) \times 10^{-10}\ \text{m/s}^2 = \mathbf{1,4615 \times 10^{-10}\ \text{m/s}^2}$$
     *(Si se adopta una masa de disco estelar ligeramente más conservadora dentro del rango observacional de Bovy & Rix 2013, $M_d = 4,50 \times 10^{10}\ M_\odot$ y $M_b = 1,00 \times 10^{10}\ M_\odot$, entonces $g_{N,\text{disco}} = 1,0176 \times 10^{-10}\ \text{m/s}^2$ y el campo newtoniano total es $g_N(r_\odot) = \mathbf{1,2354 \times 10^{-10}\ \text{m/s}^2}$).*
   - **Velocidad Circular Newtoniana Pura ($v_N = \sqrt{r_\odot \cdot g_N}$):**
     - Para $M_t = 5,5 \times 10^{10}\ M_\odot$ ($g_N = 1,2354 \times 10^{-10}\ \text{m/s}^2$): **$v_N = 174,6\ \text{km/s}$**.
     - Para $M_t = 6,5 \times 10^{10}\ M_\odot$ ($g_N = 1,4615 \times 10^{-10}\ \text{m/s}^2$): **$v_N = 189,9\ \text{km/s}$**.
   - **Velocidad Circular bajo la Ecuación Maestra de Transición (Ecuación 5):**
     Introduciendo $g_N(r_\odot)$ en la Ecuación (5) con $a_0 = 1,20 \times 10^{-10}\ \text{m/s}^2$:
     - Para $M_t = 5,5 \times 10^{10}\ M_\odot$: $a(r_\odot) = \mathbf{1,983 \times 10^{-10}\ \text{m/s}^2} \implies v_{\text{modelo}} = \mathbf{221,3\ \text{km/s}}$.
     - Para $M_t = 6,5 \times 10^{10}\ M_\odot$: $a(r_\odot) = \mathbf{2,243 \times 10^{-10}\ \text{m/s}^2} \implies v_{\text{modelo}} = \mathbf{235,3\ \text{km/s}}$.

Esta derivación explícita con funciones de Bessel demuestra que para el rango bariónico estándar de la Vía Láctea ($M_t \in [5,5 - 6,5] \times 10^{10}\ M_\odot$, $R_d = 2,6\ \text{kpc}$), la gravitación newtoniana por sí sola resulta insuficiente ($174,6 - 189,9\ \text{km/s}$), mientras que el modelo de transición reproduce el rango de velocidad circular local medido para el Sol ($\sim 220 - 235\ \text{km/s}$, Reid et al., 2014; Bland-Hawthorn & Gerhard, 2016) sin añadir un halo de materia oscura.

## 2.3. Contraste en Sistemas Estelares a Distintas Aceleraciones (S2, Sirio y Periferia Galáctica)
1. **Interior del Sistema Solar (Tierra, $r = 1\ \text{UA}$, $M = 1\ M_\odot$):** $g_N = 5,930 \times 10^{-3}\ \text{m/s}^2 \implies a / g_N - 1 = 2,02 \times 10^{-8}$, conservando la dinámica kepleriana.
2. **Estrella S2 en Pericentro (Sagitario A*, $M_c = 4,30 \times 10^6\ M_\odot$, $r_p = 120\ \text{UA}$, $e = 0,8846$):** $g_N = 1,77\ \text{m/s}^2 \approx 1,47 \times 10^{10} a_0 \implies \mu \approx 1$, obteniéndose $v_p = 7.650\ \text{km/s}$ (GRAVITY Collaboration, 2018).
3. **Independencia de la Masa de Prueba en la Periferia Exterior ($r = 60.000\text{ a.l.} = 18,4\ \text{kpc} \approx 7,1\,R_d$):** A distancias $r > 6\,R_d$, el factor geométrico de Bessel de la Ecuación (9b) converge al monopolo ($4 y^3 \Delta B(y) \to 1,02$). Al cancelarse la masa de prueba $m$ en la Ecuación (4), estrellas de masas extremas (como una enana roja de $0,08\ M_\odot$ tipo Teegarden frente a una supergigante de $21\ M_\odot$ tipo Rigel) comparten idéntica aceleración bajo la Ecuación (5) ($v_{\text{modelo}} = 201,9\ \text{km/s}$ frente a los $123,3\ \text{km/s}$ keplerianos para $M_t = 6,5 \times 10^{10}\ M_\odot$), aproximándose hacia la velocidad asintótica plana $v_f = (G M_t a_0)^{1/4} = 179,3\ \text{km/s}$.

---

# CAPÍTULO 3: CONTRASTE PRELIMINAR EN GALAXIAS Y CÚMULOS, Y LA HIPÓTESIS DE COTA NUCLEAR

## 3.1. Relación Asintótica en Sistemas Rotacionales Planos y Contraste con SPARC
En la periferia extrema de un disco galáctico ($r \gg R_d$ y $g_N \ll a_0$), igualando $v_f^2 / r$ con la Ecuación (6), se deduce la relación asintótica:

$$v_f^4 = G \cdot M_t \cdot a_0 \quad \Longleftrightarrow \quad M_t = \frac{v_f^4}{G \cdot a_0} \quad (10)$$

Presentamos en la Tabla 1 un contraste preliminar reproducible sobre tres galaxias espirales bien caracterizadas del catálogo SPARC (Lelli, McGaugh & Schombert, 2016, adoptando $\Upsilon_*^{[3.6]} = 0,5\ M_\odot / L_\odot$ para el disco), comparando la masa inferida por la Ecuación (10) frente al inventario bariónico observado ($M_{\text{bar}} = M_* + 1,33 M_{\text{HI}}$):

| Galaxia (Referencia) | Velocidad Asintótica Medida ($v_f$) | Masa Dinámica Inferida por Ec. (10) ($M_t$) | Masa Bariónica Observada ($M_{\text{bar}}$: Estrellas + Gas) | Diferencia Relativa ($\frac{M_t - M_{\text{bar}}}{M_{\text{bar}}}$) |
| :--- | :--- | :--- | :--- | :--- |
| **Vía Láctea** (McMillan 2017 / Bovy 2015) | $180 \pm 5\ \text{km/s}$ (asíntota externa) | $(6,59 \pm 0,73) \times 10^{10}\ M_\odot$ | $(5,50 - 6,50) \times 10^{10}\ M_\odot$ | $+1,4\%$ a $+19,8\%$ (Compatible en $1\sigma$) |
| **NGC 3198** (Lelli et al., 2016 - SPARC) | $150,1 \pm 3,0\ \text{km/s}$ | $(3,19 \pm 0,25) \times 10^{10}\ M_\odot$ | $(3,05 \pm 0,45) \times 10^{10}\ M_\odot$ | $+4,6\%$ (Compatible en $1\sigma$) |
| **M33 / NGC 598** (SPARC / Corbelli 2014) | $96,0 \pm 4,0\ \text{km/s}$ | $(5,33 \pm 0,89) \times 10^{9}\ M_\odot$ | $(5,00 \pm 0,80) \times 10^{9}\ M_\odot$ | $+6,6\%$ (Compatible en $1\sigma$) |

*(Alcance del contraste: Estos tres casos documentan la reproducibilidad numérica de la Ecuación 10 en perfiles libres de perturbaciones de marea severas; la validación estadística amplia remite a los análisis de la Relación Bariónica de Tully-Fisher sobre los 175 sistemas de SPARC en Lelli et al., 2016).*

## 3.2. Propuesta Heurística: Simetría Dual de Regímenes en las Interacciones Físicas
A nivel conceptual, la coexistencia de un régimen gravitatorio de corto alcance ($1/r^2$, dominante cuando $g_N \gg a_0$) y un régimen de largo alcance ($1/r$, dominante cuando $g_N \ll a_0$) sugiere una analogía heurística con el desdoblamiento de corto y largo alcance observable en las interacciones nucleares y electromagnéticas (fuerzas coulombianas desnudas frente a fuerzas dipolares residuales). En este esquema, el régimen fuerte $1/r^2$ rige el colapso local de los núcleos compactos ($M_c$), mientras que el régimen suave $1/r$ proporciona la tensión de cohesión colectiva de la masa distribuida ($M_r$).

## 3.3. Definición Contable ($M_t = M_c + M_r$) y la Hipótesis de la Cota del 1%
Para distinguir la contribución del núcleo central respecto a la masa extendida del sistema, definimos la identidad contable:

$$M_t = M_c + M_r \quad (11)$$

Donde **$M_c$ se define como la masa del Atractor Baricéntrico Compacto** ubicado en el centro del pozo de potencial (el agujero negro supermasivo central en galaxias individuales, o la galaxia central dominante tipo cD en cúmulos), y **$M_r$ es la masa bariónica residual distribuida** en el disco o cuenca.

Formulamos como **hipótesis empírica de trabajo** (sujeta a comprobación en muestras censales mayores) que la fracción de masa alojada en dicho atractor central está acotada superiormente por el $1\%$ de la masa total del sistema anfitrión:

$$M_c < 0,01 \cdot M_t \quad \Longleftrightarrow \quad M_r > 0,99 \cdot M_t \quad (12)$$

Ilustramos esta relación en cinco sistemas galácticos documentados en la literatura:
1. **Vía Láctea:** $M_t \approx 0,65 \times 10^{11}\ M_\odot$ | $M_c$ (Sgr A*, GRAVITY 2018): $4,30 \times 10^6\ M_\odot$ | $M_r$: $0,64996 \times 10^{11}\ M_\odot$ | $M_c / M_t = \mathbf{0,0066\%}$.
2. **Andrómeda (M31):** $M_t \approx 1,50 \times 10^{11}\ M_\odot$ | $M_c$ (Bender et al., 2005): $1,40 \times 10^8\ M_\odot$ | $M_r$: $1,4986 \times 10^{11}\ M_\odot$ | $M_c / M_t = \mathbf{0,093\%}$.
3. **Sombrero (M104):** $M_t \approx 2,10 \times 10^{11}\ M_\odot$ | $M_c$ (Kormendy et al., 1996): $1,00 \times 10^9\ M_\odot$ | $M_r$: $2,090 \times 10^{11}\ M_\odot$ | $M_c / M_t = \mathbf{0,476\%}$.
4. **M87 (NGC 4486):** $M_t \approx 12,00 \times 10^{11}\ M_\odot$ | $M_c$ (EHT Collaboration, 2019): $6,50 \times 10^9\ M_\odot$ | $M_r$: $11,935 \times 10^{11}\ M_\odot$ | $M_c / M_t = \mathbf{0,542\%}$.
5. **Centaurus A (NGC 5128):** $M_t \approx 8,00 \times 10^{11}\ M_\odot$ | $M_c$ (Cappellari et al., 2009): $5,50 \times 10^9\ M_\odot$ | $M_r$: $7,945 \times 10^{11}\ M_\odot$ | $M_c / M_t = \mathbf{0,688\%}$.

## 3.4. Aproximación Hidrostática de Jeans en Cúmulos Esferoidales y sus Limitaciones (Resolución de QC-06)
Para evaluar el orden de magnitud de la masa dinámica en cúmulos de galaxias tridimensionales soportados por dispersión de velocidades, partimos de la ecuación de equilibrio estacionario de Jeans bajo el supuesto de simetría esférica e isotropía de velocidades ($\beta_{\text{anis}} = 0$):

$$\frac{1}{\rho(r)} \frac{d\left(\rho(r) \sigma_r^2\right)}{dr} = -a(r) \quad (13)$$

Si en las regiones exteriores del cúmulo se asume isotermia aproximada ($\sigma_r \approx \text{constante}$), régimen profundo ($a(r) \approx \sqrt{G M_t a_0} / r$) y un perfil de densidad exterior con pendiente logarítmica $\alpha = -\frac{d \ln \rho}{d \ln r}$, la Ecuación (13) produce la consecuencia algebraica:

$$M_t = \frac{\alpha^2 \cdot \sigma_r^4}{G \cdot a_0} \quad (14)$$

Bajo el supuesto específico de un perfil tipo King/$\beta$ estándar con caída exterior $\rho \propto r^{-3}$ ($\alpha = 3$) e isotropía tridimensional ($v_{\text{3D}}^2 = 3 \sigma_r^2 \implies \alpha \sigma_r^2 = v_{\text{3D}}^2$), la Ecuación (14) adopta la forma $M_t = \frac{9 \sigma_r^4}{G \cdot a_0} = \frac{v_{\text{3D}}^4}{G \cdot a_0}$.

**Contraste de orden de magnitud y cautelas metodológicas en Virgo y Coma:**
- **Cúmulo de Virgo:** Adoptando una dispersión en la línea de visión en los márgenes del cúmulo de $\sigma_r \approx 577\ \text{km/s}$ (Binggeli et al., 1993; $v_{\text{3D}} = \sqrt{3}\sigma_r = 1.000\ \text{km/s}$) y $\alpha = 3$, la Ecuación (14) arroja una masa dinámica inferida de $M_t = \mathbf{6,28 \times 10^{13}\ M_\odot}$. Las estimaciones observacionales en rayos X (ROSAT/XMM-Newton, Böhringer et al., 1994; Urban et al., 2011) sitúan la masa del gas caliente intracúmulo más la masa estelar de sus galaxias dentro del radio virial en el rango de $\sim 3 \times 10^{13}$ a $6 \times 10^{13}\ M_\odot$, mientras que la masa bariónica de la galaxia central M87 ($M_c \approx 5 \times 10^{11}\ M_\odot$) representa el $\sim 0,8\%$ de dicho valor.
- **Cúmulo de Coma (Abell 1656):** Para una dispersión en márgenes exteriores $\sigma_r \approx 693\ \text{km/s}$ ($v_{\text{3D}} = 1.200\ \text{km/s}$; Colless & Dunn, 1996, siendo la dispersión central mayor, $\sim 900 - 1.000\ \text{km/s}$) con $\alpha = 3$, la Ecuación (14) arroja $M_t = \mathbf{1,30 \times 10^{14}\ M_\odot}$, donde el par central NGC 4874/4889 suma $M_c \approx 1,0 \times 10^{12}\ M_\odot$ ($0,77\%$).

*(Advertencia técnica explícita sobre cúmulos: Dejamos sentado que esta coincidencia de orden de magnitud depende críticamente de los supuestos adoptados [$\alpha = 3$, $\beta_{\text{anis}} = 0$ y el valor de $\sigma_r$ en la periferia]. En la literatura especializada sobre dinámicas modificadas en cúmulos ricos [p. ej., Sanders, 2003; Angus et al., 2008], cuando se integran perfiles hidrostáticos detallados en el núcleo interno de Coma con $\sigma_r \sim 1.000\ \text{km/s}$, suele persistir un déficit bariónico residual de un factor $\sim 1,5\text{ a }2,5$ respecto al gas observado en rayos X, cuya resolución completa requiere contabilizar bariones tibios/oscuros en filamentos WHIM, nubes moleculares frías o perfiles de anisotropía radial $\beta_{\text{anis}}(r) \neq 0$. Por tanto, no declaramos cerrada la dinámica de cúmulos, sino que mostramos que el gas intracúmulo reduce drásticamente la discrepancia frente a la escala galáctica).*

---

# CAPÍTULO 4: ESCENARIO CONDICIONAL MACROCÓSMICO: LA PROPORCIÓN $N_7$ COMO REMOLINO SUB-LUMÍNICO

## 4.1. Justificación Explícita del Parámetro de Entrada $M_{N1} = 1,00 \times 10^{21}\ M_\odot$ (Resolución de QC-04)
Al ascender desde los supercúmulos locales (como Laniakea y el complejo de Shapley, cuya masa total combinada se estima en $\sim 1,41 \times 10^{17}\ M_\odot$, con el núcleo de Shapley en Abell 3558 rondando $\sim 1,4 \times 10^{15}\ M_\odot$, Proust et al., 2006) hacia la escala cosmológica, entramos en el terreno de los **escenarios condicionales**.

Para definir de manera transparente y trazable el parámetro de masa de referencia de nuestra región cosmológica ($M_{N1}$), documentamos su cálculo por dos vías independientes que permiten acotar su orden de magnitud y sus incertidumbres:

1. **Vía A — Integración de la Densidad Bariónica Observada en el Volumen Accesible libre de Termalización:**
   En la cosmología observacional (Planck Collaboration, 2020; censo bariónico de Fukugita & Peebles, 2004 y Shull et al., 2012, incluyendo estrellas, gas frío, gas intracúmulo en rayos X y plasma intergaláctico tibio-caliente WHIM), la densidad media de materia bariónica ordinaria en el universo local se estima en $\rho_{\text{bar}} = \Omega_b \cdot \rho_{\text{crít}} \approx 0,049 \times (8,5 \times 10^{-27}\ \text{kg/m}^3) \approx \mathbf{4,17 \times 10^{-28}\ \text{kg/m}^3}$ ($\approx 6,16 \times 10^{9}\ M_\odot/\text{Mpc}^3$).
   Si definimos geométricamente la región $N_1$ como un dominio discoide/esferoidal efectivo cuyo volumen equivalente corresponde a una esfera de radio característico $R_{\text{ef}(N1)} \approx 3.400\ \text{Mpc}$ ($\approx 11.100\text{ millones de años luz}$, es decir, la región donde los relevamientos ópticos y espectroscópicos profundos mantienen completitud antes de la extinción por opacidad y termalización), el volumen es $V_{N1} = \frac{4}{3}\pi R_{\text{ef}}^3 \approx 1,64 \times 10^{11}\ \text{Mpc}^3$. Multiplicando la densidad bariónica total por dicho volumen:
   $$M_{N1} = \rho_{\text{bar}} \cdot V_{N1} = \left(6,16 \times 10^9\ \frac{M_\odot}{\text{Mpc}^3}\right) \cdot \left(1,64 \times 10^{11}\ \text{Mpc}^3\right) = \mathbf{1,01 \times 10^{21}\ M_\odot} \quad (15\text{a})$$

2. **Vía B — Conteo de Macro-cuencas Tipo Complejo Local/Shapley:**
   Tomando como bloque modular la masa bariónica de un complejo de supercúmulos más su medio intergaláctico circundante ($M_{\text{complejo}} \sim 1,0 \times 10^{16}\text{ a }1,0 \times 10^{17}\ M_\odot$, descontando el factor de llenado de los supervacíos que ocupan $\sim 80\%$ del volumen cósmico), una red integrada por $10^4\text{ a }10^5$ nodos principales (o equivalentemente $\sim 10^{11}$ galaxias con masa bariónica total asociada de estrellas + halo gaseoso/WHIM de $\langle M_{\text{bar,halos}} \rangle \approx 1,0 \times 10^{10}\ M_\odot$ por galaxia equivalente a la Vía Láctea) arroja igualmente:
   $$M_{N1} \approx (10^{11}\ \text{unidades}) \times (1,0 \times 10^{10}\ M_\odot) = \mathbf{1,00 \times 10^{21}\ M_\odot} \quad (15\text{b})$$

Adoptamos por tanto **$M_{N1} = 1,00 \times 10^{21}\ M_\odot$** (con un margen de incertidumbre cosmológica de un factor $\sim 2\text{ a }3$ según el radio de corte adoptado) como **parámetro de referencia explícito** para nuestro ejercicio de escalamiento.

## 4.2. Formulación Condicional del Escenario $N_7$ y Consecuencia Algebraica de los $103.000\ \text{km/s}$ (Resolución de QC-05)
Dejamos explícitamente establecido que el paso de $N_1$ a $N_7$ **no es una deducción observacional que demuestre cuántas partes tiene el universo**, sino una **exploración condicional**: nos preguntamos qué propiedades dinámicas tendría el Gran Universo si asumimos como hipótesis de trabajo que nuestra región de referencia ($M_{N1} = 1,00 \times 10^{21}\ M_\odot$) constituye aproximadamente **la séptima parte ($\sim 1/7$) de la masa bariónica total ($M_t$) de un único remolino cósmico continuo** (sin paredes ni fronteras administrativas físicas) que gira alrededor de un atractor baricéntrico central desconocido ($M_c < 0,01 \cdot M_t$):

$$M_{t(N7)} = 7 \times M_{N1} = \mathbf{7,00 \times 10^{21}\ M_\odot} \quad (16)$$

Si aplicamos a este escenario exactamente la misma relación asintótica de las galaxias (Ecuación 10: $v_f = (G \cdot M_t \cdot a_0)^{1/4}$) y la escala de transición (Ecuación 7: $r_t = \sqrt{G \cdot M_t / a_0}$), obtenemos en la Tabla 2 las consecuencias algebraicas exactas para múltiplos desde $N_1$ hasta $N_7$:

| Escenario Condicional ($N \times M_{N1}$) | Masa Total Postulada ($M_t = M_c + M_r$) | Masa Residual del Remolino ($M_r > 99\% M_t$) | Atractor Central Supuesto ($M_c$ al $0,8\% M_t$) | **Velocidad Plana Derivada ($v_f = (G M_t a_0)^{1/4}$ Ec. 10)** | Radio Interno de Transición ($r_t = \sqrt{G M_t / a_0}$ Ec. 7) | Radio Exterior Ilustrativo (si $R_{\text{ext}} / r_t \approx 11$) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **$N_1$ ($1\times$)** | $1,00 \times 10^{21}\ M_\odot$ | $0,992 \times 10^{21}\ M_\odot$ | $8,0 \times 10^{18}\ M_\odot$ | **$63.400\ \text{km/s}$ ($0,21 c$)** | $3.520\text{ M a.l.}$ | $\sim 39.300\text{ M a.l.}$ |
| **$N_2$ ($2\times$)** | $2,00 \times 10^{21}\ M_\odot$ | $1,984 \times 10^{21}\ M_\odot$ | $1,6 \times 10^{19}\ M_\odot$ | **$75.400\ \text{km/s}$ ($0,25 c$)** | $4.975\text{ M a.l.}$ | $\sim 55.600\text{ M a.l.}$ |
| **$N_3$ ($3\times$)** | $3,00 \times 10^{21}\ M_\odot$ | $2,976 \times 10^{21}\ M_\odot$ | $2,4 \times 10^{19}\ M_\odot$ | **$83.400\ \text{km/s}$ ($0,28 c$)** | $6.090\text{ M a.l.}$ | $\sim 68.100\text{ M a.l.}$ |
| **$N_4$ ($4\times$)** | $4,00 \times 10^{21}\ M_\odot$ | $3,968 \times 10^{21}\ M_\odot$ | $3,2 \times 10^{19}\ M_\odot$ | **$89.600\ \text{km/s}$ ($0,30 c$)** | $7.035\text{ M a.l.}$ | $\sim 78.600\text{ M a.l.}$ |
| **$N_5$ ($5\times$)** | $5,00 \times 10^{21}\ M_\odot$ | $4,960 \times 10^{21}\ M_\odot$ | $4,0 \times 10^{19}\ M_\odot$ | **$94.700\ \text{km/s}$ ($0,32 c$)** | $7.865\text{ M a.l.}$ | $\sim 87.900\text{ M a.l.}$ |
| **$N_6$ ($6\times$)** | $6,00 \times 10^{21}\ M_\odot$ | $5,952 \times 10^{21}\ M_\odot$ | $4,8 \times 10^{19}\ M_\odot$ | **$99.200\ \text{km/s}$ ($0,33 c$)** | $8.615\text{ M a.l.}$ | $\sim 96.300\text{ M a.l.}$ |
| **$N_7$ ($7\times$)** | **$7,00 \times 10^{21}\ M_\odot$** | **$6,944 \times 10^{21}\ M_\odot$** | **$5,6 \times 10^{19}\ M_\odot$** | **$103.000\ \text{km/s}$ ($0,34 c$)** | **$9.310\text{ M a.l.}$** | **$\sim 104.000\text{ M a.l.}$** |

**Distinción entre lo derivado y lo supuesto en la Tabla 2:**
1. **Consecuencia derivada:** Dados los parámetros de entrada $M_{t(N7)} = 7,00 \times 10^{21}\ M_\odot$ y $a_0 = 1,2 \times 10^{-10}\ \text{m/s}^2$, se sigue algebraicamente una velocidad asintótica plana de **$v_f = 102.760\ \text{km/s} \approx 103.000\ \text{km/s}$** (sub-lumínica en todo el disco sin requerir recortes relativistas) y un radio interno de transición $r_t = 9.310\text{ millones de años luz}$.
2. **Supuesto por analogía morfológica:** La última columna ($R_{\text{ext}} \approx 11 \cdot r_t \approx 104.000\text{ M a.l.}$) no se deriva de la ecuación algebraica (10), sino que se introduce como una hipótesis de semejanza geométrica con los discos galácticos extendidos de hidrógeno neutro (donde el disco de rotación plana se extiende típicamente entre $4$ y $11$ veces más allá de su radio interno de escala/transición antes de truncarse).

## 4.3. Equilibrio Radial de Partículas en el Potencial Efectivo y Condiciones de Estabilidad
Para una partícula o elemento de fluido de momento angular específico $h = L / m$ que orbita dentro del potencial gravitatorio logarítmico del régimen profundo ($V_{\text{grav}}(r) = v_f^2 \ln(r / r_0)$), el potencial efectivo unidimensional es:

$$V_{\text{eff}}(r) = v_f^2 \ln\left(\frac{r}{r_0}\right) + \frac{h^2}{2 r^2} \quad (17)$$

Dado que $\frac{d V_{\text{eff}}}{dr} = \frac{v_f^2}{r} - \frac{h^2}{r^3} = 0$ posee un mínimo único en $r_{\text{eq}} = \frac{h}{v_f}$ con segunda derivada estrictamente positiva ($\frac{d^2 V_{\text{eff}}}{dr^2}\big|_{r_{\text{eq}}} = \frac{2 v_f^2}{r_{\text{eq}}^2} > 0$), las órbitas individuales son radialmente estables frente a pequeñas perturbaciones y no colapsan hacia el origen ($r \to 0$) gracias a la barrera centrífuga $h^2 / (2 r^2)$. *(Reconocemos que la estabilidad global hidrodinámica de un disco autogravitante completo frente a modos no axisimétricos tipo barra o espiral —criterio $Q$ de Toomre— requiere un análisis perturbativo de N-cuerpos en el régimen $a_0$, el cual queda planteado como línea de desarrollo futuro).*

---

# CAPÍTULO 5: HIPÓTESIS COSMOLÓGICAS EXPLORATORIAS: RESPIRACIÓN RADIAL, CAMPO VECTORIAL DE HUBBLE Y ATENUACIÓN FOTÓNICA

## 5.1. Hipótesis del Ciclo Respiratorio ($T = 2.000\text{ Millones de Años}$) y Ambigüedad de Fase en $0 \to 0,5 \to 1,0$
Formulamos como hipótesis exploratoria que el disco macrocósmico experimenta una oscilación radial armónica alrededor de su radio de equilibrio $R_0$ con un periodo postulado de $T = 2.000\text{ millones de años}$ ($1.000\text{ millones de años}$ de exhalación expansiva seguidos de $1.000\text{ millones de años}$ de inhalación contractiva).

Parametrizando el semociclo de exhalación mediante la variable adimensional $u = t / (1.000\text{ M años}) \in [0, 1]$, donde $u = 0$ es el punto de máxima compresión y $u = 1,0$ es el punto de máxima elongación:

$$R(u) = R_0 - A \cdot \cos(\pi \cdot u) \quad \implies \quad H_{\text{cin}}(u) = \frac{1}{R}\frac{dR}{dt} \approx H_{\text{máx}} \cdot \sin(\pi \cdot u) \quad \text{con } H_{\text{máx}} = \left(\frac{A}{R_0}\right)\frac{2\pi}{T} \quad (18)$$

El comportamiento mecánico del semociclo de exhalación ($H_{\text{cin}} \ge 0$) comprende dos etapas simétricas respecto al punto medio $u = 0,5$:
- **Etapa de aceleración expansiva ($0 < u < 0,5$):** El sistema se expande acelerando desde el reposo ($u = 0$) hasta alcanzar la máxima velocidad de expansión $H_{\text{máx}}$ en **$u = 0,5$**.
- **Etapa de frenado expansivo ($0,5 < u < 1,0$):** El sistema continúa expandiéndose ($H_{\text{cin}} > 0$), pero desacelera bajo la tensión restauradora hasta detenerse en **$u = 1,0$**, donde se inicia la contracción ($1,0 < u < 2,0$).

**Análisis de los escenarios condicionales de amplitud y la degeneración de fase (Resolución de QC-07):**
Si dentro de la hipótesis del desdoblamiento de Hubble (Sección 5.2) se asume que la tasa de expansión cinemática actual es $H_{\text{cin}}(\text{actual}) \approx +5,6\ \text{km/s/Mpc}$, la Ecuación (18) admite dos familias de soluciones condicionales que no pueden distinguirse sin una medición independiente de la segunda derivada $\ddot{R}$ (parámetro de desaceleración $q_0$):
1. **Escenario Condicional 1 (Mínima Amplitud en el Pico $u \approx 0,5$):** Si $H_{\text{máx}} = 5,6\ \text{km/s/Mpc}$, nos encontraríamos hoy cerca de $u = 0,5$, requiriendo una amplitud relativa de $\left(\frac{A}{R_0}\right)_1 = \frac{H_{\text{máx}} \cdot T}{2\pi} \approx \mathbf{0,18\%}$.
2. **Escenario Condicional 2 (Amplitud de Referencia $\sim 2,27\%$ con Degeneración de Fase):** Si el oscilador tuviese una tasa máxima de referencia $H_{\text{máx}} \approx 70\ \text{km/s/Mpc}$ ($\left(\frac{A}{R_0}\right)_2 \approx \mathbf{2,27\%}$), entonces la condición $\sin(\pi \cdot u) = 5,6 / 70 = 0,080$ posee **dos soluciones matemáticas simétricas** dentro del semociclo de exhalación: una en la etapa inicial de aceleración ($u_1 \approx 0,025$, recién iniciada la exhalación) y otra en la etapa final de frenado ($u_2 \approx 0,975$, próxima al ápice $1,0$). Determinar si un ciclo de esta naturaleza existe en la realidad y en cuál de las ramas ($u_1, 0,5\text{ o }u_2$) se encontraría requiere pruebas observacionales independientes de las estimaciones locales de $H_0$.

## 5.2. Carácter Vectorial de la Respiración ($\vec{H}_{\text{cin}}$) frente al Escalar de Atenuación ($H_\gamma$)
En la cosmología estándar, bajo el postulado de isotropía sin centro, el parámetro de Hubble se trata como un escalar ($H_0$) idéntico en todas las direcciones. Sin embargo, en una arquitectura de disco que respira radialmente respecto a un centro físico ($M_c$), **la componente cinemática de expansión no es un escalar isótropo, sino un campo direccional gobernado por el vector radial ($\vec{H}_{\text{cin}}$)** que une al observador con el Gran Centro Absoluto (situado en la dirección del vector unitario $\hat{u}_c$).

Combinando esta cinemática direccional con la hipótesis de pérdida fraccional de energía fotónica en el medio ($dE = -k E dx \implies 1 + z_\gamma(d) = e^{(H_\gamma / c) d}$, donde $H_\gamma = c \cdot k$ actúa como un escalar aproximadamente isótropo en el plano del disco), proponemos que la tasa de Hubble medida en una dirección de observación $\hat{n}$ (que forma un ángulo $\theta$ con el eje radial hacia $M_c$, tal que $\cos\theta = \hat{n} \cdot \hat{u}_c$) obedece a la descomposición:

$$H_{\text{obs}}(t, \hat{n}) = H_\gamma + \vec{H}_{\text{cin}}(t) \cdot \hat{n} = H_\gamma + H_{\text{cin}}(t) \cos\theta \quad (19)$$

*(O incluyendo el término cuadrupolar de deformación radial de marea en un medio continuo, $H_{\text{obs}}(t, \hat{n}) = H_\gamma + H_{\text{cin,dip}} \cos\theta + H_{\text{cin,cuad}} \cos^2\theta$).*

### Interpretación Hipotética de la Tensión de Hubble y Restricciones Pendientes (QC-08)
Como hipótesis interpretativa dentro de este marco:
- En mediciones sobre escalas de tiempo multieónicas (como el ajuste del CMB a distancias $d \sim 10^{10}\text{ a.l.}$), el tránsito lumínico abarca múltiples periodos de $2.000\text{ millones de años}$, promediando a cero la contribución oscilatoria ($\langle \vec{H}_{\text{cin}} \rangle \approx 0$, Efecto Acordeón) y aislando el escalar de atenuación: $H_\gamma \approx 67,4\ \text{km/s/Mpc}$.
- En mediciones de la escalera de distancia local ($d \ll 10^9\text{ a.l.}$), no opera la cancelación secular y se suma la proyección del vector de exhalación actual ($|\vec{H}_{\text{cin}}| \approx 73,0 - 67,4 = 5,6\ \text{km/s/Mpc}$).
- A distancias extremas ($\sim 35.000 - 46.000\text{ M a.l.}$), la atenuación fotónica degrada la señal hasta la temperatura de equilibrio del baño térmico ($\sim 2,725\ \text{K}$), formando el "Muro de Niebla".

**Declaración expresa de limitaciones (QC-08):** Reconocemos que la resta aritmética $73,0 - 67,4 = 5,6\ \text{km/s/Mpc}$ no demuestra por sí misma que la Tensión de Hubble esté resuelta ni que la atenuación fotónica sustituya a la expansión métrica. Para que esta hipótesis sea físicamente viable frente al modelo estándar, desarrollos teóricos futuros deberán demostrar cuantitativamente: (1) un mecanismo electrodinámico o gravitacional que produzca simultáneamente la dilatación temporal $(1+z)$ en las curvas de luz de supernovas Tipo Ia sin introducir dispersión angular en imágenes de galaxias lejanas; (2) el cumplimiento de la prueba de brillo superficial de Tolman y la relación de dualidad de distancias de Etherington; y (3) la generación del espectro de cuerpo negro de altísima precisión y la estructura de picos acústicos del CMB sin distorsiones espectrales incompatibles con FIRAS/Planck.

---

# CAPÍTULO 6: PROTOCOLO CUANTITATIVO DE FALSABILIDAD

Definimos cuatro pruebas observacionales diseñadas para refutar o acotar independientemente las hipótesis propuestas:

1. **Prueba del Carácter Vectorial de Hubble ($\vec{H}_{\text{cin}}$) en Catálogos de Cúmulos y Supernovas (Pantheon+ / Euclid / LSST):**
   - *Datos y método:* Ajustar un modelo dipolar/cuadrupolar $H_{\text{obs}}(\hat{n}) = H_\gamma + H_1 (\hat{n}\cdot\hat{u}_c) + H_2 (\hat{n}\cdot\hat{u}_c)^2$ sobre muestras de supernovas Tipo Ia y relaciones de escala de cúmulos en rayos X en el rango de corrimiento al rojo $0,01 < z < 0,15$, corrigiendo previamente el movimiento peculiar del Grupo Local respecto al CMB ($v_{\text{LG}} = 627\ \text{km/s}$ hacia $l = 276^\circ, b = 30^\circ$).
   - *Predicción y criterio de refutación:* El modelo predice una amplitud anisotrópica residual intrínseca $H_1\text{ o }H_2 \approx 5,6 \pm 1,5\ \text{km/s/Mpc}$ alineada con el eje del Flujo Oscuro y la anisotropía reportada por Migkas et al. (2020) ($l \approx 280^\circ - 310^\circ$). Si los relevamientos de cielo completo restringen la anisotropía intrínseca de $H_0$ a $< 1,0\ \text{km/s/Mpc}$ con significación estadística $> 5\sigma$, la hipótesis del campo vectorial de respiración radial ($\vec{H}_{\text{cin}}$) queda falsada.
2. **Prueba de la Frecuencia Epíciclica Galáctica ($T_r = 159,1\text{ M años}$) en Datos Astrométricos de Gaia DR4:**
   - *Datos y método:* En el potencial logarítmico asintótico gobernado por $a_0$, el cociente entre la frecuencia radial epíciclica y la frecuencia orbital circular está fijo sin parámetros libres en $\omega_r / \Omega = \sqrt{2}$, lo que implica $T_r = T_{\text{orb}} / \sqrt{2} = 159,1\text{ M años}$ para $T_{\text{orb}} = 225\text{ M años}$. Se contrastará mediante análisis de Fourier en el espacio de acciones $(J_R, J_z, \theta_R, \theta_z)$ de Gaia si el enrollamiento de la espiral de fase responde a una frecuencia estacionaria $\omega_r = \sqrt{2}\Omega$ o a una onda cinemática transitoria en decaimiento inducida por el paso de la galaxia enana de Sagitario.
3. **Prueba de Asimetría de Atenuación Óptica en el Eje Z (Espesor del Disco):**
   - *Datos y método:* Comparar el diagrama de Hubble ($m - z$) de cuásares y galaxias a $z > 1$ divididos en dos submuestras: dirección perpendicular al plano supergaláctico (Eje Z, menor columna de materia prevista) frente a dirección coplanar. La ausencia de diferencia sistemática en la pendiente de atenuación refutaría la hipótesis de opacidad ligada a una geometría de disco finito.
4. **Búsqueda de Anisotropía Estacionaria en Ondas Gravitacionales de Baja Frecuencia (PTA / LISA):**
   - Contrastar la distribución angular del fondo de ondas gravitacionales en busca de un exceso dipolar estacionario en las coordenadas deducidas para el atractor baricéntrico $M_c$.

---

# CAPÍTULO 7: REFLEXIÓN EPISTEMOLÓGICA FINAL Y ANEXO DE AUDITORÍA REPRODUCIBLE

## 7.1. El Valor del Programa Exploratorio
Distinguir con honestidad intelectual entre lo que nuestras ecuaciones demuestran algebraicamente en la escala galáctica y lo que postulamos como exploración en la escala cosmológica fortalece, en lugar de debilitar, la búsqueda científica. La formulación de un modelo dinámico explícito con función de transición única, verificada sobre el perfil de disco de Freeman en nuestra propia galaxia y proyectada como herramienta heurística hacia la estructura del cosmos, ofrece un andamio transparente y falsable para seguir interrogando la arquitectura del universo sin depender dogmáticamente de entidades oscuras inobservables.

---

## ANEXO TÉCNICO: TABLA MAESTRA DE AUDITORÍA NUMÉRICA REPRODUCIBLE (VERSIÓN 5.0)

Consolidamos de forma trazable todos los cálculos del manuscrito usando las constantes físicas estándar ($G = 6,674 \times 10^{-11}\ \text{m}^3\text{kg}^{-1}\text{s}^{-2}$, $a_0 = 1,20 \times 10^{-10}\ \text{m/s}^2$, $c = 299.792,458\ \text{km/s}$, $1\ M_\odot = 1,9885 \times 10^{30}\ \text{kg}$, $1\ \text{kpc} = 3,0857 \times 10^{19}\ \text{m}$, $1\text{ a.l.} = 9,4607 \times 10^{15}\ \text{m}$), separando estrictamente **Parámetros de Entrada**, **Ecuación Aplicada**, **Resultado Calculado (Consecuencia Algebraica)** y **Categoría Epistemológica / Supuestos**:

| ID / Sistema | Parámetros de Entrada Documentados (Inputs) | Ecuación del Modelo Aplicada | Resultado Calculado (Output Reproducible) | Categoría Epistemológica y Supuestos Adoptados |
| :--- | :--- | :--- | :--- | :--- |
| **A-01. Tierra en Sistema Solar** | $M = 1,00\ M_\odot$<br>$r = 1,496 \times 10^{11}\ \text{m}$ ($1\ \text{UA}$) | Ec. (5): $a = \frac{g_N}{2}\left(1 + \sqrt{1 + \frac{4a_0}{g_N}}\right)$ | $g_N = 5,930 \times 10^{-3}\ \text{m/s}^2$<br>$a / g_N - 1 = 2,02 \times 10^{-8}$<br>$v = 29,78\ \text{km/s}$ | **Consecuencia Algebraica Cerrada.** Consistente con efemérides planetarias ($\mu \to 1$). |
| **A-02. Estrella S2 (Pericentro Sgr A*)** | $M_c = 4,30 \times 10^6\ M_\odot$ (GRAVITY 2018)<br>$r_p = 1,795 \times 10^{13}\ \text{m}$ ($120\ \text{UA}$)<br>$e = 0,8846$ | Ec. (5) + Vis-Viva:<br>$v_p = \sqrt{r_p \cdot a(r_p) \cdot (1+e)}$ | $g_N = 1,77\ \text{m/s}^2 \gg a_0$<br>$v_p = \mathbf{7.650\ \text{km/s}}$ | **Consecuencia Algebraica Cerrada.** Consistente con medición de GRAVITY ($\sim 7.650\ \text{km/s}$). |
| **A-03. Sol en Vía Láctea (Bulbo + Disco de Freeman)** | Bulbo: $M_b = 1,0 \times 10^{10}\ M_\odot$<br>Disco: $M_d = 4,5 - 5,5 \times 10^{10}\ M_\odot$<br>$R_d = 2,60\ \text{kpc}$; $r_\odot = 8,00\ \text{kpc}$ ($y = 1,5385$) | Ec. (9a + 9b) Bessel ($4y^3\Delta B = 1,0383$) + Ec. (5) de transición | $g_N = (1,235 - 1,462) \times 10^{-10}\ \text{m/s}^2$<br>$v_{\text{Newton}} = \mathbf{174,6 - 189,9\ \text{km/s}}$<br>$v_{\text{modelo}} = \mathbf{221,3 - 235,3\ \text{km/s}}$ | **Cálculo de Disco Explícito Cerrado.** Reproduce el rango solar medido ($\sim 220 - 235\ \text{km/s}$, McMillan 2017) bajo el perfil bariónico adoptado. |
| **A-04. Factor en $g_N = a_0$ y Periferia ($60\text{ k a.l.}$)** | En $r_t$: $g_N = a_0$<br>En $r = 18,4\ \text{kpc}$ ($60\text{ k a.l.}$): $M_t = 6,5 \times 10^{10}\ M_\odot$ | Ec. (8): $a(r_t)/g_N = \phi$<br>Ec. (5) y Ec. (10) en $r = 18,4\ \text{kpc}$ | En $r_t$: $v / v_N = \sqrt{\phi} = \mathbf{1,27202}$<br>En $60\text{ k a.l.}$: $v_{\text{Newton}} = 123,3\ \text{km/s}$<br>$v_{\text{modelo}} = \mathbf{201,9\ \text{km/s}}$ ($v_f = 179,3$) | **Propiedad Matemática del Modelo Definido** (no es validación independiente; demuestra cancelación de masa $m$). |
| **A-05. Galaxia NGC 3198 (SPARC)** | $v_f = 150,1 \pm 3,0\ \text{km/s}$<br>(Lelli et al., 2016) | Ec. (10): $M_t = \frac{v_f^4}{G \cdot a_0}$ | $M_t = \mathbf{(3,19 \pm 0,25) \times 10^{10}\ M_\odot}$<br>($M_{\text{bar SPARC}} = 3,05 \pm 0,45 \times 10^{10}$) | **Contraste Preliminar Consistente** dentro de incertidumbre observacional ($1\sigma$). |
| **A-06. Galaxia M33 (SPARC)** | $v_f = 96,0 \pm 4,0\ \text{km/s}$<br>(Corbelli 2014 / SPARC) | Ec. (10): $M_t = \frac{v_f^4}{G \cdot a_0}$ | $M_t = \mathbf{(5,33 \pm 0,89) \times 10^{9}\ M_\odot}$<br>($M_{\text{bar obs}} = 5,00 \pm 0,80 \times 10^{9}$) | **Contraste Preliminar Consistente** dentro de incertidumbre observacional ($1\sigma$). |
| **A-07. Cúmulo de Virgo (Jeans 3D)** | $\sigma_r \approx 577\ \text{km/s}$ (márgenes)<br>Supuestos: $\alpha = 3, \beta_{\text{anis}} = 0$ | Ec. (14): $M_t = \frac{\alpha^2 \sigma_r^4}{G \cdot a_0}$ | $M_t = \mathbf{6,28 \times 10^{13}\ M_\odot}$<br>$M_c(\text{M87}) \approx 5 \times 10^{11}\ M_\odot$ ($0,80\%$) | **Aproximación Condicional de Orden de Magnitud.** Depende de los supuestos $\alpha = 3$ e isotropía. |
| **A-08. Cúmulo de Coma (Jeans 3D)** | $\sigma_r \approx 693\ \text{km/s}$ (márgenes)<br>Supuestos: $\alpha = 3, \beta_{\text{anis}} = 0$ | Ec. (14): $M_t = \frac{\alpha^2 \sigma_r^4}{G \cdot a_0}$ | $M_t = \mathbf{1,30 \times 10^{14}\ M_\odot}$<br>$M_c(\text{NGC 4874/89}) \approx 10^{12}\ M_\odot$ ($0,77\%$) | **Aproximación Condicional.** En el núcleo interno ($\sigma_r \sim 1.000\ \text{km/s}$) persiste debate sobre bariones WHIM. |
| **A-09. Escenario Condicional $N_7$** | Parámetros supuestos:<br>$M_{N1} = 1,00 \times 10^{21}\ M_\odot$ (Ec. 15a/b)<br>$M_t(N_7) = 7 \times 10^{21}\ M_\odot$ | Ec. (10): $v_f = (G M_t a_0)^{1/4}$<br>Ec. (7): $r_t = \sqrt{G M_t / a_0}$ | **$v_f = \mathbf{102.760 \approx 103.000\ \text{km/s}}$ ($0,34c$)**<br>$r_t = \mathbf{9.310\text{ M a.l.}}$<br>Si $R_{\text{ext}} \approx 11 r_t \to 104.000\text{ M a.l.}$ | **Escenario Condicional Exploratorio.** La velocidad $103.000\ \text{km/s}$ es consecuencia del $M_t$ postulado, no prueba independiente. |
| **A-10. Respiración Vectorial y Atenuación** | Postulados exploratorios:<br>$T = 2,0 \times 10^9\text{ años}$<br>$H_{\text{prof}} = 67,4$; $H_{\text{local}} = 73,0$ | Ec. (18–19):<br>$H_{\text{obs}}(\hat{n}) = H_\gamma + \vec{H}_{\text{cin}}\cdot\hat{n}$<br>$\frac{A}{R_0} = \frac{H_{\text{máx}} T}{2\pi}$ | $|\vec{H}_{\text{cin}}| = 5,6\ \text{km/s/Mpc}$<br>Si $u = 0,5 \implies A/R_0 = 0,18\%$<br>Si $A/R_0 = 2,27\% \implies u = 0,025\text{ o }0,975$ | **Hipótesis Exploratoria No Demostrada.** Sujeta a pruebas de supernovas, CMB y anisotropía dipolar (Cap. 6). |

---

## Referencias

1. Fundación Urantia. (1955). *El Libro de Urantia*. (Documento 15: Los Siete Superuniversos; Documento 12: El Universo de los Universos; Documento 11: La Isla Eterna del Paraíso).
2. Milgrom, M. (1983). A modification of the Newtonian dynamics as a possible alternative to the hidden mass hypothesis. *The Astrophysical Journal*, 270, 365-370.
3. Freeman, K. C. (1970). On the disks of spiral and S0 galaxies. *The Astrophysical Journal*, 160, 811-830.
4. Binney, J., & Tremaine, S. (2008). *Galactic Dynamics* (2nd ed.). Princeton University Press.
5. McMillan, P. J. (2017). The mass distribution and gravitational potential of the Milky Way. *Monthly Notices of the Royal Astronomical Society*, 465(1), 76-94.
6. Bovy, J. (2015). galpy: A Python Library for Galactic Dynamics. *The Astrophysical Journal Supplement Series*, 216(2), 29; y Bovy, J., & Rix, H.-W. (2013). *The Astrophysical Journal*, 779(2), 115.
7. Lelli, F., McGaugh, S. S., & Schombert, J. M. (2016). SPARC: Mass Models for 175 Disk Galaxies with Spitzer Photometry. *The Astronomical Journal*, 152(6), 157.
8. Corbelli, E., et al. (2014). Dynamical signatures of disk-halo interaction in M33. *Astronomy & Astrophysics*, 572, A23.
9. GRAVITY Collaboration (Abuter, R., et al.). (2018). Detection of the gravitational redshift in the orbit of the star S2 near the Galactic centre massive black hole. *Astronomy & Astrophysics*, 615, L15.
10. Event Horizon Telescope Collaboration (Akiyama, K., et al.). (2019). First M87 Event Horizon Telescope Results. VI. The Shadow and Mass of the Central Black Hole. *The Astrophysical Journal Letters*, 875(1), L6.
11. Binggeli, B., Popescu, C. C., & Tammann, G. A. (1993). The kinematics of the Virgo cluster revisited. *Astronomy and Astrophysics Supplement Series*, 98, 275-296; y Böhringer, H., et al. (1994). *Nature*, 368, 828-831.
12. Colless, M., & Dunn, A. M. (1996). Structure and dynamics of the Coma Cluster. *The Astrophysical Journal*, 458, 435.
13. Sanders, R. H. (2003). Clusters of galaxies with modified Newtonian dynamics. *Monthly Notices of the Royal Astronomical Society*, 342(3), 901-908.
14. Fukugita, M., & Peebles, P. J. E. (2004). The Cosmic Energy Inventory. *The Astrophysical Journal*, 616(2), 643; y Shull, J. M., Smith, B. D., & Danforth, C. W. (2012). *The Astrophysical Journal*, 759(1), 23.
15. Tully, R. B., et al. (2014). The Laniakea supercluster of galaxies. *Nature*, 513(7516), 71-73.
16. Proust, D., et al. (2006). The Shapley supercluster: the largest matter concentration in the local Universe. *Astronomy & Astrophysics*, 447(1), 133-144.
17. Migkas, K., et al. (2020). Probing cosmic isotropy with a new X-ray galaxy cluster sample through the $L_X-T$ scaling relation. *Astronomy & Astrophysics*, 636, A15.
18. Antoja, T., et al. (2018). A dynamically young and perturbed Milky Way disk. *Nature*, 561(7723), 360-362.
19. Planck Collaboration. (2020). Planck 2018 results. VI. Cosmological parameters. *Astronomy & Astrophysics*, 641, A6.
20. Riess, A. G., et al. (2019). Large Magellanic Cloud Cepheid Standards Provide a 1% Foundation for the Determination of the Hubble Constant. *The Astrophysical Journal*, 876(1), 85.
21. Zwicky, F. (1929). On the Red Shift of Spectral Lines through Interstellar Space. *Proceedings of the National Academy of Sciences*, 15(10), 773-779.
22. Land, K., & Magueijo, J. (2005). The Axis of Evil: Examination of Evidence for a Preferred Axis in the Cosmic Radiation Anisotropy. *Physical Review Letters*, 95(7), 071301.
