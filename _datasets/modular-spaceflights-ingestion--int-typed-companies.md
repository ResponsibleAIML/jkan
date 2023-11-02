---
schema: default
title: modular-spaceflights-ingestion--int-typed-companies
organization: demo_org
notes: type = kedro_datasets.pandas.parquet_dataset.ParquetDataset
resources:
  - name: modular-spaceflights-ingestion--int-typed-companies
    url: 'https://github.com/ResponsibleAIML/django-kedro/tree/main/kedro-projects/demo-project-kedro/data/02_intermediate/typed_companies.pq'
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
        <th>company_rating</th>
        <th>company_location</th>
        <th>total_fleet_count</th>
        <th>iata_approved</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th>0</th>
        <td>35029</td>
        <td>1.00</td>
        <td>Niue</td>
        <td>4.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>1</th>
        <td>30292</td>
        <td>0.67</td>
        <td>Anguilla</td>
        <td>6.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>2</th>
        <td>19032</td>
        <td>0.67</td>
        <td>Russian Federation</td>
        <td>4.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>3</th>
        <td>8238</td>
        <td>0.91</td>
        <td>Barbados</td>
        <td>15.0</td>
        <td>True</td>
      </tr>
      <tr>
        <th>4</th>
        <td>30342</td>
        <td>NaN</td>
        <td>Sao Tome and Principe</td>
        <td>2.0</td>
        <td>True</td>
      </tr>
      <tr>
        <th>5</th>
        <td>32413</td>
        <td>1.00</td>
        <td>Faroe Islands</td>
        <td>1.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>6</th>
        <td>35620</td>
        <td>0.90</td>
        <td>Micronesia</td>
        <td>3.0</td>
        <td>False</td>
      </tr>
      <tr>
        <th>7</th>
        <td>23820</td>
        <td>NaN</td>
        <td>Rwanda</td>
        <td>1.0</td>
        <td>True</td>
      </tr>
      <tr>
        <th>8</th>
        <td>46528</td>
        <td>1.00</td>
        <td>Uzbekistan</td>
        <td>3.0</td>
        <td>True</td>
      </tr>
      <tr>
        <th>9</th>
        <td>11875</td>
        <td>1.00</td>
        <td>Micronesia</td>
        <td>2.0</td>
        <td>True</td>
      </tr>
    </tbody>
  </table>
---