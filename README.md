### ACM Citation Network
The Association for Computing Machinery (ACM) publishes peer reviewed journal articles focused on computer science research. Tang et al, prepared a dataset consisting of over 2 million articles for the purpose of analyzing the ACM citation network. The dataset includes article metadata including a list of references that each article cites.

### Analysis
This program, written in Scala using Spark SQL, the Spark GraphX library, and Jupyter Notebook, explores article properties, graphs the indegree distribution, ranks articles, and quantifies clustering.

### Contents
Scala source file: https://github.com/gdpeters/ACM-CitationNetwork/blob/master/acm_master.ipynb
Latex report: https://github.com/gdpeters/ACM-CitationNetwork/blob/master/acm_latex/acm_report.tex
Compiled report: https://github.com/gdpeters/ACM-CitationNetwork/blob/master/acm_latex/acm_report.pdf

#### Dataset
\bibitem{tang} Jie Tang, Jing Zhang, Limin Yao, Juanzi Li, Li Zhang, and Zhong Su. ArnetMiner: Extraction and Mining of Academic Social Networks. In Proceedings of the Fourteenth ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (SIGKDD'2008). pp.990-998.