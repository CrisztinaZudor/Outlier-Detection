# Outlier-Detection

Outlier detection is essential for identifying anomalies in datasets, ensuring data quality, and enabling actionable insights. <br>
This project evaluates three key methods: Empirical Covariance, Robust Covariance (MCD), and One-Class Support Vector Machine (OCSVM), using the Wine dataset. <br>
<br>
Ouliers can be defined as: <br>
* Observations that deviate significantly from the expected patterns or distributions within a dataset <br>
* Noise points lying outside a set of defined clusters <br>
* Surprising veridical data <br>
<br>
In the image bellow, the dataset contains two distinct regions of normal behavior, denoted as N1 and
N2, where the majority of observations are concentrated. Observations that markedly deviate from these normative clusters can be classified as outliers. This is exemplified by 
points O1 and O2, which are isolated data points situated at considerable distances from
the normal regions. Additionally, the region O3 represents a cluster of outliers, demonstrating that anomalous observations may occur either as individual points or as groups 
that collectively deviate from the established normal behavior patterns.<br>

![Image](https://github.com/user-attachments/assets/2aa83800-0f85-478c-a026-39b57fd733e0)

<br>
The project consists of two analyses. The first analysis focuses on the variables "ash" and "malic acid," which exhibit a simpler, clustered distribution, demonstrating the algorithm's effectiveness in identifying outliers in structured data. The second analysis examines the variables "flavanoids" and "color intensity," characterized by a banana-shaped, non-linear distribution, testing the algorithms' ability to handle complex patterns.<br>


## How to Run the Code

### Running the Code in Google Colab

You can easily run the code in Google Colab with the following steps:

1. **Open in Colab**: Navigate to the `OutlierDetection.ipynb` notebook in this repository. You will find an "Open in Colab" button at the top of the notebook. Click this button to open the notebook directly in Google Colab.

2. **Running the Notebook**: Once the notebook is open in Google Colab, you can execute the code:
    - Run all cells in sequence by clicking on `Runtime` in the menu bar, then selecting `Run all`.
    - Alternatively, run each cell individually by clicking the play button on the left side of each code cell.

### Running Locally

If you prefer to run the notebook locally:
1. **Download the Notebook**: Click on `OutlierDetection.ipynb` in the GitHub repository and download it by clicking on `Raw`, then right-clicking and choosing "Save as" to download the file to your local machine.
2. **Upload to Colab**: Go to [Google Colab](https://colab.research.google.com/), and select `Upload notebook` from the `File` menu to upload the downloaded `.ipynb` file.
3. **Run the Notebook**: Follow the same steps as above to run the notebook cells sequentially or individually.


