# Gas Station Management System

A comprehensive management solution for gas stations designed to streamline administrative tasks, sales, services, and customer loyalty programs.

## Overview
This project implements a multi-user platform with Role-Based Access Control (RBAC). The system allows for distinct operational flows, ranging from high-level administration to customer-facing features like service scheduling and reward redemption.

## Key Features
* **Authentication & RBAC:** Secure login with six predefined permission levels.
* **Sales Management:** Real-time registration of sales and product inventory.
* **Service Scheduling:** Assignment and tracking of technical services.
* **Loyalty Program:** Points accumulation, rewards catalog, and automated redemption.
* **Operational Monitoring:** Pump status alerts and availability management.

## Tech Stack
* **Backend:** PHP
* **Frontend:** HTML, CSS, JavaScript, Bootstrap
* **Database:** MySQL (Modeled via MySQL Workbench)
* **Environment:** XAMPP (Apache & MySQL)

## User Roles
| Role | Main Responsibilities |
| :--- | :--- |
| **Administrator** | Full user management and account oversight. |
| **Station Manager** | Pump alert monitoring and operational data. |
| **Operator** | Sales registration and product entry. |
| **Admin Staff** | Service assignment and loyalty program management. |
| **Service Staff** | Execution of scheduled services and system commands. |
| **Customer** | Service booking and points/rewards consultation. |

## Database Structure
The relational database consists of the following core tables:
* **Users:** `utilizadores`, `login`.
* **Sales:** `venda`, `venda_item`, `produto`.
* **Services:** `servico`, `agendamento`, `indisponibilidade`.
* **Loyalty:** `cartao_fidelidade`, `movimento_cartao`.
* **Infrastructure:** `bomba`, `alerta`.

## Installation and Setup
1. **Repository:** Move the project files to the XAMPP `htdocs` directory.
2. **Database:** Import the provided SQL file using MySQL Workbench or phpMyAdmin.
3. **Server:** Start Apache and MySQL modules in the XAMPP Control Panel.
4. **Access:** Open your browser and navigate to `http://localhost/SistemaGestaoPosto`.

## Learning Objectives
This project was developed to consolidate expertise in:
* Full-stack web development using PHP and MySQL.
* Responsive UI design with Bootstrap.
* Implementation of complex permission-based logic.
* Database modeling and relational integrity.
