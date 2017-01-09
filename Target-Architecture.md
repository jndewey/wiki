The ePrescribe target architecture is a collection of mobile and web applications which are integrated with a Prescription Hub for purpose of automating various prescription drug processes, built-in abuse detection, and monitoring.  The goal is to provide added convenience to all parties involved, ensure patients are only receiving certified drugs, and detect/prevent the abuse of legal prescription drugs.

![](https://github.com/ttsDubai/ePharma/blob/master/docs/slides/Target%20Architecture.png)

***
## Client Applications
There are four distinct client applications found in the ePrescribe ecosystem, one for each of the primary roles involved in the prescription drug processes.

### ePrescribe Physician Application
The Physician Application is a mobile application allowing the Physician to securely view a patient's prescription history, regardless of the source of prescriptions.  The hardware includes an integrated fingerprint scanner for purpose of authenticating patients, although an EID is an optional authentication mechanism.  Physicians use this application to create new prescriptions, review requests for prescription renewals, and receive alerts when the system associates their patient activity with potential abuse.

Register patient into the system, sends an SMS to the patient which includes a link to download the Patient Mobile App (see below)

### ePrescribe Pharmacist Application
The Pharmacist Application is a mobile application allowing the Pharmacist to securely act on prescriptions they are to fill.  The hardware includes an integrated fingerprint scanner for purpose of authenticating patients, although an EID is an optional authentication mechanism. Pharmacists use this application to view prescriptions they are to fill and view patient prescription history when there is concern about the refill request.  

Patients are only permitted to pick up drugs after authenticating with the integrated fingerprint scanner, or provide a valid EID/Passport Number.  The Pharmacist is required to scan each drug dispensed to the patient, and the system will automatically associate that scanned drug to the prescription the patient is receiving. This ensures the patient is always receiving the correct drugs for each prescription.  This activity also ensures the ePharma blockchain (not included in this hackathon) has dispensed drugs deducted from its ledger.

Note the Pharmacist may also used this application to register a declined prescription refill, with rationale for declining the Patient's request.  This capability is intended to capture potential abuse, such as trying to refill an expired prescription, or requesting a refill just a few days after a prior refill.


### ePrescribe Patient Mobile App
The Patient mobile application allows the patient to view his prescriptions, both those that are currently open as well as those which are expired.

There is also a caregiver functionality which permit

caregiver

### ePrescribe Regulator Dashboard
Describe


***

## Server Components

### Web Server
Describe the application server

### Application Server
Describe the application server


Biometric integration
Microservices
Blockchain integration


Describe the blockchain

### Relational Database
Describe database


***

## Blockchain

