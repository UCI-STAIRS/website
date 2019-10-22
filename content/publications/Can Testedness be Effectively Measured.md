+++
abstract = "Among the major questions that a practicing tester faces are deciding where to focus additional testing effort, and deciding when to stop testing. Test the least-tested code, and stop when all code is well-tested, is a reasonable answer. Many measures of 'testedness' have been proposed; unfortunately, we do not know whether these are truly effective. In this paper we propose a novel evaluation of two of the most important and widely-used measures of test suite quality. The first measure is statement coverage, the simplest and best-known code coverage measure. The second measure is mutation score, a supposedly more powerful, though expensive, measure.We evaluate these measures using the actual criteria of interest: if a program element is (by these measures) well tested at a given point in time, it should require fewer future bug-fixes than a 'poorly tested' element. If not, then it seems likely that we are not effectively measuring testedness. Using a large number of open source Java programs from Github and Apache, we show that both statement coverage and mutation score have only a weak negative correlation with bug-fixes. Despite the lack of strong correlation, there are statistically and practically significant differences between program elements for various binary criteria. Program elements (other than classes) covered by any test case see about half as many bug-fixes as those not covered, and a similar line can be drawn for mutation score thresholds. Our results have important implications for both software engineering practice and research evaluation."
authors = ["Iftekhar Ahmed","Rahul Gopinath", "Caius Brindescu","Alex Groce", "Carlos Jensen" ]
date = "2016-07-01"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In *International Symposium on Foundations of Software Engineering*, ACM SIGSOFT."
publication_short = "In *FSE*"
selected = true
title = "Can Testedness be Effectively Measured?"
url_code = ""
url_dataset = ""
url_pdf = "pdf/paper10.pdf"
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

