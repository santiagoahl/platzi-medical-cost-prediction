
<h1 align="center">
  <br>
  <a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiXr4mw4Zj7AhX0SDABHfibBTIQFnoECBYQAQ&url=https%3A%2F%2Fwww.census.gov%2F&usg=AOvVaw3GuO0GtBqUhZ_msyq5s0RM"><img src="https://update.lib.berkeley.edu/wp-content/uploads/2016/05/census-logo.png" alt="US Census Bureau" width="300"></a>
  <br>
  Linear regressor medical cost predicter
  <br>
</h1>

<h4 align="center">A scikit-learn implementation of linear regressors.</h4>

<p align="center">
  <a href='https://www.kaggle.com/' target="_blank"><img alt='kaggle' src='https://img.shields.io/badge/Kaggle-100000?style=for-the-badge&logo=kaggle&logoColor=37BAE8&labelColor=BEFDFF&color=37BAE8'/></a> <a href='https://github.com/shivamkapasia0' target="_blank"><img alt='scikit-learn' src='https://img.shields.io/badge/scikit-learn-100000?style=for-the-badge&logo=scikit-learn&logoColor=FFFFFF&labelColor=FF6A00&color=1882EA'/></a> <a href='https://seaborn.pydata.org/' target="_blank"><img alt='seaborn' src='https://img.shields.io/badge/Seaborn-100000?style=for-the-badge&logo=seaborn&logoColor=white&labelColor=black&color=186FCD'/></a>
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a>
</p>

![screenshot](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/478b5ba4-46cf-4d31-94e7-0b87621464d6/pb_life_How_to_increase_Health_insurance_cover_1592063367.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221106%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221106T052053Z&X-Amz-Expires=86400&X-Amz-Signature=0102361a953be50bbd1959bc3f6f691d5371bc92ddf4210b9ea5d296efca7204&X-Amz-SignedHeaders=host&x-id=GetObject)

## Key Features

This machine learning model predicts the amount of charge of a given patient. This prediction is a number given in dollars. The dataset is taken from the [Medical Cost Personal Datasets
](https://www.kaggle.com/datasets/mirichoi0218/insurance). So here are the key features of this project:

* Prediction is based on this patient's features:
 
	- `age`: age of primary beneficiary

	- `sex`: insurance contractor gender, female, male

	- `bmi`: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height,
objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9

	- `children`: Number of children covered by health insurance / Number of dependents

	- `smoker`: Smoking

	- `region`: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.

	- `charges`: Individual medical costs billed by health insurance
* Conventional notebook data science scheme.
* Specialized **dataviz** tools .
* Based on **Scikit-Learn** modules and functions such like:
  -  `preprocessing.StandardScaler` :   Data standarization.
  - `linear_model.LinearRegression` :   Linear Regression modeling.
  - `metrics.r2_score` :  R2 score metric.

## How To Use

To clone and run this application, you will need [Git](https://git-scm.com).

```bash
# Clone this repository
$ git clone https://github.com/santiagoahl/medical-cost-prediction.git

# Go into the repository
$ cd linear-algebra-in-python

# Install Jupyter Notebooks
$ pip install jupyterlab
$jupyter-lab
$pip install notebook

# Run
$jupyter notebook
```

## Credits

This model uses the following open source datasets packages:

- [Scikit-learn](https://scikit-learn.org/stable/)
- [Insurance US Census Bureau](https://www.census.gov/)
- [Pandas](https://pandas.pydata.org/)
- [Numpy](https://numpy.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Matplotlib](https://matplotlib.org/)


## License

MIT

---

> Web Site [santiagoal.super.site](https://santiagoal.super.site/) &nbsp;&middot;&nbsp;
> GitHub [@santiagoahl](https://github.com/santiagoahl) &nbsp;&middot;&nbsp;
> Twitter [@sahumadaloz](https://twitter.com/sahumadaloz)
