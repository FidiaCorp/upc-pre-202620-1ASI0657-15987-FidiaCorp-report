<div align="center">

  <img src="https://github.com/FidiaCorp/upc-pre-202620-1ASI0657-15987-FidiaCorp-report/blob/main/Resources/UPC_logo.png?raw_true" alt="Logo-UPC" width="150">

**Universidad Peruana de Ciencias Aplicadas**

**Ingeniería de Software**

**1ASI0657 | Fundamentos de Arquitectura de Software**<br>
**202620**

**NRC: 15987**


**Profesor: Wilder Aurelio Vega Calero**

## Trabajo Final

**Nombre del producto: CrediCasa** 

**Integrantes:**

| Código | Apellidos y nombres |
|---|---|
| [Por completar] | Jonseck Choque, Oliver |
| [Por completar] | Godoy Santillan, Jesus Andres |
| [Por completar] | Pumahualcca Garcia, Diego Rodrigo |
| u202224130 | Ramos Hinostroza, Diego Antonio |
| u202310349 | Rubio Otiz, Luis Sebastián |

<div align="justify">


<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe

| Versión | Fecha | Autor(es) | Descripción de modificación |
|---|---|---|---|
| 1.0 | 03/09/2026 | Diego Antonio Ramos Hinostroza | Creación del documento y estructura base |
| 1.0.0.1 | 03/09/2026 | Luis Sebastián Rubio Ortiz | Modificación de nombre y agregado de código de estudiante |
| 1.0.0.2 | 06/09/2026 | Diego Antonio Ramos Hinostroza | Se añadió todo el contenido del Capitulo I |



<div style="page-break-after: always;"></div>

# Contenido

- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
	- [1.1. Startup Profile](#11-startup-profile)
		- [1.1.1. Descripción de la startup](#111-descripción-de-la-startup)
		- [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
	- [1.2. Solution Profile](#12-solution-profile)
		- [1.2.1. Nombre del producto](#121-nombre-del-producto)
		- [1.2.2. Antecedentes y problemática](#122-antecedentes-y-problemática)
		- [1.2.3. Lean UX Process](#123-lean-ux-process)
			- [1.2.3.1. Lean UX Problem Statement](#1231-lean-ux-problem-statement)
			- [1.2.3.2. Lean UX Assumptions](#1232-lean-ux-assumptions)
			- [1.2.3.3. Lean UX Hypothesis](#1233-lean-ux-hypothesis)
			- [1.2.3.4. Lean UX Canvas](#1234-lean-ux-canvas)

	- [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
	- [2.1. Competidores](#21-competidores)
	- [2.2. Entrevistas](#22-entrevistas)
	- [2.3. NeedFinding](#23-needfinding)
- [Capítulo III: Requirements Elicitation & Analysis](#capítulo-iii-requirements-elicitation--analysis)
	- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
	- [3.2. User Stories](#32-user-stories)
	- [3.3. Impact Map](#33-impact-map)
	- [3.4. Product Backlog](#34-product-backlog)
- [Conclusiones](#conclusiones)
- [Referencias Bibliográficas](#referencias-bibliográficas)
- [Anexos](#anexos)

<div style="page-break-after: always;"></div>

# Student Outcome

<table>
	<thead>
		<tr>
			<th>Criterio</th>
			<th>Acción realizada</th>
			<th>Conclusión</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.</td>
			<td><strong>Jonseck Choque, Oliver:</strong><br> AV1:<br><strong><br>Godoy Santillan, Jesus Andres:</strong><br> AV1:<br><strong><br>Pumahualcca Garcia, Diego Rodrigo:</strong><br> AV1:<br><strong><br>Ramos Hinostroza, Diego Antonio:</strong><br> AV1: Investigué y actualicé de manera autónoma conceptos avanzados de arquitectura empresarial y descomposición por microservicios basados en Domain-Driven Design (DDD). Asimismo, asimilé la normativa técnica y financiera de la SBS relativa a la transparencia en créditos hipotecarios, lo que me permitió traducir reglas de negocio complejas (método francés, conversión de regímenes de capitalización, VAN, TIR y TCEA) en especificaciones directas para el modelado del motor de cálculo y el diseño preliminar de los bounded contexts de la plataforma CrediCasa.<br><strong><br>Rubio Ortiz, Luis Sebastián:</strong><br> AV1:</td>
			<td>AV1:</td>
		</tr>
		<tr>
			<td>Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.</td>
			<td><strong>Jonseck Choque, Oliver:</strong><br> AV1:<br><strong><br>Godoy Santillan, Jesus Andres:</strong><br> AV1:<br><strong><br>Pumahualcca Garcia, Diego Rodrigo::</strong><br> AV1:<br><strong><br>Ramos Hinostroza, Diego Antonio:</strong><br> AV1: Reconocí la importancia de la autoformación continua al enfrentar la brecha entre los requerimientos funcionales del dominio inmobiliario-financiero y la definición de requerimientos de calidad arquitectónicos (ASRs). Comprendí que el rol de arquitecto de software exige investigar activamente estándares emergentes de la industria, metodologías de diseño como Attribute-Driven Design (ADD) y patrones cloud nativos para garantizar soluciones escalables, auditables y con alta mantenibilidad frente a entornos regulatorios dinámicos.<br><strong><br>Rubio Ortiz, Luis Sebastián:</strong><br> AV1:</td>
			<td>AV1:</td>
		</tr>
	</tbody>
</table>

<div style="page-break-after: always;"></div>


## 1.1. Startup Profile

### 1.1.1. Descripción de la startup

**FidiaCorp** es una iniciativa tecnológica concebida y desarrollada por estudiantes de la carrera de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas (UPC). La propuesta se materializa a través de CrediCasa, un ecosistema digital y plataforma FinTech/PropTech orientada a transformar radicalmente el proceso de simulación, estructuración y originación de créditos hipotecarios en el mercado peruano, transitando desde modelos de asesoría financiera tradicionales, lentos y asimétricos hacia un esquema digital, transparente y analíticamente riguroso.

CrediCasa articula una arquitectura empresarial moderna basada en microservicios y servicios en la nube, integrando un motor financiero especializado capaz de computar cronogramas de amortización mediante el método francés vencido ordinario (bajo convención de meses de 30 días o año bancario de 360 días). El sistema soporta operaciones multimoneda (Soles y Dólares), maneja conversión estricta entre tasas de interés efectivas y nominales con períodos variables de capitalización, incorpora períodos de gracia total o parcial, y procesa esquemas de financiamiento estructurado con cuotas balón. Asimismo, automatiza la evaluación de rentabilidad y costo financiero para el prestatario mediante el cálculo del Valor Actual Neto (VAN), la Tasa Interna de Retorno (TIR) desde la óptica del deudor, y la Tasa de Costo Efectivo Anual (TCEA), transparentando primas de seguro de desgravamen y seguros multirriesgo del bien inmueble conforme a las disposiciones normativas de la Superintendencia de Banca, Seguros y AFP (SBS).

**Misión:** Transformar la experiencia de adquisición de vivienda y estructuración de crédito hipotecario en el Perú mediante el desarrollo de software confiable, auditable y escalable, eliminando la asimetría informativa financiera y optimizando la toma de decisiones económicas tanto para familias compradoras como para entidades promotoras e intermediarias.

**Visión:** Consolidarnos como la plataforma PropTech/FinTech de referencia a nivel nacional y regional en la simulación, evaluación y orquestación arquitectónica de créditos hipotecarios e inversión inmobiliaria, promoviendo la bancarización transparente, la eficiencia operativa en el sector de la construcción y el acceso universal a instrumentos financieros justos y comprensibles.

### 1.1.2. Perfiles de integrantes del equipo

<table>
	<thead>
		<tr>
			<th>Integrante</th>
			<th>Perfil</th>
			<th>Imagen</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Jonseck Choque, Oliver</td>
			<td>[Por completar]</td>
			<td>[Por completar]</td>
		</tr>
		<tr>
			<td>Godoy Santillan, Jesus Andres</td>
			<td>[Por completar]</td>
			<td>[Por completar]</td>
		</tr>
		<tr>
			<td>Pumahualcca Garcia, Diego Rodrigo</td>
			<td>[Por completar]</td>
			<td>[Por completar]</td>
		</tr>
		<tr>
			<td>Ramos Hinostroza, Diego Antonio - u202224130</td>
			<td>Estudiante de sexto ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Cuenta con dominio en diseño de arquitectura de software, desarrollo backend y consumo/integración de servicios web bajo estándares de la industria. Posee experiencia técnica en la construcción e integración de APIs REST utilizando Java (Spring Boot), C# y Python, así como en el diseño y modelado de bases de datos relacionales y NoSQL.</td>
			<td>[Por completar]</td>
		</tr>
		<tr>
			<td>Rubio Ortiz, Luis Sebastián - u202310349</td>
			<td>[Por completar]</td>
			<td>[Por completar]</td>
		</tr>
	</tbody>
</table>

## 1.2. Solution Profile

### 1.2.1. Nombre del producto

**CrediCasa** es la denominación comercial y técnica de nuestra plataforma digital. El nombre surge de la integración conceptual de dos pilares esenciales: el prefijo "Credi-", que remite tanto al concepto de crédito hipotecario como a su raíz etimológica latina credere (creer, confiar y dar fe), y el sustantivo "-Casa", que simboliza el anhelo patrimonial y habitacional central de las familias peruanas.

### 1.2.2. Antecedentes y problemática

El sector inmobiliario peruano experimenta una paradoja estructural: mientras la demanda habitacional supera las 1.8 millones de unidades a nivel nacional debido al déficit habitacional cualitativo y cuantitativo registrado por el Ministerio de Vivienda, Construcción y Saneamiento (MVCS, 2024), la tasa de colocación de créditos hipotecarios enfrenta severas barreras de entrada motivadas por la complejidad financiera y la desconfianza del usuario frente al sistema bancario.

De acuerdo con reportes de la Superintendencia de Banca, Seguros y AFP (SBS, 2025), más del 65% de los solicitantes de crédito para vivienda declaran incomprensión de las hojas de liquidación y los factores que integran la Tasa de Costo Efectivo Anual (TCEA), confundiendo frecuentemente la Tasa Efectiva Anual (TEA) contractual con el desembolso total periódico. Esta opacidad se agudiza por la incorporación de conceptos como primas de seguro de desgravamen (con tasas fijas o porcentuales sobre saldo insoluto), pólizas multirriesgo obligatorias, comisiones de estructuración y esquemas de amortización con cuotas dobles o cuotas balón diferidas.

Asimismo, las empresas inmobiliarias y promotoras pierden entre un 25% y un 35% de prospectos calificados durante el proceso de preventa debido a los extensos tiempos de respuesta y la falta de herramientas inmediatas de pre-calificación que permitan modelar en tiempo real distintos escenarios financieros adaptados al perfil del comprador (financiamiento en Soles o Dólares, tasas fijas o mixtas, y períodos de gracia total o parcial).

Para estructurar formalmente el análisis de la problemática, se aplica la técnica 5 W's y 2 H's:

| Pregunta | Respuesta |
|---|---|
| **What (qué)** | La existencia de asimetría informativa, falta de transparencia y lentitud en la simulación, estructuración y evaluación matemática de créditos hipotecarios en el Perú, impidiendo que el comprador visualice el costo real del financiamiento (TCEA, VAN, TIR) y que la empresa inmobiliaria concrete colocaciones de forma ágil y fidedigna. |
| **Why (por qué)** | Debido a la dispersión de la información bancaria, la complejidad de las fórmulas financieras aplicadas (conversiones entre tasas nominales/efectivas con capitalizaciones no estándar, cálculo francés de cuota constante con gracia e inclusión de seguros) y la dependencia de simuladores web bancarios cerrados, desactualizados y con omisión sistemática de gastos colaterales obligatorios. |
| **Who (quién)** | Afecta en primera instancia a las familias y profesionales peruanos con intención de compra de su primer inmueble (deudores), y en segunda instancia a las empresas promotoras, constructoras e inmobiliarias que necesitan cerrar compromisos de venta sustentados en la viabilidad crediticia de sus clientes. |
| **When (cuándo)** | Se suscita durante la etapa crítica de preventa y evaluación crediticia inicial, momento en el cual el comprador explora opciones de inmuebles y requiere definir su estructura de financiamiento a mediano o largo plazo (de 5 a 25 años) sin contar con certezas sobre su carga financiera mensual futura. |
| **Where (dónde)** | El entorno de estudio se focaliza en el mercado inmobiliario de Lima Metropolitana, zona que concentra más del 55% de los créditos hipotecarios emitidos en el Perú (CAPECO, 2025), con visión de escalabilidad e integración a nivel nacional en las principales urbes del país. |
| **How (cómo)** | A través de una plataforma web y móvil empresarial basada en microservicios que ofrece un motor de cálculo financiero auditable. Este motor modela el plan de pagos por el método francés vencido ordinario a 30 días, calcula indicadores financieros clave de decisión (VAN y TIR del deudor, TCEA oficial), evalúa opciones de configuración multimoneda, regímenes de tasa y períodos de gracia, y provee comparativas directas frente a benchmarks del sistema financiero autorizado. |
| **How much (cuánto)** | A nivel de mercado, la caída de operaciones de preventa por falta de financiamiento viable representa pérdidas comerciales anuales estimadas en más de US$ 120 millones para el sector constructor limeño. A nivel técnico, el desarrollo e implementación de la arquitectura cloud de CrediCasa proyecta un presupuesto de inversión inicial acotado entre S/. 35,000 y S/. 65,000 para su fase de MVP y despliegue sobre infraestructura serverless y contenedores de alta disponibilidad. |

### 1.2.3. Lean UX Process

#### 1.2.3.1. Lean UX Problem Statement

**Problem Statement 1: Segmento Demandante - Comprador de Vivienda**

El acceso a la primera vivienda en el Perú representa una de las decisiones patrimoniales más trascendentales de un individuo o grupo familiar; no obstante, el proceso de obtención de un crédito hipotecario está marcado por la opacidad en el cálculo de las cuotas y la desinformación en torno al costo total del crédito. Los postulantes a financiamiento habitacional se enfrentan a cronogramas bancarios difíciles de auditar, donde la Tasa de Costo Efectivo Anual (TCEA) real no es transparente desde el inicio y los períodos de gracia (totales o parciales) o cuotas extraordinarias son presentados sin desglosar su impacto matemático en los intereses acumulados.

*¿Cómo podemos diseñar una solución digital intuitiva y rigurosa que permita a los futuros propietarios simular, personalizar y comprender con precisión matemática y transparencia legal el plan de amortización, el costo efectivo real y la viabilidad económica de su crédito hipotecario antes de contraer un compromiso crediticio a largo plazo?*

**Problem Statement 2: Segmento Oferente - Empresas Inmobiliarias y Asesores**

Las empresas promotoras e inmobiliarias peruanas enfrentan una alta tasa de deserción de compradores potenciales durante la etapa de cotización debido a la incapacidad de calcular de forma instantánea y fidedigna planes de financiamiento estructurado adaptados a la capacidad económica real de cada cliente. La necesidad de derivar al comprador a múltiples agentes bancarios para cotizaciones manuales genera fricción operativa, tiempos muertos de hasta 20 días laborales y pérdida irreversible de reservas de compra.

*¿Cómo podemos proveer a las inmobiliarias y gestores comerciales de un sistema centralizado de simulación y evaluación hipotecaria multientidad que acelere la pre-calificación crediticia, optimice el cierre de ventas y genere cronogramas normativos en cuestión de minutos?*

---

#### 1.2.3.2. Lean UX Assumptions

##### Business Assumptions

1. Lograr una tasa de adopción de más de 1,500 simulaciones mensuales durante los primeros 4 meses de operaciones en Lima Metropolitana.
2. Alcanzar alianzas con al menos 10 empresas promotoras inmobiliarias para integrar el motor de simulación de CrediCasa en sus salas de venta.
3. Monetizar la plataforma a través de un modelo SaaS B2B para inmobiliarias (licenciamiento por sala de ventas y gestión de leads pre-calificados) y comisiones de referenciación con entidades financieras aliadas.
4. Posicionar la marca FidiaCorp como líder tecnológico en soluciones FinTech y PropTech en el ámbito académico y profesional.

##### User Assumptions

**¿Quién es el usuario?:** Individuos y familias con capacidad de ahorro y estabilidad laboral que buscan adquirir una vivienda mediante crédito hipotecario (B2C), así como asesores comerciales y gestores de venta de proyectos inmobiliarios (B2B).

**¿Dónde encaja el producto en su rutina?:** Como una plataforma de autoservicio y asesoría comercial accesible desde dispositivos móviles y navegadores web durante la fase de búsqueda de inmuebles, cotización y negociación de condiciones de crédito.

**¿Cuándo y cómo se utiliza?:** Al momento de evaluar un proyecto inmobiliario específico, cotizar cuotas iniciales y plazos, comparar alternativas de tasa (efectiva vs. nominal con distintas capitalizaciones) o definir la pertinencia de solicitar meses de gracia.

**¿Qué problemas resuelve la solución?:** Elimina la opacidad financiera, evita sobrecostos imprevistos derivados de primas y comisiones ocultas, y automatiza la generación de cronogramas de pagos bajo el método francés vencido con balance a saldo cero verificado matemáticamente.

**¿Qué características son prioritarias?:** 
- Gestión de Identidades
- Registro de propietario e inmobiliario
- Consulta de entidades bancarias
- Cálculo de métricas de decisión de inversión
- Generación de cronogramas y ayudas contextuales


**¿Cómo debe comportarse la plataforma?:** La interfaz debe ser limpia, libre de tecnicismos bancarios confusos, con visualizaciones gráficas del flujo de amortización vs. intereses, y con tiempos de respuesta sub-segundo en el cálculo dinámico de cuotas.

#### 1.2.3.3. Lean UX Hypothesis

1. **H1:** Creemos que proporcionar a los compradores de vivienda una herramienta interactiva de simulación en tiempo real que transparente la TCEA y el cronograma de amortización francés aumentará su confianza y determinación de compra. Sabremos que hemos tenido éxito cuando alcancemos una tasa de conversión superior al 25% entre los usuarios que configuran una simulación completa y aquellos que solicitan la formalización de su expediente de crédito.
2. **H2:** Creemos que al permitir a los promotores inmobiliarios estructurar planes de financiamiento con tasas nominales/efectivas, cuotas dobles y períodos de gracia total y parcial desde una sola plataforma se reducirán drásticamente los tiempos de cotización. Sabremos que hemos tenido éxito cuando el tiempo de atención y emisión de una propuesta de financiamiento en salas de venta disminuya de 45 minutos a menos de 5 minutos, validado en encuestas de satisfacción técnica de nuestros socios B2B.
3. **H3:** Creemos que incorporar los indicadores VAN y TIR evaluados estrictamente desde la óptica del deudor permitirá a los usuarios comparar objetivamente las ofertas entre entidades financieras. Sabremos que esto es cierto cuando el 70% de los usuarios recurrentes utilicen la función de comparación multientidad antes de definir la entidad financiera para su solicitud formal.

#### 1.2.3.4. Lean UX Canvas

<table>
    <tr>
        <td valign="top">
            <div align="center"><br><b>Business Problem</b></div><br>
            <p>El mercado de financiamiento hipotecario en Lima Metropolitana presenta una severa asimetría informativa y opacidad financiera, donde más del 65% de los solicitantes de crédito no comprende la composición real de la TCEA, seguros obligatorios ni el impacto de los períodos de gracia. A su vez, las empresas inmobiliarias experimentan pérdidas operativas y caídas de reservas de entre el 25% y el 35% debido a la lentitud en la evaluación crediticia y a la falta de herramientas ágiles de simulación en salas de venta.<br><br>¿Cómo podríamos facilitar un ecosistema digital confiable y auditable que automatice la simulación financiera hipotecaria multientidad, acelerando la pre-calificación comercial y transparentando el costo efectivo real (TCEA, VAN y TIR) para el deudor?</p><br>
        </td>
        <td rowspan="2" valign="top">
            <div align="center"><br><b>Solutions</b></div><br>
            <ul>
                <li>Desarrollar un motor financiero cloud nativo que compute cronogramas de pago bajo el método francés ordinario vencido (meses de 30 días), soportando cuotas balón y períodos de gracia total o parcial.</li><br>
                <li>Implementar un módulo de configuración financiera flexible para operaciones multimoneda (PEN y USD) con conversión de tasas efectivas y nominales según su capitalización.</li><br>
                <li>Construir un dashboard interactivo de simulación para compradores que desglose en tiempo real cuotas, primas de seguros y métricas de rentabilidad (VAN y TIR desde la óptica del deudor).</li><br>
                <li>Integrar un módulo de gestión de ventas para promotoras e inmobiliarias que permita generar cotizaciones formales, exportar cronogramas normativos en PDF/Excel y contrastar ofertas frente a benchmarks de la SBS.</li><br>
            </ul><br>
        </td>
        <td valign="top">
            <div align="center"><br><b>Business Outcomes</b></div><br>
            <ul>
                <li>Alcanzar un volumen superior a las 1,500 simulaciones mensuales completadas durante los primeros 4 meses de despliegue en Lima Metropolitana.</li><br>
                <li>Concretar alianzas estratégicas con al menos 10 empresas promotoras e inmobiliarias para integrar CrediCasa en sus salas de venta en el primer semestre.</li><br>
                <li>Reducir el tiempo promedio de estructuración y emisión de cotizaciones hipotecarias en sala de ventas de 45 minutos a menos de 5 minutos.</li><br>
                <li>Lograr una tasa de conversión igual o mayor al 25% entre usuarios que configuran una simulación completa y aquellos que inician su pre-calificación formal.</li>
            </ul><br>
        </td>
    </tr>
    <tr>
        <td valign="top">
            <div align="center"><br><b>Users</b></div><br>
            <ul>
                <li><b>Empresas inmobiliarias y promotores de vivienda en Lima (B2B):</b> Jefes de venta y asesores comerciales que necesitan pre-calificar clientes y emitir cotizaciones financieras fidedignas al instante.</li><br>
                <li><b>Compradores de vivienda y deudores hipotecarios (B2C):</b> Familias y profesionales bancarizados que buscan certidumbre sobre el desembolso mensual, tasas reales y costos colaterales de su financiamiento patrimonial.</li>
            </ul><br>
        </td>
        <td valign="top">
            <div align="center"><br><b>User Outcomes & Benefits</b></div><br>
            <ul>
                <li><b>Inmobiliarias:</b> Reducción de la tasa de cancelación de reservas, cierre ágil de preventas y asesoría comercial respaldada en cálculos financieros exactos y normativos.</li><br>
                <li><b>Compradores:</b> Claridad absoluta del costo total de la deuda (TCEA), mitigación del sobreendeudamiento y visualización de la evolución real del saldo insoluto con balances a cero.</li><br>
                <li><b>Ambos:</b> Eliminación de fricciones comerciales y asimetrías de información mediante cotizaciones estandarizadas y verificables frente al sistema bancario.</li>
            </ul><br>
        </td>
    </tr>
    <tr>
        <td valign="top">
            <div align="center"><br><b>Hypotheses</b></div><br>
            <p>Creemos que la plataforma CrediCasa incrementará la colocación de viviendas y la certidumbre del deudor al transparentar el cronograma francés, la TCEA real y los indicadores VAN/TIR mediante un motor analítico en tiempo real.<br><br>Sabremos que esto es cierto cuando al menos el 70% de los usuarios recurrentes comparen ofertas financieras en la plataforma y se registre una conversión superior al 25% de simulaciones hacia solicitudes crediticias formalizadas en las salas de venta aliadas.</p><br>
        </td>
        <td valign="top">
            <div align="center"><br><b>What's the most important thing we need to learn first?</b></div><br>
            <ul>
                <li>Validar si los compradores comprenden la diferencia e impacto económico entre una tasa nominal/efectiva y la TCEA con seguros de desgravamen incluidos.</li><br>
                <li>Comprobar si los asesores inmobiliarios están dispuestos a sustituir sus plantillas locales en Excel por una solución web integrada para atender al cliente en sala.</li><br>
                <li>Determinar qué indicadores de decisión (cuota mensual, TCEA o VAN/TIR) resultan más determinantes para que el usuario elija una entidad financiera.</li>
            </ul><br>
        </td>
        <td valign="top">
            <div align="center"><br><b>What's the least amount of work we need to do to learn the next most important thing?</b></div><br>
            <ul>
                <li>Desplegar un MVP funcional del simulador con el motor de cálculo francés, opciones de gracia total/parcial y desglose de TCEA conforme a la SBS.</li><br>
                <li>Realizar pruebas piloto de usabilidad y cotización en vivo con 10 compradores potenciales y 5 asesores de proyectos inmobiliarios en Lima.</li><br>
                <li>Auditar la concordancia matemática entre los cronogramas generados por la plataforma y liquidaciones bancarias reales para garantizar error cero.</li>
            </ul><br>
        </td>
    </tr>
</table>


## 1.3. Segmentos objetivo

La propuesta de valor de FidiaCorp mediante el ecosistema CrediCasa se estructura bajo un modelo de mercado bilateral (two-sided market) dentro del sector inmobiliario y financiero de Lima Metropolitana. Este modelo articula a dos segmentos interdependientes cuyas operaciones son armonizadas mediante servicios cloud nativos y aplicaciones digitales:

### Segmento 1: Empresas Inmobiliarias y Promotoras de Vivienda

#### Definición y Perfil Demográfico
Este segmento comprende a empresas medianas y grandes dedicadas al desarrollo inmobiliario, construcción y comercialización de proyectos de vivienda multifamiliar en distritos de Lima Top y Lima Moderna (Miraflores, San Isidro, Surco, Jesús María, Magdalena, Lince y San Miguel). El perfil del usuario operativo corresponde a jefes de ventas, ejecutivos comerciales y asesores inmobiliarios de entre 26 y 52 años, orientados al cumplimiento de metas de colocación mensual, habituados al uso de CRMs de ventas pero limitados tecnológicamente al manejo de hojas de cálculo aisladas para confeccionar cotizaciones crediticias preliminares.

#### Sustento Estadístico y Problemática del Dominio
El mercado de vivienda nueva en Lima Metropolitana se encuentra impulsado fundamentalmente por el financiamiento bancario. Según el último informe económico de la Cámara Peruana de la Construcción (CAPECO, 2025), el 82.4% de las adquisiciones de vivienda residencial en Lima se efectúan a través de un crédito hipotecario (convencional o mediante programas del Fondo MIVIVIENDA). No obstante, los desarrolladores inmobiliarios reportan pérdidas operativas de entre el 20% y el 30% en sus salas de venta debido a la ineficiencia del embudo de conversión crediticia:

* El 40% de las intenciones de reserva se cancela durante las primeras 3 semanas por falta de calificación crediticia oportuna del cliente.
* Los asesores comerciales carecen de herramientas para simular estructuras complejas requeridas por el cliente (como financiamientos con períodos de gracia o amortización extraordinaria) en el momento exacto de la visita, perdiendo el impulso de compra.
* Existe desconexión entre la lista de precios y cotizaciones de la promotora y las políticas de evaluación de las entidades financieras de crédito hipotecario.

#### Articulación con la Solución CrediCasa
CrediCasa proporciona a este segmento un módulo especializado de gestión comercial que permite a los asesores inmobiliarios simular planes de crédito personalizados en presencia del cliente en menos de tres minutos. Al estar configurado con parámetros financieros vigentes (normativa SBS, tipos de tasa, seguros obligatorios y opciones de gracia total/parcial), el asesor emite cotizaciones verificables con cálculo de TCEA y cuota final exacta, permitiendo formalizar pre-calificaciones y reservas comerciales de manera inmediata y reduciendo la tasa de deserción en preventa.

**Fuente de referencia:**  
- Cámara Peruana de la Construcción - CAPECO. (2025). 30° Informe del Mercado de Edificaciones Urbanas en Lima Metropolitana y Callao. Dirección de Estudios Económicos de CAPECO.

---

### Segmento 2: Compradores de Inmuebles Residenciales y Deudores Hipotecarios

#### Definición y Perfil Demográfico
Este segmento está constituido por hombres y mujeres de 25 a 48 años de edad, pertenecientes a los niveles socioeconómicos A, B y C de Lima Metropolitana. Se trata de profesionales dependientes o independientes con ingresos mensuales formales demostrables superiores a los S/. 3,500 (individual o mancomunado), que se encuentran en la búsqueda activa de adquisición de su primer departamento o casa para vivienda familiar. Poseen alta bancarización, mantienen cuentas de ahorro o tarjetas de crédito y utilizan de forma cotidiana aplicaciones móviles bancarias, canales digitales y plataformas web.

#### Sustento Estadístico y Problemática del Dominio
La adquisición de un inmueble representa el pasivo financiero más prolongado y demandante para una persona o núcleo familiar (plazos promedio de 15 a 25 años). Pese a contar con educación superior o técnica, el comprador promedio presenta importantes vacíos de educación financiera en materia crediticia. De acuerdo con estudios del Instituto Peruano de Economía (IPE, 2024) y la SBS (2025):

* El 73% de los postulantes a créditos para vivienda no sabe distinguir la diferencia operativa y económica entre una Tasa Efectiva Anual (TEA) y una Tasa de Costo Efectivo Anual (TCEA).
* El 58% desconoce el impacto del seguro de desgravamen y los seguros contra todo riesgo de la infraestructura en el monto final de su cuota mensual.
* Un 62% no cuenta con capacidad para evaluar si un período de gracia parcial o total resulta financieramente conveniente a largo plazo, o si representa una capitalización onerosa de intereses sobre el saldo adeudado.
* Existe una marcada frustración por la discrepancia sistemática entre los simuladores bancarios genéricos de internet y la hoja de liquidación final entregada por los funcionarios bancarios al momento del cierre contractual.

#### Articulación con la Solución CrediCasa
CrediCasa entrega al comprador de vivienda una plataforma transparente, auditable e interactiva. El usuario no solo simula su cuota bajo el método francés tradicional en soles o dólares, sino que comprende la arquitectura de su deuda: visualiza la evolución del saldo insoluto, experimenta el efecto de capitalizaciones de tasas nominales a efectivas, proyecta periodos de gracia y analiza de manera comprensible el Valor Actual Neto (VAN) y la Tasa Interna de Retorno (TIR) de su financiamiento desde su propia perspectiva como deudor. Adicionalmente, cuenta con tooltips y asistentes contextuales en cada campo financiero, mitigando la brecha de conocimiento y empoderando al ciudadano en la negociación de su crédito hipotecario.

**Fuente de referencia:**  
- Instituto Peruano de Economía - IPE. (2024). Inclusión y Educación Financiera en el Perú: Desafíos en el Acceso al Crédito Hipotecario. Serie de Estudios Económicos, N° 18.

- Superintendencia de Banca, Seguros y Administradoras Privadas de Fondos de Pensiones - SBS. (2025). Informe de Transparencia y Conducta de Mercado del Sistema Financiero Peruano. Departamento de Supervisión de Conducta de Mercado, SBS.

---

<div style="page-break-after: always;"></div>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

Analicen competidores directos e indirectos y definan la posición diferenciadora de CrediCasa.

| Competidor | Perfil | Fortalezas | Debilidades | Oportunidad para CrediCasa |
|---|---|---|---|---|
| [Por completar] | [Por completar] | [Por completar] | [Por completar] | [Por completar] |

### 2.1.1. Estrategias frente a los competidores

[Por completar]

Definan objetivos, participantes, criterios de selección, preguntas y método de registro para cada segmento.

| 1 | [Por completar] | [Por completar] | [Enlace o imagen] |

### 2.2.3. Análisis de entrevistas

#### Hallazgos del segmento 1

[Por completar]

#### Hallazgos del segmento 2

[Por completar]

#### Síntesis cruzada

[Por completar]

## 2.3. Needfinding

### 2.3.1. User Personas

#### Persona 1: [Nombre]

[Descripción, objetivos, frustraciones, necesidades y cita representativa.]

<!-- Inserten la ficha visual de la persona. -->

#### Persona 2: [Nombre]

[Descripción, objetivos, frustraciones, necesidades y cita representativa.]

### 2.3.2. User Task Matrix

| Tarea | Persona 1: frecuencia | Persona 1: importancia | Persona 2: frecuencia | Persona 2: importancia |
|---|---|---|---|---|
| [Por completar] | [Por completar] | [Por completar] | [Por completar] | [Por completar] |

### 2.3.3. Empathy Maps

[Incluyan los mapas de empatía y una breve interpretación de cada uno.]

### 2.3.4. As-Is Scenario Mapping

[Describan la experiencia actual de cada segmento, sus puntos de dolor y oportunidades.]

<div style="page-break-after: always;"></div>

# Capítulo III: Requirements Elicitation & Analysis

## 3.1. To-Be Scenario Mapping

[Describan la experiencia propuesta con CrediCasa para cada segmento.]

## 3.2. User Stories

| ID | Epic | User Story | Criterios de aceptación | Prioridad |
|---|---|---|---|---|
| US01 | [Por completar] | Como [usuario], quiero [acción], para [beneficio]. | Given / When / Then | Must |

## 3.3. Impact Map

[Incluyan el Impact Map y expliquen la relación entre Business Goals, actores, impactos y entregables.]

| Business Goal | Actor | Impacto | Entregable | User Stories |
|---|---|---|---|---|
| BG-01 | [Por completar] | [Por completar] | [Por completar] | [Por completar] |

## 3.4. Product Backlog

Expliquen el método de priorización utilizado y documenten el estado de cada User Story.

| Orden | ID | User Story | Prioridad MoSCoW | Estado | Sprint |
|---|---|---|---|---|---|
| 1 | US01 | [Por completar] | Must | Todo | [Por completar] |

<div style="page-break-after: always;"></div>

# Conclusiones

1. [Conclusión sobre el problema y la solución]
2. [Conclusión sobre la arquitectura]
3. [Conclusión sobre la implementación y validación]

# Recomendaciones

1. [Trabajo futuro o mejora prioritaria]
2. [Por completar]

# Bibliografía

- Cámara Peruana de la Construcción. (2025). 30° Informe del mercado de edificaciones urbanas en Lima Metropolitana y Callao. Dirección de Estudios Económicos de CAPECO. https://capeco.org

- Instituto Peruano de Economía. (2024). Inclusión y educación financiera en el Perú: Desafíos en el acceso al crédito hipotecario (Serie de Estudios Económicos N° 18). Instituto Peruano de Economía. https://www.ipe.org.pe

- Ministerio de Vivienda, Construcción y Saneamiento. (2024). Plan nacional de vivienda y urbanismo: Diagnóstico del déficit habitacional y financiamiento residencial en el Perú. Plataforma Digital Única del Estado Peruano. https://www.gob.pe/vivienda

- Superintendencia de Banca, Seguros y Administradoras Privadas de Fondos de Pensiones. (2025). Informe de transparencia y conducta de mercado del sistema financiero peruano. Superintendencia de Banca, Seguros y AFP. https://www.sbs.gob.pe

# Anexos

## Links

| Descripción | Enlace |
|---|---|
| Repositorio del Reporte | [Abrir repositorio](https://github.com/FidiaCorp/upc-pre-202620-1ASI0657-15987-FidiaCorp-report) |
| Tablero del Product Backlog | [Por completar] |
| Evidencias de entrevistas | [Por completar] |
| Prototipo o diseño UX/UI | [Por completar] |