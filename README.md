# ACRec_Taxonomy

---

## 🗂️ Repository Structure

### `dataset_creation/`
Prompts used for constructing the ACRec dataset.

#### `phase_1/`
Initial prompt-based extraction of Affective (A), Cognitive (C), and Affective-Cognitive (AC) statements from book reviews.

- `guidelines.txt`: Detailed annotation guidelines for identifying and distinguishing between A, C, and AC statements.
- `ICL_examples.txt`: In-context learning examples provided to the LLM to ensure correct extraction and classification of statements.
- `prompt.txt`: Prompt template used in Phase 1 to generate structured AC statements from raw Goodreads reviews.

#### `phase_2/`
Refinement phase to correct misclassifications and improve type separation.

- `phase_2_prompt.txt`: Prompt for correcting misclassified outputs from Phase 1 and improving separation between affective and cognitive statements

### `emotion_classification/`
Emotion categorization of extracted affective statements.

- `prompt.txt`: Prompt used to classify each A or AC statement into one of the 26 categories emotion based on a modified Geneva Emotion Wheel.

---
