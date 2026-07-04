# Healthcare Clinical Ontology

## Overview
This project presents a Healthcare Clinical Ontology developed using OWL 2.0 in the Protégé environment. The ontology models important healthcare concepts such as patients, doctors, nurses, hospitals, diseases, treatments, appointments, prescriptions, medical records, and insurance.

The ontology demonstrates semantic relationships among healthcare entities and supports logical reasoning using the HermiT Reasoner.

---

## Tools Used

- Protégé 5.x
- OWL 2.0
- HermiT Reasoner
- GitHub

---

## Ontology Structure

### Main Classes
- Person
  - Patient
  - Doctor
  - Nurse

- Healthcare Facility
  - Hospital
  - Department

- Medical Resource
  - Medicine
  - Prescription
  - Medical Record
  - Equipment

- Medical Service
  - Appointment
  - Diagnosis
  - Treatment
  - Surgery
  - Vaccination

- Medical Condition
  - Disease
  - Symptom

- Administrative Entity
  - Insurance

---

## Object Properties

Examples include:

- hasDisease
- diagnosedWith
- receivesTreatment
- treatedBy
- prescribedMedicine
- hasAppointment
- hasPrescription
- hasMedicalRecord
- hasInsurance
- admittedTo
- worksIn
- belongsToDepartment

---

## Data Properties

Examples include:

- patientName
- doctorName
- nurseName
- hospitalName
- diseaseName
- medicineName
- diagnosisDate
- dosage
- insuranceID
- gender

---

## Reasoning

The ontology was verified using the HermiT Reasoner.

The following DL Queries were successfully executed:

- Patient
- Doctor
- Nurse
- Patient and hasDisease some Disease

The ontology was found to be logically consistent.

---

## Repository Contents

- HealthcareClinicalOntology.owl
- Project_Report.pdf
- README.md

---

## Author

Ayna Ramzan

Knowledge Representation Project

University of Verona
