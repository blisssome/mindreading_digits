# Notes on attempts in mind reading - EEG 

  ## Motivation
  
  No worries, my intention are not nefarious. I am trying to understand to what extent can we use the brain signals from the surface of the scalp to read minds.
I always wanted to store my thoughts so I can go through them, maybe to discover something new about myself, or store a flash idea that I have. This is a bit too ambitious, however this dataset shows me that it is not impossible. Our thoughts originate in the brain which consists of many neurons that produce electric fields when excited. They propagate and reach our scalp from where we use BCI devices to read them. These signals are strongly attenuated and distorted as they pass through the brain, skull, and scalp due to volume conduction and the resistive properties of biological tissues. Despite those interferences, they are often used to diagnose health issues like epilepsy, head traumas, sleep issues, etc. However, I still want to understand to what extent it is possible to decode the higher-order cognitive function from non-invasive EEG.
  There have already been advances where invasive EEG implants were used to decode thoughts for paralized individuals (or a single individual to be more precise) [[1](#1)]. This is an amazing advancement, that made me happy. Perhaps in the future people with such disabilities can regain ability to speak again, at least I hope so. 

## Dataset

The dataset I am using in this project is called [MINDBIGDATA](https://www.mindbigdata.com/). There are plenty of dataset which were organized by David Vivancos and Felix Cuesta. From the dataset catalog I have decided to use "MNIST of Brain Digits 2015". Here we can find the readings from 4 BCI devices and the format is given as a .txt file.   


# References

<a id="1"></a>  
**[1]** Littlejohn, K. T., Cho, C. J., Liu, J. R., Silva, A. B., Yu, B., Anderson, V. R., Kurtz‑Miott, C. M., Brosler, S., Kashyap, A. P., Hallinan, I. P., Shah, A., Tu‑Chan, A., Ganguly, K., Moses, D. A., Chang, E. F., & Anumanchipalli, G. K. (2025). A streaming brain‑to‑voice neuroprosthesis to restore naturalistic communication. *Nature Neuroscience, 28*(4), 902–912. https://doi.org/10.1038/s41593-025-01905-6
