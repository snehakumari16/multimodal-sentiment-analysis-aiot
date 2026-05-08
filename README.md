 Multimodal Sentiment Analysis with AIoT Integration

Research Prototype by Sneha Kumari J
B.Tech Artificial Intelligence & Machine Learning | Presidency University, Bengaluru



 Overview
A multimodal research prototype combining NLP-based text 
sentiment analysis with simulated physiological IoT signals 
(heart rate, galvanic skin response) to infer emotional states 
beyond text alone.



 System Architecture
Text Input → NLP Sentiment Analysis (VADER + TextBlob)
                          ↓
IoT Signals → Physiological Analysis (HR + GSR)
                          ↓
          Multimodal Fusion Engine (60/40 weighted)
                          ↓
              Final Emotion Classification



Modules

Module 1 — Text Sentiment Analysis
- VADER sentiment scoring
- TextBlob polarity and subjectivity
- Combined sentiment scoring

 Module 2 — Physiological Signal Analysis
- Heart rate simulation from IoT sensors
- Galvanic Skin Response (GSR) simulation
- Physiological state classification

 Module 3 — Multimodal Data Fusion
- Weighted fusion of text and physiological signals
- Text weight: 60%, Physiological weight: 40%
- Final emotion classification with confidence score

Module 4 — Visualization
- Text sentiment scores
- Heart rate analysis
- GSR levels
- Final fused emotion scores

---

Tech Stack
- Python
- VADER Sentiment Analysis
- TextBlob
- NumPy, Pandas
- Matplotlib
- Affective Computing concepts
- AIoT Signal Simulation

---

Key Findings
1. Text alone misses physiological stress signals
2. Multimodal fusion improves emotion classification accuracy
3. Physiological signals capture arousal that text cannot
4. Weighted fusion balances both modalities effectively

---

 Research Relevance
- Affective Computing
- Human Computer Interaction
- Mental Health Monitoring
- AIoT Systems
- Multimodal AI

---

 Author
Sneha Kumari J
- LinkedIn: https://www.linkedin.com/in/sneha-kumari-computer-engineering
- Email: snehakumari1869@gmail.com
