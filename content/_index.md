---
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '2rem'

sections:
  - block: resume-biography-3
    id: about
    content:
      username: me
      text: |
        I am a clinical pharmacist building AI-enabled clinical pharmacy platforms inside real hospital workflows.

        My current work focuses on three connected systems: an intelligent adverse drug reaction reporting platform, a clinical pharmacist workstation, and a clinical pharmacist training base. Together, these projects translate large language models, rule engines, hospital data integration, pharmacokinetic calculation, and document automation into daily medication safety, pharmaceutical care, and education management.

        I am especially interested in AI applications that are not just demonstrations, but usable clinical infrastructure: systems that capture safety signals, reduce documentation burden, standardize pharmacist work, and make clinical expertise easier to deploy, evaluate, and scale.
    design:
      avatar:
        size: large
        shape: circle
      background:
        color: white

  - block: impact-metrics
    id: impact
    content:
      title: AI-enabled clinical pharmacy platforms
      subtitle: Current work centered on medication safety surveillance, pharmacist workflow intelligence, and structured training management.
      metrics:
        - value: "3"
          label: Active platform directions
          detail: ADR reporting, pharmacist workstation, and training base
          icon: hero/squares-2x2
        - value: "0.970"
          label: Hybrid ADR detection F1
          detail: Rule-based signals combined with AI-assisted extraction and triage
          icon: hero/clipboard-document-check
        - value: "10+"
          label: Workstation modules
          detail: Clinical pharmacist workflows organized into a single operating surface
          icon: hero/computer-desktop
        - value: "17"
          label: Training task types
          detail: Structured clinical pharmacist training, review, and export workflows
          icon: hero/building-library
    design:
      background:
        color: white

  - block: featured-work
    id: explore
    content:
      title: Explore
      subtitle: The site is organized into separate pages so each section stays focused.
      items:
        - kicker: Current work
          title: Platforms
          text: The main portfolio page for ADR reporting, the clinical pharmacist workstation, and the clinical pharmacist training base.
          status: Focused page
          url: /platforms/
          stats:
            - "AI-enabled clinical pharmacy systems"
            - "Medication safety, workflow, and training infrastructure"
        - kicker: Evidence
          title: Publications
          text: Manuscripts and publications connected to ADR informatics, individualized medication safety, and clinical pharmacy training.
          status: Focused page
          url: /publications/
          stats:
            - "ADR platform manuscripts"
            - "Published supporting evidence"
        - kicker: Background
          title: CV
          text: Education, hospital experience, professional service, intellectual property, and recognitions.
          status: Focused page
          url: /cv/
          stats:
            - "Clinical pharmacist profile"
            - "Credentials and awards"
    design:
      background:
        color: white
---
