<h1 align="center">Awesome Resources for Scholarly Big Data </h1>
<h2 align="center">
Pick up scattered pearls and light up the fire for scholarly big data
 
</h2>

# News

#### Nature:[**Hundreds of extreme self-citing scientists revealed in new database**](https://www.nature.com/articles/d41586-019-02479-7)
#### [**Returnees are more difficult to obtain the title of "Yangtze River Scholar"**](https://academic.oup.com/spp/advance-article-abstract/doi/10.1093/scipol/scz004/5364332?redirectedFrom=fulltext)
#### The death of top-tier Totems：[ICLR](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652057572&idx=1&sn=8e9885a3d96095da23a67eceb1c5dc07&chksm=f1205b15c657d2036b993100ad841beb0f744b94c07563bd9a0802903f1990f05802c0d9cb1a&scene=0&xtrack=1&key=540c8d6698c698e06bc5312a273087055508e4c2e216c8f63d5b2af402ae24452958ee8a0eb42472ead3dc5c6f4d8b075eadb3e50f5c6d79caedaaa886af7f6607a07a21c24836effeafa68b68c29fba&ascene=1&uin=MjIxMTkyNDk2Mg%3D%3D&devicetype=Windows+10&version=62070152&lang=zh_CN&pass_ticket=JZtXew%2BqShLz1dYPDL1QXnpmS%2FTwdV212ecncVX1nap73IaLFqNCG1PrdxyD377V) 、[CVPR](https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650774388&idx=1&sn=777b02bed87586bb615be2f4026818e2&chksm=871a5f0ab06dd61c7bb3efd16fe45d81a61f50fa5b891c2e6788927ffc396eaacaee7ba575a3&scene=0&xtrack=1&key=ffd929ece98ce3760403617a053f0f2406251984d39be2a4998dcb79b8656fac97ff11dde75fee29a6575b85c5a174e45c1993fe167c89aa1cef2212c969dbb95f6eb380f9412ac8be0217cc9182ee81&ascene=1&uin=MjIxMTkyNDk2Mg%3D%3D&devicetype=Windows+10&version=62070158&lang=zh_CN&pass_ticket=gRlvpYVPPGNTo%2B18X2hqdrkE4SfJfR2Jk3EdLOgJ4OpNE616fvig9oP3tYuXOKie) 、[Xuetao Cao](https://www.guancha.cn/politics/2019_11_18_525504.shtml)

# Tools
## Bibliographical Extraction 
[**ParsCit**](https://github.com/knmnyn/ParsCit/blob/master/USAGE): 

ParsCit is a utility for extracting citations from research papers based on Conditional Random Fields and heuristic regularization.


### [GROBID](https://github.com/kermitt2/grobid) :
a machine learning library for extracting, parsing and re-structuring raw documents such as PDF into structured TEI-encoded documents with a particular focus on technical and scientific publications
http://cloud.science-miner.com/grobid/

### [CERMINE](http://cermine.ceon.pl/cermine/task.html?task=8692584047461514230):
Content ExtRactor and MINEr


### [FreeCite](http://freecite.library.brown.edu/welcome): 
FreeCite is an open-source application that parses document citations into fielded data. You can use it as a web application or a service

### [PerlPipelineExtractor] (https://github.com/SeerLabs/PerlPipelineExtractor)
Legend single threaded extractor written in Perl. External libraries such as SVMheaderparse, ParsCit, and PDFBox are involked.

## Figure Extraction from PDF Articles
### [PDFFigures](http://pdffigures2.allenai.org/) :
Extracting Figures from Research Papers,Mining Figures from Research Papers

### [deepfigures-open](https://github.com/allenai/deepfigures-open):
Figure extraction using deep neural nets

### [figure-extraction-ijdar](figure-extraction-ijdar)
Source code for methods described in Lu, Xiaonan, et al. "Automated analysis of images in documents for intelligent document search." International Journal on Document Analysis and Recognition (IJDAR) 12.2 (2009): 65-81.

## Table Extraction from PDF Articles
### [pdf2table](https://github.com/tfmorris/pdf2table):
extraction of table information from PDF-files based on pdf2html
URL2： http://ieg.ifs.tuwien.ac.at/projects/pdf2table/

### [Zanran](https://pdf.zanran.com/extract-table-from-pdf):
Many report types – financial reports, analysts reports, scientific reports – exist as PDFs (i.e. unstructured data).  And they often have valuable data in tables. 
The Zanran ‘Scaffolder’ software helps you get those tables out automatically – into Excel, XML or HTML.

### [TableBank](https://github.com/doc-analysis/TableBank)
TableBank is a new image-based table detection and recognition dataset built with novel weak supervision from Word and Latex documents on the internet, contains 417K high-quality labeled tables


## Equation or Formula Extraction
### [Formula-extraction](https://github.com/buaaliuming/Formula-extraction)

### [ChemxSeer Tagger](https://github.com/SeerLabs/chemxseer-tagger)
ChemxSeer Tagger provides a chemcial entity extractor that identifies mentions of chemical formula and names in free text.

## Algorithm Extractor
A Java jar to extract algorithms from PDFs.

## Keywords or Keyphrase Extraction 
### [KEA](http://community.nzdl.org/kea/):
Extracting Keywords or keyphrases. KEA is an algorithm for extracting keyphrases from text documents. It can be either used for free indexing or for indexing with a controlled vocabulary. KEA is implemented in Java and is platform independent. 

### [TextRank](https://github.com/davidadamojr/TextRank)
https://github.com/davidadamojr/TextRank

## Metedata Extraction

### [pdfmef](https://github.com/SeerLabs/pdfmef):
Multi-Entity Extraction Framework for Academic Documents (with default extraction tools)


### [Science-Parse](https://github.com/allenai/science-parse):
Science Parse parses scientific papers (in PDF form) and returns them in structured form.
It supports these fields: Title, Authors, Abstract, Sections (each with heading and body text), Bibliography, each with Title, Authors
Venue, Year, Mentions, i.e., places in the paper where bibliography entries are mentioned, In JSON format.


## Plain Text Extraction
### [PDFBox](https://pdfbox.apache.org/): 
Extract Unicode text from PDF files.

### [Apache POI](http://poi.apache.org/) - the Java API for Microsoft Documents
You can read and write MS Excel, PPT and Word files using Java API.The Apache POI Project's mission is to create and maintain Java APIs for manipulating various file formats based upon the Office Open XML standards (OOXML) and Microsoft's OLE 2 Compound Document format (OLE2).

## Research Papers Classification
[sbdsubjectclassifier](https://github.com/SeerLabs/sbdsubjectclassifier)
classify research papers into their subject areas. By splitting abstracts into words and converting each word into a n-dimensional word embedding, we project the text data into a vector space with time-steps.

## Academic Article Evaluation

### [Automatic Academic Paper Rating](https://github.com/lancopku/AAPR)
Rating articles based on LATEX source files and academic metedata

### [PeerRead](https://github.com/allenai/PeerRead)
Automatic PeerReview: Predict the accept/reject decisions in top-tier venues

### [Deep Paper Gestalt](https://github.com/vt-vl-lab/paper-gestalt)
a classifier to predict whether a paper should be accepted or rejected based ont the visual appearance of the paper

## Paper-Reviewer Assignments
### [The Toronto Paper Matching System (TPMS)](http://torontopapermatching.org/webapp/profileBrowser/about_us/)
The goal of this system is to help conference chairs with the task of assigning papers to reviewers.

### [MyReview](http://myreview.lri.fr/)(unavailable currently/20181202)


## Scholar Influence Analysis
### [Computer Science Rankings](https://github.com/emeryberger/CSrankings):
This ranking of top computer science schools is designed to identify institutions and faculty actively engaged in research across a number of areas of computer science. 
http://csrankings.org/#/index?all

## Scholar Gender Prediction
### [A simple scholar gender predictor.](https://github.com/xgeric/gender):


## Research Trends Visualization
### [Neviewer](https://link.springer.com/article/10.1007/s11192-014-1347-y)：
Analyse the evolution of research topics in a discipline based on co-word network analysis

### [CiteSpace](http://cluster.cis.drexel.edu/~cchen/citespace/): 
Visualizing Patterns and Trends in Scientific Literature


##  Dataset Search
[Making it easier to discover datasets](http://g.co/datasetsearch)

https://www.blog.google/products/search/making-it-easier-discover-datasets/

## Ontology parsing libraries
### [PyMedTermino](http://pythonhosted.org/PyMedTermino/)
A Python module for easy access to the main medical terminologies

### [Pronto5](http://pronto.readthedocs.io/en/latest/)
MeSH ontology

## Text Annotation
### [Research Articles in Simplified HTML (RASH)](https://github.com/essepuntato/rash)
Research Articles in Simplified HTML (RASH) Framework includes a markup language defined as a subset of HTML+RDF for writing scientific articles, and related tools to convert it into different formats, to extract data from it, etc.

### [Brat](http://brat.nlplab.org/introduction.html):
a web-based tool for text annotation

### [Chinese-Annotator](https://github.com/deepwel/Chinese-Annotator):
Annotator for Chinese Text Corpus 中文标注工具

### [GATE](https://gate.ac.uk/)
 GATE includes components for diverse language processing tasks, e.g. parsers, morphology, tagging, Information Retrieval tools, Information Extraction components for various languages, and many others. GATE Developer and Embedded are supplied with an Information Extraction system (ANNIE) which has been adapted and evaluated very widely (numerous industrial systems, research systems evaluated in MUC, TREC, ACE, DUC, Pascal, NTCIR, etc.). ANNIE is often used to create RDF or OWL (metadata) for unstructured conten

## Medical NLP Packages
### [Illinois Medical NER](http://cogcomp.org/page/software_view/MedNER)
This software identifies concepts in medical reports on patients, per the i2b2 shared task: https://www.i2b2.org/NLP/Relations/. 

### [Illinois Medical Coreference](http://cogcomp.org/page/software_view/MedCoref)

### [Illinois Medical Drug Abuse Detector](http://cogcomp.org/page/software_view/MedSHARPS)

## Platform
[DBLP](https://dblp.uni-trier.de/)  The dblp computer science bibliography provides open bibliographic information on major computer science journals and proceedings. Originally created at the University of Trier in 1993, dblp is now operated and further developed by Schloss Dagstuhl.

[CiteSeer](http://citeseerx.ist.psu.edu/index)

[AMiner](https://www.aminer.cn/)

[ResearchGate](https://www.researchgate.net/)

[onAcademic](https://www.onacademic.com)

[SCI-HUB |unavailable currently/20190110](http://www.sci-hub.org/)

[CiteUlike](http://www.citeulike.org/)

[SemanticSchoolar](https://www.semanticscholar.org/)

[Google Schoolar](https://scholar.google.com.hk/)

[Arxiv](https://arxiv.org/)
arXiv is a free distribution service and an open-access archive for 1,737,208 scholarly articles in the fields of physics, mathematics, computer science, quantitative biology, quantitative finance, statistics, electrical engineering and systems science, and economics. Materials on this site are not peer-reviewed by arXiv.

[BioRxiv](https://www.biorxiv.org/)

[AfricArxiv](https://info.africarxiv.org/)

[OpenReview](https://openreview.net/)

[PubPeer](https://pubpeer.com/)
The PubPeer database contains all articles. Search results return articles with comments.

[CORE](https://core.ac.uk/)

# Datasets, KG ,and Corpus
### [ Computer Science Ontology (CSO),14K topics and over 159K relationships](http://cso.kmi.open.ac.uk/home)
 The Computer Science Ontology (CSO) is a large-scale ontology of research areas that was automatically generated using the Klink-2 algorithm on the Rexplore dataset, which consists of about 16 million publications, mainly in the field of Computer Science. The Klink-2 algorithm combines semantic technologies, machine learning, and knowledge from external sources to automatically generate a fully populated ontology of research areas. Some relationships were also revised manually by experts during the preparation of two ontology-assisted surveys in the field of Semantic Web and Software Architecture. The main root of CSO is Computer Science, however, the ontology includes also a few secondary roots, such as Linguistics, Geometry, Semantics, and so on.

### [Academia/Industry DynAmics (AIDA) Knowledge Graph](http://aida.kmi.open.ac.uk/)
Academia/Industry DynAmics (AIDA) Knowledge Graph, which describes 14M publications and 8M patents according to the research topics drawn from the Computer Science Ontology. 4M publications and 5M patents are further characterized according to the type of the author's affiliations (academy, industry, or collaborative) and 66 industrial sectors (e.g., automotive, financial, energy, electronics) organized in a two-level taxonomy.

### [Ace KG](https://archive.acemap.info/app/AceKG/)
AceKG describes 114.30 million academic entities based on a consistent ontology, including 61,704,089 papers, 52,498,428 authors, 50,233 research fields, 19,843 academic institutes, 22,744 journals, 1,278 conferences and 3 special affiliations.

### [Artificial Intelligence Knowledge Graph (AI-KG)](http://scholkg.kmi.open.ac.uk/)
The Artificial Intelligence Knowledge Graph (AI-KG) is a large-scale automatically generated knowledge graph that describes 857,658 research entities. AI-KG includes 14M RDF triples and 1,2M statements extracted from 333K research publications in the field of AI and describes 5 types of entities (e.g., tasks, methods, metrics, materials, others) linked by 27 relations. It was designed to support a large variety of intelligent services for analyzing and making sense of research dynamics, supporting researchers in their daily job, and informing decision of founding bodies and research policy makers.

### [S2ORC: The Semantic Scholar Open Research Corpus](https://github.com/allenai/s2orc)
 This is the largest publicly-available contextual citation graph. The full text alone is the largest structured academic text corpus to date. The S2ORC dataset is a citation graph of 81.1M academic publications and 380.5M citation edges. Abstracts are available for 73.4M papers. Full text and citation contexts are available for 8.1M papers. Citation contexts are linked to their corresponding paper in the graph.

### [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/)
PubMed comprises more than 28 million citations for biomedical literature from MEDLINE, life science journals, and online books. Citations may include links to full-text content from PubMed Central and publisher web sites.


### [SN SciGraph](https://www.springernature.com/gp/researchers/scigraph)
Linked Open Data offering which aggregates data sources from Springer Nature and key partners from the scholarly domain. The Linked Open Data platform collates information from across the research landscape, for example funders, research projects, conferences, affiliations and publications.

### [Automatic Article Commenting: the Task and Dataset](http://ai.tencent.com/upload/PapersUploads/article_commenting.tgz)
The dataset is available on http://ai.tencent.com/upload/PapersUploads/article_commenting.tgz
https://arxiv.org/pdf/1805.03668.pdf

### [ICLR2020-OpenReviewData](https://github.com/shaohua0116/ICLR2020-OpenReviewData)

### [Automatic Academic Paper Rating (Dataset)](https://drive.google.com/file/d/1ttKdXUjaFi3eS6zeHITuZjsTGrh6M4ij/view)

### [PeerRead](https://github.com/allenai/PeerRead) （code and dataset for predict whether you paper will be accepted by top-tier venues）
PearRead is a dataset of scientific peer reviews available to help researchers study this important artifact. The dataset consists of over 14K paper drafts and the corresponding accept/reject decisions in top-tier venues including ACL, NIPS and ICLR, as well as over 10K textual peer reviews written by experts for a subset of the papers.

### [TableBank](https://github.com/doc-analysis/TableBank)
TableBank is a new image-based table detection and recognition dataset built with novel weak supervision from Word and Latex documents on the internet, contains 417K high-quality labeled tables

### [Academic Vocabulary Lists](https://www.academicvocabulary.info/)

### [AMiner Dataset](https://www.aminer.cn/data)

### [AMiner manually-labeled name disambiguation dataset](https://www.aminer.cn/billboard/id:5d7884c6530c70858e1bbbd2)

### [Microsoft Academic Graph](https://wsdmcupchallenge.azurewebsites.net/)
The Microsoft Academic Graph is a heterogeneous graph containing scientific publication records, citation relationships between publications, as well as authors, institutions, journal and conference "venues," and fields of study.

### [Open Academic Graph](https://www.openacademic.ai/oag/)
This data set is generated by linking two large academic graphs: Microsoft Academic Graph (MAG) and AMiner

### [Arxiv Bluk Corpus](https://arxiv.org/help/bulk_data)

### [Citeseer data and metadata](http://csxstatic.ist.psu.edu/downloads/data)
CiteSeerx data and metadata are available for others to use. Data available includes CiteSeerx metadata, databases, data sets of pdf files and text of pdf files.

### [DBLP XML Data](https://dblp.uni-trier.de/xml/)

### [ACL Anthology](http://aclweb.org/anthology/)
A Digital Archive of Research Papers in Computational Linguistics,The ACL Anthology currently hosts over 44,000 papers on the study of computational linguistics and natural language processing

### [AAN: ACL Anthology Network](http://clair.eecs.umich.edu/aan/index.php)
ACL Anthology Network,Here we have collected information regarding all of the papers included in the many ACL venues. From those papers, we have created several networks, including paper citation, author citation, and author collaboration. 
http://tangra.cs.yale.edu/newaan/

## Citation networks (for community detection):

### [Arxiv High Energy Physics paper citation network and Citation network among US Patents](https://snap.stanford.edu/data/#citnets)
nodes represent papers, edges represent citations

### [Collaboration networks (for community detection)](https://snap.stanford.edu/data/#canets)
Collaboration network of Arxiv Astro Physic,Collaboration network of Arxiv Condensed Matter,Collaboration network of Arxiv General Relativity,	Collaboration network of Arxiv High Energy Physics,	Collaboration network of Arxiv High Energy Physics Theory

### [Relational Classification Dataset](http://tangra.cs.yale.edu//homepage/downloads/aan_relational/)
This classification dataset contains 380 scientific publications from AAN manually classified into three research areas ("Machine Translation", "Dependency Parsing" and "Summarization"). 

### [Publication Classification Dataset](http://tangra.cs.yale.edu//homepage/downloads/aan_session/)
This classification dataset contains 383 scientific publications from AAN manually classified into 31 research areas using session information. The session information was compiled using the session information from ACL, COLING and EMNLP.


### [DSAP-document semantic similarity evaluation](https://github.com/buaaliuming/DSAP-document-semantics-for-academic-papers/tree/buaaliuming-annotation)

### [NIPS Conference dataset](https://cs.nyu.edu/~roweis/data.html)

### [ChestX-ray8](http://openaccess.thecvf.com/content_cvpr_2017/papers/Wang_ChestX-ray8_Hospital-Scale_Chest_CVPR_2017_paper.pdf)
Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases

### [NCI-PID-PubMed Genomics Knowledge Base Completion Dataset](https://www.microsoft.com/en-us/download/details.aspx?id=54054)
This dataset includes a database of regulation relationships among genes and corresponding textual mentions of pairs of genes in PubMed article abstracts.

### [CCL anthology](http://www.cips-cl.org/anthology)
中文计算机语言学会历年论文集


# Venues and Challenge with datasets
## KDD Cup 2020- [Regular Machine Learning Competition Track (ML Track 2) “Adversarial Attacks and Defense on Academic Graph”](https://biendata.com/competition/kddcup_2020/)
在论文引用网络中，可能存在多种类型的对抗攻击。例如，预打印论文网站（如arxiv）中的论文因为无需同行评议，所以存在很多低质量的引用。另一种是虚假引用（coercive citation）。2019年，《自然》杂志报道了著名出版商爱思唯尔调查发现数百名研究人员通过操纵同行评议流程，增加自己的论文引用数。这些对引文网络的攻击不仅会降低公众对科技行业的信任，也会损害对学术数据进行定量分析的努力。所以，我们组织这次比赛，希望可以研究如何攻击和防御学术图数据

## KDD Cup 2016- [Whose papers are accepted the most: towards measuring the impact of research institutions](https://www.kdd.org/kdd-cup/view/kdd-cup-2016/Tasks)
Given any upcoming top conferences such as KDD, SIGIR, and ICML in 2016, rank the importance of institutions based on predicting how many of their papers will be accepted.


## KDD Cup 2013- [Author-Paper Identification Challenge](https://www.kaggle.com/c/kdd-cup-2013-author-paper-identification-challenge)
Determine whether an author has written a given paper

## KDD Cup 2008- [Detection of Breast Cancer](https://www.kdd.org/kdd-cup/view/kdd-cup-2008)
early detection of breast cancer from X-ray images of the breast

## KDD Cup 2006- [Pulmonary Embolisms Detection from Image Data](https://www.kdd.org/kdd-cup/view/kdd-cup-2006)
identifying pulmonary embolisms from three-dimensional computed tomography data

## KDD Cup 2004- [Particle Physics and Protein Homology Prediction Task](https://www.kdd.org/kdd-cup/view/kdd-cup-2004/Tasks)
The goal in Particle Physics task is to learn a classification rule that differentiates between two types of particles generated in high energy collider experiments. The goal of Protein Homology Prediction is to predict which proteins are homologous to a native sequence

## KDD Cup 2003- [Network mining and usage log analysis: Citation Prediction and Download Estimation](https://www.kdd.org/kdd-cup/view/kdd-cup-2003/Tasks)
The goal of  Citation Prediction is to predict changes in the number of citations to individual papers over time.The goal of Download Estimation task is to estimate the number of downloads that a paper receives in its first two months in the arXiv.

## KDD Cup 2002- [BioMed document; plus gene role classification](https://www.biostat.wisc.edu/~craven/kddcup/tasks.html)
This year the competition included two tasks that involved data mining in molecular biology domains. Task 1: Information Extraction from Biomedical Articles；Task 2: Yeast Gene Regulation Prediction. The first task focused on constructing models that can assist genome annotators by automatically extracting information from scientific articles. The second task focused on learning models that characterize the behavior of individual genes in a hidden experimental setting. Both are described in more detail on the Tasks page.


## KDD Cup 2001- [Mining Biological Databases](http://pages.cs.wisc.edu/~dpage/kddcup2001/)
KDD Cup 2001 was focused on data from genomics and drug design. Sufficient (yet concise) information was provided so that detailed domain knowledge was not a requirement for entry. A total of 136 groups participated to produce a total of 200 submitted predictions over the 3 tasks: 114 for Thrombin, 41 for Function, and 45 for Localization.

## NAACL 2019: [Workshop on extracting structured knowledge from scientific publications (ESSP)](https://scientific-knowledge.github.io/#)
Structured information can be extracted at different levels of granularity. Previous and ongoing work has focused on bibliographic information (segmentation and linking of referenced literature, Wick et al., 2013), keyword extraction and categorization (e.g., what are tasks, materials and processes central to a publication, (Augenstein et al., 2017)), and cataloguing research findings. Scientific discoveries can often be represented as pairwise relationships, e.g., protein-protein (Mallory et al., 2016), drug-drug (Segura-Bedmar et al., 2013), and chemical-disease (Li et al., 2016) interactions, or as more complicated networks such as action graphs describing scientific procedures (e.g., synthesis recipes in material sciences, (Mysore et al., 2017)). Information extracted with such methods can be enriched with time-stamps, and other meta-information, such as indicators of uncertainty or limitations of the discovered facts (Zhou et al., 2015).
While various workshops have focused separately on several aspects -- extraction of information from scientific articles, building and using knowledge graphs, the analysis of bibliographical information, graph algorithms for text analysis -- the proposed workshop focuses on processing scientific articles and creating structured repositories such as knowledge graphs for finding new information and making scientific discoveries. The aim of this workshop is to identify the necessary representations for facilitating automated reasoning over scientific information, and to bring together experts in natural language processing and information extraction with scientists from other domains (e.g. material sciences, biomedical research) who want to leverage the vast amount of information stored in scientific publications.

## SIGIR 2018-[Workshop on Bibliometric-enhanced Information Retrieval and Natural Language Processing for Digital Libraries](https://wing.comp.nus.edu.sg/~birndl-sigir2018/)

## KDD 2018: Workshop [BigScholar 2018](http://thealphalab.org/bigscholar/2018/)

## JCDL 2018 : [Joint Conference on Digital Libraries](https://2018.jcdl.org/accepted_papers)

## BioNLP 2018: [Biomedical Natural Language Processing](http://aclweb.org/anthology/W18-2300)

## SemEval-2019: [NLP for scientific applications](http://alt.qcri.org/semeval2019/index.php?id=tasks)
### Task 11: Normalization of Medical Concepts in Clinical Narrative
### Task 12: Toponym Resolution in Scientific Papers

## SemEval-2018 
### Task 7: [Semantic Relation Extraction and Classification in Scientific Papers](https://competitions.codalab.org/competitions/17422#learn_the_details-overview)
### Task 8: [SecureNLP (Semantic Extraction from CybersecUrity REports using NLP)](https://competitions.codalab.org/competitions/17262)

## SemEval 2017 
### Task 10: [ScienceIE - Extracting Keyphrases and Relations from Scientific Publications](http://alt.qcri.org/semeval2017/task10/)

### Task 12: [Clinical TempEval](http://alt.qcri.org/semeval2017/task12/)
Timeline Extraction, Clinical TempEval will focus on domain adaptation: systems will be trained on data from colon cancer patients, but will be asked to make predictions on brain cancer patients.

## SemEval-2016 
### [Task 12 TempEval](http://alt.qcri.org/semeval2016/task12/)
Clinical TempEval 2016 follows in the footsteps of Clinical TempEval 2015 and the i2b2 2012 shared task in bringing timeline extraction to the clinical domain.

## SemEval-2015 
### [Task 6 TempEval](http://alt.qcri.org/semeval2015/task6/)
Clinical TempEval brings the temporal information extraction tasks of previous TempEvals to the clinical domain, using clinical notes and pathology reports for cancer patients from the Mayo Clinic.
   TS: identifying the spans of time expressions
   ES: Identifying the spans of event expressions
   TA: identifying the attributes of time expressions
   type=DATE, TIME, DURATION, QUANTIFIER, PREPOSTEXP or SET
   value=TIMEX3 value string as defined by TimeML
   EA: identifying the attributes of event expressions
   type=N/A, ASPECTUAL or EVIDENTIAL
   polarity=POS or NEG
   degree=N/A, MOST or LITTLE
   modality=ACTUAL, HEDGED, HYPOTHETICAL or GENERIC
   DR: identifying the relation between an event and the document creation time
   docTimeRel=BEFORE, OVERLAP, BEFORE-OVERLAP or AFTER
   CR: identifying narrative container relations (CONTAINS a.k.a. INCLUDES)


## SemEval 2014 Task 7: [Analysis of Clinical Text](http://alt.qcri.org/semeval2014/task7/)
### Task A This includes the recognition of mentions of concepts that belong to the UMLS semantic group disorders
### Task B This task involves the mapping of each disorder mention to a unique UMLS CUI.  This is referred to as the task of normalization and the mapping is limited to UMLS CUIs of SNOMED codes.


## SemEval 2010 Task 5: [Automatic Keyphrase Extraction from Scientific Articles ](http://semeval2.fbk.eu/semeval2.php?location=tasks&area=Information%20Extraction)
[Github Resource](https://github.com/snkim/AutomaticKeyphraseExtraction)

## [Open Academic Data Challenge 2018](https://biendata.com/competition/scholar2018/) （开放学术数据挖掘大赛）
### Task： Researcher Name Disambiguation

## [Open Academic Data Challenge 2017](https://biendata.com/competition/scholar/) (开放学术精准画像大赛)
### Task 1: Extract a scholar’s profile information 
### Task 2: Predictthe scholar’s research interests labels
### Task 3: Predict the scholar’s future influence
根据学术数据挖掘系统AMiner.org和Microsoft Academic Graph提供的数据集，提取学者的个人描述信息，分析学者的研究兴趣，以及预测学者的论文引用情况


## AAAI 2016: [Workshop on Scholarly Big Data: AI Perspectives, Challenges, and Ideas Workshop](http://people.cs.ksu.edu/~ccaragea/aaai2016ws/program.html)

## AAAI 2015: [Workshop on Scholarly Big Data: AI Perspectives, Challenges, and Ideas Workshop](https://www.aaai.org/Workshops/ws15workshops.php)


## WWW 2016-2018: SAVE-SD: Workshop on Semantics, Analytics and Visualisation: Enhancing Scholarly Data
### [SAVE-SD 2016](https://dl.acm.org/doi/10.1145/2872518.2890600) http://cs.unibo.it/save-sd/2016/index.html
### [SAVE-SD 2017](http://oro.open.ac.uk/53280/)
### [SAVE-SD 2018](https://save-sd.github.io/2018/index.html)

## WSDM 2017: [Workshop on Scholarly Web Mining (SWM 2017)](https://ornlcda.github.io/SWM2017/program.html)


## International Workshop on Mining Scientific Publications 2012-2018

The entire body of research literature is currently estimated at 100-150 million publications with an annual increase of around 1.5 million. Research literature constitutes the most complete representation of knowledge we have assembled as human species. It enables us to develop cures to diseases, solve difficult engineering problems and answer many of the world’s challenges we are facing today. Systematically reading and analysing the full body of knowledge is now beyond the capacities of any human being. Consequently, it is important to better understand how we can leverage Natural Language Processing/Text Mining techniques to aid knowledge creation and improve the process by which research is being done.

This workshop aims to bring together people from different backgrounds who:

have experience with analysing and mining databases of scientific publications,
develop systems that enable such analysis and mining of scientific databases (especially those who publication databases) or
who develop novel technologies that improve the way research is being done.
### [International Workshop on Mining Scientific Publications(IWOMSP) 2018] (https://wosp.core.ac.uk/lrec2018/)
### [International Workshop on Mining Scientific Publications(IWOMSP) 2017] (https://wosp.core.ac.uk/jcdl2017/)
### [International Workshop on Mining Scientific Publications(IWOMSP) 2016] (https://wosp.core.ac.uk/jcdl2016/)
### [International Workshop on Mining Scientific Publications(IWOMSP) 2015] (https://wosp.core.ac.uk/jcdl2015/)
### [International Workshop on Mining Scientific Publications(IWOMSP) 2014] (http://project.core.ac.uk/dl2014/)
### [International Workshop on Mining Scientific Publications(IWOMSP) 2013] (http://project.core.ac.uk/jcdl2013/)
### [International Workshop on Mining Scientific Publications(IWOMSP) 2012] (http://project.core.ac.uk/jcdl2012/)

## WWW 2016 : [BIG 2016 CUP](http://big2016.org/big-2016-cup/)
Microsoft provides the latest Microsoft Academic Search data set and an online graph query interface for BIG 2016 CUP

## TAC 2018 [Drug-Drug Interaction Extraction from Drug Labels](https://bionlp.nlm.nih.gov/tac2018druginteractions/)
The purpose of this TAC track is to test various natural language processing (NLP) approaches for their information extraction (IE) performance on drug-drug interactions in SPLs. A set of 20 gold-standard SPLs annotated with drug-drug interactions will be provided to participants. An additional set of 180 SPLs annotated in slightly different format is available for training. Participants will be evaluated by their performance on a held-out set of 50 labeled SPLs.


## TAC 2017 [Adverse Drug Reaction Extraction from Drug Labels](https://bionlp.nlm.nih.gov/tac2017adversereactions/)
One of the major aspects of drug information are safety concerns in the form of Adverse Drug Reactions (ADRs). In this evaluation, we are focusing on extraction of ADRs from the prescription drug labels.
Task 1: Extract AdverseReactions and related mentions (Severity, Factor, DrugClass, Negation, Animal). This is similar to many NLP Named Entity Recognition (NER) evaluations.
Task 2: Identify the relations between AdverseReactions and related mentions (i.e., Negated, Hypothetical, and Effect). This is similar to many NLP relation identification evaluations.
Task 3: Identify the positive AdverseReaction mention names in the labels. For the purposes of this task, positive will be defined as the caseless strings of all the AdverseReactions that have not been negated and are not related by a Hypothetical relation to a DrugClass or Animal. Note that this means Factors related via a Hypothetical relation are considered positive (e.g., "[unknown risk]Factor of [stroke]AdverseReaction") for the purposes of this task. The result of this task will be a list of unique strings corresponding to the positive ADRs as they were written in the label.
Task 4: Provide MedDRA PT(s) and LLT(s) for each positive AdverseReaction (occassionally, two or more PTs are necessary to fully describe the reaction). For participants approaching the tasks sequentially, this can be viewed as normalization of the terms extracted in Task 3 to MedDRA LLTs/PTs. Because MedDRA is not publicly available, and contains several versions, a standard version of MedDRA v18.1 will be provided to the participants. Other resources such as the UMLS Terminology Services may be used to aid with the normalization process.


## TAC 2014 [Biomedical Summarization Track](https://tac.nist.gov/2014/BiomedSumm/index.html)
Given: A set of Citing Papers (CPs) that all contain citations to a Reference Paper (RP). In each CP, the text spans (i.e., citances) have been identified that pertain to a particular citation to the RP.
Task 1a: For each citance, identify the spans of text (cited text spans) in the RP that most accurately reflect the citance. These are of the granularity of a sentence fragment, a full sentence, or several consecutive sentences (no more than 5).
Task 1b: For each cited text span, identify what facet of the paper it belongs to, from a predefined set of facets.
Task 2: Finally, generate a structured summary of the RP and all of the community discussion of the paper represented in the citances. The length of the summary should not exceed 250 words. Task 2 is tentative.


