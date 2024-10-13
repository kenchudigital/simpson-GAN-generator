# simpson-GAN-generator

First, Introduce the dataset from Kaggle `The Simpsons Characters Data`:

https://www.kaggle.com/datasets/alexattia/the-simpsons-characters-dataset

---

### 01 Install the dataset

Of course, you can directly download it from the link, but we can code it:

```bash

pip install opendatasets --upgrade --quiet

pip install pandas

```

And then, write that in Python:

```python
import opendatasets as od
dataset = 'https://www.kaggle.com/ryanholbrook/dl-course-data'
od.download(dataset)
```

If you get the kaggle.json from Kaggle > Setting > API > Create new Token, it will read the json directly and don't need to input the `username` and `password`.

Previous:

```
- README.md
- kaggle.json
- download_dataset.py
- the-simpsons-characters-dataset
```

move `the-simpsons-characters-dataset` to `datasets/the-simpsons-characters-dataset`


---

### 02 minist_GAN

First, we will go throught the simple GAN.

Please see the minist example in `basic_GAN.ipynb`.

After, write this code, you should understand more GAN.

---

However, this repo has not completed, right now. will update it if I have time.



