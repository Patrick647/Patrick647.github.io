---
title: Clinical Pharmacist Workstation
cms_exclude: true
type: landing

design:
  spacing: '2.5rem'

sections:
  - block: clinical-focus
    id: overview
    content:
      title: Clinical Pharmacist Workstation
      subtitle: "A pharmacist-facing workbench that reorganizes hospital data into daily clinical decisions, documentation, TDM/PK support, and pharmacy quality workflows."
      cards:
        - title: Clinical problem
          text: Pharmacists need to move between orders, labs, EMR narratives, nursing records, culture results, calculators, and Word templates before making a practical recommendation.
          icon: hero/arrows-right-left
          tags: ["Data fragmentation", "Documentation burden", "Decision latency"]
        - title: What I built
          text: A modular workstation covering patient monitoring, Patient 360, ward rounds, consultations, MTM clinic, TDM, neonatal pharmacy, clinical pathways, order review, and quality control.
          icon: hero/computer-desktop
          tags: ["Patient 360", "TDM/PK", "Ward workflow"]
        - title: My role
          text: I translated clinical pharmacy workflows into data-driven modules, exportable documents, risk filters, and review surfaces aligned with real hospital work.
          icon: hero/user-circle
          tags: ["Workflow design", "Hospital data", "Document export"]
    design:
      background:
        color: white

  - block: platform-screens
    id: interface
    content:
      title: Interface Preview
      subtitle: "A de-identified English preview showing the workstation as a clinical cockpit rather than a static report page."
      screens:
        - kicker: Clinical operations
          title: Pharmacist clinical cockpit
          description: "The interface keeps patient risk, medication context, timelines, TDM/PK calculation, and exportable notes close to the pharmacist's daily decision path."
          window_title: Clinical Pharmacist Workstation
          image: /media/platforms/pharmacist-workstation.png
          image_alt: English interface preview of the clinical pharmacist workstation
          features:
            - "Patient-level risk indicators are surfaced from orders, abnormal labs, antimicrobials, cultures, and allergy history."
            - "Medication timelines and laboratory trends support pharmacist interpretation rather than simple data display."
            - "Clinical notes and review documents are generated from structured data plus editable pharmacist input."
    design:
      background:
        color: white

  - block: clinical-focus
    id: modules
    content:
      title: Core capability areas
      subtitle: "The workstation is strongest when viewed as an integrated clinical operating system for pharmacists."
      cards:
        - title: Patient 360 and monitoring
          text: Patient cards, risk flags, order context, abnormal laboratory results, nursing/EMR traces, and department filters support fast prioritization.
          icon: hero/users
          tags: ["Patient context", "Risk flags", "Prioritization"]
        - title: TDM / PK support
          text: Vancomycin dosing, dose adjustment, simulation, and report workflows bring pharmacokinetic reasoning into the same work surface.
          icon: hero/beaker
          tags: ["Vancomycin", "AUC", "Dose adjustment"]
        - title: Clinical documentation
          text: Ward-round notes, consultation records, MTM follow-up, clinical pathway review, and order-review outputs are designed for real hospital documentation formats.
          icon: hero/document-check
          tags: ["Ward rounds", "MTM", "Quality review"]
    design:
      background:
        color: white

  - block: clinical-focus
    id: value
    content:
      title: What this demonstrates
      subtitle: "The workstation shows the ability to build usable AI-adjacent infrastructure around pharmacist judgment, not merely a dashboard."
      cards:
        - title: Data-to-decision design
          text: "The system reorganizes complex hospital data around actions pharmacists actually take: assess risk, write notes, adjust therapy, and produce auditable outputs."
          icon: hero/light-bulb
          tags: ["Clinical reasoning", "Actionable UI", "Workflow"]
        - title: Operational depth
          text: Multiple pharmacy service areas are connected through consistent patient context and documentation patterns, reducing isolated one-off tools.
          icon: hero/squares-2x2
          tags: ["Modular system", "Shared context", "Scalable workflow"]
        - title: Implementation readiness
          text: The emphasis on export formats, editable records, and ward-level work surfaces makes the platform understandable to clinicians and hospital managers.
          icon: hero/rocket-launch
          tags: ["Exports", "Clinician adoption", "Hospital operations"]
    design:
      background:
        color: white
---
