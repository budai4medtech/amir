# References 

### Tutorials
* https://medium.com/analytics-vidhya/automatic-medical-report-generation-from-x-ray-images-through-ai-fd04de21e0e5


### Papers 

* "Kisilev, Pavel, Eugene Walach, Ella Barkan, Boaz Ophir, Sharon Alpert, and Sharbell Y. Hashoul. "From medical image to automatic medical report generation." IBM Journal of Research and Development 59, no. 2/3 (2015): 2-1."
	* https://scholar.google.com/scholar?cites=8599281882524414873&as_sdt=2005&sciodt=0,5&hl=en
	* https://dl.acm.org/doi/abs/10.1147/JRD.2015.2393193 

* "Beddiar, Djamila-Romaissa, Mourad Oussalah, and Tapio Seppänen. "Automatic captioning for medical imaging (MIC): a rapid review of literature." Artificial Intelligence Review (2022): 1-58."
	* https://scholar.google.com/scholar?cites=17538774958422476129&as_sdt=2005&sciodt=0,5&hl=en
	* https://link.springer.com/article/10.1007/s10462-022-10270-w
	* http://jultika.oulu.fi/files/nbnfi-fe2022112266458.pdf 

* "Messina, Pablo, Pablo Pino, Denis Parra, Alvaro Soto, Cecilia Besa, Sergio Uribe, Marcelo Andía, Cristian Tejos, Claudia Prieto, and Daniel Capurro. "A survey on deep learning and explainability for automatic report generation from medical images." ACM Computing Surveys (CSUR) 54, no. 10s (2022): 1-40."
	* https://scholar.google.com/scholar?cites=16068217954678035852&as_sdt=2005&sciodt=0,5&hl=en
	* https://dl.acm.org/doi/full/10.1145/3522747
	* https://d1wqtxts1xzle7.cloudfront.net/83527458/3522747-libre.pdf?1649482279=&response-content-disposition=inline%3B+filename%3DA_Survey_on_Deep_Learning_and_Explainabi.pdf

* "Pavlopoulos, John, Vasiliki Kougia, and Ion Androutsopoulos. "A survey on biomedical image captioning." In Proceedings of the second workshop on shortcomings in vision and language, pp. 26-36. 2019."
	* https://scholar.google.com/scholar?cites=14486454225648790993&as_sdt=2005&sciodt=0,5&hl=en
	* https://link.springer.com/article/10.1007/s10115-022-01684-7 
	* http://nlp.cs.aueb.gr/pubs/sivl2019_survey_biomedical_image_captioning.pdf 



* "Jing, Baoyu, Pengtao Xie, and Eric Xing. "On the automatic generation of medical imaging reports." arXiv preprint arXiv:1711.08195 (2017)."  
	* https://scholar.google.com/scholar?cites=9461012927859481985&as_sdt=2005&sciodt=0,5&hl=en
	* https://arxiv.org/abs/1711.08195

* "Bustos, Aurelia, Antonio Pertusa, Jose-Maria Salinas, and Maria de la Iglesia-Vayá. "Padchest: A large chest x-ray image dataset with multi-label annotated reports." Medical image analysis 66 (2020): 101797."     
	* https://scholar.google.com/scholar?cites=17182219564324787720&as_sdt=2005&sciodt=0,5&hl=en 
	* https://arxiv.org/abs/1901.07441v1
	* https://doi.org/10.1016/j.media.2020.101797 
	* https://bimcv.cipf.es/bimcv-projects/padchest/ 

* "Zhang, Yuhao, Hang Jiang, Yasuhide Miura, Christopher D. Manning, and Curtis P. Langlotz. "Contrastive learning of medical visual representations from paired images and text." arXiv preprint arXiv:2010.00747 (2020)."   
	* https://scholar.google.com/scholar?cites=764350615429622964&as_sdt=2005&sciodt=0,5&hl=en
	* https://arxiv.org/abs/2010.00747

* "Sun, Jinghan, Dong Wei, Liansheng Wang, and Yefeng Zheng. "Lesion guided explainable few weak-shot medical report generation." In Medical Image Computing and Computer Assisted Intervention–MICCAI 2022: 25th International Conference, Singapore, September 18–22, 2022, Proceedings, Part V, pp. 615-625. Cham: Springer Nature Switzerland, 2022."
	* https://scholar.google.com/scholar?cites=286386169678107398&as_sdt=2005&sciodt=0,5&hl=en
	* https://link.springer.com/chapter/10.1007/978-3-031-16443-9_59
	* https://arxiv.org/abs/2211.08732


### Software libraries

### Adding new literature in bibtex
When adding a new manuscript or proceedings, it is suggested to do the following:
1. Copy and paste the template with -${year}, -${author}, -${venue of the publication} and -${PUBLISHER}:
``` 
cp -r 0000-YEAR-LastNameFirstAuthor-in-Journal-PUBLISHER/ ${year}-${author}-${venue of the publication}-${PUBLISHER}
```

2. Edit README and add the date when the work was retrieved, google citations, bibtex and other fields if there is information. See below one example:
```  

### Citations
1

https://scholar.google.com/scholar?cites=15657830865269166932&as_sdt=2005&sciodt=0,5&hl=en
Retrived
Mon 20 Sep 19:50:40 BST 2021

### Authors 

### Notes

### Links 
https://github.com/laumerf/DeepHeartBeat

https://slideslive.com/38941017/deepheartbeat-latent-trajectory-learning-of-cardiac-cycles-using-cardiac-ultrasounds?locale=cs



### Bibtex 

@InProceedings{pmlr-v136-laumer20a,
  title = 	 {DeepHeartBeat: Latent trajectory learning of cardiac cycles using cardiac ultrasounds},
  author =       {Laumer, Fabian and Fringeli, Gabriel and Dubatovka, Alina and Manduchi, Laura and Buhmann, Joachim M.},
  booktitle = 	 {Proceedings of the Machine Learning for Health NeurIPS Workshop},
  pages = 	 {194--212},
  year = 	 {2020},
  editor = 	 {Alsentzer, Emily and McDermott, Matthew B. A. and Falck, Fabian and Sarkar, Suproteem K. and Roy, Subhrajit and Hyland, Stephanie L.},
  volume = 	 {136},
  series = 	 {Proceedings of Machine Learning Research},
  month = 	 {11 Dec},
  publisher =    {PMLR},
  pdf = 	 {http://proceedings.mlr.press/v136/laumer20a/laumer20a.pdf},
  url = 	 {https://proceedings.mlr.press/v136/laumer20a.html},
  abstract = 	 {Echocardiography monitors the heart movement for noninvasive diagnosis of heart diseases. It proves to be of profound practical importance as it combines low-cost portable instrumentation and rapid image acquisition without the risks of ionizing radiation. However, echocardiograms produce high-dimensional, noisy data which frequently proved difficult to interpret. As a solution, we propose a novel autoencoder-based framework, DeepHeartBeat, to learn human interpretable representations of cardiac cycles from cardiac ultrasound data. Our model encodes high dimensional observations by a cyclic trajectory in a lower dimensional space. We show that the learned parameters describing the latent trajectory are well interpretable and we demonstrate the versatility of our model by successfully applying it to various cardiologically relevant tasks, such as ejection fraction prediction and arrhythmia detection. As a result, DeepHeartBeat promises to serve as a valuable assistant tool for automating therapy decisions and guiding clinical care.}
}

```

3. Add bibtex file to the latex new-literature document
Open [new-literature.tex](new-literature.bib) and add bibtex of the paper. 
Then add a summary of the paper using citing the author in [../content-tex/new-literature.tex](../content-tex/new-literature.tex). 
For instance: `Laumer et al. proposed a novel autoencoder-based framework to learn human interpretable representation of cardiac cycles from cardiac ultrasound data \cite{laumer2020}`.

4. Commit changes to branch 10-new-literature 
```
git add .
git commit -m '#10 adds 2020-laumer-in-NeurIPS-PMLR; CITEX'
git push origin 10-new-literature  
```
