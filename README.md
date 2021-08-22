# Mentoring at Hackathon RIIAA 2021 “JusticIA para los desaparecidos”
The aim of this repository is to put together few references that might be of helpful for the participants of the [Hackathon RIIAA 2021 “JusticIA para los desaparecidos”](https://docs.google.com/document/d/1-4cKb-VQ6WOTmxnj1yc_pmQwYRFwmTxmf6xndlFYKmg/edit). 
References are related to the topics of (1) automatic document image analysis, (2) reproducibility and (3) guidelines for pitches.

## (1) Automatic document image analysis
### Handwritten text recognition 
* [google-search](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=handwritten+text+recognition&btnG=)
* [arXiv-papers](https://arxiv.org/search/?query=Handwritten+text+recognition+&searchtype=all&source=header)
* Tutorials
  * https://towardsdatascience.com/build-a-handwritten-text-recognition-system-using-tensorflow-2326a3487cd5  
  * https://pythonrepo.com/repo/arthurflor23-handwritten-text-recognition-python-computer-vision 

###  Detecting signatures 
* :notebook_with_decorative_cover: Tutorials
  * https://stackoverflow.com/questions/57382935/detecting-and-extracting-signature-from-image-with-opencv
* :octopus: Github repositories 
  * https://github.com/ahmetozlu/signature_extractor 
* Papers
  * https://link.springer.com/chapter/10.1007/978-3-030-63319-6_43

### Optical Character Recognition (OCR)
* LayoutLM: Pre-training of Text and Layout for Document Image Understanding. Xu et al. 2019 [arXiv](https://arxiv.org/abs/1912.13318) 
  > LayoutXLM is a multimodal pre-trained model for multilingual document understanding, which aims to bridge the language barriers for visually-rich document understanding. https://github.com/microsoft/unilm/tree/master/layoutxlm
  * document AI : https://www.microsoft.com/en-us/research/project/document-ai/ 
  * paper: https://arxiv.org/abs/1912.13318
  * code: https://huggingface.co/transformers/model_doc/layoutlm.html
  
* Document Layout Analysis
  * See references in [papers-with-code](https://paperswithcode.com/task/document-layout-analysis)
  * L. O'Gorman, "The document spectrum for page layout analysis," in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 15, no. 11, pp. 1162-1173, Nov. 1993. [google-citations](https://scholar.google.com/scholar?cites=2431160171337997771&as_sdt=2005&sciodt=0,5&hl=en)

* Scene Text Detection 
  * See references in [papers-with-code](https://paperswithcode.com/task/scene-text-detection)
  * Wang et al. "ContourNet: Taking a Further Step toward Accurate Arbitrary-shaped Scene Text Detection", 2020, [arXiv](https://arxiv.org/abs/2004.04940)
  
### OCR based on tesseract 

#### :notebook_with_decorative_cover: Tutorials 
* Practical application of OpenCV OCR (Optical Character Recognition) with python and tesseract-ocr. 
https://www.pyimagesearch.com/2018/09/17/opencv-ocr-and-text-recognition-with-tesseract/ 
* Getting started with EasyOCR for Optical Character Recognition
https://www.pyimagesearch.com/2020/09/14/getting-started-with-easyocr-for-optical-character-recognition/
* Extracting text from images with Tesseract OCR, OpenCV, and Python  
https://www.opcito.com/blogs/extracting-text-from-images-with-tesseract-ocr-opencv-and-python   
* Build from Source Tesseract-OCR 4.0 for OpenCV tracking and OCR on Ubuntu 16.04   
https://www.youtube.com/watch?v=WZLJucXZy-g    
* OpenCV Text Detection (EAST text detector)   
https://www.pyimagesearch.com/2018/08/20/opencv-text-detection-east-text-detector  

#### :octopus: Github repositories 
* https://github.com/JaidedAI/EasyOCR   
* https://github.com/a1xg/Tesseract-opencv-OCR-for-product-labels   
* https://github.com/chd0043/openCV_Tesseract_test   
* https://github.com/kairess/license_plate_recognition   
* https://github.com/stefbo/ulr-ocr    
* https://github.com/viraj96/Smart_Glasses    
* https://github.com/tesseract-ocr/tesseract   
* More in this search: https://github.com/search?q=+Tesseract+and+OpenCV&type=repositories    

### :cherries: Few references on topics around automatic document image analysis
* G Nagy, "Twenty years of document image analysis in PAMI" in in IEEE Transactions on Pattern Analysis and Machine Intelligence [paper](https://www.ee.bgu.ac.il/~dinstein/stip2002/TwentyYearDocAnalysisPAMI.pdf), [google-citations](https://scholar.google.com/scholar?cites=18209354881365601693&as_sdt=2005&sciodt=0,5&hl=en).
* L. O'Gorman, "The document spectrum for page layout analysis," in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 15, no. 11, pp. 1162-1173, Nov. 1993. [google-citations](https://scholar.google.com/scholar?cites=2431160171337997771&as_sdt=2005&sciodt=0,5&hl=en)
* Sarika et al.,"CNN based Optical Character Recognition and Applications", in 2021 6th International Conference on Inventive Computation Technologies (ICICT) [ieee-paper](https://ieeexplore.ieee.org/abstract/document/9358735)
* Zhou et al 2017, "EAST: An Efficient and Accurate Scene Text Detector", [arXiv](https://arxiv.org/abs/1704.03155) 
* N Sarika, NR Sirisala,  "Deep Learning Techniques for Optical Character Recognition" in Sustainable Communication Networks and ..., 2021 - Springer [paper-research-gate](https://www.researchgate.net/profile/Bapayya-Kommula/publication/348748584_An_Efficient_Energy_Management_of_Hybrid_Renewable_Energy_Sources_Based_Smart-Grid_System_Using_an_IEPC_Technique/links/60586be8a6fdccbfeaf8b25e/An-Efficient-Energy-Management-of-Hybrid-Renewable-Energy-Sources-Based-Smart-Grid-System-Using-an-IEPC-Technique.pdf#page=344)  
* References from Joaquín Peña Acevedo.
  * CJ Du, DW Sun " Recent developments in the applications of image processing techniques for food quality evaluation" in Trends in food science & technology, 2004 - Elsevier  [google-citations](https://scholar.google.com/scholar?cites=4841850530052080161&as_sdt=2005&sciodt=0,5&hl=en)  [DOI](https://doi.org/10.1016/j.tifs.2003.10.006)
  * M Kass, A Witkin, D Terzopoulos "Snakes: Active contour models" in International journal of computer vision, 1988 - Springer [google-citations](https://scholar.google.com/scholar?cites=4764690932703791888&as_sdt=2005&sciodt=0,5&hl=en) [PDF](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.124.5318&rep=rep1&type=pdf)
  * M Omid, M Khojastehnazhand…  "" in Journal of food …, 2010 - Elsevier [google-citations](https://scholar.google.com/scholar?cites=11079442554057887436&as_sdt=2005&sciodt=0,5&hl=en) [DOI](https://doi.org/10.1016/j.jfoodeng.2010.04.015)
  * N Otsu "A threshold selection method from gray-level histograms" in IEEE transactions on systems, man, and cybernetics, 1979 [google-citations](https://scholar.google.com/scholar?cites=18093383773288908217&as_sdt=2005&sciodt=0,5&hl=en) [PDF](https://cw.fel.cvut.cz/b201/_media/courses/a6m33bio/otsu.pdf)
  * JA Sethian "Level Set Methods and Fast Marching Methods" in book 1999 [google-citations](https://scholar.google.com/scholar?cites=2901443054886525192&as_sdt=2005&sciodt=0,5&hl=en) [PS](https://math.berkeley.edu/~sethian/Books/hold_sethian_book.ps)
  * A. Papandreou et al "Efficient skew detection of printed document images based on novel combination of enhanced profiles" in International Journal on Document Analysis and Recognition (IJDAR) 17(4):433-454. [google-citations](https://scholar.google.com/scholar?cites=13913932226282934167&as_sdt=2005&sciodt=0,5&hl=en) [PDF](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.704.1552&rep=rep1&type=pdf)
  * F Drira, F LeBourgeois "Mean-Shift segmentation and PDE-based nonlinear diffusion: toward a common variational framework for foreground/background document image segmentation" in International Journal on Document Analysis and …, 2017 - Springer [google-citations](https://scholar.google.com/scholar?cites=11435358389871937066&as_sdt=2005&sciodt=0,5&hl=en) [DOI](https://link.springer.com/article/10.1007/s10032-017-0285-7)
  
### :green_book: Books
* "Document Image Analysis", Lawrence O’Gorman and Rangachar Kasturi 2009 [:link:](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.182.6107&rep=rep1&type=pdf) [google-citations](https://scholar.google.com/scholar?cites=15004238720478995212&as_sdt=2005&sciodt=0,5&hl=en)

## (2) :school_satchel: Computational reproducibility  
* Freire et. al, "Computational reproducibility: state-of-the-art, challenges, and database research opportunities" 2012 in SIGMOD '12: Proceedings of the 2012 ACM SIGMOD International Conference on Management of Data [paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.369.8403&rep=rep1&type=pdf) [google-citations](https://scholar.google.com/scholar?cites=15216268858418305840&as_sdt=2005&sciodt=0,5&hl=en) 
* [ACM SIGMOD 2021 Reproducibility](https://reproducibility.sigmod.org/)
* (Reproducibility Challenge @ NeurIPS 2019)[https://reproducibility-challenge.github.io/neurips2019/resources/]
* Joelle Pineau’s Reproducibility [Checklist](https://www.cs.mcgill.ca/~jpineau/ReproducibilityChecklist.pdf) 
* [ICLR2018-ReproducibilityChallenge-Readings](https://www.cs.mcgill.ca/~jpineau/ICLR2018-ReproducibilityChallenge-Readings.pdf)
* ICLR 2019 Reproducibility Challenge [Accepted Papers](https://rescience.github.io/read/#volume-5-2019) at ReScience Journal
* ICLR 2019 Reproducibility Challenge [Submissions](https://github.com/reproducibility-challenge/iclr_2019/pulls) 
* Joelle Pineau’s Keynote [talk](https://www.facebook.com/nipsfoundation/videos/2120856364798049/) on Reproducibility at NeurIPS 2018 

## (3) Guidelines for pitches  
* Comprehension & Content( Did the presentation provide an understanding of the background to the research question being addressed and its significance?, Did the presentation clearly describe the key results of the research including conclusions and outcomes?, Did the presentation follow a clear and logical sequence?, Was the thesis topic, key results and research significance and outcomes communicated in language appropriate to a non-specialist audience?,etc)
* Engagement & Communication (Did the oration make the audience want to know more?, Was the presenter careful not to trivialise or generalise their research?, Did the presenter convey enthusiasm for their research?, Did the presenter capture and maintain their audience's attention?,Did the speaker have sufficient stage presence, eye contact and vocal range; maintain a steady pace, and have a confident stance?, Did the PowerPoint slide enhance the presentation - was it clear, legible, and concise?) 
* Tips for the pitches (Be enthusiastic and show your passion for your subject, Help the audience relate to your research by emphasising its relevance and any real-world applications or examples, Speak clearly and don’t rush... if you tend to speed up when nervous, check yourself on this, Time yourself and practice keeping within the three minute limit, A comfortable speed of delivery for oral presentation is approximately 80 words per minute. You should therefore be aiming for approximately 200 -250 written words for your three-minute summary,etc).
* See this reference for more [:link:](https://github.com/mxochicale/3mt#presentations-will-be-judged-according-to-the-following-criteria)

## :busts_in_silhouette: Contributors 
Bursztyn, Victor [@username](https://github.com/)  
Peña Acevedo, Joaquín [@username](https://github.com/)  
Xochicale, Miguel  [@mxochicale](https://github.com/mxochicale)

## Clone repository
After generating your SSH keys as suggested [here](https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) or [here](https://github.com/mxochicale/tools/blob/main/github/SSH.md) with few personal notes.
You can then clone the repository by typing (or copying) the following line in a terminal at your selected path in your machine:
```
git clone git@github.com:mxochicale/mentoring-at-justicIA-2021.git
```

## Issues Contact 
If you have specific questions about the content of this repository, you can contact 
[Miguel Xochicale](mailto:perez.xochicale@gmail.com?subject="[Mentoring@JusticIA]"). 
If your question might be relevant to other people, please instead 
[open an issue](https://github.com/mxochicale/mentoring-at-justicIA-2021/issues).
