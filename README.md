# KayirangaDeus

### 📘 Assignment One – OOP Java Projects with Docker

This repository includes three Java-based Object-Oriented Programming (OOP) projects designed as part of an academic assignment. Each project is containerized using Docker for easy setup and deployment.

## 📁 Project Structure

- 🚀 **Mission Management System**
- 🌍 **Land Management System**
- 🌱 **Nursery School Management System**

Each system demonstrates core OOP concepts such as encapsulation, inheritance, polymorphism, and abstraction. All solutions are modular and follow clean coding standards for scalability and maintenance.

---

## 🚀 1. Mission Management System

### 🔹 Description
Simulates the management of various mission types (e.g., scientific, military, commercial), including dynamic cost calculations and validation logic based on mission parameters.

### 🔧 Technologies
- Java
- Docker
- Command Line Interface (CLI)

### 🛠️ Build Instructions
```bash
javac missionManagementSystem/*.java
```
### ▶️ Run Locally

```bash
java missionManagementSystem.Main
```
### 🐳 Docker Commands

```bash
docker build -t oop_26699_mission_management_system .
docker tag oop_26699_mission_management_system deus12/oop_26699_mission_management_system
docker push deus12/oop_26699_mission_management_system
docker run -it deus12/oop_26699_mission_management_system
```

### 🌍 2. Land Management System

## 🔹 Description

Handles different land types (residential, agricultural, commercial) with relevant tax or fee calculations. Incorporates validation logic based on land usage and area.

## 🔧 Technologies

Java (Inheritance, Abstraction)

Docker

## 🛠️ Build Instructions

```bash
javac landManagementSystem/*.java
```

### ▶️ Run Locally

```bash
java landManagementSystem.Main
```

### 🐳 Docker Commands

```bash
docker build -t oop_26699_land_management_system .
docker tag oop_26699_land_management_system deus12/oop_26699_land_management_system
docker push deus12/oop_26699_land_management_system
docker run -it deus12/oop_26699_land_management_system
```

### 🌱 3. Nursery School Management System

## 🔹 Description

Manages information about various plant types, their growth stages, watering needs, and selling prices. Applies OOP principles like polymorphism, abstraction, and encapsulation.

## 🔧 Technologies

Java

Docker

## 🛠️ Build Instructions
```bash
javac nurserySchoolManagementSystem/*.java
```

### ▶️ Run Locally

```bash
java nurserySchoolManagementSystem.Main
```

### 🐳 Docker Commands

```bash
docker build -t oop_26699_nursery_school_management_system .
docker tag oop_26699_nursery_school_management_system deus12/oop_26699_nursery_school_management_system
docker push deus12/oop_26699_nursery_school_management_system
docker run -it deus12/oop_26699_nursery_school_management_system
```

### 👨‍🎓 Author

KAYIRANGA Deus – 26699

**Docker Hub: deus12**

### 📦 Notes

All images are based on Java 17 using the slim JDK variant.

Each project is self-contained and can run independently via Docker.

Ensure Docker is properly installed and running before executing any container commands.


