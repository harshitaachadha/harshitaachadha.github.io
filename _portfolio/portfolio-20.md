---
title: "Scalnet7"
excerpt: "<img src='/images/scalnet.png'><br/><br/>Using convolutional neural networks to analyze EEG data to detect Schizophrenia in adolescents."
collection: portfolio
---
> Access the GitHub repository for the project [here](https://github.com/harshitaachadha/Scalnet7){:target="_blank"}

> A brief presentation summarising the project and results can be found [here](/files/scalnet.pdf){:target="_blank"}

Schizophrenia is a serious mental health disorder that inhibits the ability of an individual to function as a productive member of society. Despite the criticality of this disorder’s nature, clinical detection methods remain highly convoluted and the diagnosis is usually delayed. This article proposes a convolutional neural network-based schizophrenia detection technique that makes use of biomedical signals to classify patient groups. The use of electroencephalogram (EEG) data from an adolescent control group is done to tailor the model to facilitate accurate early detection.

To prepare the EEG impulses, the Morlet Wavelet Transform is used to obtain RGB scalograms in image format. These are fed into the 7 layers-deep convolutional neural network. In the end, the model is shown to have the highest testing accuracy of 94.4% and an F1 score of 0.945. The lightweight nature of the model and the comparatively less computational complexity of the used algorithms therein coupled with the superior performance metrics make it a classifier that can be successfully used for field diagnostics.
