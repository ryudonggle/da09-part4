# da09-part4
Google Cloud Platform 기반 클라우드 환경에서 SNS 투표 데이터를 활용한 데이터 엔지니어링 및 분석 프로젝트

# SNS 투표 데이터 엔지니어링 및 분석 프로젝트

(Google Cloud Platform 기반 클라우드 환경)

1. 프로젝트 개요

본 프로젝트는 Google Cloud Platform(GCP) 기반 클라우드 환경에서
SNS 투표 데이터를 활용한 데이터 엔지니어링 및 분석 파이프라인을 구축하는 것을 목표로 한다.

이미 Google Cloud Storage(GCS)에 적재된 데이터를 시작점으로 삼아,
Apache Airflow를 활용한 ETL 자동화와
BigQuery 기반 데이터 분석 환경을 설계·구현한다.

본 프로젝트는 데이터 수집 단계는 제외하고,
클라우드 환경에서의 데이터 처리·저장·분석 전 과정에 집중한다.

2. 프로젝트 목표

GCP 클라우드 환경에서의 데이터 엔지니어링 파이프라인 설계

GCS → BigQuery 기반 데이터 흐름 이해 및 구현

Apache Airflow를 활용한 ETL 자동화

분석을 위한 정형 데이터 모델링

실무에 가까운 클라우드 데이터 아키텍처 경험

3. 기술 스택 (Tech Stack)
☁️ Cloud Platform

Google Cloud Platform (GCP)

Compute Engine (VM)

Cloud Storage (GCS)

BigQuery

🔁 Data Orchestration

Apache Airflow

DAG 기반 ETL 워크플로우 관리

스케줄링 및 작업 의존성 관리

🗄️ Data Storage & Warehouse

Google Cloud Storage (GCS)

원천 데이터 저장 (Data Lake 역할)

BigQuery

분석용 데이터 웨어하우스

🧑‍💻 Programming & Analysis

Python

데이터 처리 및 변환

BigQuery 연동

SQL (BigQuery SQL)

데이터 분석 및 집계

🛠️ Development Environment

Linux (Ubuntu)

VS Code (Remote-SSH)

Git & GitHub
