+++
abstract = "Background: Merge conflicts are a common occurrence in software development. Researchers have shown the negative impact of conflicts on the resulting code quality and the development workflow. Thus far, no one has investigated the effect of bad design (code smells) on merge conflicts. Aims: We posit that entities that exhibit certain types of code smells are more likely to be involved in a merge conflict. We also postulate that code elements that are both “smelly” and involved in a merge conflict are associated with other undesirable effects (more likely to be buggy). Method: We mined 143 repositories from GitHub and recreated 6,979 merge conflicts to obtain metrics about code changes and conflicts. We categorized conflicts into semantic or non-semantic, based on whether changes affected the Abstract Syntax Tree. For each conflicting change, we calculate the number of code smells and the number of future bug-fixes associated with the affected lines of code. Results: We found that entities that are smelly are three times more likely to be involved in merge conflicts. Method-level code smells (Blob Operation and Internal Duplication) are highly correlated with semantic conflicts. We also found that code that is smelly and experiences merge conflicts is more likely to be buggy. Conclusion: Bad code design not only impacts maintainability, it also impacts the day to day operations of a project, such as merging contributions, and negatively impacts the quality of the resulting code. Our findings indicate that research is needed to identify better ways to support merge conflict resolution to minimize its effect on code quality."
authors = ["Iftekhar Ahmed","Caius Brindescu","Umme Ayda Mannan","Anita Sarma", "Carlos Jensen" ]
date = "2017-07-01"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In *11th ACM/IEEE International Symposium on Empirical Software Engineering and Measurement (ESEM )*, ACM/IEEE."
publication_short = "In *ESEM*"
selected = true
title = "An Empirical Examination of the Relationship Between Code Smells and Merge Conflicts"
url_code = ""
url_dataset = ""
url_pdf = "pdf/paper11.pdf"
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

