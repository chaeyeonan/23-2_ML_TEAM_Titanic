# 23-2_ML_TEAM_Titanic

## 📝 Project Info
![image](https://github.com/chhaewxn/23-2_ML_TEAM_Titanic/assets/96541582/018b20cd-8ae1-4ea2-bee9-5f6c333cf44a)

### Overview
Our project delves into the intricate realm of combating Website Fingerprinting—a menace to user privacy. As technology advances, adversaries exploit traffic patterns, posing a threat to anonymity, especially within the Tor network. Our research aims to unveil vulnerabilities inherent in Tor's defense mechanisms against fingerprinting attacks, crucial for preserving user privacy.

### Problem Definition
Website Fingerprinting, a sophisticated form of attack, jeopardizes user privacy by allowing adversaries to deduce visited websites based on traffic patterns. Despite Tor's robust anonymity, it struggles to fully defend against such attacks, necessitating thorough research. Our focus is to identify and understand these vulnerabilities, paving the way for the development of effective defenses, ensuring the resilience of Tor's anonymity.

### Experiment Settings and Environment
Executing experiments in the Colab environment, we harnessed the power of T4 GPU, 12.7GB RAM, and 78.2GB disk space. To ensure robustness, we employed an INTEL i9-12900K as an alternative during downtimes. Initial experiments involved feature visualization and subsequent refinement through the removal of less significant features, resulting in improved accuracy.


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
    import numpy as np
    import pandas as pd
    import matplotlib.pyplot as plt
    
    from sklearn.model_selection import train_test_split
    from sklearn.preprocessing import StandardScaler
    from sklearn.metrics import accuracy_score, confusion_matrix
    ```
    
4. Load the dataset:

    ```python
    mon_features_modified = pd.read_csv('/content/drive/MyDrive/ML_Project/mon_features_modified.csv')
    mon_labels = pd.read_csv('/content/drive/MyDrive/ML_Project/mon_labels.csv')

    unmon_features_modified = pd.read_csv('/content/drive/MyDrive/ML_Project/unmon_features_modified.csv')
    unmon_labels = pd.read_csv('/content/drive/MyDrive/ML_Project/unmon_labels.csv')
    ```
    **⭐ Note: If you have the dataset stored in a different location, modify the paths accordingly.**

5. Run the code cells in the Colab notebook sequentially to reproduce the experiments.

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
