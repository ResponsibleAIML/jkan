---
schema: default
title: modular-spaceflights-ingestion--int-typed-shuttles--pandas2
organization: demo_org
notes: type = kedro_datasets.pandas.parquet_dataset.ParquetDataset
resources:
  - name: modular-spaceflights-ingestion--int-typed-shuttles--pandas2
    url: 'https://github.com/ResponsibleAIML/django-kedro/tree/main/kedro-projects/demo-project-kedro/data/02_intermediate/typed_shuttles.pq'
    format: pq
category:
  - 02-intermediate
maintainer: 
maintainer_email: 
project:
  - modular-spaceflights
preview: |
  <table border="1" class="dataframe">
    <thead>
      <tr style="text-align: right;">
        <th></th>
        <th>id</th>
        <th>shuttle_location</th>
        <th>shuttle_type</th>
        <th>engine_type</th>
        <th>engine_vendor</th>
        <th>engines</th>
        <th>passenger_capacity</th>
        <th>cancellation_policy</th>
        <th>crew</th>
        <th>d_check_complete</th>
        <th>moon_clearance_complete</th>
        <th>price</th>
        <th>company_id</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th>0</th>
        <td>63561</td>
        <td>Niue</td>
        <td>Type V5</td>
        <td>Quantum</td>
        <td>ThetaBase Services</td>
        <td>1.0</td>
        <td>2</td>
        <td>strict</td>
        <td>1.0</td>
        <td>False</td>
        <td>False</td>
        <td>1325.0</td>
        <td>35029</td>
      </tr>
      <tr>
        <th>1</th>
        <td>36260</td>
        <td>Anguilla</td>
        <td>Type V5</td>
        <td>Quantum</td>
        <td>ThetaBase Services</td>
        <td>1.0</td>
        <td>2</td>
        <td>strict</td>
        <td>1.0</td>
        <td>True</td>
        <td>False</td>
        <td>1780.0</td>
        <td>30292</td>
      </tr>
      <tr>
        <th>2</th>
        <td>57015</td>
        <td>Russian Federation</td>
        <td>Type V5</td>
        <td>Quantum</td>
        <td>ThetaBase Services</td>
        <td>1.0</td>
        <td>2</td>
        <td>moderate</td>
        <td>0.0</td>
        <td>False</td>
        <td>False</td>
        <td>1715.0</td>
        <td>19032</td>
      </tr>
      <tr>
        <th>3</th>
        <td>14035</td>
        <td>Barbados</td>
        <td>Type V5</td>
        <td>Plasma</td>
        <td>ThetaBase Services</td>
        <td>3.0</td>
        <td>6</td>
        <td>strict</td>
        <td>3.0</td>
        <td>False</td>
        <td>False</td>
        <td>4770.0</td>
        <td>8238</td>
      </tr>
      <tr>
        <th>4</th>
        <td>10036</td>
        <td>Sao Tome and Principe</td>
        <td>Type V2</td>
        <td>Plasma</td>
        <td>ThetaBase Services</td>
        <td>2.0</td>
        <td>4</td>
        <td>strict</td>
        <td>2.0</td>
        <td>False</td>
        <td>False</td>
        <td>2820.0</td>
        <td>30342</td>
      </tr>
      <tr>
        <th>5</th>
        <td>45163</td>
        <td>Sao Tome and Principe</td>
        <td>Type V5</td>
        <td>Plasma</td>
        <td>ThetaBase Services</td>
        <td>2.0</td>
        <td>4</td>
        <td>moderate</td>
        <td>2.0</td>
        <td>False</td>
        <td>False</td>
        <td>1715.0</td>
        <td>32413</td>
      </tr>
      <tr>
        <th>6</th>
        <td>64643</td>
        <td>Faroe Islands</td>
        <td>Type F5</td>
        <td>Quantum</td>
        <td>ThetaBase Services</td>
        <td>1.0</td>
        <td>2</td>
        <td>strict</td>
        <td>1.0</td>
        <td>True</td>
        <td>False</td>
        <td>1247.0</td>
        <td>35620</td>
      </tr>
      <tr>
        <th>7</th>
        <td>23389</td>
        <td>Micronesia</td>
        <td>Type V5</td>
        <td>Quantum</td>
        <td>ThetaBase Services</td>
        <td>1.0</td>
        <td>1</td>
        <td>moderate</td>
        <td>1.0</td>
        <td>False</td>
        <td>False</td>
        <td>1845.0</td>
        <td>23820</td>
      </tr>
      <tr>
        <th>8</th>
        <td>39934</td>
        <td>Rwanda</td>
        <td>Type V5</td>
        <td>Quantum</td>
        <td>ThetaBase Services</td>
        <td>1.0</td>
        <td>3</td>
        <td>strict</td>
        <td>2.0</td>
        <td>False</td>
        <td>False</td>
        <td>1520.0</td>
        <td>46528</td>
      </tr>
      <tr>
        <th>9</th>
        <td>57063</td>
        <td>Faroe Islands</td>
        <td>Type F5</td>
        <td>Plasma</td>
        <td>ThetaBase Services</td>
        <td>4.0</td>
        <td>8</td>
        <td>strict</td>
        <td>5.0</td>
        <td>False</td>
        <td>False</td>
        <td>3275.0</td>
        <td>11875</td>
      </tr>
    </tbody>
  </table>
---