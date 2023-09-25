# Aarogyata Health Management System

![image](https://github.com/pranavundre/Aarogyata/assets/90198260/7c9137d5-9fa6-40bc-b0ce-501665a886cd)


## Overview

Aarogyata is a comprehensive health management system designed to centralize health records for citizens. This system provides unique identification cards to individuals involved in the medical records process, including hospitals, doctors, and patients. Aarogyata enables efficient access to medical records and grants central medical authorities the ability to monitor healthcare activities as needed.

### Why Aarogyata?

- **Efficiency**: Aarogyata ensures medical practitioners have quick access to patient records, leading to more efficient treatment.

- **Preventing Misuse**: It helps prevent the misuse of drugs, as patients only receive medication for their diagnosed conditions.

- **Central Oversight**: The system allows central authorities to manage medical institutions and practitioners, addressing malpractice and misuse of power.

## Entities and Attributes

- **Card**: Contains user type, expiry date, status, credit balance, phone number, Aadhar number, residence, blood group, email, gender, name, and date of birth.

- **Administrator**: Includes card ID, license number, and department.

- **Hospital**: Comprises hospital ID, location, name, type (government/private), license number, telephone number, and hospital fees.

- **Doctor**: Contains card ID, specialty, license number, fees, and hospital ID.

- **Patient**: Includes card ID, ongoing treatment, and previous health records.

- **Diseases**: Consists of disease ID, name, treated by doctor specialty, and symptoms.

## Data Requirements

- Every person in the system has a personal Aarogyata Card with various attributes.

- The Administrator has the highest authority and can manage patient, doctor, and hospital data, as well as add or remove diseases.

- Hospitals assign patients to doctors based on ailments, update patient treatment data, and assist with past ongoing treatments.

- Doctors can add ongoing treatments, modify their fees, manage their credit balance, add hospital IDs, and update patient records.

- Patients should regularly update their records, book appointments, and view ongoing treatments.

## Functional Requirements

### Administrator

- Manages all entities.
- Must be a government employee or an authorized firm.
- Can change details of all other entities, delete, append, or update attributes.
- Authorized to make changes to hospital, doctor, and patient attributes.
- Can delete non-functional hospitals and append new diseases.

### Hospital

- Assigns patients to doctors.
- Updates patient treatment data.
- Helps patients with past ongoing treatments.

### Doctor

- Adds ongoing treatments.
- Manages fees.
- Has access to credit balance.
- Adds new hospital IDs.
- Manages patient records.

### Patient

- Updates records.
- Books appointments.
- Can be registered under multiple hospital IDs.
- Views ongoing treatments.

## DML Operations

### Data Modification

- Administrators can update hospital telephone numbers, append disease symptoms, and append doctor specialties.
- Hospitals can update their credit balance, add new diseases, append disease symptoms, and update hospital fees.
- Doctors can append patient ongoing treatments, update fees, and add new hospital IDs.
- Patients can view doctor information, choose doctors by specialty, and pay hospital fees.
- Diseases can be added by hospitals with license numbers or by administrators.

### Data Deletion

- Administrators can remove inactive patients, doctors, and administrators, and remove hospitals with defunct IDs.
- Hospitals can remove seasonal disease symptoms.

### Data Retrieval

- Administrators can retrieve hospitals near a specific location, doctors specializing in specific diseases, and inactive patients.
- Hospitals can retrieve diseases with specific symptoms and all doctors associated with a hospital.
- Doctors can retrieve diseases with specific symptoms and hospital fees.
- Patients can retrieve doctor information, choose doctors by specialty, and pay hospital fees.
- Diseases can be added by a specific hospital with a license number or by administrators.

## Enhanced Entity Relationship Diagram

![image](https://github.com/pranavundre/Aarogyata/assets/90198260/6dfa6319-0dfc-4dbc-a38e-99c593be72cf)

## Relational Diagram

![image](https://github.com/pranavundre/Aarogyata/assets/90198260/9f13bfed-53da-4e98-946a-b07b76db28a6)


## Documentation

For more details and SQL code for SQL schema creation and operation instructions, please refer to the provided documentation.
