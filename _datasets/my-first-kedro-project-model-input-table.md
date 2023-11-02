---
schema: default
title: my-first-kedro-project-model-input-table
organization: 
notes: type = kedro_datasets.pandas.parquet_dataset.ParquetDataset
resources:
  - name: my-first-kedro-project-model-input-table
    url: 'https://github.com/fakeOrg/fakeRepo/tree/main/data/03_primary/model_input_table.pq'
    format: pq
category:
  - 03-primary
maintainer: 
maintainer_email: 
project:
  - my-first-kedro-project
preview: |
  <table border="1" class="dataframe">
    <thead>
      <tr style="text-align: right;">
        <th></th>
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
        <th>shuttle_id</th>
        <th>review_scores_rating</th>
        <th>review_scores_comfort</th>
        <th>review_scores_amenities</th>
        <th>review_scores_trip</th>
        <th>review_scores_crew</th>
        <th>review_scores_location</th>
        <th>review_scores_price</th>
        <th>number_of_reviews</th>
        <th>reviews_per_month</th>
        <th>id</th>
        <th>company_rating</th>
        <th>company_location</th>
        <th>total_fleet_count</th>
        <th>iata_approved</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th>0</th>
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
        <td>63561</td>
        <td>97.0</td>
        <td>10.0</td>
        <td>9.0</td>
        <td>10.0</td>
        <td>10.0</td>
        <td>9.0</td>
        <td>10.0</td>
        <td>133</td>
        <td>1.65</td>
        <td>35029</td>
        <td>1.00</td>
        <td>Niue</td>
        <td>4.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>1</th>
        <td>Niue</td>
        <td>Type V5</td>
        <td>Quantum</td>
        <td>Banks, Wood and Phillips</td>
        <td>1.0</td>
        <td>2</td>
        <td>strict</td>
        <td>1.0</td>
        <td>False</td>
        <td>False</td>
        <td>1325.0</td>
        <td>35029</td>
        <td>53260</td>
        <td>98.0</td>
        <td>10.0</td>
        <td>9.0</td>
        <td>10.0</td>
        <td>10.0</td>
        <td>9.0</td>
        <td>10.0</td>
        <td>37</td>
        <td>0.48</td>
        <td>35029</td>
        <td>1.00</td>
        <td>Niue</td>
        <td>4.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>2</th>
        <td>Niue</td>
        <td>Type V5</td>
        <td>Quantum</td>
        <td>ThetaBase Services</td>
        <td>1.0</td>
        <td>2</td>
        <td>flexible</td>
        <td>1.0</td>
        <td>False</td>
        <td>False</td>
        <td>1260.0</td>
        <td>35029</td>
        <td>51019</td>
        <td>92.0</td>
        <td>10.0</td>
        <td>9.0</td>
        <td>10.0</td>
        <td>10.0</td>
        <td>9.0</td>
        <td>9.0</td>
        <td>10</td>
        <td>0.15</td>
        <td>35029</td>
        <td>1.00</td>
        <td>Niue</td>
        <td>4.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>3</th>
        <td>Niue</td>
        <td>Type V5</td>
        <td>Plasma</td>
        <td>ThetaBase Services</td>
        <td>3.0</td>
        <td>5</td>
        <td>strict</td>
        <td>3.0</td>
        <td>False</td>
        <td>False</td>
        <td>2196.0</td>
        <td>35029</td>
        <td>53898</td>
        <td>98.0</td>
        <td>10.0</td>
        <td>9.0</td>
        <td>10.0</td>
        <td>10.0</td>
        <td>9.0</td>
        <td>10.0</td>
        <td>11</td>
        <td>0.21</td>
        <td>35029</td>
        <td>1.00</td>
        <td>Niue</td>
        <td>4.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>4</th>
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
        <td>36260</td>
        <td>90.0</td>
        <td>8.0</td>
        <td>9.0</td>
        <td>10.0</td>
        <td>9.0</td>
        <td>9.0</td>
        <td>9.0</td>
        <td>3</td>
        <td>0.09</td>
        <td>30292</td>
        <td>0.67</td>
        <td>Anguilla</td>
        <td>6.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>6</th>
        <td>Anguilla</td>
        <td>Type O3</td>
        <td>Quantum</td>
        <td>ThetaBase Services</td>
        <td>1.0</td>
        <td>3</td>
        <td>strict</td>
        <td>3.0</td>
        <td>True</td>
        <td>False</td>
        <td>1975.0</td>
        <td>30292</td>
        <td>32973</td>
        <td>80.0</td>
        <td>8.0</td>
        <td>6.0</td>
        <td>10.0</td>
        <td>10.0</td>
        <td>10.0</td>
        <td>8.0</td>
        <td>1</td>
        <td>0.21</td>
        <td>30292</td>
        <td>0.67</td>
        <td>Anguilla</td>
        <td>6.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>7</th>
        <td>Anguilla</td>
        <td>Type O3</td>
        <td>Quantum</td>
        <td>ThetaBase Services</td>
        <td>1.0</td>
        <td>2</td>
        <td>strict</td>
        <td>1.0</td>
        <td>True</td>
        <td>False</td>
        <td>1754.0</td>
        <td>30292</td>
        <td>5333</td>
        <td>60.0</td>
        <td>8.0</td>
        <td>6.0</td>
        <td>10.0</td>
        <td>10.0</td>
        <td>8.0</td>
        <td>6.0</td>
        <td>1</td>
        <td>0.03</td>
        <td>30292</td>
        <td>0.67</td>
        <td>Anguilla</td>
        <td>6.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>9</th>
        <td>Anguilla</td>
        <td>Type O3</td>
        <td>Quantum</td>
        <td>ThetaBase Services</td>
        <td>1.0</td>
        <td>1</td>
        <td>strict</td>
        <td>1.0</td>
        <td>True</td>
        <td>False</td>
        <td>1455.0</td>
        <td>30292</td>
        <td>23871</td>
        <td>80.0</td>
        <td>10.0</td>
        <td>10.0</td>
        <td>10.0</td>
        <td>10.0</td>
        <td>10.0</td>
        <td>10.0</td>
        <td>1</td>
        <td>0.37</td>
        <td>30292</td>
        <td>0.67</td>
        <td>Anguilla</td>
        <td>6.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>10</th>
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
        <td>57015</td>
        <td>95.0</td>
        <td>9.0</td>
        <td>10.0</td>
        <td>9.0</td>
        <td>10.0</td>
        <td>9.0</td>
        <td>9.0</td>
        <td>14</td>
        <td>0.14</td>
        <td>19032</td>
        <td>0.67</td>
        <td>Russian Federation</td>
        <td>4.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>11</th>
        <td>Russian Federation</td>
        <td>Type V5</td>
        <td>Plasma</td>
        <td>ThetaBase Services</td>
        <td>1.0</td>
        <td>5</td>
        <td>moderate</td>
        <td>2.0</td>
        <td>False</td>
        <td>False</td>
        <td>2807.0</td>
        <td>19032</td>
        <td>19134</td>
        <td>93.0</td>
        <td>9.0</td>
        <td>9.0</td>
        <td>10.0</td>
        <td>10.0</td>
        <td>9.0</td>
        <td>9.0</td>
        <td>76</td>
        <td>0.85</td>
        <td>19032</td>
        <td>0.67</td>
        <td>Russian Federation</td>
        <td>4.0</td>
        <td>False</td>
      </tr>
    </tbody>
  </table>
---