# thesis

The aim of the present thesis is the design, development and evaluation of an interpretable model
for the assessment of the risk of Cardiovascular Disease (CVD) in patients with Type 2 Diabetes
Mellitus (T2DM). T2DM is the most common form of DM and is characterized by elevated blood
glucose levels due to insulin resistance and/or limited insulin secretion. Patients with T2DM are
at an increased CVD risk and present higher CVD-related mortality rates compared to the general
population. Although international guidelines recommend the use of predictive models to assess the
risk of developing a first CVD event, the inability to develop models that achieve both accuracy and
interpretability is a barrier to the adoption of predictive models in clinical practice.
The development of the proposed interpretable model is based on the combined use of the boosting algorithm XGBoost and the Tree SHAP interpretability method. The model receives as input
demographic, somatometric and clinical data as well as lifestyle and treatment data, and calculates the
probability of CVD incidence within a five-year time span. In order to handle the unbalanced nature
of the used dataset, an ensemble learning strategy is adopted towards the generation of multiple individual models, and the combination of their decisions in order to produce the final CVD risk scores.
The same combination scheme is applied towards the interpretation of the decisions of the final (ensemble) model, by utilising the Tree SHAP method. Data collected from a 5-year follow up of 560
T2DM individuals at the Hippokration General Hospital of Athens were used for development and
evaluation purposes. The model’s predictive performance was measured in terms of discrimination
and calibration, and evidence was provided on the model’s ability to produce explainable CVD risk
scores.

http://artemis.cslab.ece.ntua.gr:8080/jspui/handle/123456789/17811


This paper received the Best Student Paper Award in IEEE BIBE 2020
