## ML Prague 2023

### Applying NLP to aid drug discovery

- **Workshop structure**:
1. Introduction to drug discovery and diseases
2. What are proteins and small molecules?
3. How to use machine learning for drug discovery?
4. Data sources and feature representations
5. Introduction to NLP on language as we know it
6. NLP for drug discovery
7. NLP for small molecules
8. The future of AI in drug discovery


#### Coding assignments:

Assignment 1: Intro to transformers 
<a target="_blank" href="https://colab.research.google.com/github/dataclair-ai/mlprague2023/blob/master/notebooks/01_assignment_intro_to_transformers.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Assignment 2: Preprocess BBB 
<a target="_blank" href="https://colab.research.google.com/github/dataclair-ai/mlprague2023/blob/master/notebooks/02_assignment_preprocess_BBB.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Assignment 3: BBB PubMed BERT
<a target="_blank" href="https://colab.research.google.com/github/dataclair-ai/mlprague2023/blob/master/notebooks/03_assignment_BBB_PubMed_BERT.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Assignment 4: BBB using SMILES model 
- The assignment here is to use the previous notebook to help guide you to implement the same classification task but this time you will use a model that was pretrained on SMILES (search on HuggingFace or have a peek at the solution if you want to see the model I used)
- The dataset you will use is the one with the cleaned SMILES column - this is the input to fine-tune the model (in the previous notebook you used the "name" column)
- Otherwise the procedure should be almost identical as the above notebook - one of the advantages of using HuggingFace models :) 

#### Solutions:
Solution 1: Intro to transformers 
<a target="_blank" href="https://colab.research.google.com/github/dataclair-ai/mlprague2023/blob/master/notebooks/01_solution_intro_to_transformers.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Solution 2: Preprocess BBB 
<a target="_blank" href="https://colab.research.google.com/github/dataclair-ai/mlprague2023/blob/master/notebooks/02_solution_preprocess_BBB.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Solution 3: BBB PubMed BERT
<a target="_blank" href="https://colab.research.google.com/github/dataclair-ai/mlprague2023/blob/master/notebooks/03_solution_BBB_PubMed_BERT.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Solution 4: BBB ChemBERTa
<a target="_blank" href="https://colab.research.google.com/github/dataclair-ai/mlprague2023/blob/master/notebooks/04_solution_BBB_ChemBERTa.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>


**Bonus material:**

Assignment 5: BBB combine text and SMILES
<a target="_blank" href="https://colab.research.google.com/github/dataclair-ai/mlprague2023/blob/master/notebooks/05_BBB_combine_txtSMILE.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
