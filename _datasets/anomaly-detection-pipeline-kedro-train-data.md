---
schema: default
title: anomaly-detection-pipeline-kedro-train-data
organization: other_org
notes: type = kedro_mlflow.io.artifacts.mlflow_artifact_dataset.CSVDataset.MlflowCSVDataset
resources:
  - name: anomaly-detection-pipeline-kedro-train-data
    url: 'https://github.com/ResponsibleAIML/django-kedro/tree/main/kedro-projects/anomaly-detection-pipeline-kedro/data/05_model_input/train.csv'
    format: csv
category:
  - 05-model-input
maintainer: 
maintainer_email: 
project:
  - anomaly-detection-pipeline-kedro
preview: |
  <table border="1" class="dataframe">
    <thead>
      <tr style="text-align: right;">
        <th></th>
        <th>TX_AMOUNT</th>
        <th>TX_DURING_WEEKEND</th>
        <th>TX_DURING_NIGHT</th>
        <th>CUSTOMER_ID_NB_TX_1DAY_WINDOW</th>
        <th>CUSTOMER_ID_NB_TX_7DAY_WINDOW</th>
        <th>CUSTOMER_ID_NB_TX_30DAY_WINDOW</th>
        <th>CUSTOMER_ID_AVG_AMOUNT_1DAY_WINDOW</th>
        <th>CUSTOMER_ID_AVG_AMOUNT_7DAY_WINDOW</th>
        <th>CUSTOMER_ID_AVG_AMOUNT_30DAY_WINDOW</th>
        <th>TERMINAL_ID_NB_TX_1DAY_WINDOW</th>
        <th>TERMINAL_ID_NB_TX_7DAY_WINDOW</th>
        <th>TERMINAL_ID_NB_TX_30DAY_WINDOW</th>
        <th>TERMINAL_ID_RISK_1DAY_WINDOW</th>
        <th>TERMINAL_ID_RISK_7DAY_WINDOW</th>
        <th>TERMINAL_ID_RISK_30DAY_WINDOW</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th>0</th>
        <td>57.16</td>
        <td>1</td>
        <td>1</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>57.160</td>
        <td>57.160</td>
        <td>57.160</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
      </tr>
      <tr>
        <th>1</th>
        <td>81.51</td>
        <td>1</td>
        <td>1</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>81.510</td>
        <td>81.510</td>
        <td>81.510</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
      </tr>
      <tr>
        <th>2</th>
        <td>146.00</td>
        <td>1</td>
        <td>1</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>146.000</td>
        <td>146.000</td>
        <td>146.000</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
      </tr>
      <tr>
        <th>3</th>
        <td>64.49</td>
        <td>1</td>
        <td>1</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>64.490</td>
        <td>64.490</td>
        <td>64.490</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
      </tr>
      <tr>
        <th>4</th>
        <td>50.99</td>
        <td>1</td>
        <td>1</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>50.990</td>
        <td>50.990</td>
        <td>50.990</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
      </tr>
      <tr>
        <th>5</th>
        <td>44.71</td>
        <td>1</td>
        <td>1</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>44.710</td>
        <td>44.710</td>
        <td>44.710</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
      </tr>
      <tr>
        <th>6</th>
        <td>96.03</td>
        <td>1</td>
        <td>1</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>96.030</td>
        <td>96.030</td>
        <td>96.030</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
      </tr>
      <tr>
        <th>7</th>
        <td>24.36</td>
        <td>1</td>
        <td>1</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>24.360</td>
        <td>24.360</td>
        <td>24.360</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
      </tr>
      <tr>
        <th>8</th>
        <td>26.34</td>
        <td>1</td>
        <td>1</td>
        <td>2.0</td>
        <td>2.0</td>
        <td>2.0</td>
        <td>45.415</td>
        <td>45.415</td>
        <td>45.415</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
      </tr>
      <tr>
        <th>9</th>
        <td>59.07</td>
        <td>1</td>
        <td>1</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>59.070</td>
        <td>59.070</td>
        <td>59.070</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.0</td>
      </tr>
    </tbody>
  </table>
---