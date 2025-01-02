# ConcernBERT Example

This is an example of using ConcernBERT.

1. First, clone this example.

```bash
git clone https://github.com/jlefever/concernbert-example
```

2. Next, create a virtual environment for the example and activate it.

```bash
cd concernbert-example
python -m venv .venv
source .venv/bin/activate
```

3. Install the `concernbert` and `jupyter` package from pip.

```bash
python -m pip install concernbert jupyter
```

4. Download the model from [here](https://zenodo.org/records/13777344). Move the `entitybert/_models/` directory inside `replication.zip` to the current directory.

5. You should now be able to run `Notebook1.ipynb` in VS Code.
