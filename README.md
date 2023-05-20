# Arrhythmia Detection using ECG


**Abstract:**

The electrocardiogram (ECG) is a crucial tool for detecting cardiovascular problems. Traditionally, ECG records were maintained on paper, requiring manual examination that was arduous and time-consuming. However, by digitizing paper ECG records, we can leverage image processing and machine learning techniques to automate diagnosis and analysis. In this project, our objective is to develop a system that converts ECG images into a 1-D signal, enabling the extraction of P, QRS, and T waves present in ECG signals. By employing various techniques, we can effectively demonstrate the electrical activity of the heart. Furthermore, after feature extraction, our system can assist in diagnosing a wide range of cardiac diseases. Through the integration of image processing, machine learning, and ECG analysis, we aim to improve the efficiency and accuracy of cardiovascular disease diagnosis, ultimately enhancing patient care and treatment outcomes.

**Datasets:**

ECG images: https://data.mendeley.com/datasets/gwbz3fsgp8/2 

The above dataset contains ECG image signals from both healthy individuals and persons with cardiovascular problems.

Download any image from the below folder path and try uploading it to the above url to get real-time insights.
https://github.com/rameshavinash94/Cardiovascular-Detection-using-ECG-images/tree/main/ECG_IMAGES_DATASET

**Approach:**

The user uploads an ECG image to our web app. Then, we use techniques like rgb2gray conversion, gaussian filtering, resizing, and thresholding to extract only the signals that do not have grid lines. The required waves (P, QRS, T) are then extracted using contour techniques and converted to a 1D signal. The normalized 1D signal is then fed into our pre-trained ML model, which is then analyzed. When the model has completed the analysis, it returns the results to the user based on the findings.

Here, we have used 4 categories for image classification for our ECG images.
_Normal
Myocardial infarction
Abnormal Heart beat
History of Myocardial infarction_

One benefit of our app is that the user can view the entire workflow in the UI and receive real-time feedback.

The tricky path here is feature extraction from images; if done correctly and optimally, the accuracy of our model can be increased.

**SAMPLE DEMO GIF**

![](https://raw.githubusercontent.com/rameshavinash94/Cardiovascular-Detection-using-ECG-images/main/img/demo.gif)


