EDA ESTADISTICO DEL PBI EN AMÉRICA LATINA (2000–2024)

✅Objetivo del proyecto
Ej: “Analizar la evolución del PBI latinoamericano 2000–2024 y explorar patrones mediante EDA, correlación, PCA y clustering.”

✅ Metodología
Enumerar:
limpieza de datos
análisis estadístico
correlación
reducción de dimensionalidad (PCA)
clustering

✅ Resultados clave
Incluye:
que países tienen patrones similares
la interpretación de clusters
qué aprendizaje deja el análisis


<img width="1178" height="722" alt="image" src="https://github.com/user-attachments/assets/af494261-20ab-4e2b-b5ae-258cdf85d4ac" />



•	Cobertura` temporal: 25 años (2000–2024)
•	Cobertura geográfica: 17 países de América Latina
•	Unidad: PBI nominal (miles de millones de USD)
•	Naturaleza de la data: Serie temporal macroeconómica, altamente asimétrica y dominada por economías grandes.

Análisis descriptivo global (región completa)
🔹 Tendencia central

El PBI promedio regional crece de forma clara:
USD 123 mil millones en 2000
USD 382 mil millones en 2024
Esto sugiere crecimiento agregado, pero no homogéneo.

Conclusión clave:
El crecimiento regional está fuertemente sesgado por Brasil y México.

Dispersión y desigualdad económica
•	La desviación estándar aumenta fuertemente con el tiempo.
•	Esto indica que:
•	Los países grandes crecen más rápido en términos absolutos.
•	La brecha económica regional se amplía, no se reduce.

Insight estructural:
No hay convergencia regional → hay divergencia económica.

Asimetría (skewness implícita)
•	Mediana << Media en casi todos los años.
•	La mayoría de países se concentra en valores bajos.
•	Un pequeño grupo empuja el promedio hacia arriba.

América Latina tiene una estructura tipo “cola larga”:
•	2 gigantes (Brasil, México)
•	3 medianos (Argentina, Colombia, Chile)
•	12 economías pequeñas

Clasificación estructural por tamaño económico
Economías grandes
Brasil, México
Representan una porción dominante del PBI regional.
Alta volatilidad post-2013.

Sensibles a:
•	Commodities
•	Ciclos financieros globales
•	Política interna

Brasil muestra el ciclo más pronunciado:

•	Auge 2003–2011
•	Estancamiento 2014–2019
•	Choque fuerte en 2020
•	Recuperación parcial posterior

Economías medianas
•	Argentina, Colombia, Chile, Perú
•	Crecimiento fuerte 2003–2013

Choque externo común:
•	Crisis 2009
•	Fin del súper ciclo de commodities (2014–2016)
•	COVID-19 (2020)

Argentina es un outlier:
•	Alta volatilidad
•	Colapsos bruscos (2002, 2018–2020)
•	Crecimiento no sostenido

Perú y Colombia:
•	Trayectorias más estables
•	Tendencia creciente de largo plazo
•	Menor volatilidad relativa

Economías pequeñas
•	Centroamérica + Bolivia, Paraguay, Uruguay
•	Crecimiento más estable
•	Menor amplitud cíclica
•	Menor exposición a shocks financieros globales

Patrón interesante:
Economías pequeñas crecen lento pero con menos colapsos.
Análisis temporal por grandes ciclos
Ciclo 2000–2002: Crisis inicial

<img width="1028" height="632" alt="image" src="https://github.com/user-attachments/assets/90387c62-c517-4f00-9062-f02c8f3d50ca" />


Impacto fuerte en:
•	Argentina (crisis 2001–2002)
•	Uruguay
•	Brasil y México resisten mejor.

Ciclo 2003–2011: Boom de commodities
•	Crecimiento generalizado en TODA la región.
•	Brasil, Chile, Perú y Colombia se benefician enormemente.
•	Reducción de pobreza (contexto histórico).
Este es el mejor período macroeconómico regional.

Ciclo 2012–2019: Estancamiento
Caída o lateralización del PBI en muchos países.
Fin del impulso externo.
Problemas estructurales internos emergen.

América Latina entra en una “década perdida light”.
2020: Shock COVID
•	Caída sincronizada en casi todos los países.
•	Brasil, México, Argentina y Chile caen fuerte.
•	Centroamérica resiste relativamente mejor.

Alta correlación entre países → shock global puro.
2021–2024: Recuperación desigual
•	México y Brasil se recuperan con fuerza.
•	Colombia y Perú con recuperación sólida.
•	Argentina se recupera, pero sin consolidación.
•	Economías pequeñas continúan crecimiento gradual.

Análisis de volatilidad (EDA avanzado)
Países más volátiles
•	Argentina
•	Brasil
•	Chile (en menor medida)

Países más estables
•	Guatemala
•	Honduras
•	Nicaragua
•	Panamá

<img width="1111" height="627" alt="image" src="https://github.com/user-attachments/assets/29ed539e-344e-48dc-88ff-2f4da266deb3" />


Crecimiento acumulado (2000–2024)
Mayor crecimiento relativo
•	Perú
•	Panamá
•	República Dominicana
•	Colombia

Menor crecimiento relativo
•	Argentina (por crisis recurrentes)
•	Uruguay (crecimiento más lento)

Economías medianas bien gestionadas superan a gigantes inestables.
 Correlación implícita regional
•	Aunque no calculamos la matriz explícita, visualmente se observa:
•	Alta correlación durante crisis globales (2009, 2020)
•	Menor correlación en períodos normales
América Latina reacciona unida a shocks externos, pero diverge en recuperación.

Conclusiones EDA (alto nivel)
Conclusiones estructurales
•	No hay convergencia económica regional
•	El crecimiento depende de:
•	Commodities
•	Contexto externo
•	Las crisis son sincronizadas; las recuperaciones no
•	Economías medianas bien manejadas tienen mejor desempeño relativo
•	La volatilidad es un rasgo central del PBI latinoamericano

<img width="1093" height="628" alt="image" src="https://github.com/user-attachments/assets/4f588f2b-867c-4895-ba2a-af3a14c7a6a2" />




Alta sincronización regional (correlaciones muy elevadas)


<img width="997" height="919" alt="image" src="https://github.com/user-attachments/assets/79b9f585-aa1c-477c-bf7e-747846c0402b" />


La mayoría de países tiene correlaciones > 0.85
Esto indica que las trayectorias del PBI latinoamericano se mueven juntas en el tiempo.
Interpretación económica
•	Alta dependencia de:
o	Ciclo económico global
o	Precios de commodities
o	Flujos financieros internacionales
•	América Latina no crece de forma autónoma, sino sincronizada externamente
📌 No implica convergencia en nivel, sino co-movimiento temporal.


Sub-bloque muy fuerte: economías medianas–pequeñas
Países como:
•	Perú
•	Ecuador
•	Panamá
•	Costa Rica
•	Rep. Dominicana
•	Guatemala
•	Nicaragua
•	Honduras
•	El Salvador
presentan correlaciones cercanas a 0.97–0.99 entre sí.

Conclusión clave
Estas economías comparten un patrón de crecimiento casi idéntico.

Lectura estructural
•	Economías abiertas
•	Dependientes de:
o	Exportaciones primarias
o	Remesas
o	Turismo
•	Reaccionan igual ante shocks externos (2009, 2020)

Brasil: el país más “independiente” del sistema
Brasil muestra las correlaciones más bajas del cuadro:
•	Con México: ~0.68
•	Con Perú: ~0.64
•	Con Centroamérica: ~0.55–0.60
Conclusión
Brasil sigue su propio ciclo económico.
Razones
•	Mercado interno enorme
•	Política macro más autónoma
•	Menor dependencia relativa de remesas y turismo
Brasil no lidera el ciclo regional, lo acompaña solo parcialmente.

México: puente entre EE.UU. y Latinoamérica
México tiene:
•	Correlación alta con casi todos (>0.9)
•	Pero menor que Centroamérica entre sí
Interpretación
•	México está más vinculado al ciclo de EE.UU.
•	Su economía responde a:
o	Manufactura
o	Comercio internacional
o	Nearshoring
👉 Es un híbrido: latinoamericano por región, norteamericano por ciclo.

Cono Sur andino: alta coherencia interna
Países como:
•	Perú
•	Chile
•	Colombia
•	Ecuador
Tienen correlaciones muy elevadas entre sí (0.90–0.99).

Lectura económica
•	Dependencia común de:
o	Minería
o	Energía
o	China
•	Políticas macro relativamente ortodoxas (hasta cierto punto)
Esto explica por qué suelen agruparse juntos en PCA y clustering.

Centroamérica: casi un solo “bloque económico”
Guatemala, Honduras, El Salvador, Nicaragua:
•	Correlaciones ≈ 0.99
•	Trayectorias casi idénticas

Conclusión contundente
En términos dinámicos, funcionan como una economía regional única.

Causas
•	Remesas
•	Integración comercial
•	Baja diversificación productiva

Argentina: alta correlación, pero con ruido propio
Argentina correlaciona alto (>0.8) pero:
•	Menor estabilidad
•	Mayor volatilidad histórica
Lectura
•	Comparte el ciclo regional
•	Pero lo amplifica por:
o	Crisis recurrentes
o	Cambios de política
Argentina no es independiente, pero sí más inestable.

Implicación metodológica (MUY importante)
Multicolinealidad fuerte
Esta matriz indica:
•	Variables altamente redundantes
•	Usar todas juntas en regresiones → problemas
Justifica plenamente:
•	PCA
•	Clustering
•	Modelos por bloques
Esto valida técnicamente el enfoque que estás usando.

Conclusión macro general (para paper o libro)
América Latina presenta una alta sincronización cíclica, con diferencias en tamaño pero no en dinámica estructural, salvo Brasil y parcialmente México.
O más fuerte aún:
El problema de la región no es crecer distinto, sino crecer juntos… pero poco y dependientes.
