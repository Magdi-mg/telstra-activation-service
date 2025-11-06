
# Telstra SIM Activation Microservice

This project simulates a small Spring Boot RESTful web service for activating Telstra SIM cards and retrieving SIM information.  
It is based on the **Telstra Starter Repo** instructions and follows Spring Boot best practices.

---

## 🧩 Project Overview

The service exposes two main endpoints:

| Endpoint | Method | Description |
|-----------|---------|-------------|
| `/api/activate` | `POST` | Activates a SIM card by number and assigns an activation ID |
| `/api/sim/{id}` | `GET` | Retrieves details of an activated SIM by its ID |

---

## ⚙️ Technologies Used
- Java 17  
- Spring Boot
