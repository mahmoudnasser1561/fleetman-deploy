# Fleetman Deploy — Microservices-Based Vehicle Tracking System
**Fleetman** is a scalable tracking system designed for shipping and logistics companies. It orchestrates multiple loosely coupled microservices to monitor, manage, and visualize live fleet operations in real time.

<img width="1651" height="981" alt="Untitled Diagram-Page-5-Page-5 drawio" src="https://github.com/user-attachments/assets/57afa9c1-f15e-4a5b-b354-9a561e2d4f48" />

<br>
<br>

## Agenda
- Project Structure
- Deployment of fleetman to a kubernates cluster on local ubuntu machine
- Deployment of fleetman to an AWS EKS cluster
- Monitoring & Obeservability & Log Management

## Project Structure
<img width="498" height="394" alt="image" src="https://github.com/user-attachments/assets/79f6c1e3-5576-4555-8850-2ffade571731" />

#### Submodules
This project includes a submodule for monitoring resources -> [monitoring](https://github.com/mahmoudnasser1561/fleetman-monitoring)
 
## Deployment of fleetman to a kubernates cluster on local ubuntu machine:
<img width="1074" height="602" alt="Screenshot from 2025-10-20 07-43-57" src="https://github.com/user-attachments/assets/16c9872a-013c-4226-97ca-6695bcce5db9" />

<br>
<br>
<br>

<img width="1297" height="695" alt="Screenshot from 2025-10-19 15-04-47" src="https://github.com/user-attachments/assets/b798aa66-8c4a-45b7-bfb6-26103ca03846" />
<br>
<br>

#### Live Fleet Tracking
The system continuously updates vehicle positions in real time as they move.  
Each movement event is stored locally in a database to preserve historical route data.  
The database is mounted on an external storage volume to ensure persistence and data durability.

## Deplyment of fleetman to aws using EKS to create the cluster:
#### Getting the cluster ready 
<img width="1027" height="364" alt="image" src="https://github.com/user-attachments/assets/ff98ab7d-6941-4fda-99de-b5dc0149e5f4" />
<img width="1018" height="62" alt="image" src="https://github.com/user-attachments/assets/3c8be7ca-4b67-44ad-85c6-2bf830543517" />

##### Deployed successfully and pods are healthy
<img width="1018" height="151" alt="image" src="https://github.com/user-attachments/assets/1ccb73bc-971b-4a4b-8794-132d5ed1eca7" />

#### View in the browser 
<img width="1291" height="652" alt="image" src="https://github.com/user-attachments/assets/7d01144d-4883-4306-ace9-0a349b3c010c" />

## Monitoring & Obeservability & Log Management
full Monitoring & Logging stack is [here](https://github.com/mahmoudnasser1561/fleetman-monitoring) 
#### Fully Deployed + alerting + monitoring + logging
<img width="1299" height="347" alt="Screenshot from 2025-10-27 20-24-27" src="https://github.com/user-attachments/assets/2a694656-6698-44b2-93ab-8e0e9ca7651d" />
