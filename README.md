
git clone 

```
https://github.com/mireillehaddad/MLOPS.git
```

virtual enviroment:

```
python -m venv .venv   
.\.venv\Scripts\Activate.ps1
```
to authenticate with GCP

```
gcloud auth login
```

Enable vertex AI in API's and services 

![
](Images/image.png)

Project description

![
](Images/image-1.png)


In requirements.txt add 
```
google-cloud-aiplatform>=1.38.0
kfp>=2.4.0
scikit-learn>=1.4.2
imbalanced-learn>=0.12.0
pandas
numpy
```

then we upgrade pip:
```
python -m pip install --upgrade pip
```
then we install requirements

```
python -m pip install -r requirements.txt
```