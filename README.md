# Can Large Language Models Replicate Scholarly Contributions?

**Conference:**  ICCCBE2026

**Author:**  
Huan Zhou  
[hzhou715@umd.edu](mailto:hzhou715@umd.edu)

**Corresponding Author:**  
Dr. Qingbin Cui  
Build America Center  
[cui@umd.edu](mailto:cui@umd.edu)

---

## 1. Project overview

This study aimed to explores how much Large Language Models(LLMs) can replicate human scholarly work. Accordingly, the study had three questions: i) To what extent can LLMs reproduce the quality of human literature reviews? ii) Which types of contributions—theoretical, methodological, conceptual, or managerial—are most and least replicable? iii) What implications arise for the future of scholarly knowledge contribution in the AI era?


---

### 1. Paper Selection

- **Corpus size**: 30 accepted literature review papers  
- **Journals**:
  - *International Journal of Project Management (IJPM)*
  - *Project Management Journal (PMJ)*
- **Timeframe**: 2022–present  
- **Selection criteria**:
  - Clearly stated research problems  
  - Complete IMRaD structure  
  - Restricted access to AI

---

### 2. Prompt Design and Optimization

To maintain parity between human and AI outputs, standardized prompts were developed.

- **Variables**:
  - Research topic  
  - Research problem  
  - Scope and timeframe 

Three prompt types were used:
1. Research topic + research problem  
2. Research topic + research problem + method  
3. Research topic + research problem + context  

Prompts were refined using GPT-5 to minimize stylistic artifacts and isolate intellectual generation capacity.

---

### 3. AI-Assisted Replication

- **Models used**:
  - GPT-5  
  - Gemini-3-Pro (preview)
- **Output length**: ~8,000 words per paper  
- **GPT-5 settings**:
  - Reasoning effort: low  
  - Verbosity: high  

A total of **30 AI-generated literature reviews** were produced to match a subset of the human-authored corpus.

---

### 4. Quality Evaluation

Literature review quality was evaluated using **Snyder’s (2019) criteria**, covering seven dimensions:

1. Clarity of research questions  
2. Transparency of search strategies  
3. Justification of inclusion/exclusion criteria  
4. Use of quality assessment measures  
5. Reliability checks (e.g., inter-coder validation)  
6. Transparency of synthesis process  
7. Articulation of future research directions  

Each criterion was scored as:
- `0` = Not met  
- `1` = Partially met  
- `2` = Fully met  

Evaluation was conducted by an independent AI evaluator (Claude) using a strictly defined rubric.

---

### 5. Knowledge Contribution Evaluation

A pairwise comparison was conducted between:
- Human-authored reviews  
- GPT-generated reviews  
- Gemini-generated reviews  

Six dimensions of scholarly contribution were assessed:

1. Conceptual contribution  
2. Theoretical contribution  
3. Methodological contribution  
4. Empirical contribution  
5. Practical / managerial contribution  
6. Research agenda contribution  

Scores were assigned using a structured evaluation framework to ensure consistency.

---

## Results

### Quality Evaluation Results

- AI-generated and human-authored reviews achieved **comparable performance** in:
  - Search transparency  
  - Synthesis transparency  
  - Structural clarity  

- Human-authored reviews **significantly outperformed AI-generated reviews** in:
  - Quality assessment procedures  
  - Reliability and validation checks  
  - Justification of inclusion/exclusion criteria  

AI-generated reviews often described rigorous procedures without actually performing them, revealing a gap between procedural language and substantive execution.

---

### Knowledge Contribution Results

#### 1. Empirical and Methodological Contributions

- Human-authored reviews demonstrated strong empirical grounding through meta-analyses, bibliometric mapping, and structured coding.
- AI-generated reviews showed minimal empirical contribution and relied on inferred or non-verifiable data.

#### 2. Theoretical Integration

- AI effectively summarized existing theories and conceptual linkages.
- Human-authored reviews advanced theory by identifying mechanisms, tensions, and cross-disciplinary integration.

#### 3. Conceptual, Synthesis, and Managerial Contributions

- AI-generated reviews performed comparably in:
  - Conceptual framing  
  - Narrative synthesis  
  - Managerial implications  

However, AI outputs tended to remain generic and idealized, while human authors contextualized implications within real organizational and institutional constraints.

---

## Key Takeaways

- LLMs can replicate the **structure and language** of scholarly literature reviews.
- Human researchers maintain a clear advantage in:
  - Empirical validation  
  - Methodological rigor  
  - Theory building  
  - Reflexive judgment  
- AI currently functions best as a **research accelerator**, not a replacement for scholarly knowledge creation.

---

## Citation

If you use this repository or its materials, please cite:

> Cui, Q., & Zhou, H. (2026). *Can Large Language Models Replicate Scholarly Contributions?*





