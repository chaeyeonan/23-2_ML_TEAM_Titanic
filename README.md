# 23-2_ML_TEAM_Titanic

## 📝 Project Info
### Overview
This project aims to address privacy concerns in the context of Website Fingerprinting attacks on the Tor network. Website Fingerprinting poses a significant threat to user anonymity, and our objective is to explore and implement effective defense mechanisms against such attacks.

### Problem Definition
Website Fingerprinting allows adversaries to deduce visited websites based on traffic patterns, compromising user privacy even within the anonymity-focused Tor network. This project seeks to identify vulnerabilities and develop defenses to maintain Tor's anonymity.


## ⚙️ How to Run 
### Setup on Google Colab

1. Open the provided Colab notebook in Google Colab.
2. Mount your Google Drive to access the dataset. Run the following code snippet:

    ```python
    from google.colab import drive
    drive.mount('/content/drive')
    ```

3. Import necessary libraries and load the dataset:

    ```python
    import pandas as pd
    import numpy as np
    from sklearn.model_selection import train_test_split
    ```

4. Load the dataset:

    ```python
    mon_features_modified = pd.read_csv('/content/drive/MyDrive/ML_Project/mon_features_modified.csv')
    mon_labels = pd.read_csv('/content/drive/MyDrive/ML_Project/mon_labels.csv')

    unmon_features_modified = pd.read_csv('/content/drive/MyDrive/ML_Project/unmon_features_modified.csv')
    unmon_labels = pd.read_csv('/content/drive/MyDrive/ML_Project/unmon_labels.csv')
    ```
    **⭐ Note: If you have the dataset stored in a different location, modify the paths accordingly.**

5. Import additional libraries if needed and proceed with your experiments.

    ```python
    import numpy as np
    import pandas as pd
    import matplotlib.pyplot as plt
    
    from sklearn.model_selection import train_test_split
    from sklearn.preprocessing import StandardScaler
    from sklearn.metrics import accuracy_score, confusion_matrix
    ```

6. Run the code cells in the Colab notebook sequentially to reproduce the experiments.

## 🛳️ Team Titanic Member 
<table border="1" cellspacing="0" cellpadding="0" width="90%">
    <tr width="100%">
        <td width="16%" align="center"><a href= "https://github.com/jaeeunHwang">HWANG JAEEUN</a></td>
        <td width="16%" align="center"><a href= "https://github.com/
songing01">SONG JIMIN</a></td>
        <td width="16%" align="center"><a href= "https://github.com/chhaewxn">SONG CHAEWON</a></td>
        <td width="16%" align="center"><a href= "https://github.com/chaeyeonan">AN CHAEYEON</a></td>
        <td width="16%" align="center"><a href= "https://github.com/dttbia23">LEE NAMYOUNG</a></td>
        <td width="16%" align="center"><a href= "https://github.com/ri-naa">KIM RINA</a></td>
    </tr>
    <tr width="100%">
        <td width="16%" align="center"><img src = "https://github.com/jaeeunHwang.png"></td>
        <td width="16%" align="center"><img src = "https://github.com/songing01.png"/></td>
        <td width="16%" align="center"><img src = "https://github.com/chhaewxn.png"/></td>
        <td width="16%" align="center"><img src = "https://github.com/chaeyeonan.png"/></td>
        <td width="16%" align="center"><img src = "https://github.com/dttbia23.png"/></td>
        <td width="16%" align="center"><img src = "https://github.com/ri-naa.png"/></td>
    </tr>
    <tr width="100%">
        <td width="16%" align="center">Random Forest</td>
        <td width="16%" align="center">Data Analysis</td>
        <td width="16%" align="center">SVM</td>
        <td width="16%" align="center">Data Analysis</td>
        <td width="16%" align="center">Random Forest</td>
        <td width="16%" align="center">SVM</td>
   </tr>
</table>
