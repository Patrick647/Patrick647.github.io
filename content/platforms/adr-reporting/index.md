---
title: ADR Intelligent Reporting System
cms_exclude: true
type: landing

design:
  spacing: '2.5rem'

sections:
  - block: clinical-focus
    id: overview
    content:
      title: ADR Intelligent Reporting System
      subtitle: "A medication-safety platform that turns clinical instant messages and hospital-data triggers into reviewable ADR signals, report drafts, and traceable submission workflows."
      cards:
        - title: Clinical problem
          text: ADR evidence is often scattered across messages, laboratory abnormalities, medication orders, and patient narratives. Manual reporting is slow and easy to miss during routine clinical work.
          icon: hero/exclamation-triangle
          tags: ["Under-reporting", "Fragmented evidence", "Manual workload"]
        - title: What I built
          text: A workflow for message monitoring, signal mining, patient self-report intake, report management, CHPS status synchronization, and rule-center configuration.
          icon: hero/clipboard-document-check
          tags: ["Signal queue", "Draft report", "CHPS sync"]
        - title: My role
          text: I designed the clinical workflow, data logic, review states, and hybrid NLP pipeline that keeps AI assistance subordinate to pharmacist confirmation.
          icon: hero/user-circle
          tags: ["Clinical design", "Hybrid NLP", "Human review"]
    design:
      background:
        color: white

  - block: platform-screens
    id: interface
    content:
      title: Interface Preview
      subtitle: "A de-identified English preview generated from the system's actual front-end structure."
      screens:
        - kicker: Medication safety
          title: Message-to-ADR review desk
          description: "The interface brings together message monitoring, rule-triggered safety signals, LLM-assisted extraction, and pharmacist review before report submission."
          window_title: ADR Intelligent Reporting System
          image: /media/platforms/adr-system.png
          image_alt: English interface preview of the ADR intelligent reporting system
          features:
            - "Clinical IM content and structured triggers are converted into a pharmacist-readable candidate queue."
            - "Suspected drug, reaction, timing, evidence, and report completeness can be drafted automatically."
            - "Local review state and submitted-report status remain traceable after CHPS synchronization."
    design:
      background:
        color: white

  - block: clinical-focus
    id: workflow
    content:
      title: AI and data workflow
      subtitle: "The value of the system is not only extraction accuracy; it is the translation of noisy clinical traces into a governed pharmacist workflow."
      cards:
        - title: Data inputs
          text: Clinical messages, medication orders, laboratory abnormalities, rescue-medication triggers, patient self-reports, and reporting-system status are normalized into the same review surface.
          icon: hero/circle-stack
          tags: ["Messages", "Orders", "Labs", "Reports"]
        - title: Hybrid NLP layer
          text: Rules protect high-value safety signals, while LLM-assisted extraction completes narrative fields and structures candidate ADR evidence for human review.
          icon: hero/cpu-chip
          tags: ["Rules", "LLM extraction", "Confidence"]
        - title: Pharmacist checkpoint
          text: The system supports triage and drafting, but causality assessment, completeness judgment, and final submission remain pharmacist-led.
          icon: hero/check-badge
          tags: ["Review", "Causality", "Submission"]
    design:
      background:
        color: white

  - block: clinical-focus
    id: value
    content:
      title: What this demonstrates
      subtitle: "This platform shows implementation ability across clinical pharmacy, AI methods, and real hospital reporting constraints."
      cards:
        - title: Research translation
          text: The work is connected to a 2026 SSRN preprint on zero-friction ADR reporting from clinical instant messaging using hybrid NLP.
          icon: hero/document-text
          tags: ["SSRN preprint", "Hybrid NLP", "Pharmacovigilance"]
        - title: Hospital integration
          text: The system is designed around practical interfaces and review queues rather than isolated model outputs, making it closer to deployable clinical infrastructure.
          icon: hero/building-office-2
          tags: ["Workflow", "Traceability", "Operations"]
        - title: Safety-first AI
          text: Conservative retention rules preserve high-value signals such as rescue medication and hematologic toxicity flags, reducing the risk of silent misses.
          icon: hero/shield-check
          tags: ["Signal retention", "Medication safety", "Human oversight"]
    design:
      background:
        color: white
---
