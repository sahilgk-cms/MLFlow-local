# MLFlow-local



## Trying out MLFlow locally
To run the notebook, please mlflow, scikit-learn first.
Clone the repo and run
```
mlflow ui
```
to view user interface of MLFLow.
MlFLow server will be running on http://127.0.0.1:5000

This is the home page where we can see the experiments created.
<img width="1920" height="663" alt="image" src="https://github.com/user-attachments/assets/c3efe966-d2a4-4b7d-9754-6111c53fe527" />

The runs within the experiment can be viewed here...
<img width="1909" height="491" alt="image" src="https://github.com/user-attachments/assets/dd1535cb-e9ef-4a8e-aaf5-44f868d582e7" />

Each run overview has info about the metics, paramters, data hash, logged model. This can be viewed at http://127.0.0.1:5000/#/experiments/{experiment_id}/runs/{run_id}
<img width="1919" height="870" alt="image" src="https://github.com/user-attachments/assets/875db4a3-6f0a-42e3-9bc6-c7f29e9a92f9" />


In the artifacts section, we can see where our dataset is saved, This can be viewed at http://127.0.0.1:5000/#/experiments/{experiment_id}/runs/{run_id}/artifacts
<img width="1878" height="875" alt="image" src="https://github.com/user-attachments/assets/cf563789-0ac6-4217-9f6c-a5261f761e59" />

The model info can be viewed at http://127.0.0.1:5000/#/experiments/{experiment_id}/models/{model_id}
<img width="1870" height="863" alt="image" src="https://github.com/user-attachments/assets/433150ad-1ae7-4fe0-9fd5-4bf48faee81a" />

The pickle file for the model can be viewed at http://127.0.0.1:5000/#/experiments/{experiment_id}/models/{model_id}/artifacts
<img width="1531" height="434" alt="image" src="https://github.com/user-attachments/assets/c3043848-5243-476e-8265-d5238e72e329" />

The registered models can be viewed at http://127.0.0.1:5000/#/models
<img width="1910" height="397" alt="image" src="https://github.com/user-attachments/assets/483fd3e1-7afc-43b3-b884-49902ca75302" />

Inside the model, we can see the model versions, tags and aliases if pushed to production: http://127.0.0.1:5000/#/models/{model_name}
<img width="1899" height="683" alt="image" src="https://github.com/user-attachments/assets/4df3b268-1f1f-4335-9d6c-e896acfc4f3a" />

When running locally we see **mlruns** and **mlartifacts** folder in the repo where the data and model versions are stored. This consumes space.
<img width="819" height="81" alt="image" src="https://github.com/user-attachments/assets/7b2d2261-f9d8-4bd2-9ada-200458591725" />

