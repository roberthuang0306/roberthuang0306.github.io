---
title: ''
summary: ''
date: 2026-01-01
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      headings:
        about: About
        education: Education
    design:
      name:
        size: md
      avatar:
        size: large
        shape: rounded
      show_status: false
      background:
        color: white

  - block: markdown
    id: research
    content:
      title: Research
      icon: beaker
      align_right: true
      text: |-
        My work centers on electronic design automation, physical design, and 3D integrated circuits.

        - **3D IC Optimization:** 3D-via reduction, inter-die cell relocation, and timing optimization.
        - **SRC JUMP 2.0 CHIMES:** reduced legacy-node 3D IC WNS by 50–93% compared with the state of the art.
        - **Die Bonding Bumps and Pads Legalization:** developed a refined 3D-via legalization stage with no overlaps below 40% via utilization.
    design:
      columns: '1'

  - block: markdown
    id: experience
    content:
      title: Work Experience
      icon: briefcase
      align_right: true
      text: |-
        - **Synopsys Inc., Synopsys Headquarters — R&D Engineer (May–December 2025):** researched machine-learning-based signal-integrity analysis for 2.5D ICs by evaluating multiple models and independently implemented two C++ prototypes into the main branch.
        - **Synopsys CCD Team — Software Engineer R&D Intern (July–August 2021):** improved flip-flop merging and timing quality across 13 industrial benchmarks.
        - **Cadence Conformal Team — Software Engineer R&D Intern (June–September 2020):** generated more than 2,000 ECO test cases and proposed three improved flows.
    design:
      columns: '1'

  - block: markdown
    id: publications
    content:
      title: Publications
      icon: document-text
      align_right: true
      text: |-
        - **Yen-Hsiang Huang** and Sung Kyu Lim, “CLK-3D: RC-Calibrated Differentiable Clock-Tree Optimization for 3D ICs”, IEEE/ACM International Conference on Computer-Aided Design, 2026.
        - **Yen-Hsiang Huang** and Sung Kyu Lim, “Snake-3D: Differentiable Learning for Cross-Tier Logic Path Snaking Optimization in 3D ICs”, IEEE/ACM International Conference on Computer-Aided Design, 2025. ([pdf](https://sites.usc.edu/sccad/Huang-ICCAD25))
        - **Yen-Hsiang Huang**, Sai Pentapati, Anthony Agnesina, Moritz Brunion, and Sung Kyu Lim, “On Legalization of Die Bonding Bumps and Pads for 3D ICs”, IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2024. ([pdf](https://sites.usc.edu/sccad/tcad24-robert))
        - Sai Pentapati, Anthony Agnesina, Moritz Brunion, **Yen-Hsiang Huang**, and Sung Kyu Lim, “On Legalization of Die Bonding Bumps and Pads for 3D ICs”, ACM International Symposium on Physical Design, 2023. ([pdf](https://sites.usc.edu/sccad/3569052.3578925))
    design:
      columns: '1'

  - block: markdown
    id: awards
    content:
      title: Additional Awards
      icon: trophy
      align_right: true
      text: |-
        - **Honorable Mention Award, ACM ISPD Contest 2021** — 4th place worldwide.
        - **TSMC Scholarship for Undergraduate Students.**
        - **Ministry of Science and Technology Undergraduate Research Grant** — wafer-scale physics modeling for finite-element methods.
        - **The Dean's List Award** — ranked 1st with a 4.30/4.30 semester GPA.
    design:
      columns: '1'

---
