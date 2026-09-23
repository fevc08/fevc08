# Hola, soy Fidel Vera Chourio 👋
### Ingeniero Industrial | Cloud & Data Engineering — AWS

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fidelverachourio)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:fevc1988@gmail.com)

## 🧭 Sobre mí

Ingeniero Industrial con base en Curicó, Chile, en transición hacia la
arquitectura de soluciones en la nube y la ingeniería de datos. Aplico el
mismo pensamiento sistémico con el que optimizo procesos de negocio al diseño
de arquitecturas AWS y pipelines de datos: identifico restricciones reales,
evalúo alternativas con criterios explícitos (documentados en ADRs) y
priorizo soluciones sostenibles en costo, seguridad y escalabilidad — no solo
funcionales en el papel.

Actualmente profundizando en arquitectura cloud a través del programa de
SOFOFA (patrones híbridos, microservicios, serverless y seguridad en AWS), en
paralelo a construir pipelines de datos con arquitectura medallion y dbt para
llevar esas arquitecturas hasta datos listos para decisiones de negocio.

## 🛠 Stack y herramientas

**Cloud & Infraestructura**
Lambda · API Gateway · DynamoDB · S3 · ECS Fargate · ECR · CloudWatch · CloudTrail · AWS Config · ADR (Architecture Decision Records)

**Datos e Ingeniería de Datos**
Python · PostgreSQL · dbt · Arquitectura Medallion (Bronze/Silver/Gold) · Scikit-learn

## 🚀 Proyectos destacados

Arquitecturas diseñadas y documentadas durante el programa de Arquitectura
Cloud de SOFOFA, cada una resuelta con foco en el problema real, decisiones
justificadas (ADR) y trade-offs explícitos frente a las restricciones de AWS
Academy Learner Lab.

![Arquitectura Nube Sólida](https://raw.githubusercontent.com/fevc08/nube-solida-arquitectura-cloud/main/diagrams/export/arquitectura-nube-solida.png)

#### 📊 Code Syndicate Latam — Market Intelligence
**Problema:** CSL necesita definir su estrategia comercial en LATAM (segmentación de clientes, análisis de demanda de servicios, benchmarks de precios y tendencias de skills tech), partiendo de datos dispersos — MVP arrancando por Colombia. **Rol:** Diseñé un pipeline de datos con arquitectura medallion (bronze/silver/gold) en Python + PostgreSQL, con dbt para las transformaciones, documentado con ADRs, reporte de calidad de datos y guía de setup local. **Resultado:** Capa Bronze en producción — 6 tablas, 8 índices, 33 empresas y 5.832 tags de habilidades ingeridos desde la API de Get on Board. Proyecto en curso (Sprint 2), próximo hito: capa Silver con dbt.

`Python` · `PostgreSQL` · `dbt` · `Arquitectura Medallion` · `Scikit-learn`

[Ver repositorio →](https://github.com/fevc08/code-syndicate-market-intel)

#### 🛒 Andes Digital Commerce Cloud
**Problema:** ADC, retailer de e-commerce y logística con operación en Chile, Perú y Colombia, enfrenta picos de tráfico de 10-20x en eventos como CyberDay, mientras su ERP y WMS deben permanecer on-premise por integraciones contractuales con proveedores logísticos locales. **Rol:** Diseñé una arquitectura híbrida que absorbe la elasticidad de demanda en la nube sin forzar la migración de los sistemas legacy, documentando el modelo de costos y las diferencias entre entorno académico y producción. **Resultado:** Arquitectura híbrida multi-país que concilia escalabilidad cloud con restricciones reales de integración legacy — 8 ADRs, diagrama de arquitectura, esquema de comunicación entre servicios.

`AWS` · `Arquitectura híbrida` · `Alta disponibilidad` · `ADR`

[Ver repositorio →](https://github.com/fevc08/andes-digital-commerce-cloud)

#### 💳 MicroPay — Microservicios Orquestados
**Problema:** Una fintech ficticia necesitaba migrar un sistema monolítico de procesamiento de pagos hacia una arquitectura desacoplada y escalable. **Rol:** Descompuse el monolito en microservicios (usuarios, pagos), los orquesté con ECS Fargate y ECR, y expuse la API a través de API Gateway con monitoreo en CloudWatch. **Resultado:** Arquitectura de microservicios contenedorizada, documentada con 5 ADRs cubriendo cada decisión clave de la migración.

`Docker` · `Python (Flask)` · `ECS Fargate` · `ECR` · `API Gateway` · `CloudWatch`

[Ver repositorio →](https://github.com/fevc08/micropay-microservicios-aws)

#### ⚡ Serverless Inteligente
**Problema:** Un e-commerce necesitaba un backend funcional sin asumir la gestión ni el costo fijo de servidores. **Rol:** Implementé funciones Lambda en Python para usuarios y pedidos, expuestas vía API Gateway y persistidas en DynamoDB, con un frontend estático servido desde S3. **Resultado:** Backend 100% serverless, funcional de extremo a extremo (sitio estático, API, funciones y base de datos), sin infraestructura que administrar.

`AWS Lambda` · `API Gateway` · `DynamoDB` · `S3` · `CloudWatch Logs`

[Ver repositorio →](https://github.com/fevc08/serverless-inteligente-aws)

#### 🔒 Cloud Secure — AWS Academy
**Problema:** Blue Wave, una fintech ficticia, necesitaba establecer una postura de seguridad básica pero auditable en su entorno de AWS Academy. **Rol:** Implementé cifrado y bloqueo de acceso público en S3, auditoría de eventos con CloudTrail, cumplimiento continuo con AWS Config y alarmas de CloudWatch para detección temprana. **Resultado:** Cuatro controles de seguridad implementados y evidenciados por lección, con ADRs justificando cada decisión de configuración.

`AWS Config` · `CloudTrail` · `S3` · `CloudWatch` · `Seguridad Cloud`

[Ver repositorio →](https://github.com/fevc08/cloud-secure-aws-academy)

#### ☁️ Nube Sólida — Arquitectura Híbrida
**Problema:** Diseñar conceptualmente una arquitectura cloud que resolviera escalabilidad, costos operativos y resiliencia para un caso de estudio, combinando distintos modelos de servicio. **Rol:** Propuse un modelo de servicio diferenciado por componente (IaaS/PaaS/SaaS/FaaS), combinando microservicios en contenedores y funciones serverless en un modelo híbrido, documentado con 6 ADRs. **Resultado:** Evaluación con nota máxima; proyecto usado además como contenido de portafolio en LinkedIn.

`AWS` · `Cliente-Servidor` · `Arquitectura Híbrida` · `ADR`

[Ver repositorio →](https://github.com/fevc08/nube-solida-arquitectura-cloud)

## 📬 Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fidelverachourio)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:fevc1988@gmail.com)
