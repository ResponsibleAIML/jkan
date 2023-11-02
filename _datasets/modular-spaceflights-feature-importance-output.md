---
schema: default
title: modular-spaceflights-feature-importance-output
organization: demo_org
notes: type = kedro_datasets.pandas.csv_dataset.CSVDataset
resources:
  - name: modular-spaceflights-feature-importance-output
    url: 'https://github.com/ResponsibleAIML/django-kedro/tree/main/kedro-projects/demo-project-kedro/data/04_feature/feature_importance_output.csv'
    format: csv
category:
  - 04-feature
maintainer: 
maintainer_email: 
project:
  - modular-spaceflights
preview: |
  <table border="1" class="dataframe">
    <thead>
      <tr style="text-align: right;">
        <th></th>
        <th>Feature</th>
        <th>Score</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th>0</th>
        <td>feature_0</td>
        <td>0.217396</td>
      </tr>
      <tr>
        <th>1</th>
        <td>feature_1</td>
        <td>0.557859</td>
      </tr>
      <tr>
        <th>2</th>
        <td>feature_2</td>
        <td>0.872854</td>
      </tr>
      <tr>
        <th>3</th>
        <td>feature_3</td>
        <td>0.059506</td>
      </tr>
      <tr>
        <th>4</th>
        <td>feature_4</td>
        <td>0.799646</td>
      </tr>
      <tr>
        <th>5</th>
        <td>feature_5</td>
        <td>0.594777</td>
      </tr>
      <tr>
        <th>6</th>
        <td>feature_6</td>
        <td>0.438294</td>
      </tr>
      <tr>
        <th>7</th>
        <td>feature_7</td>
        <td>0.128272</td>
      </tr>
      <tr>
        <th>8</th>
        <td>feature_8</td>
        <td>0.752643</td>
      </tr>
      <tr>
        <th>9</th>
        <td>feature_9</td>
        <td>0.273373</td>
      </tr>
    </tbody>
  </table>
---