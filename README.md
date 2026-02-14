# Ampliación de Ingeniería del Software (AIS)

[![SWH](https://archive.softwareheritage.org/swh:1:rev:89511c04882c581f952591eb8aa03a92b7cc7fad)](https://archive.softwareheritage.org/wh:1:rev:89511c04882c581f952591eb8aa03a92b7cc7fad;origin=https://github.com/codigus-formacion/ais;visit=swh:1:snp:ae5800f2738d5db1bfb39af45268a28a3fbf7622)



Este repositorio contiene los ejemplos y ejercicios utilizados en la asignatura **Ampliación de Ingeniería del Software**, perteneciente al **Grado en Ingeniería Informática** de la ETSII URJC.

El objetivo es ofrecer material práctico que permita familiarizarse con las diferentes técnicas y tecnologías para asegurar la calidad del software, desde pruebas unitarias hasta integración continua, pasando por análisis estático, refactorización y mantenimiento.

## 📑 Tabla de Contenidos

- [Ampliación de Ingeniería del Software (AIS)](#ampliación-de-ingeniería-del-software-ais)
  - [📑 Tabla de Contenidos](#-tabla-de-contenidos)
  - [🛠️ Tecnologías Utilizadas](#️-tecnologías-utilizadas)
  - [📂 Estructura del Repositorio](#-estructura-del-repositorio)
  - [📚 Temario de la Asignatura](#-temario-de-la-asignatura)
    - [Parte 1. Pruebas](#parte-1-pruebas)
    - [Parte 2. Calidad](#parte-2-calidad)
    - [Parte 3. Mantenimiento](#parte-3-mantenimiento)
    - [Parte 4. CI/CD](#parte-4-cicd)
  - [⚙️ Requisitos Previos](#️-requisitos-previos)
  - [📖 Recursos](#-recursos)
  - [📄 Licencia](#-licencia)

## 🛠️ Tecnologías Utilizadas

Este repositorio incluye ejemplos y proyectos que utilizan las siguientes tecnologías:

**Testing y Pruebas:**
- JUnit 5
- Mockito
- AssertJ
- Cucumber (ATDD/BDD)
- Selenium WebDriver
- REST Assured
- Artillery (testing de carga)
- JaCoCo (cobertura de código)

**Análisis Estático y Calidad:**
- SonarQube / SonarLint
- Análisis de code smells
- Detección de vulnerabilidades

**CI/CD y DevOps:**
- GitHub Actions
- Docker
- Azure (despliegue continuo)

**Arquitectura:**
- Arquitectura Hexagonal
- Patrones de diseño

## 📂 Estructura del Repositorio

```
ais/
├── Parte_1_Pruebas/              # Técnicas y herramientas de testing
│   ├── cobertura/                # Cobertura de código con JaCoCo
│   ├── testing_selenium/         # Testing de UI con Selenium
│   └── testing_unitario/         # Testing unitario con JUnit y Mockito
│
├── Parte_2_Calidad/              # Calidad de código y arquitectura
│   ├── analisis-estatico/        # Análisis estático con SonarQube
│   └── arquitectura/             # Arquitecturas de software
│
├── Parte_3_Mantenimiento/        # Mantenimiento y refactorización
│   ├── RefactoringKata-Tennis/   # Kata de refactorización
│   │   ├── Base/                 # Código base
│   │   └── Refactored/           # Código refactorizado
│   └── TDD-Kata-RomanNumbers/    # Kata de TDD
│       ├── base/                 # Código base
│       └── solution/             # Solución
│
├── Parte_4_CICD/                 # Integración y despliegue continuo
│   ├── continuous-integration/   # Integración continua con GitHub Actions
│   ├── continuous-integration-selenium/  # CI con tests de Selenium
│   ├── continuous-delivery/      # Entrega continua
│   └── continuous-deployment-azure/      # Despliegue continuo en Azure
│
└── README.md
```

## 📚 Temario de la Asignatura

El temario de la asignatura se divide en las siguientes partes:

### Parte 1. Pruebas

Esta parte cubre las diferentes técnicas y herramientas de testing:

* **Testing Unitario:** JUnit 5, AssertJ, Mockito
  - Pruebas unitarias básicas
  - Aserciones avanzadas con AssertJ
  - Mocks y stubs con Mockito
  - 📁 Ejemplos y ejercicios en **[Parte_1_Pruebas/testing_unitario/](Parte_1_Pruebas/testing_unitario/)**

* **Testing de UI:** Selenium WebDriver
  - Automatización de pruebas de interfaz
  - Page Object Model
  - 📁 Ejemplos y ejercicios en **[Parte_1_Pruebas/testing_selenium/](Parte_1_Pruebas/testing_selenium/)**

* **Cobertura de Código:** JaCoCo
  - Medición de cobertura de tests
  - Reportes de cobertura
  - 📁 Ejemplos en **[Parte_1_Pruebas/cobertura/](Parte_1_Pruebas/cobertura/)**

### Parte 2. Calidad

Esta parte aborda la calidad del código y la arquitectura:

* **Análisis Estático:** SonarQube, SonarLint
  - Detección de code smells
  - Identificación de vulnerabilidades
  - Métricas de calidad
  - 📁 Ejemplos en **[Parte_2_Calidad/analisis-estatico/](Parte_2_Calidad/analisis-estatico/)**

* **Arquitectura de Software:**
  - Arquitectura Hexagonal (Puertos y Adaptadores)
  - Separación de responsabilidades
  - Diseño orientado al dominio
  - 📁 Ejemplos en **[Parte_2_Calidad/arquitectura/](Parte_2_Calidad/arquitectura/)**

### Parte 3. Mantenimiento

Esta parte se enfoca en técnicas de mantenimiento y evolución del software:

* **Refactorización:**
  - Técnicas de refactorización
  - Code smells y su corrección
  - Katas de refactorización (Tennis)
  - 📁 Ejemplos en **[Parte_3_Mantenimiento/RefactoringKata-Tennis/](Parte_3_Mantenimiento/RefactoringKata-Tennis/)**

* **TDD (Test-Driven Development):**
  - Desarrollo guiado por tests
  - Ciclo Red-Green-Refactor
  - Kata de números romanos
  - 📁 Ejemplos en **[Parte_3_Mantenimiento/TDD-Kata-RomanNumbers/](Parte_3_Mantenimiento/TDD-Kata-RomanNumbers/)**

### Parte 4. CI/CD

Esta parte cubre la integración y despliegue continuo:

* **Integración Continua (CI):** GitHub Actions
  - Automatización de builds
  - Ejecución de tests en CI
  - Validación de calidad
  - 📁 Ejemplos en **[Parte_4_CICD/continuous-integration/](Parte_4_CICD/continuous-integration/)**

* **Integración Continua con Selenium:**
  - Tests de UI en pipelines CI
  - 📁 Ejemplos en **[Parte_4_CICD/continuous-integration-selenium/](Parte_4_CICD/continuous-integration-selenium/)**

* **Entrega Continua (CD):**
  - Preparación de artefactos
  - Versionado automático
  - 📁 Ejemplos en **[Parte_4_CICD/continuous-delivery/](Parte_4_CICD/continuous-delivery/)**

* **Despliegue Continuo:**
  - Despliegue automático en Azure
  - Infraestructura como código
  - 📁 Ejemplos en **[Parte_4_CICD/continuous-deployment-azure/](Parte_4_CICD/continuous-deployment-azure/)**

## ⚙️ Requisitos Previos

Para trabajar con los proyectos de este repositorio necesitas tener instalado:

**Herramientas básicas:**
- **Java 21** o superior
- **Maven 3.6+**
- **Git**

**Para pruebas y desarrollo:**
- Navegador web moderno (Chrome, Firefox, Edge)

**Para CI/CD:**
- **Docker**
- Cuenta de **GitHub** (para GitHub Actions)
- Cuenta de **Azure** (opcional, para despliegue continuo)

**Análisis de calidad:**
- **SonarQube** / **SonarLint** (plugin para IDE)

**IDEs recomendados:**
- **IntelliJ IDEA** / **Visual Studio Code**

## 📖 Recursos

💡 **Nota:** Este material está pensado como apoyo para el aprendizaje práctico de técnicas y herramientas para el desarrollo de software de calidad, desde testing hasta integración continua.

**Enlaces del repositorio:**
- 🔗 Repositorio Software Heritage: https://archive.softwareheritage.org/swh:1:rev:89511c04882c581f952591eb8aa03a92b7cc7fad
- 🔗 Repositorio GitHub: https://github.com/codigus-formacion/ais

**Recursos adicionales:**
- 📚 JUnit 5: https://junit.org/junit5/
- 📚 Mockito: https://site.mockito.org/
- 📚 Cucumber: https://cucumber.io/
- 📚 Selenium: https://www.selenium.dev/
- 📚 Artillery: https://www.artillery.io/
- 📚 SonarQube: https://www.sonarqube.org/
- 📚 GitHub Actions: https://docs.github.com/actions

## 📄 Licencia

>©2026 Micael Gallego Carrillo, Francisco Gortázar Bellas, Michel Maes Bermejo, Óscar Soto Sánchez e Iván Chicano Capelo
>Algunos derechos reservados  
>Este documento se distribuye bajo la licencia  
>“Atribución-CompartirIgual 4.0 Internacional” de Creative Commons, disponible en  
>https://creativecommons.org/licenses/by-sa/4.0/deed.es
