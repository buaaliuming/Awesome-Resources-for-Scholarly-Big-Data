<h1 align="center"> Resources for Scholarly Big Data </h1>
<h2 align="center">
Pick up scattered pearls and light up the fire for scholarly big data
 
{Tools, Corpus, datasets, Glossary and venues...}
</h2>


# Tools
## Bibliographical Extraction 
[**ParsCit**](https://github.com/knmnyn/ParsCit/blob/master/USAGE): 

ParsCit is a utility for extracting citations from research papers based on Conditional Random Fields and heuristic regularization.


### [GROBID](https://github.com/kermitt2/grobid) :
a machine learning library for extracting, parsing and re-structuring raw documents such as PDF into structured TEI-encoded documents with a particular focus on technical and scientific publications
http://cloud.science-miner.com/grobid/  https://github.com/kermitt2/grobid

### CERMINE:
Content ExtRactor and MINEr
http://cermine.ceon.pl/cermine/task.html?task=8692584047461514230

### FreeCite: 
FreeCite is an open-source application that parses document citations into fielded data. You can use it as a web application or a service
http://freecite.library.brown.edu/welcome

## Figure Extraction from PDF Articles
### PDFFigures:
Extracting Figures from Research Papers,Mining Figures from Research Papers
http://pdffigures2.allenai.org/

### deepfigures-open:
Figure extraction using deep neural nets
https://github.com/allenai/deepfigures-open

## Table Extraction from PDF Articles
### pdf2table:
extraction of table information from PDF-files based on pdf2html
https://github.com/tfmorris/pdf2table
http://ieg.ifs.tuwien.ac.at/projects/pdf2table/

### Zanran:
https://pdf.zanran.com/extract-table-from-pdf

## Keywords or Keyphrase Extraction 
### KEA:
Extracting Keywords or keyphrases. KEA is an algorithm for extracting keyphrases from text documents. It can be either used for free indexing or for indexing with a controlled vocabulary. KEA is implemented in Java and is platform independent. 
http://community.nzdl.org/kea/

## Science-Parse
Science Parse parses scientific papers (in PDF form) and returns them in structured form.
It supports these fields: Title, Authors, Abstract, Sections (each with heading and body text), Bibliography, each with Title, Authors
Venue, Year, Mentions, i.e., places in the paper where bibliography entries are mentioned, In JSON format.
https://github.com/allenai/science-parse

## Plain Text Extraction
### PDFBox 
Extract Unicode text from PDF files.
https://pdfbox.apache.org/

### Apache POI - the Java API for Microsoft Documents
You can read and write MS Excel, PPT and Word files using Java API.The Apache POI Project's mission is to create and maintain Java APIs for manipulating various file formats based upon the Office Open XML standards (OOXML) and Microsoft's OLE 2 Compound Document format (OLE2).
http://poi.apache.org/

## Academic Article Evaluation
### Automatic Academic Paper Rating
Rating articles based on LATEX source files and academic metedata
https://github.com/lancopku/AAPR

## PeerRead
Automatic PeerReview: Predict the accept/reject decisions in top-tier venues
https://github.com/allenai/PeerRead

## Paper-Reviewer Assignments
### The Toronto Paper Matching System (TPMS)
The goal of this system is to help conference chairs with the task of assigning papers to reviewers.
http://torontopapermatching.org/webapp/profileBrowser/about_us/

### MyReview (unavailable currently/20181202)
http://myreview.lri.fr/


## Scholar Influence Analysis
Computer Science Rankings:This ranking of top computer science schools is designed to identify institutions and faculty actively engaged in research across a number of areas of computer science. 
https://github.com/emeryberger/CSrankings
http://csrankings.org/#/index?all

## Scholar Gender Prediction
A simple scholar gender predictor.
https://github.com/xgeric/gender

## Research Trends Visualization
### Neviewer：
Analyse the evolution of research topics in a discipline based on co-word network analysis

https://link.springer.com/article/10.1007/s11192-014-1347-y

### CiteSpace: 
Visualizing Patterns and Trends in Scientific Literature
http://cluster.cis.drexel.edu/~cchen/citespace/

##  Dataset Search
Making it easier to discover datasets
http://g.co/datasetsearch
https://www.blog.google/products/search/making-it-easier-discover-datasets/

## Medical NLP Packages
### Illinois Medical NER
This software identifies concepts in medical reports on patients, per the i2b2 shared task: https://www.i2b2.org/NLP/Relations/. 
http://cogcomp.org/page/software_view/MedNER

### Illinois Medical Coreference
http://cogcomp.org/page/software_view/MedCoref

### Illinois Medical Drug Abuse Detector
http://cogcomp.org/page/software_view/MedSHARPS

## Text Annotation
### Brat :
a web-based tool for text annotation

http://brat.nlplab.org/introduction.html

### Chinese-Annotator
Annotator for Chinese Text Corpus 中文标注工具
https://github.com/deepwel/Chinese-Annotator

## GATE 
 GATE includes components for diverse language processing tasks, e.g. parsers, morphology, tagging, Information Retrieval tools, Information Extraction components for various languages, and many others. GATE Developer and Embedded are supplied with an Information Extraction system (ANNIE) which has been adapted and evaluated very widely (numerous industrial systems, research systems evaluated in MUC, TREC, ACE, DUC, Pascal, NTCIR, etc.). ANNIE is often used to create RDF or OWL (metadata) for unstructured conten
https://gate.ac.uk/

## Platform
DBLP
https://dblp.uni-trier.de/

CiteSeer
http://citeseerx.ist.psu.edu/index

Arminer
https://www.aminer.cn/

ResearchGate
https://www.researchgate.net/

CiteUlike
http://www.citeulike.org/

SemanticSchoolar
https://www.semanticscholar.org/

Google Schoolar
https://scholar.google.com.hk/

Arxiv
https://arxiv.org/

OpenReview
https://openreview.net/

# Datasets and Corpus
## PubMed
PubMed comprises more than 28 million citations for biomedical literature from MEDLINE, life science journals, and online books. Citations may include links to full-text content from PubMed Central and publisher web sites.
https://www.ncbi.nlm.nih.gov/pubmed/

##  SN SciGraph
Linked Open Data offering which aggregates data sources from Springer Nature and key partners from the scholarly domain. The Linked Open Data platform collates information from across the research landscape, for example funders, research projects, conferences, affiliations and publications.
https://www.springernature.com/gp/researchers/scigraph

## Automatic Article Commenting: the Task and Dataset 
The dataset is available on http://ai.tencent.com/upload/PapersUploads/article_commenting.tgz
https://arxiv.org/pdf/1805.03668.pdf

## Automatic Academic Paper Rating (Dataset)
https://drive.google.com/file/d/1ttKdXUjaFi3eS6zeHITuZjsTGrh6M4ij/view

## PeerRead （code and dataset for predict whether you paper will be accepted by top-tier venues）
PearRead is a dataset of scientific peer reviews available to help researchers study this important artifact. The dataset consists of over 14K paper drafts and the corresponding accept/reject decisions in top-tier venues including ACL, NIPS and ICLR, as well as over 10K textual peer reviews written by experts for a subset of the papers.
https://github.com/allenai/PeerRead

## Academic Vocabulary Lists
https://www.academicvocabulary.info/

## AMiner Dataset
https://www.aminer.cn/data

## Microsoft Academic Graph
The Microsoft Academic Graph is a heterogeneous graph containing scientific publication records, citation relationships between publications, as well as authors, institutions, journal and conference "venues," and fields of study.
https://wsdmcupchallenge.azurewebsites.net/

## Open Academic Graph
This data set is generated by linking two large academic graphs: Microsoft Academic Graph (MAG) and AMiner
https://www.openacademic.ai/oag/

## Arxiv Bluk Corpus
https://arxiv.org/help/bulk_data

## Citeseer data and metadata
CiteSeerx data and metadata are available for others to use. Data available includes CiteSeerx metadata, databases, data sets of pdf files and text of pdf files.
http://csxstatic.ist.psu.edu/downloads/data

## DBLP XML Data
https://dblp.uni-trier.de/xml/

## ACL Anthology
A Digital Archive of Research Papers in Computational Linguistics,The ACL Anthology currently hosts over 44,000 papers on the study of computational linguistics and natural language processing
http://aclweb.org/anthology/

## AAN: ACL Anthology Network
ACL Anthology Network,Here we have collected information regarding all of the papers included in the many ACL venues. From those papers, we have created several networks, including paper citation, author citation, and author collaboration. 
http://clair.eecs.umich.edu/aan/index.php
http://tangra.cs.yale.edu/newaan/

## Citation networks (for community detection):
### Arxiv High Energy Physics paper citation network and Citation network among US Patents

nodes represent papers, edges represent citations
https://snap.stanford.edu/data/#citnets

## Collaboration networks (for community detection):
### Collaboration network of Arxiv Astro Physic,Collaboration network of Arxiv Condensed Matter,Collaboration network of Arxiv General Relativity,	Collaboration network of Arxiv High Energy Physics,	Collaboration network of Arxiv High Energy Physics Theory
https://snap.stanford.edu/data/#canets

## Relational Classification Dataset
This classification dataset contains 380 scientific publications from AAN manually classified into three research areas ("Machine Translation", "Dependency Parsing" and "Summarization"). 
http://tangra.cs.yale.edu//homepage/downloads/aan_relational/

## Publication Classification Dataset
This classification dataset contains 383 scientific publications from AAN manually classified into 31 research areas using session information. The session information was compiled using the session information from ACL, COLING and EMNLP.
http://tangra.cs.yale.edu//homepage/downloads/aan_session/

## DSAP-document semantic similarity evaluation
https://github.com/buaaliuming/DSAP-document-semantics-for-academic-papers/tree/buaaliuming-annotation


## NIPS Conference dataset
https://cs.nyu.edu/~roweis/data.html

## ChestX-ray8
Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases
http://openaccess.thecvf.com/content_cvpr_2017/papers/Wang_ChestX-ray8_Hospital-Scale_Chest_CVPR_2017_paper.pdf

## NCI-PID-PubMed Genomics Knowledge Base Completion Dataset
This dataset includes a database of regulation relationships among genes and corresponding textual mentions of pairs of genes in PubMed article abstracts.
https://www.microsoft.com/en-us/download/details.aspx?id=54054

## CCL anthology
中文计算机语言学会历年论文集
http://www.cips-cl.org/anthology

# Venues and Challenge with datasets

## NAACL 2019: Workshop on extracting structured knowledge from scientific publications (ESSP)
https://scientific-knowledge.github.io/#
Structured information can be extracted at different levels of granularity. Previous and ongoing work has focused on bibliographic information (segmentation and linking of referenced literature, Wick et al., 2013), keyword extraction and categorization (e.g., what are tasks, materials and processes central to a publication, (Augenstein et al., 2017)), and cataloguing research findings. Scientific discoveries can often be represented as pairwise relationships, e.g., protein-protein (Mallory et al., 2016), drug-drug (Segura-Bedmar et al., 2013), and chemical-disease (Li et al., 2016) interactions, or as more complicated networks such as action graphs describing scientific procedures (e.g., synthesis recipes in material sciences, (Mysore et al., 2017)). Information extracted with such methods can be enriched with time-stamps, and other meta-information, such as indicators of uncertainty or limitations of the discovered facts (Zhou et al., 2015).
While various workshops have focused separately on several aspects -- extraction of information from scientific articles, building and using knowledge graphs, the analysis of bibliographical information, graph algorithms for text analysis -- the proposed workshop focuses on processing scientific articles and creating structured repositories such as knowledge graphs for finding new information and making scientific discoveries. The aim of this workshop is to identify the necessary representations for facilitating automated reasoning over scientific information, and to bring together experts in natural language processing and information extraction with scientists from other domains (e.g. material sciences, biomedical research) who want to leverage the vast amount of information stored in scientific publications.

## JCDL 2018 : Joint Conference on Digital Libraries
https://2018.jcdl.org/accepted_papers

## BioNLP 2018
Biomedical Natural Language Processing
http://aclweb.org/anthology/W18-2300


## SemEval-2019 NLP for scientific applications
### Task 11: Normalization of Medical Concepts in Clinical Narrative
### Task 12: Toponym Resolution in Scientific Papers
http://alt.qcri.org/semeval2019/index.php?id=tasks

## SemEval-2018 
### Task 7: Semantic Relation Extraction and Classification in Scientific Papers
https://competitions.codalab.org/competitions/17422#learn_the_details-overview
###  Task 8; SecureNLP (Semantic Extraction from CybersecUrity REports using NLP)
https://competitions.codalab.org/competitions/17262

## SemEval 2017 
### Task 10: ScienceIE - Extracting Keyphrases and Relations from Scientific Publications
http://alt.qcri.org/semeval2017/task10/

### Task 12 Clinical TempEval 
Timeline Extraction, Clinical TempEval will focus on domain adaptation: systems will be trained on data from colon cancer patients, but will be asked to make predictions on brain cancer patients.
http://alt.qcri.org/semeval2017/task12/

## SemEval 2014 Task 7: Analysis of Clinical Text
### Task A This includes the recognition of mentions of concepts that belong to the UMLS semantic group disorders
### Task B This task involves the mapping of each disorder mention to a unique UMLS CUI.  This is referred to as the task of normalization and the mapping is limited to UMLS CUIs of SNOMED codes.
http://alt.qcri.org/semeval2014/task7/

## SemEval 2010 Task 5: Automatic Keyphrase Extraction from Scientific Articles 
http://semeval2.fbk.eu/semeval2.php?location=tasks&area=Information%20Extraction
https://github.com/snkim/AutomaticKeyphraseExtraction

## Open Academic Data Challenge 2018 （开放学术数据挖掘大赛）
### Task： Researcher Name Disambiguation
https://biendata.com/competition/scholar2018/

## Open Academic Data Challenge 2017 (开放学术精准画像大赛)
### Task 1: Extract a scholar’s profile information 
### Task 2: Predictthe scholar’s research interests labels
### Task 3: Predict the scholar’s future influence
根据学术数据挖掘系统AMiner.org和Microsoft Academic Graph提供的数据集，提取学者的个人描述信息，分析学者的研究兴趣，以及预测学者的论文引用情况
https://biendata.com/competition/scholar/

## AAAI 2015,2016: Workshop on Scholarly Big Data: AI Perspectives, Challenges, and Ideas Workshop
http://people.cs.ksu.edu/~ccaragea/aaai2016ws/program.html
https://www.aaai.org/Workshops/ws15workshops.php

## WWW 2016-2018: SAVE-SD: Workshop on Semantics, Analytics and Visualisation: Enhancing Scholarly Data 
SAVE-SD 2016 http://cs.unibo.it/save-sd/2016/index.html
SAVE-SD 2017 http://oro.open.ac.uk/53280/
SAVE-SD 2018 https://save-sd.github.io/2018/index.html

## WSDM 2017: Workshop on Scholarly Web Mining (SWM 2017) 

https://ornlcda.github.io/SWM2017/program.html

## International Workshop on Mining Scientific Publications 2012-2018
https://wosp.core.ac.uk/lrec2018/

https://wosp.core.ac.uk/jcdl2017/
https://wosp.core.ac.uk/jcdl2016/
https://wosp.core.ac.uk/jcdl2015/
http://project.core.ac.uk/dl2014/
http://project.core.ac.uk/jcdl2013/
http://project.core.ac.uk/jcdl2012/

## WWW 2016 : BIG 2016 CUP
Microsoft provides the latest Microsoft Academic Search data set and an online graph query interface for BIG 2016 CUP

http://big2016.org/big-2016-cup/

## TAC 2018 Drug-Drug Interaction Extraction from Drug Labels
The purpose of this TAC track is to test various natural language processing (NLP) approaches for their information extraction (IE) performance on drug-drug interactions in SPLs. A set of 20 gold-standard SPLs annotated with drug-drug interactions will be provided to participants. An additional set of 180 SPLs annotated in slightly different format is available for training. Participants will be evaluated by their performance on a held-out set of 50 labeled SPLs.

https://bionlp.nlm.nih.gov/tac2018druginteractions/

## TAC 2017 Adverse Drug Reaction Extraction from Drug Labels
One of the major aspects of drug information are safety concerns in the form of Adverse Drug Reactions (ADRs). In this evaluation, we are focusing on extraction of ADRs from the prescription drug labels.
Task 1: Extract AdverseReactions and related mentions (Severity, Factor, DrugClass, Negation, Animal). This is similar to many NLP Named Entity Recognition (NER) evaluations.
Task 2: Identify the relations between AdverseReactions and related mentions (i.e., Negated, Hypothetical, and Effect). This is similar to many NLP relation identification evaluations.
Task 3: Identify the positive AdverseReaction mention names in the labels. For the purposes of this task, positive will be defined as the caseless strings of all the AdverseReactions that have not been negated and are not related by a Hypothetical relation to a DrugClass or Animal. Note that this means Factors related via a Hypothetical relation are considered positive (e.g., "[unknown risk]Factor of [stroke]AdverseReaction") for the purposes of this task. The result of this task will be a list of unique strings corresponding to the positive ADRs as they were written in the label.
Task 4: Provide MedDRA PT(s) and LLT(s) for each positive AdverseReaction (occassionally, two or more PTs are necessary to fully describe the reaction). For participants approaching the tasks sequentially, this can be viewed as normalization of the terms extracted in Task 3 to MedDRA LLTs/PTs. Because MedDRA is not publicly available, and contains several versions, a standard version of MedDRA v18.1 will be provided to the participants. Other resources such as the UMLS Terminology Services may be used to aid with the normalization process.

https://bionlp.nlm.nih.gov/tac2017adversereactions/


## TAC 2014 Biomedical Summarization Track
Given: A set of Citing Papers (CPs) that all contain citations to a Reference Paper (RP). In each CP, the text spans (i.e., citances) have been identified that pertain to a particular citation to the RP.
Task 1a: For each citance, identify the spans of text (cited text spans) in the RP that most accurately reflect the citance. These are of the granularity of a sentence fragment, a full sentence, or several consecutive sentences (no more than 5).
Task 1b: For each cited text span, identify what facet of the paper it belongs to, from a predefined set of facets.
Task 2: Finally, generate a structured summary of the RP and all of the community discussion of the paper represented in the citances. The length of the summary should not exceed 250 words. Task 2 is tentative.
https://tac.nist.gov/2014/BiomedSumm/index.html

## KDD Cup 2016- Whose papers are accepted the most: towards measuring the impact of research institutions
Given any upcoming top conferences such as KDD, SIGIR, and ICML in 2016, rank the importance of institutions based on predicting how many of their papers will be accepted.

https://www.kdd.org/kdd-cup/view/kdd-cup-2016/Tasks

## KDD Cup 2013- Author-Paper Identification Challenge 
Determine whether an author has written a given paper

https://www.kaggle.com/c/kdd-cup-2013-author-paper-identification-challenge

## KDD Cup 2008- Detection of Breast Cancer
early detection of breast cancer from X-ray images of the breast

https://www.kdd.org/kdd-cup/view/kdd-cup-2008

## KDD Cup 2006-Pulmonary Embolisms Detection from Image Data
identifying pulmonary embolisms from three-dimensional computed tomography data

https://www.kdd.org/kdd-cup/view/kdd-cup-2006

## KDD Cup 2004- Particle Physics and Protein Homology Prediction Task
The goal in Particle Physics task is to learn a classification rule that differentiates between two types of particles generated in high energy collider experiments. The goal of Protein Homology Prediction is to predict which proteins are homologous to a native sequence
https://www.kdd.org/kdd-cup/view/kdd-cup-2004/Tasks

## KDD Cup 2003- Network mining and usage log analysis: Citation Prediction and Download Estimation
The goal of  Citation Prediction is to predict changes in the number of citations to individual papers over time.The goal of Download Estimation task is to estimate the number of downloads that a paper receives in its first two months in the arXiv.
https://www.kdd.org/kdd-cup/view/kdd-cup-2003/Tasks

## KDD Cup 2002- BioMed document; plus gene role classification
This year the competition included two tasks that involved data mining in molecular biology domains. Task 1: Information Extraction from Biomedical Articles；Task 2: Yeast Gene Regulation Prediction. The first task focused on constructing models that can assist genome annotators by automatically extracting information from scientific articles. The second task focused on learning models that characterize the behavior of individual genes in a hidden experimental setting. Both are described in more detail on the Tasks page.
https://www.biostat.wisc.edu/~craven/kddcup/tasks.html

## KDD Cup 2001- Mining Biological Databases 
KDD Cup 2001 was focused on data from genomics and drug design. Sufficient (yet concise) information was provided so that detailed domain knowledge was not a requirement for entry. A total of 136 groups participated to produce a total of 200 submitted predictions over the 3 tasks: 114 for Thrombin, 41 for Function, and 45 for Localization.

http://pages.cs.wisc.edu/~dpage/kddcup2001/
