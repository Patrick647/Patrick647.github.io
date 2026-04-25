---
title: Clinical Pharmacist Training Base
cms_exclude: true
type: landing

design:
  spacing: '2.5rem'

sections:
  - block: clinical-focus
    id: overview
    content:
      title: Clinical Pharmacist Training Base
      subtitle: "A training-management platform that turns fragmented clinical pharmacy teaching records into structured tasks, mentor review, progress tracking, and document-grade exports."
      cards:
        - title: Training problem
          text: Clinical pharmacy training produces many paper-style records, but progress, mentor feedback, rotation requirements, and export preparation are difficult to audit when scattered.
          icon: hero/clipboard-document-list
          tags: ["Fragmented records", "Mentor workload", "Progress audit"]
        - title: What I built
          text: A task-based training base covering trainees, mentors, rotations, paper-style forms, review state, graduation requirements, attendance, and export packages.
          icon: hero/academic-cap
          tags: ["17 task types", "Review queue", "Export center"]
        - title: My role
          text: I modeled training requirements into structured schemas, front-end paper forms, review workflows, and Word/ZIP export logic.
          icon: hero/user-circle
          tags: ["Schema design", "Paper rendering", "Workflow"]
    design:
      background:
        color: white

  - block: platform-screens
    id: interface
    content:
      title: Interface Preview
      subtitle: "A de-identified English preview showing training progress, mentor review, paper-style forms, and export readiness."
      screens:
        - kicker: Education infrastructure
          title: Training compliance workspace
          description: "The interface lets trainees submit structured tasks, mentors review them, and administrators monitor completion across task types and rotations."
          window_title: Clinical Pharmacist Training Base
          image: /media/platforms/training-base.png
          image_alt: English interface preview of the clinical pharmacist training base
          features:
            - "Paper-style task forms preserve familiar training-document formats while making the data structured."
            - "Draft, submitted, approved, and rejected states are retained for review and audit."
            - "Exports support individual Word documents and trainee-level packages for administrative use."
    design:
      background:
        color: white

  - block: clinical-focus
    id: workflow
    content:
      title: Training workflow
      subtitle: "The platform treats training records as a governed workflow rather than a folder of files."
      cards:
        - title: Structured task schemas
          text: Each task type has a schema, front-end form, and exporter, making records consistent while still resembling hospital paper documents.
          icon: hero/code-bracket-square
          tags: ["Task schema", "Paper form", "Exporter"]
        - title: Mentor review
          text: Trainee submissions move through draft, submitted, approved, and rejected states with comments and review history.
          icon: hero/chat-bubble-left-right
          tags: ["Review state", "Comments", "Traceability"]
        - title: Progress dashboard
          text: Graduation requirements can be summarized by task type, approval status, rotation, and trainee, enabling administrators to see training gaps quickly.
          icon: hero/chart-bar-square
          tags: ["Requirements", "Completion", "Audit"]
    design:
      background:
        color: white

  - block: clinical-focus
    id: value
    content:
      title: What this demonstrates
      subtitle: "This platform connects your education research background with a concrete implementation for pharmacist training management."
      cards:
        - title: Education research translation
          text: The platform operationalizes the logic behind pharmacist competency evaluation and turns training requirements into measurable, reviewable outputs.
          icon: hero/book-open
          tags: ["Competency", "Assessment", "Training quality"]
        - title: Documentation precision
          text: Paper-style rendering and Word export show attention to how hospital training documents are actually reviewed, signed, archived, and inspected.
          icon: hero/document-arrow-down
          tags: ["Word export", "Paper style", "Audit package"]
        - title: Scalable management
          text: By separating task schema, form UI, review workflow, and exporter logic, new training tasks can be added without redesigning the whole system.
          icon: hero/puzzle-piece
          tags: ["Modular", "Extensible", "Administration"]
    design:
      background:
        color: white
---
