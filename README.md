This demo follows the storyline from [Machine Learning Demo: Predicting Citibike Trips Using Snowflake & Facebook Prophet](https://snowflakecomputing.atlassian.net/wiki/spaces/democentral/pages/719032128/Machine+Learning+Demo+Predicting+Citibike+Trips+Using+Snowflake+Facebook+Prophet) with one addition, it uses snowpark, instead of the snowflake python connector.


It works with [citibike V4](https://github.com/snowflakecorp/citibike)

<br>

<b>Steps to install snowpark for python:</b>
* Create Snowpark env with Python 3.8: conda create <env_name> python=3.8
* Activate new environment: conda activate <env_name>
* Download latest Snowpark https://drive.google.com/drive/folders/1clWwh6lvx3KNuT3TfPwdPG-u-phEtwab 
* Install Snowpark wheel: pip install 'snowflake_snowpark_python-0.5.0-py3-none-any.whl[pandas]'

<br>
Create a new json credential file <em>creds.json</em> following this structure:

```javascript
{
    "account": "",
    "user": "",
    "password": "",
    "warehouse": "",
    "database": "CITIBIKE",
    "schema": "DEMO"
  }
```

