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
| u20251c350 | Godoy Santillan, Jesus Andres |
| u202219266 | Pumahualcca Garcia, Diego Rodrigo |
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
		- [2.1.1. Análisis competitivo](#211-análisis-competitivo)
		- [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
	- [2.2. Entrevistas](#22-entrevistas)
		- [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
		- [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
		- [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
	- [2.3. Needfinding](#23-needfinding)
		- [2.3.1. User Personas](#231-user-personas)
		- [2.3.2. User Task Matrix](#232-user-task-matrix)
		- [2.3.3. User Journey Mapping](#233-user-journey-mapping)
		- [2.3.4. Empathy Mapping](#234-empathy-mapping)
		- [2.3.5. As-Is Scenario Mapping](#235-as-is-scenario-mapping)
	- [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
	- [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
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
			<td><strong>Jonseck Choque, Oliver:</strong><br> AV1:<br><strong><br>Godoy Santillan, Jesus Andres:</strong><br> AV1:<br><strong><br>Pumahualcca Garcia, Diego Rodrigo:</strong><br> AV1:Investigué y actualicé de manera autónoma mis conocimientos en patrones de arquitectura orientados a microservicios y despliegue en la nube (Cloud Computing), evaluando su aplicabilidad específica para el entorno SaaS de CrediCasa. Además, me documenté sobre la integración segura de APIs financieras, lo cual fue clave para estructurar la comunicación entre el simulador de cuotas y el motor de cálculo, garantizando la correcta aplicación del método francés y los lineamientos de la SBS.<br><strong><br>Ramos Hinostroza, Diego Antonio:</strong><br> AV1: Investigué y actualicé de manera autónoma conceptos avanzados de arquitectura empresarial y descomposición por microservicios basados en Domain-Driven Design (DDD). Asimismo, asimilé la normativa técnica y financiera de la SBS relativa a la transparencia en créditos hipotecarios, lo que me permitió traducir reglas de negocio complejas (método francés, conversión de regímenes de capitalización, VAN, TIR y TCEA) en especificaciones directas para el modelado del motor de cálculo y el diseño preliminar de los bounded contexts de la plataforma CrediCasa.<br><strong><br>Rubio Ortiz, Luis Sebastián:</strong><br> AV1:</td>
			<td>AV1:</td>
		</tr>
		<tr>
			<td>Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.</td>
			<td><strong>Jonseck Choque, Oliver:</strong><br> AV1:<br><strong><br>Godoy Santillan, Jesus Andres:</strong><br> AV1:<br><strong><br>Pumahualcca Garcia, Diego Rodrigo::</strong><br> AV1:Comprendí que el desarrollo de soluciones dentro del ecosistema financiero y proptech exige una actualización tecnológica y regulatoria constante. Al enfrentarme a los cálculos de TCEA, VAN y TIR, reconocí que como ingeniero de software debo integrar proactivamente nuevas herramientas de la industria, arquitecturas escalables y estándares de seguridad para asegurar que la plataforma pueda adaptarse rápidamente a futuros cambios en el mercado inmobiliario y las normativas peruanas.<br><strong><br>Ramos Hinostroza, Diego Antonio:</strong><br> AV1: Reconocí la importancia de la autoformación continua al enfrentar la brecha entre los requerimientos funcionales del dominio inmobiliario-financiero y la definición de requerimientos de calidad arquitectónicos (ASRs). Comprendí que el rol de arquitecto de software exige investigar activamente estándares emergentes de la industria, metodologías de diseño como Attribute-Driven Design (ADD) y patrones cloud nativos para garantizar soluciones escalables, auditables y con alta mantenibilidad frente a entornos regulatorios dinámicos.<br><strong><br>Rubio Ortiz, Luis Sebastián:</strong><br> AV1:</td>
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
			<td>Godoy Santillan, Jesus Andres - u20251c350</td>
			<td>Soy Jesús, tengo 22 años, me gusta mucho programar desde pequeño haciendo pequeños proyectos en videojuegos hasta lo último que hice que fue un gran proyecto en un evento online con creadores de contenido, patrocinadores y premios. Actualmente no trabajo formalmente pero ayudo a mi padre y junto a mi hermano haciendo sistemas y programas de una empresa que tiene junto a su amigo relacionado con la agroindustria y con el conocimiento que tengo de tecnología y solución de problemas también asesoró o ayudó a amigos de mi padre que tienen problemas técnicos relacionados con la tecnología ya sea personales o de trabajo.</td>
			<td>[Por completar]</td>
		</tr>
		<tr>
			<td>Pumahualcca Garcia, Diego Rodrigo</td>
			<td>Estudiante de sexto ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Cuento con un conocimiento en el diseño de arquitectura de software y desarrollo backend. En el desarrollo de CrediCasa, mi objetivo principal es utilizar la tecnología para resolver un problema real y social: la falta de transparencia en los créditos hipotecarios.</td>
			<td>[Por completar]</td>
		</tr>
		<tr>
			<td>Ramos Hinostroza, Diego Antonio - u202224130</td>
			<td>Estudiante de sexto ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Cuenta con dominio en diseño de arquitectura de software, desarrollo backend y consumo/integración de servicios web bajo estándares de la industria. Posee experiencia técnica en la construcción e integración de APIs REST utilizando Java (Spring Boot), C# y Python, así como en el diseño y modelado de bases de datos relacionales y NoSQL.</td>
			<td>  <img src="/Resources/Perfil_DiegoRamos.png" alt="Diego Ramos Profile"> </td>
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

Este capítulo desarrolla el análisis de necesidades de CrediCasa, producto de FidiaCorp, a partir de la problemática y las hipótesis del capítulo I. Comprende el análisis competitivo, el diseño de entrevistas y la identificación de necesidades de los usuarios en el proceso de simulación y cotización de créditos hipotecarios.

Se consideran dos segmentos objetivo: **Comprador**, personas que buscan financiar una vivienda en Lima Metropolitana, e **Inmobiliaria/Banca**, asesores inmobiliarios, responsables comerciales y ejecutivos hipotecarios. Dentro del segundo segmento se distinguen responsabilidades: la inmobiliaria prepara propuestas y acompaña la venta; la banca evalúa y decide sobre el otorgamiento del crédito.

**Estado de la investigación:** el análisis competitivo utiliza fuentes públicas consultadas el 10 de septiembre de 2026. Las entrevistas se encuentran pendientes de ejecución; por ello, las necesidades, personas y mapas se presentan como hipótesis de trabajo pendientes de validación. Los porcentajes y tiempos planteados como metas en el capítulo I no se consideran resultados obtenidos.

## 2.1. Competidores

CrediCasa participa en el espacio de simulación, comparación y preparación de propuestas hipotecarias. Se identifican tres alternativas relevantes:

- **Comparabien:** competidor directo en comparación de financiamiento. Su formulario hipotecario permite indicar moneda, valor del inmueble, inicial, plazo e ingresos, y presenta un recorrido de comparación, elección y solicitud. [Fuente: Comparabien](https://comparabien.com.pe/creditos-hipotecarios).
- **BCP:** competidor indirecto mediante la simulación de sus propios productos. Su herramienta permite variar inicial, plazo y tipo de cuota; señala que los resultados son referenciales y que el crédito está sujeto a evaluación. [Fuente: simulador hipotecario BCP](https://www.viabcp.com/creditos/bmo-credito-hipotecario/simulador-credito-hipotecario).
- **BBVA Perú:** competidor indirecto mediante su oferta y simulación hipotecaria. Publica un flujo de estimación y contacto con ejecutivos, así como opciones de cuotas dobles y períodos de gracia según las condiciones del producto. [Fuente: Hipotecario BBVA](https://www.bbva.pe/personas/productos/prestamos/credito-hipotecario/hipotecario-bbva.html).

Las hojas de cálculo y la coordinación por correo o mensajería se consideran sustitutos operativos planteados en el capítulo I. Su uso efectivo y sus limitaciones se contrastarán en entrevistas.

### 2.1.1. Análisis competitivo

**Competitive Analysis Landscape.** El análisis busca identificar oportunidades para combinar comprensión del financiamiento y continuidad del trabajo comercial. Las capacidades de CrediCasa son propuestas. Las limitaciones de los competidores describen el alcance observado en sus páginas públicas, no una auditoría de sus sistemas internos.

| Dimensión | CrediCasa — propuesta | Comparabien | BCP | BBVA Perú |
|---|---|---|---|---|
| Perfil | Plataforma de simulación y estructuración hipotecaria. | Comparador de productos financieros. | Entidad financiera con simulación propia. | Entidad financiera con simulación y asesoría propias. |
| Mercado objetivo | Comprador e Inmobiliaria/Banca. | Personas que comparan alternativas de crédito. | Personas interesadas en financiamiento BCP. | Personas interesadas en financiamiento BBVA. |
| Productos y servicios | Escenarios, cronogramas, indicadores y cotizaciones versionadas. | Comparación, selección y solicitud. | Estimación hipotecaria y acceso a solicitud. | Estimación y contacto comercial. |
| Ventaja relevante | Integración propuesta entre explicación financiera y preparación comercial. | Consulta de alternativas desde un mismo formulario. | Configuración de inicial, plazo y cuota simple o doble. | Opciones de pago y acompañamiento comercial. |
| Canal y captación | Web y móvil propuestas; demostraciones y pilotos en salas de venta. | Comparador web con llamadas a solicitar productos. | Web con simulador y solicitud. | Web con simulación y contacto con ejecutivos. |
| Modelo de acceso | SaaS B2B y referenciación planteados en el capítulo I; tarifas por validar. | Formulario público; no se infiere su modelo comercial completo. | Canal público asociado a contratación bancaria. | Canal público asociado a contratación bancaria. |
| Debilidad o límite observado | Producto en desarrollo, sin adopción ni exactitud operativa demostradas. | La página revisada no permite confirmar un flujo B2B de cotizaciones versionadas. | El recorrido revisado corresponde a productos de la propia entidad. | El recorrido revisado corresponde a productos de la propia entidad. |
| Oportunidad para CrediCasa | Unificar escenarios, explicación y seguimiento. | Explorar mayor detalle y continuidad del trabajo del asesor. | Comparar escenarios de distintas entidades con supuestos explícitos. | Vincular opciones de pago con explicación de efectos y versiones. |

Las descripciones de las alternativas se sustentan en las fuentes enlazadas en 2.1. Las oportunidades son interpretaciones del equipo; la ausencia de una función en una página no demuestra su inexistencia en el producto.

**Análisis SWOT de CrediCasa**

| Componente | Análisis | Implicación |
|---|---|---|
| Fortalezas propuestas | Especialización hipotecaria, cálculo explicable y atención a ambos segmentos. | Priorizar un flujo completo desde configuración hasta cotización. |
| Debilidades | Marca nueva, recursos limitados y dependencia de parámetros confiables. | Validar cálculos y delimitar el alcance inicial. |
| Oportunidades por validar | Comparación de propuestas equivalentes y reducción de tareas repetitivas. | Probar el flujo con compradores, inmobiliarias y banca. |
| Amenazas | Evolución de competidores, cambios de condiciones y resistencia a adoptar otra herramienta. | Conservar fuentes y versiones; medir el esfuerzo de incorporación. |

### 2.1.2. Estrategias y tácticas frente a competidores

| Estrategia | Tácticas propuestas | Segmento | Indicador de validación |
|---|---|---|---|
| Facilitar la comprensión | Desglosar capital, intereses, seguros y gastos; incorporar ayudas y gráficos de saldo. | Comprador | Participantes que explican los componentes del pago sin ayuda. |
| Comparar escenarios equivalentes | Mostrar monto, moneda, plazo, fecha y fuente; señalar diferencias de supuestos. | Ambos | Participantes que comparan dos propuestas y explican sus diferencias. |
| Agilizar la cotización | Reutilizar datos del inmueble y generar propuestas exportables y versionadas. | Inmobiliaria/Banca | Tiempo observado; contrastar la meta de menos de cinco minutos del capítulo I. |
| Construir confianza | Conservar entradas y reglas; contrastar cronogramas con casos de referencia. | Ambos | Discrepancias identificadas y explicadas durante la revisión. |
| Facilitar la adopción | Realizar pilotos y recoger necesidades diferenciadas de inmobiliaria y banca. | Inmobiliaria/Banca | Finalización de tareas, uso recurrente y disposición a contratar. |

El énfasis en explicar el costo se sustenta en la orientación de la SBS: la TCEA incorpora intereses, comisiones y gastos y se distingue de la tasa de interés. [Fuente: SBS, Aprende sobre créditos](https://www.sbs.gob.pe/usuarios/aprende-con-la-sbs/aprende-sobre-creditos).

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Objetivo general:** comprender cómo ambos segmentos buscan, elaboran, comparan y explican propuestas hipotecarias, identificando obstáculos y criterios de decisión antes de validar CrediCasa.

Se realizarán entrevistas semiestructuradas de 30 a 40 minutos, presenciales o virtuales, mediante selección intencional. La guía exige de tres a cinco entrevistas por segmento. Se planifican cuatro compradores y cuatro profesionales de Inmobiliaria/Banca: dos asesores o responsables inmobiliarios y dos ejecutivos hipotecarios. Esta distribución profesional es una propuesta de reclutamiento; Daniel representa al asesor inmobiliario y las respuestas de banca se analizarán por separado. La muestra es exploratoria y no representa estadísticamente al mercado.

| Segmento | Criterios de selección | Variación buscada | Objetivo específico |
|---|---|---|---|
| Comprador | Mayor de edad, vinculado a Lima Metropolitana, buscando financiamiento o con una cotización hipotecaria solicitada en los últimos doce meses. | Etapa de compra, trabajo dependiente o independiente y familiaridad financiera. | Identificar dudas, información necesaria y criterios de comparación. |
| Inmobiliaria/Banca | Profesional que cotiza, asesora o evalúa créditos hipotecarios en Lima Metropolitana, con al menos seis meses en estas tareas. | Inmobiliarias y bancos; responsabilidades comerciales y de evaluación. | Reconstruir procesos, controles y traspasos de información. |

**Procedimiento**

1. Explicar el propósito académico y solicitar consentimiento para participar, grabar y compartir la evidencia en YouTube para la entrega. Si no se autoriza, la conversación solo podrá utilizarse como exploración con permiso; no cubrirá el requisito de entrevista registrada en video.
2. Registrar código, nombres, apellidos, edad, distrito, segmento, rol y contexto de experiencia, con autorización para incluirlos en el informe. No solicitar claves ni copias de documentos identificatorios.
3. Preguntar primero por una experiencia reciente sin presentar la solución, para reducir respuestas inducidas.
4. Presentar después el concepto o prototipo y observar una tarea breve. Separar opiniones de comportamientos observados.
5. Cerrar con prioridades y dudas. Conservar evidencias anonimizadas con acceso controlado y publicar solo extractos autorizados.

**Guion de conducción**

| Momento | Duración orientativa | Intervención del entrevistador |
|---|---|---|
| Apertura y consentimiento | 3 minutos | «Somos estudiantes y buscamos comprender cómo se comparan o preparan propuestas hipotecarias. ¿Nos autorizas a grabar y compartir la entrevista como evidencia académica en YouTube?» Explicar previamente qué datos y fragmentos se incluirán. |
| Contexto personal o profesional | 5 minutos | Recoger la ficha de contexto y la experiencia reciente que se reconstruirá. |
| Experiencia real | 15–20 minutos | Seguir las preguntas del segmento y profundizar en ejemplos, herramientas, dificultades y decisiones. |
| Concepto y tarea exploratoria | 5–8 minutos | Presentar CrediCasa después de explorar el problema. Usar material ficticio preparado por el equipo y registrar las reacciones espontáneas. |
| Cierre | 2–4 minutos | «¿Qué dificultad sería más importante resolver? ¿Qué no te preguntamos y deberíamos conocer?» Confirmar qué evidencia se puede compartir. |

El guion organiza las preguntas del entrevistador. Cada participante responderá desde su experiencia; los ensayos internos y las tareas con datos ficticios se identificarán como tales y se separarán de las entrevistas de investigación.

**Ficha de contexto y preguntas complementarias para ambos segmentos**

- ¿Qué edad tienes, en qué distrito resides y a qué te dedicas? ¿Cómo describirías tu experiencia con créditos hipotecarios?
- Si deseas compartirlo: ¿con qué género te identificas, cuál es tu estado civil y con quiénes tomas decisiones de vivienda o de presupuesto familiar?
- ¿Qué dispositivos y canales digitales utilizas para buscar, guardar y compartir información financiera?
- ¿Qué herramientas o marcas consultas habitualmente y por qué? ¿Qué personas o fuentes influyen en tus decisiones?
- ¿Cómo prefieres evaluar una alternativa: revisar detalles por tu cuenta, conversar con alguien o combinar ambas opciones? Cuéntanos un ejemplo.
- Para profesionales: ¿cuánto tiempo llevas en tu rol y qué partes de una cotización dependen de ti o de otra persona?

Se registrará «prefiere no responder» cuando corresponda, sin completar datos por suposición. Como repreguntas neutrales se usarán «¿qué ocurrió después?», «¿puedes dar un ejemplo reciente?», «¿cómo lo resolviste?» y «¿qué información te faltó?».

**Preguntas para Comprador**

1. Cuéntanos cómo fue la última vez que buscaste financiamiento para una vivienda. ¿En qué etapa estás?
2. ¿Cómo determinaste la cuota inicial y el pago mensual que podrías asumir?
3. ¿Qué bancos, simuladores u otras herramientas consultaste y qué hiciste con sus resultados?
4. ¿Qué información comparaste entre propuestas? ¿Qué datos te faltaron?
5. ¿Cómo interpretaste la tasa y la cuota recibidas? ¿Qué entendiste por TEA y TCEA?
6. ¿Qué conceptos adicionales aparecieron y cuáles necesitaste que te explicaran?
7. ¿Recibiste opciones con cuotas dobles, balón o gracia? ¿Cómo las evaluaste?
8. ¿Encontraste diferencias entre una simulación y una propuesta posterior? ¿Cómo las aclaraste?
9. ¿Cómo guardaste o compartiste alternativas con quienes participan en tu decisión?
10. ¿Qué te hizo avanzar, detenerte o descartar una oferta? Describe un caso.
11. ¿Qué respaldo necesitarías para confiar en un simulador independiente?
12. Tras revisar CrediCasa, ¿qué parte te resultaría útil y cuál no usarías? ¿Por qué?

**Tarea exploratoria del Comprador:** presentar dos propuestas ficticias con igual moneda, monto y plazo, pero distintos intereses y gastos. Pedir que explique qué pagaría, qué incluye cada alternativa y qué consultaría antes de decidir. Registrar dudas y ayuda requerida.

**Preguntas para Inmobiliaria/Banca**

1. ¿Cuál es su rol y en qué etapas de la operación participa?
2. Describa la última cotización que preparó o revisó, desde la solicitud hasta la entrega.
3. ¿Qué datos recibe del comprador y del inmueble? ¿Cuáles suelen faltar?
4. ¿Qué herramientas utiliza y dónde vuelve a ingresar la misma información?
5. ¿De dónde obtiene tasas, seguros y condiciones? ¿Cómo comprueba su vigencia?
6. ¿Cómo maneja monedas distintas, gracia o pagos extraordinarios?
7. ¿Qué revisa antes de entregar una propuesta y quién valida el resultado?
8. ¿Qué dudas repiten los compradores y cómo las explica?
9. ¿En qué etapas se producen esperas o correcciones? Describa un caso reciente.
10. ¿Cómo comunica la diferencia entre simulación, cotización y aprobación crediticia?
11. ¿Cómo conserva versiones, identifica responsables y comparte información con la otra organización?
12. ¿Qué requisitos de acceso, exportación o integración necesita para adoptar una herramienta?
13. ¿Qué condiciones justificarían contratar CrediCasa y quién tomaría esa decisión?
14. Tras revisar el concepto, ¿qué parte no encaja con su trabajo?

**Repreguntas por rol:** consultar a la inmobiliaria cómo vincula la propuesta con el inmueble y la reserva; a la banca, qué información necesita para evaluar y qué condiciones solo puede confirmar dentro de su proceso autorizado.

**Tarea exploratoria de Inmobiliaria/Banca:** entregar datos ficticios de un inmueble y un comprador, solicitar una propuesta y luego cambiar el plazo. Observar preparación, comprobación, explicación y conservación de ambas versiones. Comparar con el proceso habitual cuando pueda demostrarse sin revelar datos de clientes.

### 2.2.2. Registro de entrevistas

El registro de grabaciones, transcripciones y consentimientos se realizará durante la ejecución de las entrevistas. La tabla organiza las sesiones previstas y no acredita entrevistas realizadas.

| Códigos previstos | Segmento y rol | Sesiones | Estado | Evidencia |
|---|---|---|---|---|
| COM-01 a COM-04 | Comprador | 4 | Pendientes de reclutamiento y ejecución | Sin evidencia disponible. |
| INM-01 a INM-02 | Inmobiliaria/Banca — asesor o responsable inmobiliario | 2 | Pendientes de reclutamiento y ejecución | Sin evidencia disponible. |
| BAN-01 a BAN-02 | Inmobiliaria/Banca — ejecutivo hipotecario | 2 | Pendientes de reclutamiento y ejecución | Sin evidencia disponible. |

Por sesión se registrarán código, nombres y apellidos autorizados, edad, distrito, fecha, entrevistador, duración, rol, consentimiento, captura de un cuadro del video, URL de YouTube y tiempo de inicio de la entrevista. También se redactará un resumen descriptivo de las principales respuestas y se conservarán marcas de tiempo para cada hallazgo. Los datos de contacto se mantendrán separados del informe público. Está disponible la [plantilla de registro y análisis](Resources/avance-1/plantilla-entrevistas.md) para completar con las sesiones reales.

### 2.2.3. Análisis de entrevistas

Se aplicará codificación temática y agrupación por afinidad sobre notas y transcripciones. Cada hallazgo tendrá evidencia identificable, distinguirá declaraciones de conductas observadas e incluirá casos contradictorios. La recurrencia se expresará como número de participantes y porcentaje sobre el total de respuestas válidas del segmento para esa pregunta: `porcentaje = participantes con la característica / participantes con respuesta válida × 100`. Se indicarán las no respuestas y, dentro de Inmobiliaria/Banca, los resultados por rol. Los porcentajes describirán únicamente la muestra entrevistada, sin extrapolar al mercado.

**Comprador — hipótesis por contrastar**

| ID | Hipótesis del capítulo I | Evidencia buscada | Necesidad candidata |
|---|---|---|---|
| HC-01 | La cuota aislada no permite comprender todos los pagos. | Interpretación espontánea y dudas sobre componentes. | Desglose comprensible de cuota, seguros y gastos. |
| HC-02 | Comparar ofertas exige reconstruir datos de varias fuentes. | Pasos y documentos de una comparación reciente. | Escenarios guardados con supuestos visibles. |
| HC-03 | El efecto de gracia y pagos extraordinarios es difícil de anticipar. | Explicación del cronograma antes y después de modificar condiciones. | Visualizar cambios en pagos, saldo y costo. |

**Inmobiliaria/Banca — hipótesis por contrastar**

| ID | Hipótesis del capítulo I | Evidencia buscada | Necesidad candidata |
|---|---|---|---|
| HI-01 | Reingresar información retrasa cotizaciones. | Secuencia, repeticiones y tiempos por rol. | Reutilizar datos y reducir pasos manuales. |
| HI-02 | Identificar condiciones y versiones facilita revisar propuestas. | Procedimiento de actualización y resolución de discrepancias. | Registrar fuente, fecha, parámetros y responsable. |
| HI-03 | El traspaso entre inmobiliaria y banca pierde contexto. | Casos de derivación y solicitudes de corrección. | Compartir una propuesta identificable con estado claro. |

**Síntesis cruzada preliminar:** ambos segmentos necesitan comprender la misma propuesta. El Comprador prioriza sus compromisos de pago; Inmobiliaria/Banca necesita preparar, revisar y explicar la información. Esta interpretación orienta el diseño y todavía no constituye un hallazgo de campo. Los resultados de asesores inmobiliarios y ejecutivos bancarios se conservarán diferenciados dentro del segmento.

Cada hallazgo posterior incluirá identificador, evidencia, rol, interpretación, necesidad, prioridad y vínculo con las historias de usuario del capítulo III. Las hipótesis podrán confirmarse, modificarse o descartarse.

## 2.3. Needfinding

Los siguientes artefactos sintetizan el capítulo I como modelos preliminares. Los perfiles son ficticios y sus comportamientos, emociones y frecuencias deberán contrastarse mediante entrevistas.

Las fichas y mapas gráficos disponibles en `Resources` se incorporan como borradores. Las frases en primera persona, rasgos y cifras que contienen son ilustraciones o supuestos de diseño; no constituyen testimonios ni mediciones. Falta validar su contenido y confirmar su elaboración en las herramientas exigidas: UXPressia para personas y empatía, Lucidchart/Miro para escenarios. La numeración actual conserva User Journey Mapping como sección adicional; Empathy Mapping y As-Is corresponden a los puntos 2.3.3 y 2.3.4 del cronograma.

### 2.3.1. User Personas

Las fichas relacionan las necesidades candidatas HC-01 a HC-03 con el Comprador y HI-01 a HI-03 con el asesor inmobiliario. El análisis competitivo orienta la exploración de comparación y continuidad de cotizaciones. La relación con resultados de entrevistas se incorporará cuando existan evidencias; actualmente son proto-personas.

#### Persona 1: Lucía Torres — Comprador

**Proto-persona ficticia:** Lucía tiene 32 años, trabaja de forma dependiente y vive en Lima Metropolitana. Busca su primer departamento junto con su pareja, cuenta con ahorros para la inicial y utiliza aplicaciones bancarias, aunque no domina los conceptos hipotecarios.

| Aspecto | Descripción propuesta |
|---|---|
| Objetivos | Definir un pago compatible con su presupuesto, comparar alternativas y comprender el compromiso total. |
| Comportamiento supuesto | Consulta simuladores, conserva capturas y conversa con asesores y familiares. |
| Frustraciones previstas | Conceptos poco claros, propuestas difíciles de comparar y dudas sobre cambios en la cuota. |
| Necesidades | Desglose de pagos, explicaciones sencillas, escenarios guardados y visualización del saldo. |
| Contexto de uso | Explora desde el teléfono y revisa detalles desde una computadora o en sala de ventas. |
| Criterio de éxito | Explica qué pagaría, qué costos se incluyen y qué debe confirmar con la entidad. |

**Frase ilustrativa creada para el perfil, no testimonio:** «Quiero entender cuánto pagaré y por qué cambia el resultado entre propuestas».

**Ficha visual preliminar de Lucía:** la ocupación de analista de marketing y los rasgos representados son atributos ficticios para orientar el diseño.

![Proto-persona preliminar: Lucía Torres, comprador](Resources/userpseg_1.png)

#### Persona 2: Daniel Rojas — Inmobiliaria/Banca

**Proto-persona ficticia:** Daniel tiene 38 años y es asesor comercial de una inmobiliaria de Lima Metropolitana. Atiende compradores y coordina con ejecutivos hipotecarios para dar continuidad a sus solicitudes.

| Aspecto | Descripción propuesta |
|---|---|
| Objetivos | Preparar propuestas oportunas, explicar alternativas y mantener información consistente en la coordinación bancaria. |
| Comportamiento supuesto | Consulta precios y condiciones, prepara simulaciones y conserva propuestas para seguimiento. |
| Frustraciones previstas | Duplicación de datos, cambios de condiciones y dificultad para identificar la última versión. |
| Necesidades | Parámetros trazables, reutilización de datos, cronogramas verificables y exportaciones identificadas. |
| Contexto de uso | Trabaja desde una computadora en sala de ventas y consulta propuestas durante la atención. |
| Criterio de éxito | Entrega una propuesta comprensible, recupera sus supuestos y la deriva con información suficiente. |

**Frase ilustrativa creada para el perfil, no testimonio:** «Necesito preparar una propuesta clara y saber con qué condiciones se calculó».

**Ficha visual preliminar de Daniel:** las referencias a pérdidas y tiempos de espera son supuestos por contrastar, no resultados de entrevistas.

![Proto-persona preliminar: Daniel Rojas, asesor inmobiliario](Resources/userpseg_2.png)

**Atributos complementarios propuestos para las fichas**

| Atributo | Lucía Torres | Daniel Rojas |
|---|---|---|
| Contexto y familia | Busca vivienda con su pareja; distrito concreto y composición familiar pendientes de investigación. | Atiende proyectos en Lima; distrito y contexto familiar pendientes de investigación. |
| Motivación | Tomar una decisión de vivienda compatible con su presupuesto. | Preparar propuestas comprensibles y dar continuidad a sus oportunidades comerciales. |
| Habilidades supuestas | Uso cotidiano de banca digital; requiere apoyo para interpretar condiciones hipotecarias. | Experiencia comercial y uso de hojas de cálculo; requiere verificar parámetros financieros. |
| Dispositivos y canales | Teléfono para explorar; computadora para comparar; conversación con asesores. | Computadora para preparar propuestas; teléfono y correo para seguimiento. |
| Influencias por investigar | Pareja, familiares, asesores y fuentes financieras consultadas. | Jefatura comercial, compradores y ejecutivos bancarios. |
| Marcas y personalidad | Preferencias y rasgos de la ficha pendientes de contraste; no se asignan marcas favoritas sin evidencia. | Preferencias y rasgos de la ficha pendientes de contraste; no se asignan marcas favoritas sin evidencia. |

**Cobertura de Banca:** Daniel representa la preparación comercial. El ejecutivo bancario del mismo segmento necesita revisar los datos recibidos, contrastarlos con condiciones de su entidad y comunicar el resultado de su evaluación. Las entrevistas podrán justificar una persona adicional para ese rol sin crear un tercer segmento objetivo.

### 2.3.2. User Task Matrix

La matriz compara a Lucía (Comprador) y Daniel (asesor inmobiliario del segmento Inmobiliaria/Banca). Las tareas describen objetivos que pueden realizarse con herramientas actuales, antes de CrediCasa. La frecuencia es una estimación durante la búsqueda activa de Lucía y la jornada habitual de Daniel: **alta**, varias veces en ese contexto; **media**, en determinados momentos; **baja**, ocasional. La importancia es **alta** cuando la tarea condiciona la comparación o preparación de la propuesta y **media** cuando apoya una decisión específica. Ambas escalas están pendientes de validación.

| Tarea | Lucía: frecuencia | Lucía: importancia | Daniel: frecuencia | Daniel: importancia |
|---|---|---|---|---|
| Registrar datos de inmueble y financiamiento | Media | Alta | Alta | Alta |
| Modificar inicial, moneda o plazo | Alta | Alta | Alta | Alta |
| Consultar condiciones financieras | Media | Alta | Alta | Alta |
| Comparar escenarios | Alta | Alta | Alta | Alta |
| Interpretar cuota, seguros, gastos y TCEA | Alta | Alta | Alta | Alta |
| Revisar cronograma y saldo | Media | Alta | Alta | Alta |
| Explorar gracia, cuotas dobles o balón | Baja | Media | Media | Alta |
| Consultar VAN y TIR | Baja | Media | Media | Media |
| Guardar y recuperar propuestas | Media | Alta | Alta | Alta |
| Preparar y compartir una copia de la cotización | Baja | Media | Alta | Alta |
| Derivar una propuesta para evaluación | Baja | Alta | Alta | Alta |
| Revisar versiones y responsables | Baja | Media | Alta | Alta |

La aprobación crediticia pertenece al proceso de la banca y no se considera una tarea automática de CrediCasa. La relevancia de VAN y TIR se comprobará: su inclusión en el alcance del capítulo I no demuestra que sean los indicadores principales del usuario.

**Lectura preliminar:** comparar alternativas, ajustar el financiamiento e interpretar los pagos reúnen frecuencia e importancia altas para ambas personas. Daniel necesitaría registrar datos, recuperar propuestas y revisar responsables con mayor frecuencia por la atención a varios compradores. Lucía realizaría esas tareas de forma ocasional durante su búsqueda. La coincidencia orienta la comparación y explicación del costo; las diferencias orientan la continuidad del trabajo comercial. Esta interpretación se revisará con las entrevistas.

### 2.3.3. User Journey Mapping

Los recorridos describen la experiencia actual supuesta, previa a CrediCasa. Las oportunidades servirán de entrada al To-Be Scenario Mapping del capítulo III.

**Recorrido del Comprador**

| Etapa | Acción y contacto | Emoción o pregunta prevista | Dolor supuesto | Oportunidad |
|---|---|---|---|---|
| Explorar vivienda | Consulta anuncios y visita proyectos. | Ilusión: ¿qué vivienda puedo financiar? | Precio desconectado de su presupuesto de pagos. | Relacionar precio, inicial y financiamiento. |
| Buscar crédito | Consulta páginas y bancos. | Incertidumbre sobre requisitos. | Información dispersa. | Reunir condiciones y fuentes. |
| Simular | Introduce datos en varias herramientas. | Duda sobre lo que incluye la cuota. | Repetición y dificultad de interpretación. | Desglosar componentes del pago. |
| Comparar | Revisa capturas y cotizaciones. | Inseguridad al elegir. | Diferentes supuestos entre propuestas. | Mostrar diferencias y guardar alternativas. |
| Solicitar evaluación | Entrega información y aclara condiciones. | Expectativa por la respuesta. | Confusión entre estimación y oferta confirmada. | Identificar estado y supuestos. |

**Recorrido de Inmobiliaria/Banca**

| Etapa | Acción y contacto | Emoción o pregunta prevista | Dolor supuesto | Oportunidad |
|---|---|---|---|---|
| Atender | Inmobiliaria recoge datos del comprador y del inmueble. | Interés por orientar la venta. | Información incompleta o repartida. | Estructurar datos iniciales. |
| Preparar | Asesor consulta condiciones y calcula. | Presión por responder pronto. | Cambios manuales y fuentes difíciles de rastrear. | Reutilizar datos y registrar parámetros. |
| Explicar | Presenta cuota y cronograma. | Necesidad de transmitir confianza. | Dudas que exigen repetir cálculos. | Facilitar revisión y explicación. |
| Derivar | Comparte la propuesta con la banca. | Incertidumbre sobre datos faltantes. | Pérdida de contexto. | Conservar propuesta, versión y responsable. |
| Revisar y continuar | Banca evalúa y pide aclaraciones; inmobiliaria da seguimiento. | Necesidad de conocer el avance. | Retrabajo y estados poco visibles. | Diferenciar revisión comercial de evaluación bancaria. |

### 2.3.4. Empathy Mapping

**Preparación del borrador:** se tomó cada proto-persona como centro, se organizaron las hipótesis de 2.2.3 en dimensiones de empatía y se relacionaron las frustraciones con los resultados esperados. Quedan pendientes la revisión del equipo, las observaciones de entrevistas y las capturas definitivas en UXPressia.

**Mapa de empatía preliminar — Comprador**

| Dimensión | Hipótesis sobre Lucía |
|---|---|
| Con quién se empatiza | Lucía, compradora que evalúa financiamiento para su primera vivienda. |
| Qué necesita hacer | Comparar propuestas y decidir qué condiciones consultar antes de solicitar evaluación. |
| Piensa y siente | Desea adquirir vivienda y teme asumir pagos que no comprende. |
| Ve | Anuncios, simuladores y propuestas con diferentes formatos. |
| Oye | Consejos familiares y explicaciones de asesores sobre tasas y cuotas. |
| Dice | Pregunta por el pago mensual y por los conceptos que incluye. |
| Hace | Consulta alternativas, reúne cotizaciones y guarda resultados para compararlos. |
| Esfuerzos y frustraciones | Interpretar conceptos y reconstruir comparaciones. |
| Resultados esperados | Entender su cronograma y comparar con información suficiente. |
| Qué podría convencerla | Poder explicar los costos y reconocer los supuestos de una propuesta por sí misma. |

**Interpretación:** el diseño debe permitir pasar de una cuota resumida al detalle sin exigir conocimientos previos. Se comprobará si el participante puede explicar una propuesta con sus propias palabras.

![Mapa de empatía preliminar de Lucía; frases hipotéticas](Resources/empa_m1.png)

**Mapa de empatía preliminar — Inmobiliaria/Banca**

| Dimensión | Hipótesis sobre el segmento |
|---|---|
| Con quién se empatiza | Daniel, asesor inmobiliario que prepara propuestas y coordina con la banca. |
| Qué necesita hacer | Entregar una cotización comprensible y mantener su contexto durante el seguimiento. |
| Piensa y siente | Busca responder rápido y evitar discrepancias en lo comunicado. |
| Ve | Solicitudes, condiciones y propuestas en distintas etapas. |
| Oye | Preguntas de compradores, metas comerciales y observaciones bancarias. |
| Dice | Solicita información al comprador y explica las condiciones de la propuesta. |
| Hace | Recoge datos, calcula, contrasta parámetros, deriva y revisa el seguimiento. |
| Esfuerzos y frustraciones | Reingresar datos, identificar versiones y aclarar diferencias. |
| Resultados esperados | Propuestas rastreables, coordinación clara y menor retrabajo. |
| Qué podría convencerlo | Recuperar una cotización con su fuente y versión, explicar sus pagos y actualizarla sin repetir toda la preparación. |

**Interpretación:** la información compartida debe respetar responsabilidades diferenciadas. El asesor prepara y explica; el ejecutivo bancario revisa dentro de su proceso de evaluación. Las entrevistas precisarán qué necesita cada rol.

![Mapa de empatía preliminar de Daniel; frases hipotéticas](Resources/empa_m2.png)

### 2.3.5. As-Is Scenario Mapping

Los escenarios amplían los recorridos anteriores y mantienen su carácter hipotético hasta observar casos reales.

Los gráficos existentes organizan las fases en columnas y las filas **Phases, Doing, Thinking y Feeling**. El de Lucía cubre explorar vivienda, buscar crédito, simular escenarios y comparar/decidir. El de Daniel cubre atender, preparar cotización, explicar y derivar al banco. Las frases representan pensamientos supuestos.

![As-Is preliminar de Lucía: explorar, buscar, simular y comparar](Resources/asis_m1.png)

![As-Is preliminar de Daniel: atender, preparar, explicar y derivar](Resources/asis_m2.png)

**Áreas que se revisarán con el equipo y las entrevistas**

| Persona | Áreas positivas supuestas | Áreas negativas supuestas | Blank areas: información por conocer |
|---|---|---|---|
| Lucía | Puede explorar viviendas y consultar varias alternativas. | Reingreso de datos y dificultad para entender si las propuestas son equivalentes. | Qué fuentes usa, qué costos reconoce y qué factores determinan su decisión. |
| Daniel | Conoce el proyecto y puede orientar al comprador durante la visita. | Parámetros difíciles de rastrear, repetición de datos y pérdida de contexto al derivar. | Herramientas realmente utilizadas, tiempos por fase y requisitos de recepción de cada banco. |

La preparación reúne hipótesis del capítulo I, proto-personas y recorridos de 2.3.3. En la siguiente revisión, cada integrante propondrá observaciones, se acordarán las fases y se etiquetarán las áreas positivas, negativas y desconocidas en Lucidchart/Miro. Esa sesión de trabajo y la validación de campo todavía están pendientes.

| Elemento | Comprador | Inmobiliaria/Banca |
|---|---|---|
| Situación inicial | Encuentra una vivienda y busca financiamiento. | Recibe una consulta que requiere propuesta hipotecaria. |
| Secuencia actual supuesta | Consulta, repite datos, reúne resultados, compara y pide aclaraciones. | Recoge datos, consulta condiciones, calcula, presenta, deriva y corrige. |
| Herramientas | Simuladores, correos, capturas y cotizaciones. | Listas de precios, hojas de cálculo, simuladores y documentos comerciales. |
| Ruptura principal | No identifica si compara el mismo monto, plazo y conjunto de gastos. | No conserva todo el contexto entre cálculo, cotización y revisión. |
| Consecuencia por validar | Posterga la decisión o pide ayuda para comprender alternativas. | Repite tareas y demora la respuesta. |
| Evidencia necesaria | Reconstrucción de una comparación reciente con documentos anonimizados. | Observación de una cotización y su traspaso entre roles. |
| Necesidad derivada | Comparación explicable con supuestos y estado visibles. | Continuidad y trazabilidad desde preparación hasta revisión. |

## 2.4. Big Picture EventStorming

Se propone un primer mapa de eventos para revisar en un taller con representantes de ambos segmentos. Es un modelo elaborado a partir del capítulo I y las necesidades candidatas, no el resultado de un taller realizado. Los eventos se nombran en pasado y los comandos expresan acciones que los provocan.

```mermaid
flowchart LR
    A[Datos del escenario registrados] --> B[Condiciones seleccionadas]
    B --> C[Simulación calculada]
    C --> D[Cronograma generado]
    D --> E[Indicadores calculados]
    E --> F[Escenario guardado]
    F --> G[Escenarios comparados]
    F --> H[Cotización emitida]
    G --> H
    H --> I[Derivación solicitada]
    I --> J[Solicitud recibida por la banca]
    J --> K[Evaluación bancaria externa]
```

| Actor | Comando | Evento | Regla o información propuesta |
|---|---|---|---|
| Comprador o asesor | Registrar escenario | Datos del escenario registrados | Precio, inicial, monto, moneda y plazo coherentes. |
| Usuario autorizado | Seleccionar condiciones | Condiciones seleccionadas | Tasa, capitalización, seguros, gastos y pagos; conservar fuente y fecha. |
| Comprador o asesor | Solicitar simulación | Simulación calculada | Entradas válidas y versión del motor identificable. |
| Motor financiero | Generar cronograma | Cronograma generado | Desglose según condiciones y convenciones declaradas. |
| Motor financiero | Calcular indicadores | Indicadores calculados | Flujos del deudor y supuestos explícitos; informar indicadores no calculables. |
| Comprador o asesor | Guardar escenario | Escenario guardado | Conservar entradas, resultados y versión. |
| Comprador o asesor | Comparar escenarios | Escenarios comparados | Exponer diferencias de monto, moneda, plazo y costos. |
| Asesor o ejecutivo autorizado | Emitir cotización | Cotización emitida | Autor, versión, fecha y carácter referencial. |
| Comprador con apoyo del asesor | Solicitar derivación | Derivación solicitada | Destinatario y autorización sobre datos compartidos. |
| Ejecutivo o canal acordado | Confirmar recepción | Solicitud recibida por la banca | Registrar solo con evidencia de recepción; no asumir una integración disponible. |

**Excepciones y puntos por resolver en el taller**

- Si existen datos inconsistentes, informar qué corregir antes de calcular.
- Al cambiar condiciones, crear una nueva versión conservando la propuesta anterior.
- Definir quién incorpora y valida parámetros y cómo comunica su vigencia.
- Acordar reglas de gracia, cuotas dobles, balón, redondeo y ajuste final del saldo.
- Determinar qué intercambio con la banca será manual y cuál requerirá integración futura.
- Tratar aprobación y rechazo como resultados del proceso bancario externo, registrables solo mediante comunicación verificable.

Se plantean como agrupaciones preliminares la configuración financiera, la simulación, la gestión de escenarios y la cotización/derivación. Estas agrupaciones orientan el análisis del dominio sin fijar todavía una arquitectura de microservicios.

## 2.5. Ubiquitous Language

El siguiente vocabulario se utilizará en entrevistas, modelos e historias de usuario. Las definiciones operativas se basan en el alcance del capítulo I y deberán ajustarse al validar reglas con especialistas.

| Término | Significado dentro de CrediCasa |
|---|---|
| Comprador | Persona que explora o solicita financiamiento para adquirir vivienda. |
| Inmobiliaria/Banca | Segmento profesional que agrupa preparación comercial y evaluación bancaria con responsabilidades distintas. |
| Asesor inmobiliario | Usuario que prepara y explica propuestas de un inmueble y acompaña su derivación. |
| Ejecutivo bancario | Representante que revisa solicitudes dentro del proceso de su entidad. |
| Inmueble | Vivienda cuyo precio y características contextualizan la simulación. |
| Cuota inicial | Aporte inicial del comprador utilizado para determinar el financiamiento. |
| Monto financiado | Capital del escenario; debe explicitar si incorpora gastos financiados. |
| Escenario | Conjunto de entradas y supuestos de una alternativa hipotecaria. |
| Simulación | Cálculo referencial del escenario; no constituye aprobación crediticia. |
| Moneda | Unidad del escenario: PEN o USD según el alcance del proyecto. |
| Tasa nominal | Tasa que se interpreta junto con su período y frecuencia de capitalización. |
| Tasa efectiva / TEA | Tasa de un período que refleja capitalización; TEA designa su expresión anual. |
| TCEA | Medida anual del costo efectivo que incorpora intereses, comisiones y gastos aplicables, distinta de la TEA. |
| Método francés vencido | Esquema base con pago al final del período y cuota de capital e intereses constante bajo condiciones fijas, antes de ajustes por esquemas especiales. |
| Cronograma | Detalle periódico de saldo, amortización, intereses, seguros, gastos y pago total. |
| Amortización | Parte del pago que reduce el capital adeudado. |
| Saldo insoluto | Capital pendiente de amortizar. |
| Gracia total | En el modelo propuesto, intervalo sin pago de capital ni intereses, con tratamiento explícito de intereses acumulados y cargos. |
| Gracia parcial | En el modelo propuesto, intervalo sin amortización de capital, con pago de intereses y cargos según condiciones. |
| Cuota doble | Pago programado superior al ordinario en períodos definidos; su composición debe especificarse. |
| Cuota balón | Pago extraordinario concentrado en una fecha y reflejado en el cronograma. |
| Seguros y gastos | Componentes adicionales con importe o tasa, base de cálculo y periodicidad identificables. |
| Flujo del deudor | Entradas y salidas desde el comprador: financiamiento recibido y pagos por realizar. |
| VAN del deudor | Valor de flujos descontados a una tasa declarada; su interpretación depende de esa tasa y del escenario. |
| TIR del deudor | Tasa que hace cero el VAN; debe indicarse periodicidad y advertirse si no existe una solución única interpretable. |
| Cotización | Documento referencial de una versión del escenario, con autor, fecha y condiciones. |
| Versión | Registro de entradas, reglas y resultados que permite reconstruir una propuesta. |
| Precalificación comercial | Orientación preliminar distinta de la decisión crediticia de la entidad. |
| Derivación | Traspaso autorizado de información para iniciar o continuar la atención bancaria. |
| Aprobación crediticia | Decisión de la entidad financiera, externa al motor de simulación. |

La distinción entre tasa de interés y TCEA se apoya en la [orientación de la SBS sobre créditos](https://www.sbs.gob.pe/usuarios/aprende-con-la-sbs/aprende-sobre-creditos). El carácter referencial y la separación de la evaluación crediticia se explicitan también en el [simulador BCP](https://www.viabcp.com/creditos/bmo-credito-hipotecario/simulador-credito-hipotecario). Las demás convenciones describen el modelo del proyecto y no presuponen condiciones idénticas en todas las entidades.

<div style="page-break-after: always;"></div>

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

Los escenarios proponen cómo Lucía y Daniel realizarían sus tareas con CrediCasa. Se elaboran a partir de los As-Is preliminares de 2.3.5 y las necesidades candidatas HC-01 a HC-03 e HI-01 a HI-03. Las acciones, pensamientos y emociones describen una experiencia deseada; todavía no son resultados de pruebas con usuarios.

**Preparación y revisión:** se conservan las cuatro fases de cada As-Is para comparar el proceso actual supuesto con el propuesto. Para cada fase se especifica qué haría la persona, qué necesitaría comprender y cómo se espera que se sienta. La lluvia de ideas individual, el acuerdo de fases por el equipo y la revisión con participantes quedan pendientes. Los gráficos locales permiten revisar el contenido antes de elaborarlo en Lucidchart/Miro y adjuntar las capturas exigidas por la guía.

### Escenario propuesto de Lucía — Comprador

**Situación:** Lucía ha encontrado una vivienda y quiere comparar alternativas de financiamiento antes de solicitar una evaluación. El escenario termina con una alternativa guardada y las condiciones pendientes de confirmar identificadas.

| Phases | Explorar vivienda | Buscar crédito | Simular escenarios | Comparar y decidir |
|---|---|---|---|---|
| Doing | Registra precio, moneda e inicial de la vivienda que está evaluando. | Revisa condiciones disponibles, fuente y fecha; identifica datos que debe confirmar con la entidad. | Ajusta plazo y condiciones; consulta cuota, seguros, gastos y cronograma. | Compara escenarios con sus diferencias visibles, guarda la alternativa y prepara sus consultas al asesor. |
| Thinking | ¿Qué monto necesitaría financiar con mis ahorros? | ¿Estas condiciones corresponden a mi caso y siguen vigentes? | ¿Qué incluye el pago y cómo cambia si modifico el plazo o la gracia? | ¿Qué cambia entre las alternativas y qué falta confirmar antes de solicitar evaluación? |
| Feeling | Orientación inicial al relacionar vivienda y presupuesto. | Cautela informada sobre el origen de las condiciones. | Mayor comprensión al revisar el detalle de los pagos. | Mayor claridad para decidir el siguiente paso. |

![To-Be preliminar de Lucía Torres](Resources/avance-1/tobe-lucia.svg)

### Escenario propuesto de Daniel — Asesor inmobiliario

**Situación:** Daniel atiende a un comprador interesado en un inmueble y prepara una propuesta para explicarla y, si el comprador lo solicita, compartirla con el canal bancario acordado. La evaluación crediticia ocurre fuera del simulador.

| Phases | Atender al cliente | Preparar cotización | Explicar propuesta | Derivar al banco |
|---|---|---|---|---|
| Doing | Reúne los datos necesarios del inmueble y del financiamiento; identifica información faltante. | Reutiliza los datos, verifica fuente y fecha de parámetros y genera un escenario con versión identificable. | Revisa con el comprador el desglose y las alternativas; conserva la versión elegida. | Obtiene autorización para compartir, entrega la cotización identificada y registra el envío; confirma recepción solo con evidencia. |
| Thinking | ¿Tengo los datos suficientes para una propuesta referencial? | ¿Puedo explicar de dónde salen estas condiciones y reconstruir el cálculo? | ¿El comprador comprende los pagos y el carácter referencial de la propuesta? | ¿Qué envié, a quién y qué falta para que la entidad lo evalúe? |
| Feeling | Mayor orden al iniciar la atención. | Confianza condicionada a parámetros verificables. | Claridad para explicar y responder preguntas. | Mayor control del seguimiento, sin anticipar la decisión bancaria. |

![To-Be preliminar de Daniel Rojas](Resources/avance-1/tobe-daniel.svg)



### Cambios propuestos frente al As-Is

| Persona y fase | Dificultad supuesta en el As-Is | Cambio propuesto en el To-Be | Comprobación futura |
|---|---|---|---|
| Lucía: explorar y buscar | Consulta precio y condiciones por separado. | Relaciona precio, inicial y monto; revisa procedencia y vigencia de condiciones. | Observar si identifica monto y datos pendientes de confirmar. |
| Lucía: simular | Desconoce qué costos incluye el resultado. | Accede al desglose y al efecto de modificar condiciones. | Pedir que explique los componentes de un pago con sus propias palabras. |
| Lucía: comparar | Reconstruye diferencias desde capturas. | Compara escenarios guardados y reconoce supuestos distintos. | Observar si identifica diferencias de monto, plazo y gastos. |
| Daniel: atender y preparar | Reingresa información y pierde referencia de parámetros. | Reutiliza datos y conserva fuente, fecha y versión. | Medir preparación y comprobar si recupera el contexto de la cotización. |
| Daniel: explicar y derivar | Comunica un resultado aislado y comparte documentos dispersos. | Explica el detalle y comparte una versión identificada con autorización. | Revisar comprensión del comprador e integridad de la información compartida. |

**Excepciones que deben contemplarse:** datos incompletos o incompatibles requieren corrección antes del cálculo; condiciones sin fecha o fuente se señalan como pendientes de confirmación; modificar un escenario guardado genera una nueva versión; un envío sin acuse no se presenta como recibido; ninguna simulación representa una aprobación bancaria. El canal de derivación y los parámetros financieros concretos requieren definición posterior con los responsables correspondientes.

## 3.2. User Stories

## E01 - Gestión de cuentas y autentificación

**Descripción:** Como usuario, requiero de un sistema de autentificación que me permita registrarme, iniciar sesión, modificar y cerrar sesión, para acceder de manera segura a la plataforma.<br>
<br> **Objetivo:** Proveer al usuario con un sistema sencillo, capaz y seguro para ingresar.<br>
<br> **Criterios de aceptación:** <br>
- Ingresar a la plataforma mediante de correo y contraseña.
- Actualización de la información del perfil.
- Authentificación de dos pasos.

 ## E02 - Pago de la suscripción

**Descripción:** Como usuario, requiero de un sistema de pagos simple que me permita ingresar mis datos bancarios de manera segura, para pagar mi suscripción<br>
<br> **Objetivo:** Proveer al usuario una pagina fácil de utilizar para realizar un pago. <br>
<br> **Criterios de aceptación:** <br> 
- Pago por medio de diversos procesadores de pago.
- Verificación del estado del pago.

## E03 - Gestion de los bienes inmobiliarios

**Descripción:** Como usuario, deseo un sistema que me permita registrar mis bienes inmobiliarios de manera fácil y rapida, además de verificar la legitimidad de este. <br>
<br> **Objetivo:** Proveer al usuario con un sistema intuitivo que permita registrar y autentificar los bienes. <br>
<br> **Criterios de aceptación:** <br> 
- Registrar un bien inmobiliario.
- Eliminar un bien inmobiliario ya registrado.
- Verificar que se trate un bien genuino.

## E04 - Revision del credito ofrecido

**Descripción:** Como usuario, deseo que el sistema me avise una vez el banco me haya ofrecido el credito, junto a su tasa, frecuencia de pago, etc. <br>
<br> **Objetivo:** Crear un sistema que ayude al cliente cuando ya se le haya ofrecido un credito por el inmobiliario. <br>
<br> **Criterios de aceptación:** <br> 
- Notificación cuando se haya ofrecido un bien.
- Creación de un cronograma de pagos.
- Boton para descargar el cronograma como un archivo .xlsx.

## E05 - Sistema de busqueda

**Descripción:** Como usuario, deseo que el aplicativo me permita revisar tambien otros inmuebles, el credito que podria recibir por estos e información al respecto. <br>
<br> **Objetivo:** Crear un sistema que permita al usuario buscar inmuebles según diversos "Tags" <br>
<br> **Criterios de aceptación:** <br>
- Implementar una barra de busqueda.
- Busqueda de inmuebles por tags.
- Implementar una IA para apoyar al usuario en su busqueda.

## E06 - Mensajeria

**Descripción:** Como usuario, deseo poseer un sistema de mensajeria para comunicarme con los bancos o propietarios del inmueble <br>
<br> **Objetivo:** Implementar un sistema de mensajeria, que apoye al usuario. <br>
<br> **Criterios de aceptación:** <br>
- Implementar un sistema de mensajeria.
- Implementar una opción para bloquear a otros usuarios.
- Implementar un boton para descargar la conversación.

| ID | Epic | User Story | Criterios de aceptación |
|----|------|------------|-------------------------|
| US01 | E01 | Como usuario, quiero utilizar mi correo y contraseña, para ingresar a mi cuenta. | **Scenario 1: el usuario posee los datos correctos** <br> *Given* que el usuario tenga el correo y contraseña correctos <br> *When* ingresa sus datos para ingresar a la platafomra <br> *Then* Ingresa de manera exitosa <br> **Scenario 2: el usuario no posee los datos correctos** <br> *Given* que el usuario no tenga el correo y contraseña correctos <br> *When* ingresa sus datos para ingresar a la platafomra <br> *Then* Bota el error de "correo o contraseña incorrectos" <br> |
| US02 | E01 | Como usuario, quiero modificar los datos de mi perfil, para mantener mi información actualizada. | **Scenario 1: actualización exitosa de datos** <br> *Given* que el usuario está autenticado en su perfil <br> *When* modifica sus datos personales y guarda los cambios <br> *Then* el sistema guarda la nueva información y muestra un mensaje de éxito <br> **Scenario 2: intento de guardar campos obligatorios vacíos** <br> *Given* que el usuario está editando su perfil <br> *When* deja un campo obligatorio vacío e intenta guardar <br> *Then* el sistema no guarda los cambios y muestra un mensaje de error <br> |
| US03 | E01 | Como usuario, quiero habilitar la autenticación de dos pasos, para añadir una capa extra de seguridad a mi cuenta. | **Scenario 1: configuración exitosa del segundo factor** <br> *Given* que el usuario solicita activar la autenticación de dos pasos <br> *When* vincula su método preferido e ingresa el código de verificación correcto <br> *Then* el sistema activa la función y confirma la seguridad adicional <br> **Scenario 2: código de verificación incorrecto** <br> *Given* que el usuario está configurando la autenticación de dos pasos <br> *When* ingresa un código de verificación incorrecto o expirado <br> *Then* el sistema deniega la activación y solicita un nuevo código <br> |
| US04 | E01 | Como usuario, quiero cerrar mi sesión activa, para proteger mi cuenta al dejar de usar la plataforma. | **Scenario 1: cierre de sesión exitoso** <br> *Given* que el usuario tiene una sesión activa en el sistema <br> *When* selecciona la opción de cerrar sesión <br> *Then* el sistema destruye la sesión y redirige al usuario a la pantalla de inicio <br> |
| US05 | E02 | Como usuario, quiero seleccionar entre diversos procesadores de pago, para realizar la transacción con mi método preferido. | **Scenario 1: pago procesado con éxito** <br> *Given* que el usuario selecciona un procesador de pago disponible <br> *When* ingresa los datos requeridos y confirma la transacción <br> *Then* el procesador autoriza el movimiento y se completa la compra <br> **Scenario 2: fondos insuficientes o rechazo de pasarela** <br> *Given* que el usuario intenta pagar con un método seleccionado <br> *When* el procesador de pagos rechaza la transacción por falta de fondos o datos inválidos <br> *Then* el sistema notifica el fallo y permite reintentar el pago <br> |
| US06 | E02 | Como usuario, quiero verificar el estado de mi pago, para confirmar que mi suscripción está activa. | **Scenario 1: visualización de pago exitoso** <br> *Given* que el sistema recibe la confirmación de la pasarela de pago <br> *When* el usuario consulta el estado de su suscripción <br> *Then* el sistema muestra el estado como "Pagado" o "Activo" <br> **Scenario 2: visualización de pago pendiente o fallido** <br> *Given* que la transacción quedó retenida o fue rechazada <br> *When* el usuario revisa el módulo de pagos <br> *Then* el sistema detalla el error o el estado "Pendiente" junto con opciones de soporte <br> |
| US07 | E03 | Como usuario, quiero registrar un bien inmobiliario, para guardarlo en mi cuenta y gestionar sus detalles. | **Scenario 1: registro exitoso del inmueble** <br> *Given* que el usuario completa todos los datos obligatorios del inmueble <br> *When* presiona el botón de registrar <br> *Then* el sistema guarda la propiedad y la muestra en su lista de bienes <br> **Scenario 2: campos obligatorios incompletos** <br> *Given* que el usuario deja campos requeridos vacíos <br> *When* intenta registrar el inmueble <br> *Then* el sistema muestra alertas en los campos faltantes y no procesa el registro <br> |
| US08 | E03 | Como usuario, quiero eliminar un bien inmobiliario ya registrado, para quitar de mi lista las propiedades que ya no poseo. | **Scenario 1: eliminación confirmada del inmueble** <br> *Given* que el usuario selecciona un inmueble de su lista <br> *When* presiona eliminar y confirma la acción en la ventana emergente <br> *Then* el sistema borra el inmueble de la base de datos y actualiza la vista <br> **Scenario 2: cancelación de la eliminación** <br> *Given* que el usuario presiona eliminar por error <br> *When* cancela la acción en la ventana de confirmación <br> *Then* el sistema mantiene el inmueble intacto en la lista <br> |
| US09 | E03 | Como usuario, quiero verificar la legitimidad de mi bien inmobiliario, para demostrar que es un inmueble genuino y legal. | **Scenario 1: verificación aprobada por el sistema** <br> *Given* que el usuario adjunta los documentos legales solicitados <br> *When* el sistema procesa la validación registral <br> *Then* el inmueble recibe una etiqueta o estado de "Verificado/Genuino" <br> **Scenario 2: rechazo por documentos inválidos** <br> *Given* que los documentos cargados están corruptos, incompletos o son rechazados <br> *When* finaliza la revisión automática o manual <br> *Then* el sistema cambia el estado a "Rechazado" e indica el motivo del fallo <br> |
| US10 | E04 | Como usuario, quiero recibir una notificación inmediata cuando un banco me ofrezca un crédito, para enterarme al instante de las oportunidades disponibles. | **Scenario 1: recepción de notificación push/in-app** <br> *Given* que un banco aprueba y emite una oferta crediticia para el usuario <br> *When* la oferta se procesa en el sistema <br> *Then* el usuario recibe una notificación en tiempo real con los detalles clave (tasa, frecuencia, etc.) <br> |
| US11 | E04 | Como usuario, quiero visualizar el cronograma de pagos detallado del crédito ofrecido, para planificar mis finanzas con precisión. | **Scenario 1: generación correcta del cronograma** <br> *Given* que el usuario abre los detalles de la oferta de crédito recibida <br> *When* navega a la sección de pagos <br> *Then* el sistema despliega una tabla con las fechas de vencimiento, amortización, interés y saldo restante <br> |
| US12 | E04 | Como usuario, quiero descargar el cronograma de pagos en un archivo .xlsx, para revisarlo sin conexión o compartirlo fácilmente. | **Scenario 1: descarga exitosa del archivo Excel** <br> *Given* que el usuario está visualizando el cronograma de pagos <br> *When* hace clic en el botón de descargar archivo .xlsx <br> *Then* el sistema genera y descarga automáticamente el documento de Excel formateado correctamente <br> |
| US13 | E05 | Como usuario, quiero utilizar una barra de búsqueda en el aplicativo, para localizar inmuebles específicos de manera rápida. | **Scenario 1: búsqueda con resultados coincidentes** <br> *Given* que el usuario ingresa un término o palabra clave en la barra de búsqueda <br> *When* presiona buscar o escribe <br> *Then* el sistema muestra un listado con todos los inmuebles que coinciden con la búsqueda <br> **Scenario 2: búsqueda sin resultados** <br> *Given* que el usuario busca un término que no existe en la plataforma <br> *When* ejecuta la búsqueda <br> *Then* el sistema muestra un mensaje indicando que no se encontraron coincidencias <br> |
| US14 | E05 | Como usuario, quiero buscar inmuebles utilizando filtros por tags, para encontrar propiedades que se adapten a mis preferencias específicas. | **Scenario 1: filtrado exitoso por tags** <br> *Given* que el usuario selecciona uno o varios tags (ej. "con terraza", "estacionamiento") <br> *When* aplica los filtros en la búsqueda <br> *Then* el sistema reduce la lista y muestra solo los inmuebles que cumplen con todas las etiquetas seleccionadas <br> |
| US15 | E05 | Como usuario, quiero interactuar con una IA de apoyo en la búsqueda, para recibir recomendaciones personalizadas y resolver dudas sobre los inmuebles. | **Scenario 1: consulta exitosa a la IA** <br> *Given* que el usuario abre el chat de asistencia de la IA <br> *When* redacta una consulta sobre qué inmuebles le convienen según su crédito <br> *Then* la IA analiza los datos y le responde con sugerencias precisas y enlaces a las propiedades <br> |
| US16 | E06 | Como usuario, quiero utilizar un sistema de mensajería integrado, para comunicarme directamente con los bancos o propietarios de los inmuebles. | **Scenario 1: envío y recepción de mensajes en tiempo real** <br> *Given* que el usuario inicia un chat desde la ficha de un inmueble <br> *When* escribe y envía un mensaje al propietario o banco <br> *Then* el mensaje se entrega instantáneamente y se visualiza correctamente en la ventana de chat <br> |
| US17 | E06 | Como usuario, quiero tener la opción de bloquear a otros usuarios en la mensajería, para evitar comunicaciones no deseadas o molestas. | **Scenario 1: bloqueo exitoso de un contacto** <br> *Given* que el usuario está dentro de una conversación activa <br> *When* selecciona la opción de bloquear a ese usuario y confirma la acción <br> *Then* el sistema restringe el envío de nuevos mensajes por parte de ese contacto y oculta el chat <br> |
| US18 | E06 | Como usuario, quiero descargar el historial de una conversación en un botón dedicado, para mantener un respaldo de los acuerdos o charlas sostenidas. | **Scenario 1: descarga completa del historial de chat** <br> *Given* que el usuario está revisando una conversación <br> *When* hace clic en el botón de descargar conversación <br> *Then* el sistema procesa el chat y genera un archivo descargable con todo el texto cronológico <br> |


## 3.3. Impact Map

El mapa conecta objetivos de negocio, cambios deseados en el comportamiento de las proto-personas y entregables propuestos. Se basa en las hipótesis del capítulo I y los escenarios de 3.1. Las metas son propuestas para medir después del lanzamiento o piloto; no son resultados obtenidos ni compromisos cuya viabilidad ya esté demostrada.

### Objetivos de negocio propuestos

| ID | Objetivo medible y plazo | Medición propuesta | Relación con el capítulo I |
|---|---|---|---|
| BG-01 | Lograr que al menos el 25% de compradores que completen una simulación soliciten continuar con una evaluación durante el cuarto mes desde el lanzamiento. | Compradores únicos con simulación completa y solicitud de continuación / compradores únicos con simulación completa en ese mes × 100. Si no hay casos, informar «sin datos». | H1: conversión de simulación a solicitud. Solicitar evaluación no equivale a obtener crédito. |
| BG-02 | Conseguir que al menos el 70% de compradores recurrentes compare dos o más escenarios durante el cuarto mes desde el lanzamiento. | Compradores recurrentes que comparan escenarios / compradores recurrentes del mes × 100. Se define recurrente como quien utiliza la plataforma en dos o más días distintos del mes. | H3: uso de comparación antes de decidir. El plazo y la definición operativa se proponen para esta medición. |
| BG-03 | Alcanzar un tiempo mediano inferior a cinco minutos para preparar y emitir una cotización referencial completa al finalizar el tercer mes del piloto con asesores. | Medir desde que están disponibles los datos requeridos hasta emitir la cotización; reportar mediana, número de tareas, errores e intentos incompletos. La rapidez solo se considera junto con la revisión de integridad de la propuesta. | H2: agilizar cotizaciones. El plazo y la mediana son propuestas; la referencia de 45 minutos necesita una medición inicial real. |

Las metas tienen actor, comportamiento, umbral y plazo definidos. Su factibilidad y los tamaños de muestra se revisarán con el equipo y el piloto. Los indicadores solo se calcularán a partir de observaciones o eventos reales.

### Actores, impactos y entregables

| Business Goal | Actor / Persona | Impacto: cambio esperado de comportamiento | Entregable propuesto | User Stories |
|---|---|---|---|---|
| BG-01 | Lucía — Comprador | Comprende los pagos y distingue simulación de evaluación antes de solicitar el siguiente paso. | D-01: resumen explicable de cuota, seguros, gastos y cronograma; D-02: solicitud de continuación asociada al escenario elegido. | Vinculación pendiente con las historias definitivas de 3.2. |
| BG-02 | Lucía — Comprador | Contrasta alternativas con supuestos visibles y recupera sus opciones antes de decidir. | D-03: comparación de monto, moneda, plazo y costos; D-04: conservación y recuperación de escenarios. | Vinculación pendiente con las historias definitivas de 3.2. |
| BG-03 | Daniel — Asesor inmobiliario | Reutiliza información y revisa parámetros antes de emitir la cotización. | D-05: preparación de cotizaciones con reutilización de datos y procedencia de parámetros. | Vinculación pendiente con las historias definitivas de 3.2. |
| BG-03 | Daniel — Asesor inmobiliario | Explica y comparte una versión reconocible para evitar reconstruir la propuesta. | D-06: cotización exportable con versión, autor, fecha y condiciones. | Vinculación pendiente con las historias definitivas de 3.2. |

```mermaid
flowchart LR
    G1["BG-01: 25% solicita continuar en el mes 4"] --> A1["Lucía · Comprador"]
    A1 --> I1["Comprende pagos y solicita el siguiente paso"]
    I1 --> D1["D-01: resumen y cronograma explicables"]
    I1 --> D2["D-02: solicitud ligada al escenario"]
    G2["BG-02: 70% compara en el mes 4"] --> A2["Lucía · Comprador"]
    A2 --> I2["Contrasta y recupera alternativas"]
    I2 --> D3["D-03: comparación con supuestos visibles"]
    I2 --> D4["D-04: escenarios guardados"]
    G3["BG-03: mediana menor de 5 min al mes 3 del piloto"] --> A3["Daniel · Asesor inmobiliario"]
    A3 --> I3["Reutiliza datos y verifica parámetros"]
    A3 --> I4["Explica y comparte una versión identificada"]
    I3 --> D5["D-05: preparación de cotizaciones"]
    I4 --> D6["D-06: exportación identificada"]
```

**Estado del entregable:** la estructura anterior es un borrador local. Falta trasladar el mapa a UXPressia utilizando las fichas de personas, incorporar la captura y añadir los IDs y descripciones de User Stories en formato «Como… deseo… para…» cuando el trabajo de 3.2 esté disponible. Los identificadores D-01 a D-06 representan entregables del mapa y no sustituyen los IDs de historias.

## 3.4. Product Backlog

**Estado:** se prepara el método y la estructura del backlog. Las historias se están desarrollando en 3.2; la lista priorizada y sus estimaciones se incorporarán después de acordar ese catálogo.

**Priorización propuesta:** ordenar las historias por el valor que aportan a BG-01, BG-02 y BG-03, considerando la tarea que resuelven, el alcance de su beneficio y sus dependencias. Primero se evaluará el flujo que permite obtener y comprender una simulación; luego su comparación, recuperación y uso en cotizaciones. Este orden de capacidades es preliminar y no asigna prioridad definitiva a historias aún no disponibles. Seguridad y autenticación se tratarán como requisitos transversales y dependencias técnicas; no se colocarán automáticamente al inicio solo por ser infraestructura, conforme a la guía.

**Estimación propuesta:** el equipo estimará esfuerzo relativo con Story Points de la escala `1, 2, 3, 5, 8`, considerando complejidad, incertidumbre e integración. Se elegirá una historia entendida por todos como referencia, se compararán las demás y se dividirán las que excedan ocho puntos. Los puntos no equivalen a horas ni se asignarán hasta revisar los criterios de aceptación.

**Estructura de la tabla exigida por la guía:**

| # Orden | User Story ID | Título | Descripción | Story Points (1 / 2 / 3 / 5 / 8) |
|---|---|---|---|---|

La tabla se completará con IDs y descripciones de 3.2, evitando duplicar o renombrar las historias de forma independiente. Para cada historia se comprobará su relación con un entregable del Impact Map, sus criterios de aceptación y las dependencias que condicionan su ejecución. El estado y el Sprint se podrán registrar como campos adicionales en la herramienta de gestión.

| Orden | ID | User Story | Prioridad MoSCoW | Sprint |
|---|---|---|---|---|
| 1 | US01 | Como usuario, quiero utilizar mi correo y contraseña, para ingresar a mi cuenta. | Must | Sprint 1 |
| 2 | US05 | Como usuario, quiero seleccionar entre diversos procesadores de pago, para realizar la transacción con mi método preferido. | Must | Sprint 1 |
| 3 | US07 | Como usuario, quiero registrar un bien inmobiliario, para guardarlo en mi cuenta y gestionar sus detalles. | Must | Sprint 1 |
| 4 | US13 | Como usuario, quiero utilizar una barra de búsqueda en el aplicativo, para localizar inmuebles específicos de manera rápida. | Must | Sprint 1 |
| 5 | US16 | Como usuario, quiero utilizar un sistema de mensajería integrado, para comunicarme directamente con los bancos o propietarios de los inmuebles. | Must | Sprint 1 |
| 6 | US02 | Como usuario, quiero modificar los datos de mi perfil, para mantener mi información actualizada. | Should | Sprint 2 |
| 7 | US03 | Como usuario, quiero habilitar la autenticación de dos pasos, para añadir una capa extra de seguridad a mi cuenta. | Should | Sprint 2 |
| 8 | US04 | Como usuario, quiero cerrar mi sesión activa, para proteger mi cuenta al dejar de usar la plataforma. | Must | Sprint 2 |
| 9 | US08 | Como usuario, quiero eliminar un bien inmobiliario ya registrado, para quitar de mi lista las propiedades que ya no poseo. | Should | Sprint 2 |
| 10 | US10 | Como usuario, quiero recibir una notificación inmediata cuando un banco me ofrezca un crédito, para enterarme al instante de las oportunidades disponibles. | Should | Sprint 2 |
| 11 | US11 | Como usuario, quiero visualizar el cronograma de pagos detallado del crédito ofrecido, para planificar mis finanzas con precisión. | Should | Sprint 2 |
| 12 | US14 | Como usuario, quiero buscar inmuebles utilizando filtros por tags, para encontrar propiedades que se adapten a mis preferencias específicas. | Should | Sprint 2 |
| 13 | US06 | Como usuario, quiero verificar el estado de mi pago, para confirmar que mi suscripción está activa. | Should | Sprint 3 |
| 14 | US09 | Como usuario, quiero verificar la legitimidad de mi bien inmobiliario, para demostrar que es un inmueble genuino y legal. | Should | Sprint 3 |
| 15 | US12 | Como usuario, quiero descargar el cronograma de pagos en un archivo .xlsx, para revisarlo sin conexión o compartirlo fácilmente. | Could | Sprint 3 |
| 16 | US15 | Como usuario, quiero interactuar con una IA de apoyo en la búsqueda, para recibir recomendaciones personalizadas y resolver dudas sobre los inmuebles. | Could | Sprint 3 |
| 17 | US17 | Como usuario, quiero tener la opción de bloquear a otros usuarios en la mensajería, para evitar comunicaciones no deseadas o molestas. | Could | Sprint 3 |
| 18 | US18 | Como usuario, quiero descargar el historial de una conversación en un botón dedicado, para mantener un respaldo de los acuerdos o charlas sostenidas. | Could | Sprint 3 |


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

![CrediCasa Archi Model](Resources/avance-1/archi_model_AV1.png)

## Links

| Descripción | Enlace |
|---|---|
| Repositorio del Reporte | [Abrir repositorio](https://github.com/FidiaCorp/upc-pre-202620-1ASI0657-15987-FidiaCorp-report) |