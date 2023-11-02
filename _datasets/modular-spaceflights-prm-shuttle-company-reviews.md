---
schema: default
title: modular-spaceflights-prm-shuttle-company-reviews
organization: demo_org
notes: type = kedro_datasets.pandas.parquet_dataset.ParquetDataset
resources:
  - name: modular-spaceflights-prm-shuttle-company-reviews
    url: 'https://github.com/ResponsibleAIML/django-kedro/tree/main/kedro-projects/demo-project-kedro/data/03_primary/prm_shuttle_company_reviews.pq'
    format: pq
category:
  - 03-primary
maintainer: 
maintainer_email: 
project:
  - modular-spaceflights
preview: |
  <table border="1" class="dataframe">
    <thead>
      <tr style="text-align: right;">
        <th></th>
        <th>shuttle_id</th>
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
        <th>review_scores_rating</th>
        <th>review_scores_comfort</th>
        <th>review_scores_amenities</th>
        <th>review_scores_trip</th>
        <th>review_scores_crew</th>
        <th>review_scores_location</th>
        <th>review_scores_price</th>
        <th>number_of_reviews</th>
        <th>reviews_per_month</th>
        <th>review_id</th>
        <th>company_rating</th>
        <th>company_location</th>
        <th>total_fleet_count</th>
        <th>iata_approved</th>
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
        <td>97</td>
        <td>10</td>
        <td>9</td>
        <td>10</td>
        <td>10</td>
        <td>9</td>
        <td>10</td>
        <td>133</td>
        <td>1.65</td>
        <td>1</td>
        <td>1.00</td>
        <td>Niue</td>
        <td>4.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>1</th>
        <td>53260</td>
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
        <td>98</td>
        <td>10</td>
        <td>9</td>
        <td>10</td>
        <td>10</td>
        <td>9</td>
        <td>10</td>
        <td>37</td>
        <td>0.48</td>
        <td>1354</td>
        <td>1.00</td>
        <td>Niue</td>
        <td>4.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>2</th>
        <td>51019</td>
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
        <td>92</td>
        <td>10</td>
        <td>9</td>
        <td>10</td>
        <td>10</td>
        <td>9</td>
        <td>9</td>
        <td>10</td>
        <td>0.15</td>
        <td>1985</td>
        <td>1.00</td>
        <td>Niue</td>
        <td>4.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>3</th>
        <td>53898</td>
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
        <td>98</td>
        <td>10</td>
        <td>9</td>
        <td>10</td>
        <td>10</td>
        <td>9</td>
        <td>10</td>
        <td>11</td>
        <td>0.21</td>
        <td>4879</td>
        <td>1.00</td>
        <td>Niue</td>
        <td>4.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>4</th>
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
        <td>90</td>
        <td>8</td>
        <td>9</td>
        <td>10</td>
        <td>9</td>
        <td>9</td>
        <td>9</td>
        <td>3</td>
        <td>0.09</td>
        <td>2</td>
        <td>0.67</td>
        <td>Anguilla</td>
        <td>6.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>5</th>
        <td>32973</td>
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
        <td>80</td>
        <td>8</td>
        <td>6</td>
        <td>10</td>
        <td>10</td>
        <td>10</td>
        <td>8</td>
        <td>1</td>
        <td>0.21</td>
        <td>16448</td>
        <td>0.67</td>
        <td>Anguilla</td>
        <td>6.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>6</th>
        <td>5333</td>
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
        <td>60</td>
        <td>8</td>
        <td>6</td>
        <td>10</td>
        <td>10</td>
        <td>8</td>
        <td>6</td>
        <td>1</td>
        <td>0.03</td>
        <td>16449</td>
        <td>0.67</td>
        <td>Anguilla</td>
        <td>6.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>7</th>
        <td>23871</td>
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
        <td>80</td>
        <td>10</td>
        <td>10</td>
        <td>10</td>
        <td>10</td>
        <td>10</td>
        <td>10</td>
        <td>1</td>
        <td>0.37</td>
        <td>16620</td>
        <td>0.67</td>
        <td>Anguilla</td>
        <td>6.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>8</th>
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
        <td>95</td>
        <td>9</td>
        <td>10</td>
        <td>9</td>
        <td>10</td>
        <td>9</td>
        <td>9</td>
        <td>14</td>
        <td>0.14</td>
        <td>3</td>
        <td>0.67</td>
        <td>Russian Federation</td>
        <td>4.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>9</th>
        <td>19134</td>
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
        <td>93</td>
        <td>9</td>
        <td>9</td>
        <td>10</td>
        <td>10</td>
        <td>9</td>
        <td>9</td>
        <td>76</td>
        <td>0.85</td>
        <td>120</td>
        <td>0.67</td>
        <td>Russian Federation</td>
        <td>4.0</td>
        <td>False</td>
      </tr>
    </tbody>
  </table>
---