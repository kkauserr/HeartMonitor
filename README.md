# HeartMonitor
Heart Health Imaging and Recording System Implementation

Welcome to my repository for Homework #4 in CS 360, Introduction to Software Engineering at SCAI, Arizona State University. This assignment focuses on implementing a heart health imaging and monitoring system using JavaFX, as outlined in our coursework.

## Overview

In previous homework assignments, we developed use cases, identified actors, and created a class diagram for a heart health imaging and monitoring system. For Homework #4, we are tasked with implementing specific functionalities of this system, focusing on various user perspectives including receptionists, technicians, and patients.

### Functionalities Implemented

- **Main View (UI)**:
  - The primary user interface of the system.

- **Receptionist View**:
  - Collects and stores patient information.
  - Generates a unique 5-digit patient ID.
  - Creates a patient file named after the patient ID (e.g., `12345_PatientInfo.txt`).

- **Technician View**:
  - Allows technicians to enter data from heart CT scans.
  - Validates that all required fields are filled before file creation.
  - Saves CT scan results in a file named after the patient ID (e.g., `12345CTResults.txt`).

- **Patient View**:
  - Enables patients to view their CT scan results by entering their patient ID.
  - Displays error messages if the data is not available or the ID is incorrect.
