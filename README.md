# Description
Melanoma is the most dangerous type of skin cancer. Globally, in 2012, it newly occurred in 232,000 people. In 2015, there were 3.1 million people with active disease, which resulted in 59,800 deaths. Australia and New Zealand have the highest rates of melanoma in the world. There are also high rates in Northern Europe and North America, while it is less common in Asia, Africa, and Latin America. In the United States melanoma occurs about 1.6 times more often in men than women.

This is a regression probelm and we try to predict the tumor size. This dataset was the part of machinehack hackathon that I participated in.
We will apply the models manually in one code and pycaret autoML in the other.

#
### Data Description:
- mass_npea:  the mass of the area understudy for melanoma tumor
- size_npear: the size of the area understudy for melanoma tumor
- malign_ratio: ration of normal to malign surface understudy
- damage_size: unrecoverable area of skin damaged by the tumor
- exposed_area: total area exposed to the tumor
- std_dev_malign: standard deviation of malign skin measurements
- err_malign: error in malign skin measurements
- malign_penalty: penalty applied due to measurement error in the lab
- damage_ratio: the ratio of damage to total spread on the skin
- tumor_size: size of melanoma_tumor

#
### Source
The dataset is downloaded from kaggle. You can find it [here](https://www.kaggle.com/vpkprasanna/melanoma-tumor-size-prediction-machinehack).
#