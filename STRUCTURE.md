# Project Structure Overview

Complete guide to this repository's organization and how to use each section.

## 📁 Directory Tree

```
personal-health/
├── docs/
│   ├── genetics/
│   │   ├── raw_data/
│   │   │   └── genome_Michael_Frederick_v4_Full_20180226061106.txt
│   │   └── analysis/
│   │       ├── Genetic_Genie_Methylation_Profile_Michael_Frederick.pdf
│   │       ├── Genetic_Genie_Detox_Profile_Michael_Frederick.pdf
│   │       └── Genetic_Summary.md [TO CREATE]
│   │
│   ├── medical/
│   │   ├── diagnoses/
│   │   │   └── Diagnoses.md [FILL IN - PCP diagnoses]
│   │   ├── lab_results/
│   │   │   └── Lab_Results.md [FILL IN - Blood panels]
│   │   └── medications/
│   │       └── Medications.md [FILL IN - Rx & supplements]
│   │
│   ├── demographics/
│   │   ├── timeline/
│   │   │   └── Personal_Timeline.md [FILL IN - Your history]
│   │   └── lifestyle/
│   │       └── Lifestyle_Baseline.md [FILL IN - Daily patterns]
│   │
│   ├── protocols/
│   │   ├── current/
│   │   │   └── Current_Protocol.md [FILL IN - Active protocol]
│   │   ├── history/
│   │   │   └── Protocol_History.md [ADD - Past protocols]
│   │   └── research/
│   │       └── Research_Index.md [BUILD - Supporting studies]
│   │
│   └── analysis/
│       └── Analysis_Framework.md [USE - Analysis templates]
│
├── TIMELINE.md [FILL IN - Major health events]
├── EVENTS.md [FILL IN - Daily/weekly observations]
├── TODO.md [EXISTING - Your task list]
├── README.md [REFERENCE - Project overview]
├── GETTING_STARTED.md [GUIDE - How to populate repo]
├── STRUCTURE.md [THIS FILE]
└── .gitignore [PRIVACY - Exclude OS files]
```

## 📚 Document Types & Purpose

### Genetics (docs/genetics/)
**Raw data and interpreted genetic analysis**
- `raw_data/`: Your 23andMe genome file
- `analysis/`: Genetic Genie profiles + your interpretation
- **Use**: Understand genetic predispositions and what they mean

### Medical (docs/medical/)
**Clinical records from healthcare providers**
- `diagnoses/`: Your diagnosed conditions (from PCP)
- `lab_results/`: Blood work and biomarkers
- `medications/`: Current and past medications/supplements
- **Use**: Ground genetic predictions in clinical reality

### Demographics (docs/demographics/)
**Personal context and lifestyle patterns**
- `timeline/`: Your personal history, locations, major events
- `lifestyle/`: Daily routines, sleep, exercise, stress patterns
- **Use**: Understand environmental factors and personal baselines

### Protocols (docs/protocols/)
**Your supplement regimens and supporting research**
- `current/`: Your active supplement schedule and rationale
- `history/`: Archive of previous protocols and what you learned
- `research/`: Scientific papers supporting your choices
- **Use**: Document what you're doing and why

### Analysis (docs/analysis/)
**Framework and templates for synthesis**
- `Analysis_Framework.md`: Templates for analyzing your data
- **Use**: Connect genetics → labs → symptoms → interventions

### Journal Files (root level)
**Ongoing tracking and observations**
- `TIMELINE.md`: Major health events and when they occurred
- `EVENTS.md`: Day-to-day observations and experiments
- `TODO.md`: Tasks and adjustments to try
- **Use**: Personal health journal and tracking

## 🔄 Data Flow & Integration

```
Genetics (What you're predisposed to)
    ↓
Labs (Confirms/denies genetic predictions)
    ↓
Symptoms (How genetics + labs show up in real life)
    ↓
Protocol (Interventions to address root causes)
    ↓
Events/Timeline (Track what's working)
    ↓
Analysis (Synthesize & optimize)
    ↓
Repeat
```

## 🎯 How to Use This Repository

### Phase 1: Setup (Week 1)
1. Fill in Basic Demographics
   - [docs/demographics/timeline/Personal_Timeline.md](docs/demographics/timeline/Personal_Timeline.md)
   
2. Add Medical Records
   - [docs/medical/diagnoses/Diagnoses.md](docs/medical/diagnoses/Diagnoses.md)
   - [docs/medical/lab_results/Lab_Results.md](docs/medical/lab_results/Lab_Results.md)
   - [docs/medical/medications/Medications.md](docs/medical/medications/Medications.md)

3. Document Lifestyle
   - [docs/demographics/lifestyle/Lifestyle_Baseline.md](docs/demographics/lifestyle/Lifestyle_Baseline.md)

### Phase 2: Protocol (Week 2)
4. Document Current Protocol
   - [docs/protocols/current/Current_Protocol.md](docs/protocols/current/Current_Protocol.md)

5. Archive Experimentation
   - [docs/protocols/history/Protocol_History.md](docs/protocols/history/Protocol_History.md)

### Phase 3: Analysis (Week 3-4)
6. Genetic Interpretation
   - Create [docs/genetics/analysis/Genetic_Summary.md](docs/genetics/analysis/Genetic_Summary.md)

7. Build Research Index
   - [docs/protocols/research/Research_Index.md](docs/protocols/research/Research_Index.md)

8. Begin Analysis
   - Use [docs/analysis/Analysis_Framework.md](docs/analysis/Analysis_Framework.md)

### Ongoing: Tracking
- Update [EVENTS.md](EVENTS.md) with daily/weekly observations
- Update [TIMELINE.md](TIMELINE.md) with major changes
- Use [TODO.md](TODO.md) for ongoing experiments

## 📝 File Naming Conventions

- **Markdown files**: `CamelCase.md` (e.g., `Personal_Timeline.md`)
- **Dates**: ISO format `YYYY-MM-DD`
- **Archive files**: Include date (e.g., `Protocol_History_v2.1.md`)
- **PDFs**: Keep original names for medical documents

## 🔒 Privacy Considerations

- This repo contains sensitive health data
- Keep private on GitHub (private repository)
- `.gitignore` excludes OS files
- Consider adding `.gitignore` rules for any additional private files
- Be careful sharing with untrusted platforms
- Only share specific sections with healthcare providers

## 🔗 Quick Links for Common Tasks

### I want to...

**Add a new diagnosis**
→ [docs/medical/diagnoses/Diagnoses.md](docs/medical/diagnoses/Diagnoses.md)

**Log observations**
→ [EVENTS.md](EVENTS.md)

**Update my supplement list**
→ [docs/medical/medications/Medications.md](docs/medical/medications/Medications.md) + [docs/protocols/current/Current_Protocol.md](docs/protocols/current/Current_Protocol.md)

**Find research on a supplement**
→ [docs/protocols/research/Research_Index.md](docs/protocols/research/Research_Index.md)

**Analyze a symptom pattern**
→ [docs/analysis/Analysis_Framework.md](docs/analysis/Analysis_Framework.md)

**Archive an old protocol**
→ [docs/protocols/history/Protocol_History.md](docs/protocols/history/Protocol_History.md)

**Update my baseline lifestyle**
→ [docs/demographics/lifestyle/Lifestyle_Baseline.md](docs/demographics/lifestyle/Lifestyle_Baseline.md)

**Review project status**
→ [README.md](README.md)

## 📊 What Data Goes Where

| Data Type | Location | Format | Purpose |
|-----------|----------|--------|---------|
| Genome file | docs/genetics/raw_data/ | .txt (raw 23andMe data) | Source of genetic variants |
| Genetic interpretation | docs/genetics/analysis/ | .pdf + .md | Understand genetic predispositions |
| Diagnoses | docs/medical/diagnoses/ | .md (structured) | Know what conditions you have |
| Lab results | docs/medical/lab_results/ | .md (tables) | Track biomarkers |
| Medications & supplements | docs/medical/medications/ | .md (structured) | Know what you're taking |
| Personal history | docs/demographics/timeline/ | .md (narrative) | Context for health decisions |
| Daily patterns | docs/demographics/lifestyle/ | .md (detailed) | Understand lifestyle factors |
| Active protocol | docs/protocols/current/ | .md (tables + notes) | Know current supplement regimen |
| Past protocols | docs/protocols/history/ | .md (versioned) | Learn from past experiments |
| Research | docs/protocols/research/ | .md (indexed) | Support your protocol choices |
| Health events | TIMELINE.md | .md (chronological) | Major milestones and changes |
| Daily observations | EVENTS.md | .md (dated entries) | Track what's working |
| Tasks & experiments | TODO.md | .md (checkboxes) | Plan your next steps |

## 🚀 Next Steps

See [GETTING_STARTED.md](GETTING_STARTED.md) for a prioritized implementation plan with time estimates.

---

**This structure provides:**
- ✅ Complete health profile in one place
- ✅ Data organized for AI analysis
- ✅ Clear separation of genetics, clinical, and lifestyle data
- ✅ Support for ongoing experimentation and optimization
- ✅ Historical tracking to understand what works
- ✅ Privacy protection for sensitive health information
