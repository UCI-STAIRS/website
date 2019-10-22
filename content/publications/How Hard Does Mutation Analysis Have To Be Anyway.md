+++
abstract = "Mutation analysis is considered the best method for measuring the adequacy of test suites. However, the number of test runs required for a full mutation analysis grows faster than project size, which is not feasible for real-world software projects, which often have more than a million lines of code. It is for projects of this size, however, that developers most need a method for evaluating the efficacy of a test suite. Various strategies have been proposed to deal with the explosion of mutants. However, these strategies at best reduce the number of mutants required to a fraction of overall mutants, which still grows with program size. Running, e.g., 5% of all mutants of a 2MLOC program usually requires analyzing over 100,000 mutants. Similarly, while various approaches have been proposed to tackle equivalent mutants, none completely eliminate the problem, and the fraction of equivalent mutants remaining is hard to estimate, often requiring manual analysis of equivalence. In this paper, we provide both theoretical analysis and empirical evidence that a small constant sample of mutants yields statistically similar results to running a full mutation analysis, regardless of the size of the program or similarity between mutants. We show that a similar approach, using a constant sample of inputs can estimate the degree of stubbornness in mutants remaining to a high degree of statistical confidence, and provide a mutation analysis framework for Python that incorporates the analysis of stubbornness of mutants."
authors = ["Rahul Gopinath","Amin Alipour","Iftekhar Ahmed", "Carlos Jensen", "Alex Groce"]
date = "2015-07-01"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In *In 26th IEEE International Symposium on Software Reliability Engineering (ISSRE)*, IEEE."
publication_short = "In *ISSRE*"
selected = true
title = "How Hard Does Mutation Analysis Have to Be, Anyway?"
url_code = ""
url_dataset = ""
url_pdf = "pdf/paper3.pdf"
#url_project = "project/deep-learning/"
url_slides = ""
url_video = ""

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

# Optional featured image (relative to `static/img/` folder).
[header]
#image = ""
#caption = "My caption :smile:"

+++

