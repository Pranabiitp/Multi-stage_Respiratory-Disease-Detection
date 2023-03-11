# Fuzzy Ensemble-based Multi-stage Network for COVID-19 detection and Severity Assessment from Chest X-ray
Abstract: Chest radiography (CXR) is a commonly used imaging modality for var-
ious lung abnormality screening. It plays a crucial role in monitoring the
progression of the disease, allocating limited medical resources, and plan-
ning treatment in daily clinical practice. However, the manual screening
process of CXR images is time-intensive and prone to human error. Thus,
computer-aided diagnosis (CAD) can be an additional decision-maker
for medical professionals. Even though previous studies achieved impres-
sive success in COVID-19 classification tasks but localizing the infection
and quantifying its severity remain challenges, which limit the generaliz-
ability and interpretability of CAD-based models. This work presents a
multi-stage ensemble architecture for COVID-19 classification, infection
localization, and severity assessment using CXR datasets. In particular,
we have utilized three segmentation models for lung region segmentation
and ensemble the outcomes to extract the region of interest at the first
stage. In the second stage, we adapted an ensemble technique based on
Choquet Fuzzy Integral with three pre-trained classifiers. The last stage
of the network identifies the infection regions, calculates the amount of
infection if the image is classified as COVID-19, and assigns a score (0–3)
based on the severity of the infection. Based on the predicted scores,
the COVID-19 images are categorized into four different severity levels,
such as mild, moderate, severe, and critical. 
