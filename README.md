<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/d/de/AirflowLogo.png" alt="Apache Airflow Logo" width="200"/>
</p>
<h1 align="center"> Airflow Mini Project – DAG with Three Tasks</h1>
<p align="center">
  <b>A simple Apache Airflow project demonstrating task scheduling, dependencies, and logging.</b>
</p>

---

## Project Overview
This project demonstrates a simple **Apache Airflow DAG** that executes three independent tasks. Each task performs a basic Python operation, and the DAG is designed to run sequentially. The project serves as a hands-on example to understand how Airflow schedules, runs, and logs tasks.

---

## ⚙️ How It Works
The DAG includes **three tasks** executed in order:

date_task → welcome_task → random_task

yaml
Copy code

All logs are stored and can be viewed in the Airflow web UI.

---

## Project Structure

airflow_dag_project/
│
├── dags/
│ └── mini_dag.py
│
├── images/
│ ├── graph.png
│ ├── date_log.png
│ ├── welcome_log.png
│ └── random_log.png
│
└── README.md

yaml
Copy code

---

## DAG Graph
Below is the DAG visualization from the Airflow UI:
<p align="center">
  <img src="images/graph.png" width="700"/>
</p>

---

## Task Logs
Below are screenshots showing the log outputs of each task:

### Task 1 – Date Log
<p align="center">
  <img src="images/date_log.png" width="600"/>
</p>

### Task 2 – Welcome Message
<p align="center">
  <img src="images/welcome_log.png" width="600"/>
</p>

### Task 3 – Random Number Generation
<p align="center">
  <img src="images/random_log.png" width="600"/>
</p>

---

## Key Takeaways
- Learned how to define and connect multiple tasks in Airflow.  
- Understood how task dependencies work (`>>`, `<<`).  
- Practiced viewing logs and monitoring DAG execution flow.

---

## Author
**Belal – Engineer & AI Enthusiast**  
Exploring automation and intelligent systems through practical Airflow projects.

<p align="center">
  <a href="https://github.com/">GitHub</a> · 
  <a href="https://airflow.apache.org/">Apache Airflow</a>
</p>

---

## 🏷️ Tags
`Apache Airflow` · `Python` · `Data Engineering` · `Automation` · `Task Scheduling`
