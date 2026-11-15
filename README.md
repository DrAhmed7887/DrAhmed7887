# Dr. Ahmed Zayed

Physician (MB BCh, Alexandria University, 2010) with 12 years in clinical practice, now building and evaluating clinical AI. M.Sc. student in Applied Health Informatics & Digital Medicine at RWTH Aachen. Based in Valencia, Spain.

I work on where medical AI fails: the rare, high-stakes cases that average scores hide. My builds put deterministic safety rules around language models, and they report their failures alongside their results.

## Selected work

| Project | What it does |
|---|---|
| [SAFE-Triage](https://github.com/DrAhmed7887/safe-triage-submission) | Emergency-department triage: an LLM classifies, deterministic rules (ESI + NEWS2) set the acuity level. 35 of 36 exact (97.2%) and no critical under-triage on the 36 MIETIC vignettes; larger stress tests, and where it still fails, are reported in the repo. English and Egyptian Arabic. Draft manuscript. |
| [Evidence-Linked Handoff](https://github.com/DrAhmed7887/hack-clocked) | A patient arrives with records from several countries: every medication and allergy is labelled supported, conflicting or missing, with each record's exact words. Conflicts are never resolved for the clinician. [Live demo](https://drahmed7887.github.io/hack-clocked/) · [film](https://youtu.be/Bjk8wvfwo-s) |
| [Anamnesis](https://github.com/DrAhmed7887/anamnesis) | What the patient says vs. what's on the medicine pack: a voice note and pack photos in, a one-page brief for the clinician out. Meta hackathon 2026. Staged tests with synthetic voices, no patient data. |
| [Hathor](https://github.com/DrAhmed7887/hathor) | Reconciles vaccination schedules across borders for families who move countries. Also as a [Hermes Agent plugin](https://github.com/DrAhmed7887/hathor-hermes-plugin): a deterministic engine checks each dose on the card against sourced national schedules. |
| [Heat Shift Planner](https://github.com/DrAhmed7887/hack-future-health) | Heat-illness early warning for outdoor work sites in Abu Dhabi: thresholds set from each zone's own weather history, a crew plan with owners and sources, and a "cool first, transport second" card. [Try it](https://drahmed7887.github.io/hack-future-health/) |
| [Sanad](https://github.com/DrAhmed7887/sanad-public) | Offline replay of sourced night-shift review rules on a fictional 17-bed ICU, built to keep alert burden low: one message per episode. Fictional data only. [Live page](https://drahmed7887.github.io/sanad-public/) |

## More builds (2026)

| Project | What it does |
|---|---|
| [Receipts](https://github.com/DrAhmed7887/hack-openserv-serv) | Audits a radiology reporting agent's draft against its tool-call receipts, so a report that only *looks* complete is caught. |
| [BillCheck](https://github.com/DrAhmed7887/hack-paypal-ai) | Compares each line of a (synthetic) US medical bill with its 2026 Medicare price and explains the gaps in plain words. |
| [TrialSwarm AI](https://github.com/DrAhmed7887/trialswarm-ai) | Multi-agent pre-screening of oncology patients against real ClinicalTrials.gov protocols, on a seeded synthetic cohort. |
| [Anteroom](https://github.com/DrAhmed7887/anteroom) | Checks whether tomorrow's clinic appointments can actually go ahead. Unreadable text is dropped before any model sees it. |
| [Namaa](https://github.com/DrAhmed7887/qiyas) | Arabic-first WHO child-growth check for parents. |
| [Preludio](https://github.com/DrAhmed7887/preludio) | A governed WhatsApp voice-story agent that helps clinicians prepare children for procedures. |
| [SceneMedic](https://github.com/DrAhmed7887/scenemedic) | Multi-agent clinical-realism advisor for medical film and TV. |
| [AMD League retrieval](https://github.com/DrAhmed7887/amd-league-retrieval) | Answers a question from a folder of mixed documents or web pages with the exact value, citing only the files it needed, or refuses. |
| [Teach Ahmes](https://github.com/DrAhmed7887/vultr-agent-rush) | A child teaches a robot maths; her words become code, run in a throwaway sandbox and graded by exact arithmetic. |

All demos use synthetic or fictional data. None of these is a medical device or a substitute for clinical judgement.

## Elsewhere

[zayedmd.com](https://zayedmd.com) · [LinkedIn](https://www.linkedin.com/in/ahmed-zayed-80280498) · [Google Scholar](https://scholar.google.com/citations?user=txOshQkAAAAJ)
