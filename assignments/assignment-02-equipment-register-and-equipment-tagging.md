# Assignment 02 — Equipment Register & Equipment Tagging

**Revision:** 00 — Training Exercise  
**Project:** Northstar Potash Processing Facility  
**Role:** Systems Completion Coordinator

## 1. Assignment Overview

The project Engineering team has issued an initial equipment list. The Construction Manager requires a controlled Equipment Register that Systems Completion can use to track individual equipment items through construction, pre-commissioning, commissioning, and handover.

The objective is to connect individual equipment tags to the correct systems and subsystems established in Assignment 01.

As Systems Completion Coordinator, I am responsible for organizing equipment information, checking data quality, maintaining traceability, identifying missing information, and coordinating clarification where required.

I am **not** responsible for designing the process, selecting equipment, or making engineering decisions.

## 2. Assignment Objectives

Create an Equipment Register that allows the project team to identify:

- What equipment exists within the project.
- Which system and subsystem each equipment item belongs to.
- Which plant area and discipline it belongs to.
- Which contractor is responsible for the equipment scope.
- Which engineering document identifies the equipment.
- Whether the equipment information is complete and verified.
- What outstanding information or clarification is required.

The main question the register must answer is:

> For any equipment tag, which system and subsystem does it belong to, who is responsible for it, and what completion evidence will eventually demonstrate that it is ready for handover?

## 3. Engineering Input — Preliminary Equipment List

The following fictional equipment list has been issued by Engineering for this training exercise.

| Equipment Tag | Equipment Description | Area | Discipline | Drawing Reference |
|---|---|---:|---|---|
| CV-101-001 | Raw ore reclaim conveyor | 100 | Mechanical | PFD-100-001 |
| CR-201-001 | Primary crusher | 200 | Mechanical | PFD-200-001 |
| CV-201-001 | Crushed ore transfer conveyor | 200 | Mechanical | PFD-200-001 |
| TK-301-001 | Slurry preparation tank | 300 | Mechanical | PFD-300-001 |
| DS-301-001 | Desliming equipment | 300 | Mechanical | PFD-300-002 |
| P-320-001 | Desliming reagent transfer pump | 300 | Mechanical | P&ID-320-001 |
| FC-350-001 | Flotation cell 1 | 300 | Mechanical | PFD-350-001 |
| P-350-001 | Product liquor transfer pump | 300 | Mechanical | P&ID-350-001 |
| TK-501-001 | Raw water storage tank | 500 | Mechanical | P&ID-501-001 |
| SWGR-601-001 | Main electrical switchgear | 600 | Electrical | SLD-600-001 |
| PLC-701-001 | Main control system PLC | 700 | Controls | Not provided |

Use the system and subsystem registers established in Assignment 01, Revision 01A, as the baseline for equipment allocation.

## 4. Required Deliverable

Create a new worksheet in the project Excel workbook named:

**Equipment Register**

The worksheet must contain the following columns:

| Column | Description |
|---|---|
| Equipment Tag | Unique equipment identifier supplied by Engineering |
| Equipment Description | Equipment description from the source list |
| Plant Area | Physical plant area |
| Discipline | Mechanical, Electrical, Controls, etc. |
| System Number | Parent system identifier |
| System Name | Parent system name |
| Subsystem Number | Parent subsystem identifier |
| Subsystem Name | Parent subsystem name |
| Responsible Contractor | Contractor responsible for the equipment scope |
| Drawing Reference | Engineering source drawing reference |
| Data Status | Verification status of the equipment record |
| Remarks / Action Required | Missing information, conflicts, or required clarification |

## 5. Data Status Definitions

Use the following statuses:

| Status | Definition |
|---|---|
| Verified | Information has been checked against the available source documentation. |
| Pending Verification | A proposed allocation or detail still requires confirmation. |
| Clarification Required | Information is missing, conflicting, or ambiguous and requires clarification. |

Do not invent missing drawing references, equipment information, or contractor assignments.

Where information is uncertain, record the issue and identify the party responsible for clarifying it.

## 6. Tasks to Complete

For each of the 11 equipment items:

1. Identify the appropriate parent system.
2. Identify the appropriate parent subsystem.
3. Identify the responsible contractor, where this can reasonably be established from Assignment 01.
4. Record the engineering drawing reference.
5. Assign an appropriate data status.
6. Record any missing information, inconsistencies, or required clarification in the remarks column.

Equipment must be allocated using the existing Revision 01A system and subsystem structure.

Do not create new equipment tags. Engineering has already supplied the equipment identifiers.

## 7. Assessment Criteria

The completed Equipment Register will be assessed against the following criteria:

### 7.1 Systemization
- Equipment is allocated to the appropriate system.
- Equipment is allocated to the appropriate subsystem.
- The existing system hierarchy is applied consistently.

### 7.2 Traceability
- Equipment tags are recorded accurately.
- Equipment records can be traced to their engineering source documents.
- Equipment can be traced through the system and subsystem hierarchy.

### 7.3 Data Quality
- Equipment identifiers and descriptions are consistent.
- Plant areas and disciplines are recorded correctly.
- Missing or incomplete information is identified.

### 7.4 Responsibility
- Responsible contractors are identified where supported by available project information.
- Unsupported responsibility assignments are not presented as confirmed facts.

### 7.5 Issue Management
- Missing information is flagged.
- Ambiguous equipment allocations are identified.
- Engineering clarifications are raised rather than resolved through assumptions.

## 8. Important Completion Management Principle

An equipment item appearing in the Equipment Register does not mean that it is mechanically complete, tested, commissioned, or ready for handover.

The Equipment Register identifies and organizes equipment within the project systemization structure.

Actual completion must be demonstrated through appropriate inspection records, test records, certificates, check sheets, and other approved completion evidence.

The expected traceability relationship is:

**Equipment Tag → Subsystem → System → Completion Records → Handover**

## 9. Expected Submission

Submit the completed Equipment Register containing all 11 equipment items.

The register may contain entries marked Pending Verification or Clarification Required. Correctly identifying an information gap is preferable to making an unsupported assumption.

The completed register will be reviewed by the Systems Completion Lead, who will assess the system allocations, data quality, traceability, responsibility assignments, and issue management approach.

**End of Assignment 02 — Revision 00**
