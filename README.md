cdi
===

* Author: Jian Wu

* Affiliation: College of IST at Penn State University

* Reference (bibtex):
  @inproceedings{wu2012cdi,
  author = {Wu, Jian and Teregowda, Pradeep and Khabsa, Madian and Carman, Stephen and Jordan, Douglas and San Pedro   Wandelmer, Jose and Lu, Xin and Mitra, Prasenjit and Giles, C. Lee},
  title = {Web crawler middleware for search engine digital libraries: a case study for citeseerX},
  booktitle = {Proceedings of the twelfth international workshop on Web information and data management},
  series = {WIDM '12},
  year = {2012},
  isbn = {978-1-4503-1720-7},
  location = {Maui, Hawaii, USA},
  pages = {57--64},
  numpages = {8},
  url = {http://doi.acm.org/10.1145/2389936.2389949},
  doi = {10.1145/2389936.2389949},
  acmid = {2389949},
  publisher = {ACM},
  address = {New York, NY, USA},
  keywords = {information retrieval, ingestion, middleware, search engine, web crawling},
  } 



This a software package designed for the CiteSeerX digital library search engine. The main function, cdi.py, is used to import a collection of documents from a crawling job to the CiteSeerX crawl database and repository. There are other crawl related modules such as the csxcrawl_schedule.py, which is used to select seed URLs injected to the crawler. 
