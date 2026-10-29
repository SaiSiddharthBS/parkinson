# Parkinson's Detection Application

**A concept interface for exploring a multimodal screening workflow.**

This repository contains the static website, screenshots, and user manual for a proposed application that would combine speech, handwriting, and gait inputs in one review flow. The goal is to show how a patient and clinician might move from an input to a readable report.

> **Project status:** This repository is a presentation prototype. It does not contain a trained model, a working diagnostic backend, clinical validation, or a downloadable application. It must not be used to diagnose or manage a medical condition.

## What the prototype shows

- A patient and clinician entry flow in the website mockup.
- Proposed modules for voice recordings, drawing or handwriting samples, and gait video.
- Screenshots of the intended analysis and reporting experience.
- A [user manual](User%20Manual%20Final.pdf) describing the concept.

The current `index.html` is a standalone front-end page. Its forms and analysis examples are illustrative; they do not process patient data. Any real screening product would require independently validated models, clinical evaluation, privacy controls, and appropriate regulatory review.

## View locally

Open `index.html` in a browser, or serve this folder locally:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Repository map

```text
index.html             Static concept website
screenshot1–5.png      Interface captures
User Manual Final.pdf  Concept documentation
logo.png               Project mark
```

This was a team project by Sai Siddharth B S, Sourabh Mekkalike, Sripathi Baliga J, and Vidya R, as credited on the website.
