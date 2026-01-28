# Data Engineer OneDay - Databricks Training

## O Repozytorium

To repozytorium zawiera materiały szkoleniowe, kody źródłowe oraz ćwiczenia do szkolenia "Data Engineer OneDay" prowadzonego przez Altkom Akademia. Materiały są zaprojektowane tak, aby przeprowadzić uczestników przez kluczowe aspekty pracy inżyniera danych na platformie Databricks Lakehouse.

## Zakres Szkolenia (Agenda)

Program szkolenia obejmuje pełny cykl życia inżynierii danych, od wprowadzenia do platformy po orkiestrację i governance.

### Moduły Demonstracyjne (`notebooks/demo/`)

1.  **01_platform_intro** - Wprowadzenie do platformy Databricks, interfejsu i podstawowych pojęć (Workspace, Compute).
2.  **02_ingestion_transformations** - Pobieranie danych (Ingestion) z różnych źródeł oraz transformacje przy użyciu PySpark i SQL.
3.  **03_delta_lake_optimization** - Praca z formatem Delta Lake, operacje ACID, Time Travel oraz techniki optymalizacji (Z-Order, Optimize).
4.  **04_streaming_incremental** - Przetwarzanie strumieniowe (Structured Streaming) i przyrostowe ładowanie danych (Auto Loader).
5.  **05_medallion_lakeflow** - Architektura Medallion (Bronze/Silver/Gold) oraz budowa potoków danych w Lakeflow (Delta Live Tables).
6.  **06_orchestration** - Orkiestracja zadań przy użyciu Databricks Workflows (Jobs).
7.  **07_governance** - Zarządzanie danymi i bezpieczeństwo z Unity Catalog.

### Warsztaty (`notebooks/workshops/`)

Praktyczne ćwiczenia do samodzielnego wykonania przez uczestników:

*   **W1_ingestion_transformations** - Warsztat z ingestionu i transformacji danych.
*   **W2_delta_optimization** - Ćwiczenia z optymalizacji tabel Delta.
*   **W3_lakeflow_pipeline** - Budowa kompletnego potoku ETL w architekturze Medallion.
*   **W4_governance_security** - Konfiguracja uprawnień i governance.

## Struktura Repozytorium

```text
.
├── assets/                 # Zasoby graficzne i pomocnicze
├── dataset/                # Przykładowe zbiory danych (CSV, JSON)
├── lakeflow/               # Definicje i skrypty dla Delta Live Tables (DLT)
│   ├── lakeflow_trn_pipeline/
│   └── lakeflow_workshop/
├── notebooks/              # Notebooki Jupyter/Databricks
│   ├── demo/               # Notebooki pokazowe (instruktorskie)
│   └── workshops/          # Notebooki warsztatowe (dla kursantów)
└── README.md               # Dokumentacja repozytorium
```

## Wymagania Wstępne

*   Podstawowa znajomość języka SQL oraz Python.
*   Dostęp do platformy Databricks (Azure Databricks, AWS Databricks lub GCP).
*   Podstawowe zrozumienie koncepcji chmurowych i bazodanowych.

## Jak korzystać?

1.  Sklonuj repozytorium do swojego obszaru roboczego w Databricks (Databricks Repos).
2.  Upewnij się, że klaster obliczeniowy (All-Purpose Compute) jest uruchomiony.
3.  Wykonaj skrypty konfiguracyjne (jeśli są dostępne, np. `00_setup.ipynb`), aby przygotować środowisko (katalogi, bazy danych).
4.  Przechodź kolejno przez notebooki z folderu `demo`.
5.  Wykonuj zadania z folderu `workshops` zgodnie z instrukcjami trenera.

---
*Materiały szkoleniowe Altkom Akademia*
