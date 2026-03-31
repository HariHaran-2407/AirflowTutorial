# 🚀 Apache Airflow DAGs – Learning & Practice

This repository contains a collection of **Apache Airflow DAGs** designed to demonstrate core concepts, patterns, and real-world use cases in workflow orchestration.

The goal of this project is to build a strong foundation in Airflow by implementing progressively advanced DAGs.

---

## 📌 About Airflow

Apache Airflow is an open-source platform used to programmatically author, schedule, and monitor workflows.

---

## 📂 Project Structure

```
dags/
│
├── 1_first_dag.py
├── 2_dag_versioning.py
├── 3_operators.py
├── 4_XCOMs_auto.py
├── 5_XCOMs_kwargs.py
├── 6_parallel_tasks.py
├── 7_branches.py
├── 8_schedule_preset.py
```

---

## 🧠 DAGs Overview

Each DAG demonstrates a specific Airflow concept:

### 1️⃣ 1_first_dag.py

* Introduction to DAG structure
* Basic task creation and execution

---

### 2️⃣ 2_dag_versioning.py

* Understanding DAG updates and versioning
* Handling changes in workflows

---

### 3️⃣ 3_operators.py

* Usage of different Airflow operators
* PythonOperator, BashOperator, etc.

---

### 4️⃣ 4_XCOMs_auto.py

* Automatic XComs (cross-task communication)
* Passing data between tasks implicitly

---

### 5️⃣ 5_XCOMs_kwargs.py

* Using XComs with `kwargs`
* Explicit data passing between tasks

---

### 6️⃣ 6_parallel_tasks.py

* Running tasks in parallel
* Understanding task dependencies

---

### 7️⃣ 7_branches.py

* Implementing branching logic
* Conditional execution of tasks

---

### 8️⃣ 8_schedule_preset.py

* Using built-in scheduling presets
* Automating DAG execution

---

## ⚙️ Setup Instructions

1. Install Airflow:

```bash
pip install apache-airflow
```

2. Initialize Airflow:

```bash
airflow db init
```

3. Start services:

```bash
airflow webserver --port 8080
airflow scheduler
```

4. Place DAGs inside:

```
~/airflow/dags/
```

---

## 🎯 Learning Outcomes

By working through these DAGs, you will learn:

* DAG creation and structure
* Task dependencies and execution flow
* XComs for data sharing
* Parallel processing and branching
* Scheduling and automation

---

## 🚀 Future Enhancements

* Integration with Azure Databricks
* Orchestrating ETL pipelines
* Integration with cloud storage (ADLS / S3)
* Real-world data engineering workflows

---

## 👨‍💻 Author

Hariharan
Aspiring Data Engineer | Focused on building scalable data pipelines
