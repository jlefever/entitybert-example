# EntityBERT Example

This is silly workaround to use EntityBERT (ConcernBERT) until I have time to package it properly.

1. First, clone the EntityBERT repository.

```bash
git clone https://github.com/jlefever/entitybert
```

2. Next, clone this example.

```bash
git clone https://github.com/jlefever/entitybert-example
```

3. Create a virtual environment for the example and activate. You will need to install the requirements from the EntityBERT project (hacky).

```bash
cd entitybert-example
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

4. In order to import `entitybert`, you will first need to update the Python path (hacky).

```python
import sys
sys.path.insert(0, "<PATH_TO_ENTITYBERT_REPO>/src/")
import entitybert
```

5. Download the model from [here](https://zenodo.org/records/13777344). Move the `entitybert/_models/` directory inside `replication.zip` to the current directory.

6. You should now be able to run `Notebook1.ipynb` in VS Code.
