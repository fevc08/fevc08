<div align="center">

# Hola, soy Fidel Vera Chourio 👋
### Ingeniero Industrial | Cloud Architecture & AWS

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fidelverachourio/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:fevc1988@gmail.com)

</div>

---

## 🧭 Sobre mí

Ingeniero Industrial con base en Curicó, Chile, en transición hacia la arquitectura de soluciones en la nube. Aplico el mismo pensamiento sistémico con el que optimizo procesos de negocio al diseño de arquitecturas AWS: identifico restricciones reales, evalúo alternativas con criterios explícitos (documentados en ADRs) y priorizo soluciones sostenibles en costo, seguridad y escalabilidad — no solo funcionales en el papel.

Actualmente profundizando en arquitectura cloud a través del programa de SOFOFA, con foco en patrones híbridos, microservicios, serverless y seguridad en AWS.

## 🛠️ Stack y herramientas

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![draw.io](https://img.shields.io/badge/draw.io-F08705?style=flat&logo=diagramsdotnet&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

`Lambda` · `API Gateway` · `DynamoDB` · `S3` · `ECS Fargate` · `ECR` · `CloudWatch` · `CloudTrail` · `AWS Config` · `ADR (Architecture Decision Records)`

## 🚀 Proyectos destacados

Arquitecturas diseñadas y documentadas durante el programa de Arquitectura Cloud de SOFOFA, cada una resuelta con foco en el problema real, decisiones justificadas (ADR) y trade-offs explícitos frente a las restricciones de AWS Academy Learner Lab.

### 🛒 [Andes Digital Commerce Cloud](https://github.com/fevc08/andes-digital-commerce-cloud)
**Problema:** ADC, retailer de e-commerce y logística con operación en Chile, Perú y Colombia, enfrenta picos de tráfico de 10-20x en eventos como CyberDay, mientras su ERP y WMS deben permanecer on-premise por integraciones contractuales con proveedores logísticos locales.
**Rol:** Diseñé una arquitectura híbrida que absorbe la elasticidad de demanda en la nube sin forzar la migración de los sistemas legacy, documentando el modelo de costos y las diferencias entre entorno académico y producción.
**Resultado:** Arquitectura híbrida multi-país que concilia escalabilidad cloud con restricciones reales de integración legacy.
`AWS` · `Arquitectura híbrida` · `Alta disponibilidad` · `ADR`

### 💳 [MicroPay – Microservicios Orquestados](https://github.com/fevc08/micropay-microservicios-aws)
**Problema:** Una fintech ficticia necesitaba migrar un sistema monolítico de procesamiento de pagos hacia una arquitectura desacoplada y escalable.
**Rol:** Descompuse el monolito en microservicios (usuarios, pagos), los orquesté con ECS Fargate y ECR, y expuse la API a través de API Gateway con monitoreo en CloudWatch.
**Resultado:** Arquitectura de microservicios contenedorizada, documentada con 5 ADRs cubriendo cada decisión clave de la migración.
`Docker` · `Python (Flask)` · `ECS Fargate` · `ECR` · `API Gateway` · `CloudWatch`

### ⚡ [Serverless Inteligente](https://github.com/fevc08/serverless-inteligente-aws)
**Problema:** Un e-commerce necesitaba un backend funcional sin asumir la gestión ni el costo fijo de servidores.
**Rol:** Implementé funciones Lambda en Python para usuarios y pedidos, expuestas vía API Gateway y persistidas en DynamoDB, con un frontend estático servido desde S3.
**Resultado:** Backend 100% serverless, funcional de extremo a extremo (sitio estático, API, funciones y base de datos), sin infraestructura que administrar.
`AWS Lambda` · `API Gateway` · `DynamoDB` · `S3` · `CloudWatch Logs`

### 🔒 [Cloud Secure – AWS Academy](https://github.com/fevc08/cloud-secure-aws-academy)
**Problema:** Blue Wave, una fintech ficticia, necesitaba establecer una postura de seguridad básica pero auditable en su entorno de AWS Academy.
**Rol:** Implementé cifrado y bloqueo de acceso público en S3, auditoría de eventos con CloudTrail, cumplimiento continuo con AWS Config y alarmas de CloudWatch para detección temprana.
**Resultado:** Cuatro controles de seguridad implementados y evidenciados por lección, con ADRs justificando cada decisión de configuración.
`AWS Config` · `CloudTrail` · `S3` · `CloudWatch` · `Seguridad Cloud`

### ☁️ [Nube Sólida – Arquitectura Híbrida](https://github.com/fevc08/nube-solida-arquitectura-cloud)
**Problema:** Diseñar conceptualmente una arquitectura cloud que resolviera escalabilidad, costos operativos y resiliencia para un caso de estudio, combinando distintos modelos de servicio.
**Rol:** Propuse un modelo de servicio diferenciado por componente (IaaS/PaaS/SaaS/FaaS), combinando microservicios en contenedores y funciones serverless en un modelo híbrido, documentado con 6 ADRs.
**Resultado:** Evaluación con nota máxima; proyecto usado además como contenido de portafolio en LinkedIn.
`AWS` · `Cliente-Servidor` · `Arquitectura Híbrida` · `ADR`

## 📫 Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Fidel_Vera_Chourio-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fidelverachourio/)
[![Gmail](https://img.shields.io/badge/Email-fevc1988%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:fevc1988@gmail.com)
