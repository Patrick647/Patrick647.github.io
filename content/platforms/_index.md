---
title: Platforms
cms_exclude: true
type: landing

design:
  spacing: '2.5rem'

sections:
  - block: clinical-focus
    id: focus
    content:
      title: Platform Focus
      subtitle: "Three systems that show how AI, hospital data, and pharmacist review can be turned into usable clinical infrastructure."
      cards:
        - title: ADR Intelligent Reporting
          text: A medication-safety workflow that turns clinical messages and hospital-data triggers into reviewable ADR signals and report drafts.
          icon: hero/clipboard-document-check
          url: /platforms/adr-reporting/
          tags: ["Signal review", "LLM extraction", "Report workflow"]
        - title: Clinical Pharmacist Workstation
          text: A daily workbench that brings patient data, medication review, TDM/PK, TPN, MTM, pathway review, and pharmacy quality work into one interface.
          icon: hero/computer-desktop
          url: /platforms/pharmacist-workstation/
          tags: ["Patient 360", "Ward workflow", "Clinical documentation"]
        - title: Clinical Pharmacist Training Base
          text: A training-management system that standardizes paper-style tasks, mentor review, progress tracking, and batch exports.
          icon: hero/academic-cap
          url: /platforms/training-base/
          tags: ["Training records", "Mentor review", "Export center"]
    design:
      background:
        color: white

  - block: platform-screens
    id: screens
    content:
      title: Interface Snapshots
      subtitle: Visual previews distilled from the local systems' actual front-end structure.
      screens:
        - kicker: Medication safety
          title: ADR Intelligent Reporting System
          description: "The interface is organized around message monitoring, signal mining, report management, patient self-reporting, and rule configuration, so the pharmacist can move from signal to report without leaving the workflow."
          window_title: ADR Intelligent Reporting System
          image: /media/platforms/adr-system.png
          image_alt: English interface preview of the ADR intelligent reporting system
          url: /platforms/adr-reporting/
          nav: ["Message Monitor", "Signal Mining", "Reports", "Analytics", "Patient Self-report", "Rule Center"]
          chips: ["ADR only", "Unreported", "Batch drafts", "Sync CHPS"]
          features:
            - "Clinical messages and structured triggers are converted into reviewable safety work."
            - "The pharmacist remains the decision point before submission."
          rows:
            - status: High confidence
              main: Leukopenia and thrombocytopenia after chemotherapy
              meta: Rule trigger with LLM-assisted completion enters report draft
            - status: Review
              main: Liver function abnormality after medication
              meta: Drug, symptom, and patient context extracted automatically
            - status: Synced
              main: CHPS report status returned to local workflow
              meta: Local review and submitted-report state remain traceable
        - kicker: Clinical operations
          title: Clinical Pharmacist Workstation
          description: "The workstation reads like a real pharmacist cockpit: patient cards, patient 360, ward-round notes, consultations, TDM/PK, neonatal pharmacy, clinical pathways, order review, statistics, and quality control."
          window_title: Clinical Pharmacist Workstation
          image: /media/platforms/pharmacist-workstation.png
          image_alt: English interface preview of the clinical pharmacist workstation
          url: /platforms/pharmacist-workstation/
          nav: ["Monitoring", "Patient 360", "Ward Rounds", "Consultation", "MTM Clinic", "TDM", "Neonatal Pharmacy", "Quality Control"]
          chips: ["Ward filter", "Patient 360", "Save note", "Export documents"]
          features:
            - "Multi-source patient data is reorganized around pharmacist decisions."
            - "Clinical documents are generated from structured data and editable pharmacist input."
          rows:
            - status: Risk
              main: Inpatient cards with medication-risk indicators
              meta: Orders, abnormal labs, antimicrobials, and allergy history merged
            - status: TDM/PK
              main: Vancomycin dosing calculator and report workflow
              meta: Initial regimen, dose adjustment, and custom simulation
            - status: PN/TPN
              main: Neonatal parenteral nutrition review
              meta: Current PN, trends, and review issues shown together
        - kicker: Education infrastructure
          title: Clinical Pharmacist Training Base
          description: "The training base turns fragmented teaching records into a managed workflow: trainees submit paper-style forms, mentors review them, administrators watch progress, and outputs can be exported."
          window_title: Clinical Pharmacist Training Base
          image: /media/platforms/training-base.png
          image_alt: English interface preview of the clinical pharmacist training base
          url: /platforms/training-base/
          nav: ["Progress", "Review Queue", "Task Records", "Rotations", "Mentors", "Export Center"]
          chips: ["New task", "Submit", "Review", "Export Word"]
          features:
            - "Paper-style forms preserve the familiar training record format."
            - "Review state and export tools make training progress easier to audit."
          rows:
            - status: Progress
              main: Trainee progress overview
              meta: Targets, submissions, approvals, and current rotation in one view
            - status: Review
              main: Mentor review queue
              meta: Approval, rejection comments, and status history are retained
            - status: Export
              main: Export center
              meta: Word documents, attendance sheets, progress tables, and trainee ZIP packages
    design:
      background:
        color: white

  - block: clinical-focus
    id: capabilities
    content:
      title: What this work demonstrates
      subtitle: "The emphasis is not that the systems are large; it is that they connect messy clinical data to usable pharmacist decisions."
      cards:
        - title: AI with pharmacist oversight
          text: Rules and LLM extraction help surface and structure candidate information, while review and submission remain pharmacist-led.
          icon: hero/cpu-chip
          tags: ["Triage", "Extraction", "Human review"]
        - title: Data brought back to workflow
          text: Orders, labs, EMR narratives, nursing records, cultures, exams, vitals, and identifiers are reorganized into practical work surfaces.
          icon: hero/circle-stack
          tags: ["Patient context", "Timeline", "Normalization"]
        - title: Outputs that survive daily use
          text: The systems produce reports, progress views, and editable Word or Excel outputs that match real hospital documentation needs.
          icon: hero/document-check
          tags: ["Reports", "Dashboards", "Exports"]
    design:
      background:
        color: white
---
