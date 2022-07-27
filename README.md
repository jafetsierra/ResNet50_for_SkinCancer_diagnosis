# ResNet50_for_SkinCancer diagnosis


### Original dataset from DOI: **10.1038/sdata.2018.161**

[See the paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6091241/)

ResNet50 model as feature straction for skin lesion classification.



Lesion types included within the dataset:

```
{
    'nv': 'Melanocytic nevi',
    'mel': 'melanoma',
    'bkl': 'Benign keratosis',
    'bcc': 'Basal cell carcinoma',
    'akiec': 'Actinic keratoses',
    'vasc': 'Vascular lesions',
    'df': 'Dermatofibroma'
}
```

*  **{nv} Melanocytic nevi**: Dry scaly patches of skin that have been damaged by the sun. The patches are not usually serious. But there's a small chance they could become skin cancer.
*  **{mel} melanoma**: The most serious type of skin cancer.
Melanoma occurs when the pigment-producing cells that give colour to the skin become cancerous.
*  **{bkl} Bening Keratosis**: A non-cancerous skin condition that appears as a waxy brown, black or tan growth.
* **{bcc} basal cell carcinoma**: A type of skin cancer that begins in the basal cells that rarely metastasizes but grows destructively if untreated.
* **{akiec} Actinic keratoses**: variants of squamous cell carcinoma that can be treated locally without surgery. Some authors regard them as precursors of squamous cell carcinomas and not as actual carcinomas.
* **{vasc} Vascular lesions**: Angiomas are dermatoscopically characterized by red or purple color and solid, well circumscribed structures known as red clods or lacunes.
* **{df} Dermatofibroma**:  benign skin lesion regarded as either a benign proliferation or an inflammatory reaction to minimal trauma.


The model return an array with 7 probabilities each one for each class.
