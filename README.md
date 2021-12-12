# Data_Cleaning_with_python <br />

## uploading a csv file into colab and converting it into dataframe

``` import pandas as pd
    import io
    from google.colab import files
    uploaded=files.upload()
    df2 = pd.read_csv(io.BytesIO(uploaded['File_name.csv'])) 
```

**Standardisation** <br />
**Syntax Errors** <br />
**Irrelevant Data**<br />
**Duplicates**<br />
**Missing Data**<br />
**Outliers**
