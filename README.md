# End-to-end-Mcq-Genrator

# How to run?
### STEPS:


Clone the repository

```bash
Project repo: git@github.com:reenal/mcq_genrator.git
```

## How to run?

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mcqgen python=3.8 -y
```

```bash
conda activate mcqgen
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your OPENAI_API_KEY credentials as follows:

```ini
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

```bash
# Finally run the following command
streamlit run StreamlitAPP.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- StreamlitAPP
- OpenAI
- GPT 3





