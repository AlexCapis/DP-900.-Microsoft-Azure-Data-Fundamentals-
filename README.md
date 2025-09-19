# 📘 Preguntas prácticas sobre Microsoft Azure Data Fundamentals (DP-900)

Repositorio con preguntas y respuestas del examen **Microsoft Azure Data Fundamentals (DP-900)** en español.  
El objetivo es proporcionar un recurso de práctica y repaso a quienes buscan certificarse.

---

## 🎯 Sobre la certificación

La certificación **Microsoft Azure Data Fundamentals (DP-900)** valida conocimientos básicos en:

- Conceptos principales de **datos** y **análisis de datos**.  
- **Modelos de datos relacionales** y **no relacionales**.  
- Servicios de datos disponibles en **Microsoft Azure**.  
- Fundamentos de **almacenamiento en la nube**, **ETL/ELT** y **análisis en tiempo real**.  
- Herramientas como **Power BI, Azure Synapse, Azure Cosmos DB, Azure Data Factory y Databricks**.  

Más info oficial 👉 [Microsoft Certified: Azure Data Fundamentals](https://learn.microsoft.com/certifications/exams/dp-900)

---

## 📝 Consejos de estudio

- Comprende la diferencia entre **OLTP y OLAP**.  
- Estudia los niveles de acceso de **Azure Blob Storage** y sus escenarios de uso.  
- Aprende los principios de **ACID** y los distintos modelos de consistencia en **Cosmos DB**.  
- Familiarízate con los **formatos de datos**: JSON, CSV, Parquet, Avro, Delta.  
- Practica con **Power BI**: modos de conexión, RLS, Incremental Refresh, Q&A.  
- Revisa los servicios de **integración y orquestación**: Azure Data Factory, Event Hubs, Event Grid, Functions.  

---

## 📑 Preguntas y respuestas (1–100)

Las respuestas están ocultas y se despliegan al hacer clic en **“Mostrar respuesta”**.



### Pregunta 1
¿Cuál es el **modelo de consistencia** predeterminado más estricto disponible en Azure Cosmos DB?

- A. Eventual  
- B. Sesión  
- C. Delimitada por prefijo  
- D. Fuerte  

<details>
<summary>✅ Mostrar respuesta</summary>
D. Fuerte
</details>

---

### Pregunta 2
En Azure Storage, ¿qué opción **minimiza el costo de almacenamiento** para datos que rara vez se leen, pero **aumenta el costo de acceso**?

- A. Nivel de acceso Frecuente (Hot)  
- B. Nivel de acceso Esporádico (Cool)  
- C. Nivel de acceso Archivo (Archive)  
- D. Premium SSD  

<details>
<summary>✅ Mostrar respuesta</summary>
C. Nivel de acceso Archivo (Archive)
</details>

---

### Pregunta 3
¿Cuál de las siguientes API de Azure Cosmos DB está diseñada para aplicaciones que necesitan **consultas SQL-like sobre documentos**?

- A. API para Table  
- B. API para Gremlin  
- C. API para NoSQL  
- D. API para Cassandra  

<details>
<summary>✅ Mostrar respuesta</summary>
C. API para NoSQL
</details>

---

### Pregunta 4
Quieres almacenar **mensajes para desacoplar microservicios** y consumirlos en orden FIFO. ¿Qué servicio de Azure elegirías?

- A. Azure Queue Storage  
- B. Azure Files  
- C. Azure Table Storage  
- D. Azure Blob Storage  

<details>
<summary>✅ Mostrar respuesta</summary>
A. Azure Queue Storage
</details>

---

### Pregunta 5
En un **esquema en estrella**, ¿qué característica distingue a la **tabla de hechos**?

- A. Guarda jerarquías de calendario y geografía  
- B. Contiene medidas numéricas y claves foráneas  
- C. Almacena sólo datos de texto  
- D. No participa en relaciones  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Contiene medidas numéricas y claves foráneas
</details>

---

### Pregunta 6
¿Cuál es el **propósito principal** de la normalización en una base de datos relacional?

- A. Acelerar informes de BI  
- B. Reducir redundancia y anomalías de actualización  
- C. Cifrar datos en descanso  
- D. Habilitar particiones horizontales  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Reducir redundancia y anomalías de actualización
</details>

---

### Pregunta 7
¿Qué servicio de Azure permite **procesamiento de flujos** de eventos en tiempo real con **consulta SQL**?

- A. Azure Data Factory  
- B. Azure Stream Analytics  
- C. Azure Databricks  
- D. Azure Synapse Pipelines  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Azure Stream Analytics
</details>

---

### Pregunta 8
Necesitas **versionado** y **ramas** para el código de canalizaciones de datos y notebooks. ¿Qué usarías?

- A. Azure DevOps Repos / Git  
- B. Azure Key Vault  
- C. Azure Monitor  
- D. Azure Purview (Microsoft Purview)  

<details>
<summary>✅ Mostrar respuesta</summary>
A. Azure DevOps Repos / Git
</details>

---

### Pregunta 9
¿Qué formato **columno-orientado** es ideal para **consultas analíticas** en lago de datos por su compresión y “predicate pushdown”?

- A. JSON  
- B. CSV  
- C. Parquet  
- D. XML  

<details>
<summary>✅ Mostrar respuesta</summary>
C. Parquet
</details>

---

### Pregunta 10
En Power BI, ¿qué componente **conecta y transforma** datos **antes** de cargarlos al modelo?

- A. Panel  
- B. Power Query  
- C. DAX  
- D. Gateway de datos local  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Power Query
</details>

---

### Pregunta 11
¿Cuál es una ventaja clave de **Azure SQL Managed Instance** sobre una base de datos única de Azure SQL?

- A. Soporta API Gremlin  
- B. Mayor compatibilidad con características de SQL Server local  
- C. Es un servicio sin servidor exclusivamente  
- D. Sólo permite autenticación SQL  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Mayor compatibilidad con características de SQL Server local
</details>

---

### Pregunta 12
¿Qué **tipo de clave** garantiza la **unicidad por fila** en una tabla relacional?

- A. Clave externa  
- B. Clave primaria  
- C. Índice no agrupado  
- D. Índice de texto completo  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Clave primaria
</details>

---

### Pregunta 13
Para **ingestión masiva** desde diferentes orígenes SaaS hacia un lago de datos con orquestación visual, ¿qué servicio usarías?

- A. Azure Data Factory  
- B. Azure Functions  
- C. Azure Files  
- D. Azure Cache for Redis  

<details>
<summary>✅ Mostrar respuesta</summary>
A. Azure Data Factory
</details>

---

### Pregunta 14
En Cosmos DB, ¿cuál es la **unidad de escalado** que define el rendimiento aprovisionado?

- A. DTU  
- B. RU/s (Request Units por segundo)  
- C. vCore  
- D. IOPS  

<details>
<summary>✅ Mostrar respuesta</summary>
B. RU/s (Request Units por segundo)
</details>

---

### Pregunta 15
¿Cuál afirmación describe mejor **OLTP**?

- A. Cargas masivas con agregaciones históricas  
- B. Transacciones cortas y frecuentes con muchas escrituras pequeñas  
- C. Consultas complejas de exploración multidimensional  
- D. Procesamiento por lotes nocturnos exclusivamente  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Transacciones cortas y frecuentes con muchas escrituras pequeñas
</details>

---

### Pregunta 16
¿Qué servicio usarías para **catálogo y linaje** de datos en Azure?

- A. Azure Monitor  
- B. Microsoft Purview  
- C. Azure Sentinel  
- D. Azure Policy  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Microsoft Purview
</details>

---

### Pregunta 17
¿Cuál es el **beneficio** de usar **particiones** en una tabla grande de un almacén relacional (p. ej., Azure Synapse Dedicated SQL Pool)?

- A. Evitar backups  
- B. Paralelismo y poda de particiones para acelerar consultas  
- C. Cifrado automático de columnas  
- D. Habilitar DAX en el motor relacional  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Paralelismo y poda de particiones para acelerar consultas
</details>

---

### Pregunta 18
Para **orquestar** un flujo ELT que ejecute notebooks Spark en un workspace, ¿qué combinación es más directa?

- A. Azure Databricks + Jobs/Workflows  
- B. Azure Queue Storage + Functions  
- C. Azure Monitor + Log Analytics  
- D. Azure Files + WebJobs  

<details>
<summary>✅ Mostrar respuesta</summary>
A. Azure Databricks + Jobs/Workflows
</details>

---

### Pregunta 19
¿Cuál es una **desventaja típica** de los formatos **CSV** frente a Parquet en análisis a gran escala?

- A. Demasiado compacto  
- B. Sin esquema y sin compresión columnar  
- C. No compatible con Power BI  
- D. No se puede abrir en Excel  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Sin esquema y sin compresión columnar
</details>

---

### Pregunta 20
En Power BI, ¿qué se usa para crear **medidas** y **cálculos** sobre el modelo tabular?

- A. M (lenguaje de Power Query)  
- B. DAX  
- C. T-SQL  
- D. Python nativo del servicio  

<details>
<summary>✅ Mostrar respuesta</summary>
B. DAX
</details>

---

### Pregunta 21
¿Qué **característica de seguridad** protege secretos como cadenas de conexión en soluciones de datos?

- A. Azure Key Vault  
- B. Azure Repos  
- C. Azure Bastion  
- D. Azure Advisor  

<details>
<summary>✅ Mostrar respuesta</summary>
A. Azure Key Vault
</details>

---

### Pregunta 22
Para **ingestar millones de eventos por segundo** desde dispositivos IoT, ¿qué servicio es el **punto de entrada** recomendado?

- A. Azure Event Hubs  
- B. Azure Queue Storage  
- C. Azure Service Bus Topics  
- D. Azure Files  

<details>
<summary>✅ Mostrar respuesta</summary>
A. Azure Event Hubs
</details>

---

### Pregunta 23
En ACID, la propiedad de **Coherencia** implica que:

- A. Una transacción confirmada sobreviva a fallos  
- B. Las transacciones no interfieren entre sí  
- C. El estado de la base de datos pasa de válido a válido  
- D. Todas las operaciones se ejecutan como una unidad indivisible  

<details>
<summary>✅ Mostrar respuesta</summary>
C. El estado de la base de datos pasa de válido a válido
</details>

---

### Pregunta 24
¿Qué característica **sin servidor** puede reducir costos en Azure SQL Database para cargas intermitentes?

- A. Zona de disponibilidad  
- B. Auto-pause y auto-scale con nivel Serverless  
- C. Replicación transaccional  
- D. Always Encrypted  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Auto-pause y auto-scale con nivel Serverless
</details>

---

### Pregunta 25
¿Cuál es el **propósito** de un **índice** en una base de datos relacional?

- A. Garantizar ACID  
- B. Acelerar búsquedas y filtros a costa de más escrituras  
- C. Cifrar filas  
- D. Generar informes paginados automáticamente  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Acelerar búsquedas y filtros a costa de más escrituras
</details>

---

### Pregunta 26
¿Qué **formato de mensajería** binario orientado a esquemas se usa frecuentemente junto a Kafka/Event Hubs?

- A. Avro  
- B. CSV  
- C. YAML  
- D. TXT  

<details>
<summary>✅ Mostrar respuesta</summary>
A. Avro
</details>

---

### Pregunta 27
En Cosmos DB, ¿qué **estrategia de partición** suele dar mejor distribución para datos transaccionales?

- A. Particionar por fecha fija  
- B. Usar una **clave de partición** con alta cardinalidad y acceso uniforme  
- C. Poner toda la colección en una partición  
- D. Particionar por tamaño de documento  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Usar una clave de partición con alta cardinalidad y acceso uniforme
</details>

---

### Pregunta 28
Para exponer datos del lago como **tablas externas** consultables con T-SQL, ¿qué usarías en Synapse?

- A. Pipelines  
- B. Serverless SQL pool (OPENROWSET/EXTERNAL TABLE)  
- C. Power BI dataset  
- D. Managed Instance  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Serverless SQL pool (OPENROWSET/EXTERNAL TABLE)
</details>

---

### Pregunta 29
¿Cuál es el **rol** responsable de construir **modelos de aprendizaje automático** y experimentar con datos?

- A. Administrador de base de datos  
- B. Científico de datos  
- C. Ingeniero de datos  
- D. Analista financiero  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Científico de datos
</details>

---

### Pregunta 30
En Power BI Service, ¿qué se necesita para **actualizar** datos locales en un dataset importado de SQL Server **on-premises**?

- A. Dataflow premium  
- B. Gateway de datos local (On-premises Data Gateway)  
- C. ADF Self-Hosted IR  
- D. Key Vault  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Gateway de datos local (On-premises Data Gateway)
</details>

### Pregunta 31
¿Cuál es una ventaja clave de **Azure Synapse Serverless SQL pool** frente a Dedicated SQL pool?

- A. Indizado automático de tablas internas  
- B. Pago por consulta sobre datos del lago sin aprovisionar clúster  
- C. Soporte de transacciones de larga duración  
- D. Requiere crear particiones físicas

<details>
<summary>✅ Mostrar respuesta</summary>
B. Pago por consulta sobre datos del lago sin aprovisionar clúster
</details>

---

### Pregunta 32
Para habilitar permisos tipo POSIX y jerarquía de carpetas en un lago de datos de Azure, debe activar:

- A. Versionado de blobs  
- B. **Hierarchical Namespace** (ADLS Gen2)  
- C. Inmutabilidad de contenedor  
- D. Snapshots de blob

<details>
<summary>✅ Mostrar respuesta</summary>
B. Hierarchical Namespace (ADLS Gen2)
</details>

---

### Pregunta 33
¿Qué formato de almacenamiento añade **transacciones ACID** y **time travel** sobre archivos en el lago?

- A. CSV  
- B. Delta Lake  
- C. Avro  
- D. ORC

<details>
<summary>✅ Mostrar respuesta</summary>
B. Delta Lake
</details>

---

### Pregunta 34
Necesitas **telemetría de dispositivos** a muy alta tasa de ingreso con retención corta y procesamiento en stream. ¿Qué combinación es más adecuada?

- A. Service Bus + Logic Apps  
- B. Event Hubs + Stream Analytics  
- C. Queue Storage + Functions  
- D. Synapse Pipelines + SQL pool

<details>
<summary>✅ Mostrar respuesta</summary>
B. Event Hubs + Stream Analytics
</details>

---

### Pregunta 35
¿Qué opción de **redundancia** mantiene tres copias en una **única región**?

- A. GRS  
- B. RA-GRS  
- C. LRS  
- D. GZRS

<details>
<summary>✅ Mostrar respuesta</summary>
C. LRS
</details>

---

### Pregunta 36
Para **recuperar archivos eliminados accidentalmente** en Blob Storage dentro de un período configurado, habilite:

- A. Legal hold  
- B. Soft delete para blobs  
- C. Rehidratación prioritaria  
- D. Versionado a nivel de cuenta

<details>
<summary>✅ Mostrar respuesta</summary>
B. Soft delete para blobs
</details>

---

### Pregunta 37
Quiere compartir acceso temporal a un contenedor de blobs **sin entregar la clave de cuenta**. ¿Qué usar?

- A. SAS (Shared Access Signature)  
- B. RBAC únicamente  
- C. Firewall de Storage  
- D. Private Endpoint solamente

<details>
<summary>✅ Mostrar respuesta</summary>
A. SAS (Shared Access Signature)
</details>

---

### Pregunta 38
¿Qué característica **aísla** el tráfico de un recurso de almacenamiento dentro de una VNet usando IP privadas?

- A. Service Endpoints  
- B. Private Endpoints  
- C. Application Gateway  
- D. NAT Gateway

<details>
<summary>✅ Mostrar respuesta</summary>
B. Private Endpoints
</details>

---

### Pregunta 39
En Power BI, ¿qué modo **evita importar datos** y consulta en vivo la fuente?

- A. Import  
- B. DirectQuery  
- C. Live Connection para Excel  
- D. Datamarts

<details>
<summary>✅ Mostrar respuesta</summary>
B. DirectQuery
</details>

---

### Pregunta 40
¿Qué característica de Power BI permite **definir agregaciones** en tablas grandes para acelerar DirectQuery?

- A. Incremental refresh  
- B. Composite models  
- C. Aggregations  
- D. Query folding

<details>
<summary>✅ Mostrar respuesta</summary>
C. Aggregations
</details>

---

### Pregunta 41
Para **restringir filas por usuario** dentro de un informe de Power BI, use:

- A. Column Encryption  
- B. Row-Level Security (RLS)  
- C. Sensitivity labels  
- D. Conditional formatting

<details>
<summary>✅ Mostrar respuesta</summary>
B. Row-Level Security (RLS)
</details>

---

### Pregunta 42
¿Qué beneficio ofrece **Incremental Refresh** en Power BI?

- A. Cálculos DAX más rápidos por GPU  
- B. Carga únicamente de particiones nuevas/modificadas  
- C. Exportación automática a CSV  
- D. Evita gateways on-prem

<details>
<summary>✅ Mostrar respuesta</summary>
B. Carga únicamente de particiones nuevas/modificadas
</details>

---

### Pregunta 43
En un modelo **estrella**, una **tabla de dimensiones** típicamente contiene:

- A. Medidas numéricas densas  
- B. Descripciones, jerarquías y atributos de negocio  
- C. Sólo claves sustitutas incrementales  
- D. Datos no normalizados prohibidos

<details>
<summary>✅ Mostrar respuesta</summary>
B. Descripciones, jerarquías y atributos de negocio
</details>

---

### Pregunta 44
¿Cuál **nivel de aislamiento** en SQL Server evita lecturas sucias, pero permite lecturas no repetibles?

- A. READ UNCOMMITTED  
- B. READ COMMITTED  
- C. SERIALIZABLE  
- D. SNAPSHOT

<details>
<summary>✅ Mostrar respuesta</summary>
B. READ COMMITTED
</details>

---

### Pregunta 45
En Azure Cosmos DB, ¿qué característica expone **cambios en orden** para disparar procesos aguas abajo?

- A. Time to Live  
- B. Change Feed  
- C. Multi-region writes  
- D. Stored Procedures

<details>
<summary>✅ Mostrar respuesta</summary>
B. Change Feed
</details>

---

### Pregunta 46
¿Cuál es una razón para usar **Azure Service Bus Topics** en lugar de Event Hubs?

- A. Ingesta masiva de telemetría  
- B. Patrón **pub/sub** con filtrado por suscripción y garantías de entrega empresarial  
- C. Rehidratación de archivos  
- D. Almacenamiento jerárquico

<details>
<summary>✅ Mostrar respuesta</summary>
B. Patrón pub/sub con filtrado por suscripción y garantías de entrega empresarial
</details>

---

### Pregunta 47
¿Qué tipo de **índice** relacional es más adecuado para **cargas analíticas** con columnas anchas y escaneos grandes?

- A. B-Tree no agrupado  
- B. Hash index  
- C. Columnstore index  
- D. XML index

<details>
<summary>✅ Mostrar respuesta</summary>
C. Columnstore index
</details>

---

### Pregunta 48
Para capturar inserciones y cambios fila a fila en SQL y procesarlos aguas abajo, se recomienda:

- A. CDC (Change Data Capture)  
- B. Always On AG  
- C. Replicación de mezcla  
- D. Log shipping

<details>
<summary>✅ Mostrar respuesta</summary>
A. CDC (Change Data Capture)
</details>

---

### Pregunta 49
En Power BI, ¿qué diferencia principal hay entre **medida** y **columna calculada**?

- A. La medida se evalúa en tiempo de consulta, la columna al refrescar el modelo  
- B. La columna admite filtros, la medida no  
- C. La medida se almacena en disco, la columna no  
- D. No hay diferencias

<details>
<summary>✅ Mostrar respuesta</summary>
A. La medida se evalúa en tiempo de consulta, la columna al refrescar el modelo
</details>

---

### Pregunta 50
¿Qué servicio de Azure proporciona **notebooks Spark colaborativos** y gestión de trabajos ELT/ML a escala?

- A. Azure Databricks  
- B. Azure Functions  
- C. Azure Batch  
- D. Azure App Service

<details>
<summary>✅ Mostrar respuesta</summary>
A. Azure Databricks
</details>

---

### Pregunta 51
En Cosmos DB, la opción **multi-master (multi-region writes)** permite:

- A. Capacidad de RU/s sin límites  
- B. Escrituras en varias regiones con convergencia mediante conflictos  
- C. Transacciones distribuidas 2PC  
- D. Eliminación de la partición lógica

<details>
<summary>✅ Mostrar respuesta</summary>
B. Escrituras en varias regiones con convergencia mediante conflictos
</details>

---

### Pregunta 52
¿Cuál es el **uso típico** de una **tabla temporal** (System-Versioned Temporal Table) en SQL Server?

- A. Controlar acceso por rol  
- B. Mantener historial automático de cambios por fila  
- C. Acelerar JOINs  
- D. Reemplazar vistas indexadas

<details>
<summary>✅ Mostrar respuesta</summary>
B. Mantener historial automático de cambios por fila
</details>

---

### Pregunta 53
¿Qué componente de ADF permite **programar** la ejecución de una canalización?

- A. Linked Service  
- B. Dataset  
- C. Trigger  
- D. Integration Runtime

<details>
<summary>✅ Mostrar respuesta</summary>
C. Trigger
</details>

---

### Pregunta 54
Para **automatizar** el procesamiento al cargarse un nuevo archivo en un contenedor de blobs, ¿qué elegir?

- A. Azure Function con **trigger de Blob**  
- B. App Service plan Free  
- C. Azure DNS  
- D. Azure Automation Update Management

<details>
<summary>✅ Mostrar respuesta</summary>
A. Azure Function con trigger de Blob
</details>

---

### Pregunta 55
¿Cuál es un **beneficio principal** de **Composite Models** en Power BI?

- A. Permiten conectar a múltiples workspaces a la vez  
- B. Combinan tablas Import con otras DirectQuery en el mismo modelo  
- C. Ejecutan DAX en la base de datos origen  
- D. Evitan crear relaciones

<details>
<summary>✅ Mostrar respuesta</summary>
B. Combinan tablas Import con otras DirectQuery en el mismo modelo
</details>

---

### Pregunta 56
En Azure Files, ¿qué protocolo permite montajes desde Linux sin SMB?

- A. NFS  
- B. FTP  
- C. SFTP  
- D. WebDAV

<details>
<summary>✅ Mostrar respuesta</summary>
A. NFS
</details>

---

### Pregunta 57
¿Qué política en Blob Storage impide modificar o borrar datos durante un periodo por **cumplimiento**?

- A. Soft delete  
- B. Retención de versiones  
- C. **Immutability Policy** (WORM) / Legal Hold  
- D. Lifecycle Management

<details>
<summary>✅ Mostrar respuesta</summary>
C. Immutability Policy (WORM) / Legal Hold
</details>

---

### Pregunta 58
En Cosmos DB (API NoSQL), la propiedad **TTL** en un contenedor sirve para:

- A. Definir el tamaño máximo de un documento  
- B. Expirar automáticamente elementos transcurrido un tiempo  
- C. Cambiar el nivel de consistencia por elemento  
- D. Desactivar el change feed

<details>
<summary>✅ Mostrar respuesta</summary>
B. Expirar automáticamente elementos transcurrido un tiempo
</details>

---

### Pregunta 59
¿Cuál es el **tipo de relación** más común entre una tabla de hechos y una de dimensiones en modelos tabulares?

- A. Muchos a muchos  
- B. Uno a uno  
- C. Uno a muchos (de dimensión a hechos)  
- D. Autorelación

<details>
<summary>✅ Mostrar respuesta</summary>
C. Uno a muchos (de dimensión a hechos)
</details>

---

### Pregunta 60
Para **migrar** cargas de trabajo OLTP con **mínimo cambio de código T-SQL** desde SQL Server local a PaaS, la mejor opción es:

- A. Azure SQL Managed Instance  
- B. Azure Database for PostgreSQL  
- C. Azure Cosmos DB for MongoDB  
- D. Azure Synapse Dedicated SQL pool

<details>
<summary>✅ Mostrar respuesta</summary>
A. Azure SQL Managed Instance
</details>

### Pregunta 61
¿Qué método de ingesta en Synapse Analytics permite **procesar datos en tiempo casi real** desde Event Hubs?

- A. PolyBase  
- B. COPY INTO  
- C. Streaming ingestion  
- D. Bulk insert

<details>
<summary>✅ Mostrar respuesta</summary>
C. Streaming ingestion
</details>

---

### Pregunta 62
En un clúster Spark de Azure Databricks, ¿qué componente ejecuta los **trabajos distribuidos** sobre los nodos?

- A. Driver  
- B. Worker  
- C. Resource Manager  
- D. Catalog

<details>
<summary>✅ Mostrar respuesta</summary>
A. Driver
</details>

---

### Pregunta 63
¿Cuál es un **ejemplo de datos no estructurados**?

- A. Tabla de clientes en SQL  
- B. Archivo JSON con registros de logs  
- C. Video MP4  
- D. Hoja de Excel con celdas tabulares

<details>
<summary>✅ Mostrar respuesta</summary>
C. Video MP4
</details>

---

### Pregunta 64
¿Qué **nivel de consistencia** en Cosmos DB garantiza lecturas monotónicas y ordenadas, pero con menor latencia que Strong?

- A. Eventual  
- B. Bounded Staleness  
- C. Consistent Prefix  
- D. Session

<details>
<summary>✅ Mostrar respuesta</summary>
C. Consistent Prefix
</details>

---

### Pregunta 65
¿Cuál es una **limitación** del nivel de acceso de **Archivo (Archive)** en Blob Storage?

- A. No permite recuperación  
- B. Solo puede usarse en Premium Storage  
- C. Requiere rehidratación antes de acceder a los datos  
- D. No admite blobs mayores a 100 MB

<details>
<summary>✅ Mostrar respuesta</summary>
C. Requiere rehidratación antes de acceder a los datos
</details>

---

### Pregunta 66
¿Qué característica de Power BI **detecta automáticamente relaciones** entre tablas al cargar datos?

- A. Auto-Detect Relationships  
- B. Quick Insights  
- C. Q&A Visual  
- D. Cross Filtering

<details>
<summary>✅ Mostrar respuesta</summary>
A. Auto-Detect Relationships
</details>

---

### Pregunta 67
Para **enviar mensajes ordenados y con entrega garantizada** entre microservicios, se recomienda:

- A. Azure Queue Storage  
- B. Azure Event Grid  
- C. Azure Service Bus Queue  
- D. Azure Notification Hubs

<details>
<summary>✅ Mostrar respuesta</summary>
C. Azure Service Bus Queue
</details>

---

### Pregunta 68
¿Qué opción de escalabilidad usa Cosmos DB para **dimensionar automáticamente** los RU/s?

- A. Dedicated Gateway  
- B. Multi-homing APIs  
- C. Autoscale throughput  
- D. Request Units Burst

<details>
<summary>✅ Mostrar respuesta</summary>
C. Autoscale throughput
</details>

---

### Pregunta 69
En un modelo en estrella, las **tablas de hechos** suelen contener:

- A. Jerarquías de producto  
- B. Descripciones textuales  
- C. Claves externas y medidas numéricas  
- D. Solo claves primarias naturales

<details>
<summary>✅ Mostrar respuesta</summary>
C. Claves externas y medidas numéricas
</details>

---

### Pregunta 70
¿Qué servicio de Azure permite **procesar archivos CSV y JSON** directamente desde Blob Storage con SQL sin crear tablas físicas?

- A. Synapse Serverless SQL pool  
- B. Azure Database for MySQL  
- C. Azure Cosmos DB  
- D. Azure SQL Database

<details>
<summary>✅ Mostrar respuesta</summary>
A. Synapse Serverless SQL pool
</details>

---

### Pregunta 71
¿Cuál es una característica principal de **Data Lakehouse**?

- A. Solo admite datos estructurados  
- B. Fusiona capacidades de Data Lake y Data Warehouse  
- C. No soporta machine learning  
- D. Solo puede usarse en SQL Server

<details>
<summary>✅ Mostrar respuesta</summary>
B. Fusiona capacidades de Data Lake y Data Warehouse
</details>

---

### Pregunta 72
¿Qué tipo de datos almacena mejor una **base de datos de serie temporal**?

- A. Relaciones jerárquicas  
- B. Eventos secuenciales con marca de tiempo  
- C. Datos de transacciones OLTP  
- D. Archivos de imágenes

<details>
<summary>✅ Mostrar respuesta</summary>
B. Eventos secuenciales con marca de tiempo
</details>

---

### Pregunta 73
¿Cuál es un **beneficio clave** de usar **ORC o Parquet** frente a CSV?

- A. Ocupan más espacio  
- B. No permiten compresión  
- C. Soportan esquemas columnar y compresión eficiente  
- D. Solo funcionan en Windows

<details>
<summary>✅ Mostrar respuesta</summary>
C. Soportan esquemas columnar y compresión eficiente
</details>

---

### Pregunta 74
En Power BI, ¿qué visualización es más adecuada para mostrar la proporción entre categorías?

- A. Tabla  
- B. Gráfico de barras  
- C. Gráfico de líneas  
- D. Gráfico de anillos

<details>
<summary>✅ Mostrar respuesta</summary>
D. Gráfico de anillos
</details>

---

### Pregunta 75
¿Qué característica de Azure Storage permite **proteger datos confidenciales** mediante cifrado administrado por Microsoft?

- A. SSE (Server-Side Encryption)  
- B. Blob Snapshots  
- C. RBAC  
- D. SAS Tokens

<details>
<summary>✅ Mostrar respuesta</summary>
A. SSE (Server-Side Encryption)
</details>

---

### Pregunta 76
¿Cuál es un escenario típico para usar **Azure Event Grid**?

- A. Analítica en tiempo real de telemetría  
- B. Procesar millones de mensajes por segundo  
- C. Disparar funciones serverless ante eventos como creación de un blob  
- D. Garantizar orden de entrega de mensajes

<details>
<summary>✅ Mostrar respuesta</summary>
C. Disparar funciones serverless ante eventos como creación de un blob
</details>

---

### Pregunta 77
¿Cuál de los siguientes servicios ofrece **exploración interactiva de datos con lenguaje natural** en Power BI?

- A. Q&A Visual  
- B. Row-level security  
- C. Power Automate  
- D. Drillthrough

<details>
<summary>✅ Mostrar respuesta</summary>
A. Q&A Visual
</details>

---

### Pregunta 78
¿Cuál es el **propósito de un índice clustered** en SQL Server?

- A. Permitir múltiples copias de los datos  
- B. Reordenar físicamente las filas de la tabla según la clave  
- C. Crear un hash de las columnas  
- D. Asegurar la unicidad de una columna

<details>
<summary>✅ Mostrar respuesta</summary>
B. Reordenar físicamente las filas de la tabla según la clave
</details>

---

### Pregunta 79
¿Qué formato de archivo en Azure Data Lake es más adecuado para **entrenar modelos de machine learning** por su eficiencia?

- A. JSON  
- B. Parquet  
- C. TXT  
- D. CSV

<details>
<summary>✅ Mostrar respuesta</summary>
B. Parquet
</details>

---

### Pregunta 80
¿Qué propiedad de **Eventual Consistency** en Cosmos DB puede ser una desventaja?

- A. Ofrece siempre lecturas más rápidas  
- B. Puede devolver lecturas obsoletas temporalmente  
- C. Requiere mayor latencia de escritura  
- D. Bloquea operaciones de escritura concurrentes

<details>
<summary>✅ Mostrar respuesta</summary>
B. Puede devolver lecturas obsoletas temporalmente
</details>

---

### Pregunta 81
¿Cuál de las siguientes es una **tarea principal de un ingeniero de datos**?

- A. Crear visualizaciones interactivas en Power BI  
- B. Definir modelos estadísticos avanzados  
- C. Construir canalizaciones de ingesta y transformación de datos  
- D. Administrar la seguridad de la base de datos

<details>
<summary>✅ Mostrar respuesta</summary>
C. Construir canalizaciones de ingesta y transformación de datos
</details>

---

### Pregunta 82
En Power BI, ¿qué característica permite **refrescar datos alojados en on-premises**?

- A. Gateway de datos local  
- B. DirectQuery  
- C. Incremental Refresh  
- D. AutoML

<details>
<summary>✅ Mostrar respuesta</summary>
A. Gateway de datos local
</details>

---

### Pregunta 83
¿Qué tipo de clave se utiliza en un **Data Warehouse** para enlazar tablas de hechos con dimensiones?

- A. Clave primaria natural  
- B. Clave sustituta (surrogate key)  
- C. Hash key  
- D. Foreign key virtual

<details>
<summary>✅ Mostrar respuesta</summary>
B. Clave sustituta (surrogate key)
</details>

---

### Pregunta 84
¿Cuál es el propósito principal de un **data mart**?

- A. Reemplazar al data warehouse completo  
- B. Proveer un subconjunto temático de datos para un área específica de negocio  
- C. Sustituir los lagos de datos  
- D. Procesar flujos de eventos en tiempo real

<details>
<summary>✅ Mostrar respuesta</summary>
B. Proveer un subconjunto temático de datos para un área específica de negocio
</details>

---

### Pregunta 85
¿Cuál es un caso de uso ideal para **Azure Queue Storage**?

- A. Streaming de IoT a gran escala  
- B. Comunicación simple asíncrona entre componentes con baja latencia  
- C. Replicación de archivos de gran tamaño  
- D. Consultas analíticas

<details>
<summary>✅ Mostrar respuesta</summary>
B. Comunicación simple asíncrona entre componentes con baja latencia
</details>

---

### Pregunta 86
¿Qué función cumple el **catálogo de datos (Data Catalog)** en un entorno analítico?

- A. Almacenar datos sin procesar  
- B. Gestionar la seguridad de la red  
- C. Documentar, clasificar y descubrir datasets  
- D. Acelerar cálculos DAX

<details>
<summary>✅ Mostrar respuesta</summary>
C. Documentar, clasificar y descubrir datasets
</details>

---

### Pregunta 87
¿Cuál de estas es una característica de **PolyBase** en Synapse?

- A. Crear dashboards  
- B. Consultar datos externos como si fueran tablas SQL  
- C. Ejecutar modelos predictivos en Python  
- D. Gestionar permisos de acceso

<details>
<summary>✅ Mostrar respuesta</summary>
B. Consultar datos externos como si fueran tablas SQL
</details>

---

### Pregunta 88
¿Cuál es un ejemplo de **datos semiestructurados**?

- A. Video MP4  
- B. Archivo JSON con registros de usuarios  
- C. Tabla normalizada en SQL  
- D. Imagen PNG

<details>
<summary>✅ Mostrar respuesta</summary>
B. Archivo JSON con registros de usuarios
</details>

---

### Pregunta 89
¿Qué servicio de Azure puede ejecutar **tareas ETL programadas sin servidores**?

- A. Azure Functions  
- B. Azure Synapse SQL pool  
- C. Azure Cosmos DB  
- D. Azure Monitor

<details>
<summary>✅ Mostrar respuesta</summary>
A. Azure Functions
</details>

---

### Pregunta 90
¿Qué opción de redundancia en Azure Storage mantiene copias en **tres zonas dentro de una misma región**?

- A. LRS  
- B. ZRS  
- C. GRS  
- D. RA-GRS  

<details>
<summary>✅ Mostrar respuesta</summary>
B. ZRS
</details>

### Pregunta 91
¿Cuál es el propósito de **Row-Level Security (RLS)** en Power BI?

- A. Acelerar las consultas SQL  
- B. Limitar el acceso a filas de datos según el rol del usuario  
- C. Crear medidas calculadas  
- D. Optimizar modelos en memoria  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Limitar el acceso a filas de datos según el rol del usuario
</details>

---

### Pregunta 92
¿Qué propiedad de ACID asegura que una base de datos siempre pase de un estado válido a otro tras ejecutar una transacción?

- A. Atomicidad  
- B. Consistencia  
- C. Aislamiento  
- D. Durabilidad  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Consistencia
</details>

---

### Pregunta 93
¿Cuál es la principal ventaja de usar **DirectQuery en Power BI**?

- A. Mejora la seguridad en dashboards  
- B. Permite acceder a los datos en tiempo real sin importarlos  
- C. Reduce el uso de CPU en el servidor  
- D. Convierte archivos en formato Parquet automáticamente  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Permite acceder a los datos en tiempo real sin importarlos
</details>

---

### Pregunta 94
¿Qué característica de Azure Data Lake Storage Gen2 lo diferencia de Blob Storage estándar?

- A. Soporte para transacciones OLTP  
- B. Jerarquía de directorios y permisos a nivel de carpeta  
- C. Solo admite datos en formato CSV  
- D. No permite replicación geográfica  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Jerarquía de directorios y permisos a nivel de carpeta
</details>

---

### Pregunta 95
En SQL, ¿qué instrucción se usa para **modificar la estructura de una tabla** existente?

- A. UPDATE  
- B. ALTER  
- C. INSERT  
- D. MERGE  

<details>
<summary>✅ Mostrar respuesta</summary>
B. ALTER
</details>

---

### Pregunta 96
¿Qué característica de Power BI permite **publicar un informe como aplicación** para un grupo de usuarios?

- A. Workspaces  
- B. Apps  
- C. Q&A  
- D. Paginated reports  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Apps
</details>

---

### Pregunta 97
¿Qué motor de almacenamiento usa **Azure Synapse Dedicated SQL Pool**?

- A. OLTP in-memory  
- B. Columnar distribuido  
- C. Graph engine  
- D. Key-value store  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Columnar distribuido
</details>

---

### Pregunta 98
¿Cuál es un beneficio de los **dataflows en Power BI**?

- A. Ejecutar consultas DAX directamente  
- B. Reutilizar transformaciones ETL en varios informes  
- C. Crear índices en bases relacionales  
- D. Generar automáticamente roles de seguridad  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Reutilizar transformaciones ETL en varios informes
</details>

---

### Pregunta 99
En un entorno híbrido, ¿qué herramienta se utiliza para **migrar bases de datos locales a Azure**?

- A. Azure Migrate  
- B. Azure Database Migration Service (DMS)  
- C. Azure Functions  
- D. Data Catalog  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Azure Database Migration Service (DMS)
</details>

---

### Pregunta 100
¿Cuál es el propósito del **Azure Synapse Link** para Cosmos DB?

- A. Replicar automáticamente contenedores en varias regiones  
- B. Habilitar análisis en tiempo real de datos operativos sin ETL complejo  
- C. Convertir documentos JSON en tablas relacionales  
- D. Cifrar datos almacenados en Cosmos DB  

<details>
<summary>✅ Mostrar respuesta</summary>
B. Habilitar análisis en tiempo real de datos operativos sin ETL complejo
</details>

---

## 🤝 Contribuciones

Este repositorio es un recurso abierto y en constante mejora.  
Si tienes sugerencias, nuevas preguntas o correcciones, ¡tus aportes son bienvenidos!  

- Puedes abrir un **Issue** para reportar mejoras o dudas.  
- O enviar un **Pull Request** con nuevas preguntas en el mismo formato Markdown.  

La idea es que entre todos creemos un **banco de preguntas práctico y colaborativo** para ayudar a la comunidad a aprobar el examen.  


