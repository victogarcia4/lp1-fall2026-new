# BIOL 2401 Lab Practical 1 — Revision Plan

## Objective

Create a revised Anatomy and Physiology I laboratory practical for Lone Star College–North Harris consisting of 30 station slides and 105 multiple-choice questions. Every question will be answered by examining a numbered image, physical anatomical model, specimen, microscope slide, or other named laboratory reference unless it is explicitly marked **NO MODEL NEEDED**.

## Deliverables

1. A 30-slide PowerPoint presentation, with slide titles and station labels fixed as **Station 01** through **Station 30**.
2. A revised CSV containing the question bank, SLO alignment, answer choices, correct answers, visual-reference details, and image-redesign flags.

The original source CSV, SLO CSV, and station images will remain unchanged.

## Current Baseline

- 30 station images are available as `LP1-01.png` through `LP1-30.png`.
- The current bank contains 105 questions: 15 stations have 3 questions and 15 stations have 4 questions.
- Four questions at Stations 08–09 have unresolved answer placeholders.
- Most current stems can be answered as reading-test items rather than as practical-laboratory items.
- Existing correct nominal answers include duplicates such as `base`, `smooth`, and `parasagittal plane`.

## Workflow

### 1. Station and SLO blueprint

Map every numbered pointer, model feature, tissue image, specimen, or microscope component to its intended concept and the applicable BIOL 2401 SLO.

### 2. Visually anchored question revision

Rewrite all 105 questions so the stem explicitly requires the station reference. Examples include:

- “Identify the structure indicated by label 56.”
- “Which function is performed by the structure indicated by label 56?”
- “Using the microscope model at this station, identify the component indicated by label 47.”

At least 90% of questions will be direct identification or function questions. Questions that cannot be validly supported by an image or model will be marked **NO MODEL NEEDED** beside the relevant station identifier, with the affected question number specified.

### 3. Answer-option revision

Provide four plausible, parallel answer options for each item. Ensure that each question has one defensible answer and that the correct nominal answer is unique across the full exam. Context-specific names will be qualified where needed, for example:

- `chemical base (proton acceptor)`
- `microscope base (support)`

### 4. Answer-key balancing

Balance correct-letter positions as closely as possible across 105 questions: one letter used 27 times and each remaining letter used 26 times. Check the sequence for predictable station-level or consecutive-letter patterns.

### 5. CSV output

Create a new CSV with these columns:

- `Station`
- `Question_Number`
- `SLO`
- `Question_Type`
- `Stem`
- `Option_A`
- `Option_B`
- `Option_C`
- `Option_D`
- `Correct_Letter`
- `Correct_Answer`
- `Reference_Type`
- `Reference_Label`
- `Image_Represents_Question`
- `Image_Redesign_Needed`
- `Redesign_Notes`
- `No_Model_Needed`

### 6. Presentation output

Create one 16:9 slide for each station. Every slide must use the exact station identifier format:

`Station 01`, `Station 02`, …, `Station 30`.

Each slide will show the corresponding station image or named model reference and its 3–4 matching questions. Question wording and choices will match the CSV exactly.

### 7. Quality assurance

Before delivery, verify:

- 30 slides, numbered `Station 01` through `Station 30`.
- 105 CSV rows with 3–5 questions per station.
- SLO alignment and four answer choices for every item.
- No unresolved placeholders or duplicated nominal correct answers.
- Proportional A/B/C/D distribution.
- Exact agreement between CSV content and slide content.
- All slides rendered and inspected for readable text, visible labels, appropriate image crop, clipping, and overlap.
