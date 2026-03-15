# ⚡ Krypton: Predicción de Churn en Fintech
## 💳 Solución Integral de Predicción de Cancelación de Tarjetas

Este proyecto desarrolla una solución avanzada orientada a la **predicción de cancelación de tarjetas de crédito** para empresas del sector **Fintech**. El objetivo es anticipar el comportamiento de abandono (*churn*) para implementar estrategias de retención efectivas y optimizar la toma de decisiones basada en datos.

> **Rol Destacado:** Líder de equipo Back-end & Co-desarrollador Front-end.

---

## 🎯 Objetivo

- **Identificar** clientes con alta probabilidad de cancelar su tarjeta mediante Machine Learning.
- **Permitir** acciones preventivas de retención en tiempo real.
- **Exponer** las predicciones a través de una API robusta y escalable.
- **Respaldar** la toma de decisiones comerciales con analítica predictiva.

## 🧩 Arquitectura
Nuestra API está diseñada para una integración simple y escalable. Utiliza un ecosistema híbrido donde un motor de **Python** procesa la inteligencia predictiva y un núcleo de **Java** gestiona la lógica de negocio y seguridad.

## ⚙️ Setup del Proyecto

### Requisitos Técnicos
| Componente | Tecnología |
| :--- | :--- |
| **Runtime Backend** | Java 21 (LTS) / Spring Boot 3.2 |
| **Runtime ML** | Python 3.11.x |
| **Contenedores** | Docker Engine 24.0+ |
| **Orquestación** | Docker Compose V2 |

### Recursos de Hardware (Mínimos)
- **CPU:** 4 vCPUs (x86_64).
- **RAM:** 8 GB Total (Heap Java: 2GB | RAM ML Engine: 4GB).
- **Storage:** 20 GB SSD.

---

## 🛠️ Tecnologías Utilizadas

### 🐍 Data Science & Analytics
| Tecnología | Uso Principal | Nivel |
| :--- | :--- | :--- |
| ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) | Lenguaje principal de ML | Avanzado |
| ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) | Manipulación de datos | Avanzado |
| ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white) | Modelos predictivos | Avanzado |

### ☕ Back End Development
| Tecnología | Uso Principal | Versión |
| :--- | :--- | :--- |
| ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) | Lenguaje backend principal | 21 LTS |
| ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white) | Framework Core | 3.2.x |
| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) | Base de datos relacional | 15+ |
| ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white) | Seguridad y JWT | 3.x |

---

## 👨‍💻 Autor y Roles

### **Ianjaner Alfonso Beltrán Guañarita**
**Líder de equipo Back-end | Front-end Developer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-blue?logo=linkedin)](https://www.linkedin.com/in/ianjaner-alfonso-beltran-gua%C3%B1arita) 
[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?logo=github)](https://github.com/ianjaner75)

# Diagrama de Arquitectura del Proyecto

```mermaid
graph TD
    DS["Data Science"] -- Conectado a --> BE["Back End"]
    
    DS -->|Entrena| ML["Modelos ML"]
    BE -->|Expone| API["APIs REST"]
    
    ML -->|Proporciona| DA["Data API"]
    API -->|Sirve| C["Consumo"]
    
    DA -->|Alimenta| PF["Producto Final"]
    C -->|Utiliza| PF
 ```
# Ecosistema Tecnológico
```mermaid
graph TB
    A[Data Sources] --> B[Python/Pandas]
    B --> C[ML Models]
    C --> D[Spring Boot APIs]
    D --> E[PostgreSQL]
    F[Git/GitHub] --> B
    F --> D
    G[Trello] --> H[Scrum Process]
    H --> B
    H --> D
```
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
    I[Google Colab] --> B
    J[Maven] --> D
 ```
