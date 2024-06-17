# Brain-Tumor-Classification

**Task 2: Brain Tumor Classification**

- **What is a Brain Tumor**

A brain tumor, known as an intracranial tumor, is an abnormal mass of tissue in which cells grow and multiply uncontrollably, seemingly unchecked by the mechanisms that control normal cells.

It can be diagnosed using MRI Scans. The MRI technique provides information about white matter tracts, which are signaling pathways in the brain, to help the physician evaluate the cellularity, nature and structure of a brain tumor. This technique can also provide information about a stroke.

- **What is the project**

This project tends to utilize deep learning algorithms essentially Convulational Neural Network (CNN) to classify the MRI scan images to detect if it contains a tumor cell or not.

- **About the input dataset**

The input dataset is divided into 2 categories namely, train and test. The train category contain to further categories including the scans which has tumor cell and the one which does not contain that. Further, the dataset also includes test folder which contains the scans to test the deployed model.

- **Methodology utilized**

The basic outline of the methodology can be divided into the following categories:

i) Data Preprocessing

ii) Exploratory Data Analysis and visualization

iii) Deploying a CNN model

iv) Evaluation of the result

i) Data Preprocessing:

The name and format of each of the file is not consistent for further analysis, thus it is made consistent by renaming the train and test data as for instance Y_1.jpg if the file contains an image having the tumor. The same operation is performed on the train as well as test dataset.

Additionally, the borders of the images are cropped to make the study as little easier

![](file:///C:/Users/kumar/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

ii) Exploratory Data Analysis:

Programming approach is taken to get familier of the dataset. All the images present in the train dataset is plotted by labelling it as 'yes' and 'no'.

![](file:///C:/Users/kumar/AppData/Local/Temp/msohtmlclip1/01/clip_image004.jpg)![](file:///C:/Users/kumar/AppData/Local/Temp/msohtmlclip1/01/clip_image006.jpg)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  

iii) Deploying a CNN Model:

The dataset is divided into train and test datasets and then a CNN model is fitted on the dataset.

The summary of the deployed model is as following:

![](file:///C:/Users/kumar/AppData/Local/Temp/msohtmlclip1/01/clip_image008.png)

The model is deployed over 30 epoch cycles and only the model is best accuracy score is contained.

iv) Evaluation of the result:

The model is evaluated basically on four main parameters namely,

a. Training Loss

b. Validation Loss

c. Training Accuracy

d. ![](file:///C:/Users/kumar/AppData/Local/Temp/msohtmlclip1/01/clip_image010.png)Validation Accuracy

|  |
|  | ![](file:///C:/Users/kumar/AppData/Local/Temp/msohtmlclip1/01/clip_image012.png) |

- **Result Discussion**

The CNN model is able to predict the presence and non-presence of tumor cells in the MRI scans. Though the accuracy of the model can to be further refined to achieve an optimum level.

Obtained Statistics:

Test Loss = 0.8308942914009094

Test Accuracy = 0.4166666567325592

Number of examples:78

Percentage of positive examples: 48.717948717948715%, number of pos examples: 38

Percentage of negative examples: 51.282051282051285%, number of neg examples: 40

Training Data:

Number of examples:54

Percentage of positive examples: 48.148148148148145%, number of pos examples: 26

Percentage of negative examples: 51.851851851851855%, number of neg examples: 28

Validation Data:

Number of examples:12

Percentage of positive examples: 58.333333333333336%, number of pos examples: 7

Percentage of negative examples: 41.666666666666664%, number of neg examples: 5

Testing Data:

Number of examples:12

Percentage of positive examples: 41.666666666666664%, number of pos examples: 5

Percentage of negative examples: 58.333333333333336%, number of neg examples: 7

- **References:**

[Link to Jupyter Notebook](https://colab.research.google.com/drive/1j7GwDly9FIdzmKwyzp8x0_5LMPHq8SGC?usp=sharing)

Github Repository
