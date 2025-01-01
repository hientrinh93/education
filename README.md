# NYC-TLC-Trips

This repository contains 3 Jupyter notebooks and a streamlit file.
- tlc1.ipynb attempts to work on a very small subset of the dataset. This includes some machine learning models
- tlc2.ipynb attempts to work on a very smaller subset of the dataset. This includes some machine learning models
- group.ipynb works on the entire dataset for Q1 2024 without any ML models
- streamlit.py, is the backend for the streamlit app (https://nyc-tlc-trips.streamlit.app/)

## Getting Started

1. Create a Virtual Environment "Education":

```bash
python -m venv education

2. Activate the Virtual Environment

```bash
education\Scripts\activate
 
3. Install the necessary libraries mentioned in requirements below.

```bash
pip install -r requirements.txt

4. Install Jupyter Notebook in the Virtual Environment

```bash
pip install notebook

5. Add the Virtual Environment to Jupyter

```bash
pip install ipykernel
python -m ipykernel install --user --name=myenv --display-name "education"

6. Add the Virtual Environment to Jupyter

```bash
jupyter notebook

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

MIT

pip install -r requirements.txt