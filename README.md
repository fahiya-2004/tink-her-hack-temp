<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# AI-DETECTOR 🎯

## Basic Details

### Team Name:ASPIRE

### Team Members
- Member 1:Fahiya M S -lbsitw
- Member 2:Jyothika K S -lbsitw

### Hosted Project Link
[mention your project hosted link here]

### Project Description
It is a website to detect whether the image uploaded is ai generated or not

### The Problem statement
In todays world so many AI related fraud is happening this is a best way to find out

### The Solution
This web will tell whether the given the probability of the image if it is ai generated or not
---

## Technical Details

### Technologies/Components Used

**For Software:**
- Languages used: HTML,CSS,javascript,python
- Frameworks used: Flask,Spring Boot,pillow
- Libraries used: flask,
- Tools used: [ VS Code, Git]


## Implementation

### For Software:

#### Installation
```bash
python add.py

#### Run
```bash
[Run commands - e.g., npm start, python app.py]
```

## Project Documentation

### For Software:

#### Screenshots (Add at least 3)


#### Diagrams

**System Architecture:**

┌─────────────────────────────────────────────────────────────────┐
│                    LEVEL 1: USER INTERFACE                      │
│                         (Frontend)                              │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│     [Upload Image] → [Preview] → [Analyze Button]              │
│                                                                 │
│            Displays: Results, Confidence, Scores                │
│                                                                 │
│     Technologies: HTML, CSS, JavaScript                         │
│                                                                 │
└────────────────────────┬────────────────────────────────────────┘
                         │
                         │ HTTP Request (JSON)
                         │ Image as Base64
                         ↓
┌─────────────────────────────────────────────────────────────────┐
│                    LEVEL 2: API SERVER                          │
│                      (Backend)                                  │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│     Flask Web Server                                            │
│                                                                 │
│     Routes:                                                     │
│     • POST /api/analyze  → Process image                        │
│     • GET  /api/health   → Check status                         │
│                                                                 │
│     Handles: Requests, Responses, Errors                        │
│                                                                 │
└────────────────────────┬────────────────────────────────────────┘
                         │
                         │ Function Calls
                         │
                         ↓
┌─────────────────────────────────────────────────────────────────┐
│                  LEVEL 3: AI DETECTION LOGIC                    │
│                   (8 Detection Modules)                         │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  1. Deep Learning (50%) → Neural Network prediction             │
│  2. Dimensions (10%)    → Check AI-standard sizes               │
│  3. Entropy (8%)        → Measure randomness                    │
│  4. Noise (10%)         → Detect camera noise                   │
│  5. Color (8%)          → Analyze color patterns                │
│  6. Metadata (7%)       → Check EXIF camera data                │
│  7. Frequency (5%)      → FFT analysis                          │
│  8. Saturation (2%)     → Check oversaturation                  │
│                                                                 │
│  → Combine all scores with weights → Final AI Probability      │
│                                                                 │
└────────────────────────┬────────────────────────────────────────┘
                         │
                         │ Library Calls
                         │
                         ↓
┌─────────────────────────────────────────────────────────────────┐
│                 LEVEL 4: LIBRARIES & MODELS                     │
│                  (Processing Tools)                             │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  • PyTorch        → Deep learning, neural networks              │
│  • PIL/Pillow     → Image loading and processing                │
│  • NumPy          → Array operations, math                      │
│  • SciPy          → Advanced calculations (FFT, filters)        │
│  • ResNet50 Model → Pre-trained AI detection model              │
│                                                                 │
│  Runs on: CPU or GPU                                            │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘


═══════════════════════════════════════════════════════════════════
                         DATA FLOW
**Application Workflow:**

![Workflow](docs/workflow.png)
*Add caption explaining your workflow*

---





### Video
[Add your demo video link here - YouTube, Google Drive, etc.]
blob:null/d69ad3e6-3024-46be-b1ee-10d805fcacf8
*Explain what the video demonstrates - key features, user flow, technical highlights*



## Team Contributions

- Fahiya M S:backend
-Jyothika K S:feontend
---

## License

This project is licensed under the [LICENSE_NAME] License - see the [LICENSE](LICENSE) file for details.

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub
