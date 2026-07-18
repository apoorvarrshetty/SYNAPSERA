# 🧠 SYNAPSERA

**Where intelligent software meets neuroscience.**

SYNAPSERA is a growing portfolio of interactive applications exploring neuroscience education, neurotechnology, signal processing, machine learning and cognitive learning.

This repository serves as the central hub for the SYNAPSERA ecosystem. Each application is developed and maintained in a separate GitHub repository with its own documentation and live deployment.

---

## Explore SYNAPSERA

| Project | Focus | Status | Repository | Live Demo |
|---|---|---:|---|---|
| **EEG Insight** | Educational EEG report explanation | ✅ Live | [GitHub](https://github.com/apoorvarrshetty/synapsera-eeg-insight) | [Open App](https://synapsera-eeg-insight.vercel.app) |
| **NeuroAtlas** | Interactive neuroanatomy learning | ✅ Live | [GitHub](https://github.com/apoorvarrshetty/synapsera-neuroatlas) | [Open App](https://synapsera-neuroatlas.vercel.app) |
| **NeuroMood Lens** | On-device ML emotion classification | ✅ Live | [GitHub](https://github.com/apoorvarrshetty/synapsera-neuromood-lens) | [Open App](https://synapsera-neuromood-lens.vercel.app) |
| **PatternLab** | Memory, focus and pattern-learning games | ✅ Live | [GitHub](https://github.com/apoorvarrshetty/synapsera-patternlab) | [Open App](https://synapsera-patternlab-92ziy5lpt-apoorva-shetty-s-projects.vercel.app/) |
| **SignalFlow** | Interactive signal-processing visualisation | ✅ Live | [GitHub](https://github.com/apoorvarrshetty/synapsera-signalflow) | [Open App](https://synapsera-signalflow.vercel.app) |
| **ModelMetrics** | Interactive ML classification metrics | ✅ Live | [GitHub](https://github.com/apoorvarrshetty/synapsera-modelmetrics) | [Open App](https://synapsera-modelmetrics.vercel.app) |

---

## Featured projects

### 🧠 EEG Insight

**Educational EEG report explainer for neuroscience and clinical learning.**

EEG Insight converts technical EEG terminology into structured educational explanations. It identifies key findings, explains important terms and provides separate summaries for learners and non-specialist users.

The current version uses a transparent mock-analysis workflow and does not provide clinical interpretation or diagnosis.

**Highlights:**

- Structured EEG report explanations
- Key finding identification
- Technical terminology glossary
- Student-focused learning notes
- Patient-friendly educational summaries
- Clear medical disclaimer

[Repository](https://github.com/apoorvarrshetty/synapsera-eeg-insight) · [Live Demo](https://synapsera-eeg-insight.vercel.app)

---

### 🧩 NeuroAtlas

**Interactive neuroanatomy explorer for clinical learning.**

NeuroAtlas transforms traditional neuroanatomy study material into an interactive learning experience. Learners can explore major brain regions and review their functions, lesion deficits, blood supply and clinical localisation.

**Highlights:**

- Interactive lateral brain diagram
- Ten major neuroanatomical regions
- Region-specific functions
- Lesion deficit summaries
- Blood supply information
- Clinical localisation vignettes
- Quick quizzes with feedback

[Repository](https://github.com/apoorvarrshetty/synapsera-neuroatlas) · [Live Demo](https://synapsera-neuroatlas.vercel.app)

---

### 🔬 NeuroMood Lens

**Private, on-device emotion classification using a pretrained transformer model.**

NeuroMood Lens analyses short English journal entries and estimates the emotional tone expressed in the text. It uses a DistilRoBERTa model running directly in the browser through Transformers.js and ONNX Runtime Web.

The application returns probabilities for seven emotion categories: joy, sadness, anger, fear, surprise, disgust and neutral.

**Highlights:**

- Real transformer-based ML inference
- Seven-class emotion classification
- Probability bars and radar-chart visualisation
- Dominant emotion with confidence score
- Browser-based Mood History
- Dark and light themes
- No application backend or API key
- Journal text remains in the user’s browser

> NeuroMood Lens is an educational machine-learning demonstration. It does not diagnose, assess or treat any mental-health condition.

[Repository](https://github.com/apoorvarrshetty/synapsera-neuromood-lens) · [Live Demo](https://synapsera-neuromood-lens.vercel.app)

---

### 🎯 PatternLab

**Interactive mini-games for memory, attention and pattern learning.**

PatternLab is a browser-based learning application containing five short interactive activities. It combines reusable game architecture, local scoring and a responsive learning interface.

**Included activities:**

- Memory Tiles
- Colour Match
- Pattern Recall
- Number Span
- Focus Timer

PatternLab is intended for education and entertainment. It does not measure or diagnose cognitive ability.

[Repository](https://github.com/apoorvarrshetty/synapsera-patternlab) · [Live Demo](https://synapsera-patternlab-92ziy5lpt-apoorva-shetty-s-projects.vercel.app/)

---

### 🌊 SignalFlow

**Interactive signal-processing visualiser for exploring waveforms, noise and filters.**

SignalFlow helps learners build intuition about basic signal-processing concepts by manipulating waveforms and viewing the results in real time.

**Highlights:**

- Sine, square, triangle, sawtooth and mixed signals
- Adjustable frequency and amplitude
- Configurable noise level
- Moving-average filtering
- Clean, noisy and filtered waveform overlays
- Signal statistics
- Signal-processing mini quiz

[Repository](https://github.com/apoorvarrshetty/synapsera-signalflow) · [Live Demo](https://synapsera-signalflow.vercel.app)

---

### 📊 ModelMetrics

**Interactive classification-metrics dashboard for machine-learning education.**

ModelMetrics demonstrates how changing a binary-classification threshold affects predictions, confusion-matrix values and evaluation metrics.

**Highlights:**

- Editable prediction data
- Interactive decision-threshold slider
- Live confusion matrix
- Accuracy, precision and recall
- F1 score, specificity and false-positive rate
- Five educational classification scenarios
- Plain-language metric explanations
- Built-in learning challenge

[Repository](https://github.com/apoorvarrshetty/synapsera-modelmetrics) · [Live Demo](https://synapsera-modelmetrics.vercel.app)

---

## Project categories

### Neuroscience and clinical education

- EEG Insight
- NeuroAtlas

### Machine learning and natural-language processing

- NeuroMood Lens
- ModelMetrics

### Signal processing

- SignalFlow

### Interactive cognitive learning

- PatternLab

---

## Technology across the ecosystem

The individual projects use different combinations of:

- React
- TypeScript
- JavaScript
- Vite
- React Router
- Transformers.js
- ONNX Runtime Web
- DistilRoBERTa
- SVG-based visualisation
- Browser `localStorage`
- Client-side state management
- Responsive CSS
- GitHub Codespaces
- Vercel

Not every project uses every technology. See the individual project repositories for implementation-specific details.

---

## Portfolio architecture

```text
SYNAPSERA
├── synapsera-eeg-insight
├── synapsera-neuroatlas
├── synapsera-neuromood-lens
├── synapsera-patternlab
├── synapsera-signalflow
└── synapsera-modelmetrics
```

Each application is maintained as an independent repository so that it can have:

- Its own source code and commit history
- Independent dependencies
- A dedicated README
- Separate deployment
- Project-specific limitations and disclaimers
- An independent development roadmap

The main SYNAPSERA repository acts as the portfolio index connecting these projects.

---

## Design principles

SYNAPSERA projects are guided by the following principles:

### Educational clarity

Technical and scientific ideas should be presented in language appropriate for learners.

### Honest implementation

Projects distinguish between real algorithms, pretrained models, static educational content, synthetic data and mock demonstrations.

### Privacy-conscious design

Where possible, applications operate locally in the browser without accounts or unnecessary collection of user information.

### Responsible scientific communication

Applications clearly describe their limitations and avoid presenting educational output as clinical or professional advice.

### Interactive learning

Visualisation and direct interaction are used to help learners develop intuition rather than simply presenting static information.

### Modular development

Each project is independently documented, deployed and maintainable.

---

## Educational and medical disclaimer

SYNAPSERA applications are intended for:

- Education
- Technical learning
- Research skill development
- Software demonstration
- Portfolio presentation

They are not medical devices and do not provide:

- Medical diagnosis
- Mental-health diagnosis
- Treatment recommendations
- Clinical decision support
- Patient monitoring
- Emergency or crisis assessment
- Professional medical advice

Any medical or mental-health concern should be discussed with an appropriately qualified healthcare professional.

---

## Development status

SYNAPSERA is an evolving portfolio. Existing applications may receive improvements in areas such as:

- Automated testing
- Accessibility
- Scientific validation
- Performance optimisation
- Additional educational modules
- Improved mobile support
- Expanded visualisations
- Dataset integration
- Model evaluation
- Documentation

New projects may be added as the ecosystem develops.

---

## Mission

**To make neuroscience, signal processing and machine learning easier to explore through responsible, interactive software.**

---

## Author

**Apoorva Shetty**

- GitHub: [@apoorvarrshetty](https://github.com/apoorvarrshetty)
- SYNAPSERA Hub: [github.com/apoorvarrshetty/SYNAPSERA](https://github.com/apoorvarrshetty/SYNAPSERA)

---

## License

Licensing may vary between individual SYNAPSERA projects. Refer to the `LICENSE` file in each project repository for its applicable terms.

---

**SYNAPSERA — where intelligent software meets neuroscience.**

**Built with ❤️ for neuroscience.**
