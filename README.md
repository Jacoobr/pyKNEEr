# pyKNEEr

### An image analysis workflow for **open** and **reproducible** research on **femoral knee cartilage**


Try *pyKNEEr* on Binder:   
- Example #1: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sbonaretti/2019_QMSKI_Transparent_Research_WS/master?filepath=pykneer_example%2Fpykneer_example.ipynb)
- Example #2: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sbonaretti/2019_QMSKI_Transparent_Research_WS/master?filepath=pykneer_example_2%2Fpykneer_example_2.ipynb)


Documentation on [website](https://sbonaretti.github.io/pyKNEEr/)  
Peprint paper on [bioRxiv](https://www.biorxiv.org/content/10.1101/556423v1.article-info)

Release on Zenodo: [![DOI](https://zenodo.org/badge/155445441.svg)](https://zenodo.org/badge/latestdoi/155445441)

---

### Contributors

New code:
- Serena Bonaretti  

Open source code included in pyKNEEr:  
- [intensity preprocessing](https://bitbucket.org/marcniethammer/ksrt/src) by Liang Shan and [Marc Niethammer](http://wwwx.cs.unc.edu/~mn/?q=content/overview) 
- [Elastix](https://github.com/SuperElastix/elastix) for registration in atlas-based segmentation by [Stefan Klein](http://bigr.nl/people/StefanKlein/)
- Cylinder fitting for cartilage flattening by https://github.com/xingjiepan/cylinder_fitting

User feedbacks and suggestions for improvements:
- Tijmen Van Zadelhoff  
- Piyush Kumar Prajapati  
  
---  

### Changelog 
v 0.0.3: Reduced mask file size, added check to end of string in input .txt files, fixing ITK version to download for image orientation in preprocessing, added demo to Zenodo 
v 0.0.2: Minor  
v 0.0.1: First release  
