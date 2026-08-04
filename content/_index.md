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
        - **Synopsys Inc., Synopsys Headquarters — R&D Engineer (May–December 2025):** researched AI-based signal-integrity analysis for 2.5D ICs using graph neural networks and independently implemented two C++ prototypes into the main branch.
        - **Synopsys CCD Team — Software Engineer R&D Intern (July–August 2021):** improved flip-flop merging and timing quality across 13 industrial benchmarks.
        - **Cadence Conformal Team — Software Engineer R&D Intern (June–September 2020):** generated more than 2,000 ECO test cases and proposed three improved flows.

        <div class="not-prose mt-8 grid grid-cols-1 gap-5 sm:grid-cols-2">
        <div class="flex items-center justify-between gap-4 rounded-xl border border-gray-200 bg-white p-5 shadow-sm dark:border-gray-700 dark:bg-gray-800">
        <div class="flex min-w-0 items-center gap-3">
        <div class="flex h-10 w-10 flex-shrink-0 items-center justify-center rounded-full bg-primary-100 text-primary-600 dark:bg-primary-900/50 dark:text-primary-300">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.7" stroke="currentColor" class="h-7 w-7" aria-hidden="true"><path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 0 0-3.375-3.375h-1.5A1.125 1.125 0 0 1 13.5 7.125v-1.5A3.375 3.375 0 0 0 10.125 2.25H8.25m.75 12 3 3m0 0 3-3m-3 3v-6m-1.5-9H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 0 0-9-9Z" /></svg>
        </div>
        <h3 class="text-lg font-semibold text-gray-900 dark:text-white">CV</h3>
        </div>
        <div class="flex flex-shrink-0 flex-col gap-2">
        <a href="/cv/" class="inline-flex items-center justify-center rounded-md bg-primary-600 px-3 py-2 text-sm font-semibold text-white transition hover:bg-primary-700">View</a>
        <a href="/uploads/cv.pdf" download class="inline-flex items-center justify-center rounded-md border border-primary-600 px-3 py-2 text-sm font-semibold text-primary-700 transition hover:bg-primary-50 dark:text-primary-300 dark:hover:bg-primary-900/40">Download</a>
        </div>
        </div>
        <div class="flex items-center justify-between gap-4 rounded-xl border border-gray-200 bg-white p-5 shadow-sm dark:border-gray-700 dark:bg-gray-800">
        <div class="flex min-w-0 items-center gap-3">
        <div class="flex h-10 w-10 flex-shrink-0 items-center justify-center rounded-full bg-secondary-100 text-secondary-600 dark:bg-secondary-900/50 dark:text-secondary-300">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.7" stroke="currentColor" class="h-7 w-7" aria-hidden="true"><path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 0 0-3.375-3.375h-1.5A1.125 1.125 0 0 1 13.5 7.125v-1.5A3.375 3.375 0 0 0 10.125 2.25H8.25m.75 12 3 3m0 0 3-3m-3 3v-6m-1.5-9H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 0 0-9-9Z" /></svg>
        </div>
        <h3 class="text-lg font-semibold text-gray-900 dark:text-white">Resume</h3>
        </div>
        <div class="flex flex-shrink-0 flex-col gap-2">
        <a href="/resume/" class="inline-flex items-center justify-center rounded-md bg-secondary-600 px-3 py-2 text-sm font-semibold text-white transition hover:bg-secondary-700">View</a>
        <a href="/uploads/resume.pdf" download class="inline-flex items-center justify-center rounded-md border border-secondary-600 px-3 py-2 text-sm font-semibold text-secondary-700 transition hover:bg-secondary-50 dark:text-secondary-300 dark:hover:bg-secondary-900/40">Download</a>
        </div>
        </div>
    design:
      columns: '1'

  - block: markdown
    id: publications
    content:
      title: Publications
      icon: document-text
      align_right: true
      text: |-
        - [CLK-3D: RC-Calibrated Differentiable Clock-Tree Optimization for 3D ICs](https://gtcad.gatech.edu/www/papers/Huang-ICCAD25.pdf) — IEEE/ACM ICCAD, 2026.
        - [Snake-3D: Differentiable Learning for Cross-Tier Logic Path Snaking Optimization in 3D ICs](https://sites.usc.edu/sccad/Huang-ICCAD25) — IEEE/ACM ICCAD, 2025.
        - [On Legalization of Die Bonding Bumps and Pads for 3D ICs](https://sites.usc.edu/sccad/tcad24-robert) — IEEE TCAD, 2024.
        - [On Legalization of Die Bonding Bumps and Pads for 3D ICs](https://sites.usc.edu/sccad/3569052.3578925) — ACM ISPD, 2023.
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
