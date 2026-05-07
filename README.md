<!-- ════════════════════════════ HERO ════════════════════════════ -->

![header](https://capsule-render.vercel.app/api?type=cylinder&color=gradient&customColorList=20,24,12,2&height=180&section=header&text=KALVEEN%20JOSEPH&fontSize=58&fontColor=ffffff&fontAlignY=50&desc=Senior%20Big%20Data%20Engineer%20%E2%80%A2%20Petabyte-Scale%20Architectures&descSize=16&descAlignY=80&animation=fadeIn)

<div align="center">

<a href="mailto:kalveenjoseph8@gmail.com"><img src="https://img.shields.io/badge/-kalveenjoseph8%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white&labelColor=0a0e27" /></a>
<img src="https://img.shields.io/badge/-Atlanta,_GA-EC4899?style=flat-square&logo=googlemaps&logoColor=white&labelColor=0a0e27" />
<img src="https://img.shields.io/badge/-9_Years-3B82F6?style=flat-square&labelColor=0a0e27" />
<img src="https://img.shields.io/badge/-Healthcare_Data-22C55E?style=flat-square&labelColor=0a0e27" />

</div>

<!-- ══════════════════════ THE NUMBERS ══════════════════════ -->

<div align="center">

```
╔═════════════════════════════════════════════════════════════════════╗
║                                                                     ║
║    28B+              4.7 PB              99.99%             38      ║
║    events/day        data managed        uptime          hospitals  ║
║                                                                     ║
╚═════════════════════════════════════════════════════════════════════╝
```

</div>

---

## ▌ SELECT * FROM about_me

> **Most big data engineers can build a pipeline. Few can architect the system that makes 4.7 petabytes feel like a spreadsheet query.**

Nine years engineering data platforms at scales where traditional tools break — from tuning Spark clusters that process **28 billion events daily** to designing lakehouse architectures that serve sub-second analytics on trillion-row tables. Currently at **Oznolo** I own the entire big data ecosystem powering healthcare analytics for 38 hospital networks. **1.2PB** of new data flows in monthly. **99.99%** pipeline uptime — for 14 consecutive months and counting.

---

## ▌ THE PIPELINE

```
                        ┌─────────────────────────────────────────────┐
   HL7 / FHIR feeds ────▶│  Kafka  ─▶  Flink  ─▶  Sub-60s alerts      │
                        ├─────────────────────────────────────────────┤
   Claims events    ────▶│  Spark 3.4 (AQE + DPP)  ─▶  Delta Lake     │
                        ├─────────────────────────────────────────────┤
   38 hospital NWs  ────▶│  EMR · 2,400 nodes  ─▶  Unity Catalog      │
                        ├─────────────────────────────────────────────┤
   Quality gates    ────▶│  Great Expectations  ─▶  18k contracts/nt  │
                        └─────────────────────────────────────────────┘
                                                     │
                                                     ▼
                                          280 analysts · 45 ML eng
```

---

## ▌ THE STACK

<div align="center">

#### Core Engines
![Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white&labelColor=0a0e27)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white&labelColor=0a0e27)
![Flink](https://img.shields.io/badge/Apache_Flink-E6526F?style=for-the-badge&logo=apacheflink&logoColor=white&labelColor=0a0e27)
![Hadoop](https://img.shields.io/badge/Hadoop_/_HDFS-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black&labelColor=0a0e27)

#### Lakehouse
![Delta](https://img.shields.io/badge/Delta_Lake-00ADD4?style=for-the-badge&labelColor=0a0e27)
![Iceberg](https://img.shields.io/badge/Apache_Iceberg-1976D2?style=for-the-badge&labelColor=0a0e27)
![Hudi](https://img.shields.io/badge/Apache_Hudi-FF6B35?style=for-the-badge&labelColor=0a0e27)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white&labelColor=0a0e27)

#### Cloud · Orchestration · Quality
![AWS](https://img.shields.io/badge/AWS_EMR-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white&labelColor=0a0e27)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white&labelColor=0a0e27)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white&labelColor=0a0e27)
![K8s](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white&labelColor=0a0e27)

#### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=0a0e27)
![Scala](https://img.shields.io/badge/Scala-DC322F?style=for-the-badge&logo=scala&logoColor=white&labelColor=0a0e27)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=0a0e27)

</div>

---

## ▌ EXPLAIN PLAN — career path

```sql
-- experience.sql
WITH career AS (

  SELECT 'Oznolo'      AS company, '2022-03' AS start_date, 'present' AS end_date
  UNION ALL
  SELECT 'Humana'      AS company, '2019-06' AS start_date, '2022-02' AS end_date
  UNION ALL
  SELECT 'Anthem'      AS company, '2016-08' AS start_date, '2019-05' AS end_date

)
SELECT  company,
        DATEDIFF(NOW(), start_date) AS time_at_co,
        impact
  FROM  career
 ORDER  BY start_date DESC;
```

<details open>
<summary><b>🚀 &nbsp; Oznolo &nbsp;·&nbsp; <code>Senior Big Data Engineer</code> &nbsp;·&nbsp; Mar 2022 → Present</b></summary>

<br/>

> Owning the big data platform powering healthcare analytics for **38 hospital networks** — 28B daily events, 4.7 PB managed, 99.99% uptime.

| **Wins** |  |
|:---------|:-|
| ⚡ ETL runtime | `14 hrs → 47 min` (Spark 3.4 + AQE + DPP on 1.2 PB/day) |
| 🌊 Streaming throughput | `3.2M events/sec` from HL7/FHIR (Kafka + Flink) |
| 🧊 Lakehouse migration | HDFS → Delta Lake → `−68% storage`, `12x query perf` |
| ✅ Data quality | `18,000 contracts/night` validated · 23 bad-data incidents stopped |
| 🏥 HIPAA data mesh | Unity Catalog · 280 analysts · 45 ML engineers |

</details>

<details>
<summary><b>🩺 &nbsp; Humana &nbsp;·&nbsp; <code>Big Data Engineer</code> &nbsp;·&nbsp; Jun 2019 → Feb 2022</b></summary>

<br/>

> Tech lead for the 6-person data platform team at a Fortune 50 health insurer.

- Member risk stratification on Spark MLlib (18M profiles · 400 features) → **$340M risk-adjustment revenue**
- Real-time fraud detection (Kafka Streams + Flink, 2.4M tx/day) → **$47M flagged** in year one
- Cloudera on-prem → AWS EMR + Delta Lake migration → **−52% infra cost**, **8× throughput**
- Apache Atlas + Airflow data lineage across **2,400 datasets** with column-level traceability

</details>

<details>
<summary><b>🏛️ &nbsp; Anthem (now Elevance Health) &nbsp;·&nbsp; <code>Data Engineer</code> &nbsp;·&nbsp; Aug 2016 → May 2019</b></summary>

<br/>

> Enterprise data lake supporting clinical analytics, actuarial, and regulatory reporting (2.1 PB on Hadoop).

- Pharmacy claims pipeline ingesting **450M Rx records/year** from 67k pharmacies → **$28M cost-savings ID'd**
- Provider network analytics powering member-facing search at **12M queries/month**
- CMS regulatory reporting (14 state Medicaids → HEDIS / Stars) → **6 weeks → 3 days** per cycle
- Custom Spark UDFs + partitioning → **−40% query cost** for actuarial team

</details>

---

## ▌ CERTIFIED

<div align="center">

![Databricks](https://img.shields.io/badge/Databricks-Data_Engineer_Professional-FF3621?style=for-the-badge&logo=databricks&logoColor=white&labelColor=0a0e27)
![AWS](https://img.shields.io/badge/AWS-Data_Analytics_Specialty-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white&labelColor=0a0e27)

![Confluent](https://img.shields.io/badge/Confluent-Apache_Kafka_Developer-231F20?style=for-the-badge&logo=apachekafka&logoColor=white&labelColor=0a0e27)
![GT](https://img.shields.io/badge/MS_CS-Georgia_Tech_2016-B3A369?style=for-the-badge&labelColor=0a0e27)

</div>

---

## ▌ SHOWCASE — what's worth bragging about

```yaml
# highlights.yaml

scale_and_reliability:
  cluster:        2,400 nodes on AWS EMR
  events_per_day: 28,000,000,000
  uptime:         99.99% for 14 consecutive months
  hospitals:      38 networks

cost_optimization:
  storage_savings: -68%   # HDFS → Delta Lake
  query_speedup:   12x    # trillion-row tables
  infra_cost_cut:  -52%   # Cloudera on-prem → AWS EMR
  throughput_gain: 8x     # Hive → Spark migration

real_time_streaming:
  protocol:    HL7 / FHIR
  throughput:  3.2M events / second
  latency:     sub-60-second clinical alerts
  use_case:    sepsis & deterioration prediction

data_quality:
  validations:        18,000 contracts / night
  source_feeds:       340
  incidents_blocked:  23   # before reaching production

revenue_impact:
  risk_adjustment:    $340M / year (Humana)
  fraud_detected:     $47M  / year (Humana)
  rx_cost_savings:    $28M       (Anthem)
```

---

## ▌ COMMUNITY

```
  ★ open source ─── Apache Spark · Delta Lake (contributor)
                    spark-healthcare-toolkit (maintainer · 680 ⭐)
                    HL7 / FHIR parsing for Apache Spark

  🎤 speaking  ─── Data + AI Summit 2024
                    Kafka Summit 2023
                    Strata Data Conference 2023

  🏥 focus     ─── healthcare data engineering at Fortune-50 scale,
                    HIPAA-compliant architectures, and regulatory reporting
```

---

<div align="center">

## ▌ COMMIT — let's connect

> *working on petabyte-scale streaming, healthcare data, or lakehouse migrations?*
> *open an issue or drop a line — always happy to talk shop.*

<br/>

<a href="mailto:kalveenjoseph8@gmail.com">
  <img src="https://img.shields.io/badge/▶_send_a_message-3B82F6?style=for-the-badge&labelColor=0a0e27&color=3B82F6" />
</a>

<br/><br/>

<sub>built with ☕ &nbsp;·&nbsp; partitioned by day &nbsp;·&nbsp; replicated 3× &nbsp;·&nbsp; ACID-compliant</sub>

</div>

![footer](https://capsule-render.vercel.app/api?type=cylinder&color=gradient&customColorList=2,12,20,24&height=80&section=footer)
