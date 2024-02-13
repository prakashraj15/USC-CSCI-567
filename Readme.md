# Leveraging Multi-Task Models to Enhance Text-Classification Performance using Saliency Regularization 

## Follow the steps to execute the code!!
### Dataset

The dataset can be downloaded from the the below link 👇

[Dataset](https://drive.google.com/drive/folders/1oRzL5xhHdwte3DshkvogfagwYnCZ6Omw?usp=sharing) 

To access the dataset please use @usc.edu account

### Creating Virtual Environment

This is not mandotary but creating virtual env will make the job cosy. 
Please create the virtual env in local device 

```python 
python3 -m venv sal_env
```

After creating virtual env activate the virtual environment in command prompt using the code below. For using this code you should be in the same directory.

```python
.\sal_env\Scripts\activate
``` 

if you are using the macos or Linux based system 

```python
source sal_bin/bin/activate
```

Then run this python command to install the requird libraries.

```python
pip install pandas numpy tqdm deep_translator indic-nlp-library networkx scipy scikit-learn sentence-transformers gensim optuna matplotlib pickle torch transformers
```

### Execute the file in order
1. create the folder data and move the downloaded dataset file in the folder. 
2. The first set of codes should be run from the summarization folder. The Files can be run in any order. 
3. Next, run the python notebook found in the "saliency" folder with the filename "saliency_ranking.ipynb."
4. Finally, run the python notebooks found in the "Classification" folder. There is no order in the execution of the files, it can run irrespective of order.
5. After running each file, output can be seen.





