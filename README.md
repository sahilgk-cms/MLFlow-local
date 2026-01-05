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

