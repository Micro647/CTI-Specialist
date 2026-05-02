# CTI-Specialist: Multimodal Large Language Model  for  Cyber Threat Intelligence

#Intro:

Threat intelligence plays a critical role in tracing APT groups and facilitating threat sharing. In such intelligence data, visual and textual content are often closely intertwined. However, existing research has predominantly focused on processing textual modalities, while studies dedicated to visual content remain notably scarce. Yet, visual content often contains valuable and concentrated information that can significantly contribute to tracing APT groups. In this work, we collected APT reports from a wide range of sources, including GitHub and various cybersecurity company websites. From this corpus, we extracted 12737 high-quality images, which were then rigorously annotated over 192 person-hours  by experts and categorized into nine predefined types. The resulting dataset was split into an 8:2 ratio for training and evaluation, and formatted according to the LLaVA standard. Furthermore, we utilized the Intern-S1 model to generate a test set analogous to ScienceQA , comprising multiple-choice and true/false questions tailored to the cybersecurity domain, thereby establishing a dedicated evaluation benchmark.




## Directory Structure


- **Benchmarks:
This directory highlights and stores the specific data underlying the relevant judgments and selections.
. 
- **Examples.
This directory presents five example images from each of the nine data categories. The complete dataset is available for download as a ZIP file.

- **Image-Text Pair Dataset.
This directory stores the text modality of the image-text pair data. The corresponding complete image-text pair dataset is available for download as Image-Text_Pair_Dataset.zip

- **Multi-Turn-Dataset.
This dataset stores the textual content of the relevant multi-turn dialogue dataset. The corresponding image content can be downloaded via image.zip




```
