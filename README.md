# ECE321 — Electronic Circuits

Lecture slides and handwritten notes for **ECE321: Electronic Circuits**, Department of Electronics and Communications, Faculty of Engineering, Zagazig University, Egypt.

**Part A:** Dr. Ahmed Reda Mohamed  
**Part B:** Dr. Ahmed Wahba

The collection contains **12 lecture PDFs and 6 handwritten-note PDFs**, organized by course part with direct links below.

## Course overview

ECE321 develops the analysis and design foundations of analog electronic circuits, connecting transistor-level behavior with amplifier performance and practical circuit applications. The available materials cover frequency response, operational amplifiers, negative feedback, transistor amplifier models, current mirrors, and differential amplifiers.

## Learning objectives

Using these materials, students can practice how to:

- Analyze low- and high-frequency amplifier response and explain the Miller effect.
- Analyze linear and nonlinear operational-amplifier applications.
- Evaluate the effects of op-amp bias currents and offset voltage.
- Identify feedback topologies and determine their effects on gain and impedances.
- Apply practical feedback analysis, including feedback-network loading.
- Analyze BJT and MOSFET amplifier and current-mirror circuits.
- Distinguish differential-mode and common-mode behavior in differential amplifiers.

## Lecture index

### Part A — Dr. Ahmed Reda Mohamed

| Lecture | Topic and PDF | Main coverage | Pages |
| :---: | --- | --- | ---: |
| 01 | [Course Information](lectures/part-a/ECE321_Lecture_01_Course_Information.pdf) | Course objectives, assessment, course plan, project specifications, and references. | 19 |
| 02 | [Frequency Response I](lectures/part-a/ECE321_Lecture_02_Frequency_Response_I.pdf) | Basic concepts, coupling and parasitic capacitances, RC response, gain-bandwidth product, and decibels. | 37 |
| 03 | [Frequency Response II](lectures/part-a/ECE321_Lecture_03_Frequency_Response_II.pdf) | Low- and high-frequency BJT amplifier response, Miller effect, and worked examples. | 34 |
| 04 | [Operational Amplifiers: Introduction and Linear Applications](lectures/part-a/ECE321_Lecture_04_OpAmp_Linear_Applications.pdf) | Op-amp models; inverting, non-inverting, and difference amplifiers; voltage followers; integrators and differentiators. | 42 |
| 05 | [Operational Amplifiers: Nonlinear Applications](lectures/part-a/ECE321_Lecture_05_OpAmp_Nonlinear_Applications.pdf) | Logarithmic and antilogarithmic amplifiers with exercises. | 18 |
| 06 | [Operational Amplifiers: DC Imperfections](lectures/part-a/ECE321_Lecture_06_OpAmp_Offset.pdf) | Input bias current, input offset current, input offset voltage, and exercises. | 17 |
| 07 | [Practical Operational Amplifiers](lectures/part-a/ECE321_Lecture_07_Practical_OpAmp.pdf) | Practical op-amp characteristics and inverting/non-inverting amplifier circuits. | 12 |
| 08 | [Feedback Circuits I](lectures/part-a/ECE321_Lecture_08_Feedback_Circuits_I.pdf) | Feedback fundamentals and topologies; gain robustness, bandwidth, distortion, noise, and impedance effects. | 40 |
| 09 | [Feedback Circuits II–III](lectures/part-a/ECE321_Lecture_09_Feedback_Circuits_II_III.pdf) | Practical feedback analysis, feedback-network loading, series-shunt and series-series examples, and transistor amplifier topologies. | 44 |

### Part B — Dr. Ahmed Wahba

| Lecture | Topic and PDF | Main coverage | Pages |
| :---: | --- | --- | ---: |
| 01–02 | [Introduction and Device Review](lectures/part-b/ECE321_Lectures_01_02_Introduction_and_Review.pdf) | Semiconductor overview; BJT and MOSFET review; amplifier models. | 60 |
| 03–04 | [Amplifiers and Current Mirrors](lectures/part-b/ECE321_Lectures_03_04_Amplifiers_and_Current_Mirrors.pdf) | Amplifier gain using transconductance and output resistance; ideal/current-source models; MOSFET and BJT current mirrors. | 47 |
| 05–06 | [Current-Mirror Problems and Differential Amplifiers](lectures/part-b/ECE321_Lectures_05_06_Current_Mirrors_and_Differential_Amplifiers.pdf) | Solved current-mirror problems; differential and common-mode signals; BJT differential-pair operation. | 39 |

Part B uses its own lecture numbering. Its supplied slides are labeled Fall 2022; this repository is a collection of teaching materials rather than a current-semester timetable.

### Part A — Handwritten notes

These notes supplement the corresponding lecture slides with handwritten circuit analysis and derivations.

| Handwritten notes | Related lectures in Part A | Pages |
| --- | --- | ---: |
| [BJT Frequency Response I](notes/part-a/ECE321_Notes_BJT_Frequency_Response_I.pdf) | Lectures 02–03 | 25 |
| [BJT Frequency Response II](notes/part-a/ECE321_Notes_BJT_Frequency_Response_II.pdf) | Lectures 02–03 | 15 |
| [Op-Amp Linear Applications](notes/part-a/ECE321_Notes_OpAmp_Linear_Applications.pdf) | Lecture 04 | 15 |
| [Op-Amp Nonlinear Applications](notes/part-a/ECE321_Notes_OpAmp_Nonlinear_Applications.pdf) | Lecture 05 | 13 |
| [Op-Amp Offset](notes/part-a/ECE321_Notes_OpAmp_Offset.pdf) | Lecture 06 | 10 |
| [Practical Op-Amps](notes/part-a/ECE321_Notes_Practical_OpAmp.pdf) | Lecture 07 | 8 |

## Repository organization

| Location | Contents |
| --- | --- |
| [`lectures/part-a/`](lectures/part-a/) | Nine Part A lecture-slide PDFs. |
| [`lectures/part-b/`](lectures/part-b/) | Three Part B lecture-slide PDFs, each covering two lectures. |
| [`notes/part-a/`](notes/part-a/) | Six handwritten-note PDFs supporting Part A. |
| [`docs/FILE_INDEX.md`](docs/FILE_INDEX.md) | Mapping between the original archive filenames and repository filenames. |
| [`docs/GITHUB_SETUP.md`](docs/GITHUB_SETUP.md) | Steps for uploading this collection to GitHub. |

PDF filenames have been standardized for readability and reliable links. The PDF contents are unchanged. Part A lecture numbering follows the original archive filenames; some source cover pages use a different lecture number.

## How to use the materials

1. Start with [Course Information](lectures/part-a/ECE321_Lecture_01_Course_Information.pdf).
2. Follow the lecture sequence within each part. Use the Part B device review when revisiting transistor fundamentals.
3. Work through the circuit examples, then use the relevant handwritten notes to follow the derivations.
4. Download individual PDFs from the lecture index, or download the entire repository using **Code → Download ZIP** on GitHub.

No software installation is required to read the PDFs. For simulation practice, use the circuit simulator specified by your instructor.

## References listed in the course materials

- A. S. Sedra et al., *Microelectronic Circuits*.
- R. L. Boylestad and L. Nashelsky, *Electronic Devices and Circuit Theory*.
- B. Razavi, *Microelectronics*.
- B. Razavi, *Design of Analog CMOS Integrated Circuits*.
- Course lecture slides and handwritten notes.

## Collection scope

This repository contains the materials supplied in the course archive. The course-information slides also outline signal generation, wave shaping, and operational-amplifier structures; dedicated lecture files for those modules were not included. Assignment, quiz, examination, and project-submission files are also not included in this collection.

For current assessment requirements, deadlines, and announcements, follow the instructor's LMS or official course communication.

## Attribution

Part A slides identify **Dr. Ahmed Reda Mohamed** as their author. Part B slides identify **Dr. Ahmed Wahba** as their author. Original authorship, institutional credits, and references remain in the PDFs.

## Corrections

If you find a broken link, a missing page, or a typographical error, open a GitHub issue identifying the lecture, PDF page, and suggested correction.
