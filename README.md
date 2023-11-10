# CACN-EMNLP-2023


This repository contains the code and resources related to the paper "<b>From Chaos to Clarity: Claim Normalization to Empower Fact-Checking</b>". If you find our work helpful, please consider citing our paper:</p>

```bibtex
 @article{sundriyal2023chaos,
    title={From Chaos to Clarity: Claim Normalization to Empower Fact-Checking},
    author={Sundriyal, Megha and Chakraborty, Tanmoy and Nakov, Preslav},
    journal={arXiv preprint arXiv:2310.14338},
    year={2023}
    }
```


<h2>Getting Started</h2>

<h3>Dataset</h3>
<p>A sample of the dataset is provided in the <code>CLAN-samples.csv</code> file. Please note that this is just a small subset for demonstration purposes. If you need the complete dataset, please contact the authors.</p>



<h3>How to Run</h3>
| Step 1: Clone the Repository

```bash
git clone https://github.com/LCS2-IIITD/CACN-EMNLP-2023.git
``` 
| Step 2: Navigate to the Project Directory

```bash
cd CACN-EMNLP-2023
```
| Step 3: Install the Required Packages

```bash 
. openai == 0.28.0
. pandas == 1.5.3
. csv == 1.0
. re == 2.2.1
. nltk == 3.8.1
```

| Step 4: Set Up Configuration
Add your OpenAI API key at the designated place, i.e. \<add-your-key-here\>.

| Step 5: Run the Main Script

```bash
python cacn.py
```
