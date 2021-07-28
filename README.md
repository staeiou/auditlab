# Details
* Class: DSC 290
* Instructor: R. Stuart Geiger
* Time: 5-6:50pm on Tuesdays
* Place: SOLIS 109

# Description

This seminar is for students interested in empirically investigating the outputs of real-world algorithmic systems of all kinds, particularly those where the classifiers and/or training data are not publicly available. The first few weeks of the class will include more readings and lectures, when we cover the history of auditing and legal/ethical issues it raises. This includes studying classic audits of non-algorithmic decision systems (e.g. equal opportunity hiring investigations) to contemporary issues around the Computer Fraud and Abuse Act and the IRB. We will learn various approaches to investigate such systems, including auditing via training datasets, code, user reports, API scraping, and sockpuppet accounts. We will read and discuss various algorithmic audits by researchers and regulators, which will be a mix of selected readings and readings students choose. Then, the second half of the class will be more discussion- and activity-based, as we perform audits on several real-world models whose developers have encouraged public auditing (e.g. Wikipedia’s content moderation classifiers). Students will work towards a final project, where they will conduct their own audits of real-world algorithmic systems and develop strategies for how systems can be designed for auditability.

# Prerequsites
* Introductory Statistics: The math and statistics of auditing are not as complex as those used in developing machine learning algorithms, but does involve statistics at the undergraduate level (e.g. <a href="https://cogsci.ucsd.edu/~nunez/COGS14B_W17/Syllabus14B_W17.htm">COGS 14B</a>)
* Programming for data collection and analysis: A working knowledge of a scripting language like python or R is highly recommended (e.g. what is taught in <a href="https://ucsd-cse8a-w20.github.io/">CSE 8A</a> or <a href="https://www.coursera.org/learn/python-data-analysis#syllabus">this coursera class</a>. Some audit methods involve automated data collection. We will learn how to query APIs and run headless browsers using standard libraries. Jupyter Notebooks will be used for literate programming. This class will be registered for UCSD datahub, which provides a web/cloud-based Jupyter environment in python and R. 

# Readings
Note that the final reading list and schedule has not yet been finalized. Please reach out to Stuart Geiger if you have any suggestions or ideas. And thanks to <a href="https://auditingalgorithms.science">auditingalgorithms.science</a> for many of these!

## Classic auditing in non-algorithmic systems

* National Research Council Panel on Measuring Racial Discrimination. (2004). Measuring Racial Discrimination. Washington, DC: National Academies Press. <a href="http://www.nap.edu/catalog/10887/measuring-racial-discrimination" target="_blank">http://www.nap.edu/catalog/10887/measuring-racial-discrimination</a>
* Schulman KA, Berlin JA, Harless W, Kerner JF, Sistrunk S, et al. The effect of race and sex on physicians’ recommendations for cardiac catheterization. N. Engl. J. Med. 1999;340(8):618–626. <a href="https://doi.org/10.1056/NEJM199902253400806">https://doi.org/10.1056/NEJM199902253400806</a>
* Saltman, J. (1975). Implementing Local Housing Laws Through Social Action. Journal of Applied Behavioral Science, 11(1): 39-61. <a href="https://doi.org/10.1177%2F002188637501100105">https://doi.org/10.1177%2F002188637501100105</a> 
* Ayres, I. &amp; Siegelman, P. (1995). Race and Gender Discrimination in Bargaining for a New Car. American Economic Review 85(3): 304-321. <a href="https://inequality.stanford.edu/sites/default/files/media/_media/pdf/Reference%20Media/Ayres_Siegelman_1995_Discrimination.pdf">https://inequality.stanford.edu/sites/default/files/media/_media/pdf/Reference%20Media/Ayres_Siegelman_1995_Discrimination.pdf</a>
* Stuart, G., "Databases, Felons, and Voting: Errors and Bias in the Florida Felons Exclusion List in the 2000 Presidential Elections" (September 2002). KSG Working Paper Series RWP 02-041. Read pp. 22-40. <a href="http://ssrn.com/abstract=336540" target="_blank">http://ssrn.com/abstract=336540</a>

## Algorithmic auditing frameworks and introductions
* Sandvig, C., Hamilton, K., Karahalios, K., &amp; Langbort, C. (2014). “An Algorithm Audit.” In: Seeta Peña Gangadharan (ed.), Data and Discrimination: Collected Essays, pp. 6-10. Washington, DC: New America Foundation. <a href="http://www-personal.umich.edu/~csandvig/research/An%20Algorithm%20Audit.pdf" target="_blank">http://www-personal.umich.edu/~csandvig/research/An%20Algorithm%20Audit.pdf</a>
* Sandvig, Christian, Kevin Hamilton, Karrie Karahalios, and Cedric Langbort. forthcoming. "Auditing Algorithms: Research Methods for Detecting Discrimination on Internet Platforms." Computational Culture. <a href="http://www-personal.umich.edu/~csandvig/research/Auditing%20Algorithms%20--%20Sandvig%20--%20ICA%202014%20Data%20and%20Discrimination%20Preconference.pdf" target="_blank">http://www-personal.umich.edu/~csandvig/research/Auditing%20Algorithms%20--%20Sandvig%20--%20ICA%202014%20Data%20and%20Discrimination%20Preconference.pdf</a>
* Diakopoulos, Nicholas. 2015. ‘‘Algorithmic Accountability.’’ Digital Journalism 3 (3): 398-415. <a href="http://www.nickdiakopoulos.com/wp-content/uploads/2011/07/algorithmic_accountability_final.pdf" target="_blank">http://www.nickdiakopoulos.com/wp-content/uploads/2011/07/algorithmic_accountability_final.pdf</a>
* Data &amp; Society Research Institute. 2014 "Workshop Primer: Algorithmic Accountability" <a href="http://www.datasociety.net/pubs/2014-0317/AlgorithmicAccountabilityPrimer.pdf" target="_blank">http://www.datasociety.net/pubs/2014-0317/AlgorithmicAccountabilityPrimer.pdf</a>

## The legal and ethical issues of conducting audits
* Sandvig v. Barr ruling by the U.S. District Court for D.C.: <a href="https://www.aclu.org/sites/default/files/field_document/sandvig_opinion.pdf" target="_blank">https://www.aclu.org/sites/default/files/field_document/sandvig_opinion.pdf</a>
* Wendler, David; Miller, Franklin G. "Deception in Research." The Oxford Textbook of Clinical Research Ethics. Oxford University Press, New York. (2008) pgs. 320-321.

### The UMN Linux kernel security audit
* Clark, M. 2021. The Verge. "University of Minnesota banned from contributing to Linux kernel." <a href="https://www.theverge.com/2021/4/22/22398156/university-minnesota-linux-kernal-ban-research" target="_blank">https://www.theverge.com/2021/4/22/22398156/university-minnesota-linux-kernal-ban-research</a>
* Linux Foundation Technical Advisory Board. 2021. "An emergency re-review of kernel commits authored by members of the University of Minnesota, due to the Hypocrite Commits research paper." <a href="https://lore.kernel.org/lkml/202105051005.49BFABCE" target="_blank">https://lore.kernel.org/lkml/202105051005.49BFABCE</a>@keescook/
* Lu, K., Wu, Q., and Pakki, A. "An open letter to the Linux community - April 24, 2021" <a href="https://cse.umn.edu/cs/open-letter-linux-community-april-24-2021" target="_blank">https://cse.umn.edu/cs/open-letter-linux-community-april-24-2021</a>
* Hacker News Thread. 2021. "They introduce kernel bugs on purpose." <a href="https://news.ycombinator.com/item?id=26887670" target="_blank">https://news.ycombinator.com/item?id=26887670</a>
 
## Auditing as a legal right and responsibility
* Pasquale, Frank. 2006. "Rankings, Reductionism, and Responsibility" Cleveland State Law Review, 54:115+. <a href="http://digitalcommons.law.umaryland.edu/fac_pubs/1351/" target="_blank">http://digitalcommons.law.umaryland.edu/fac_pubs/1351/</a>
* Citron, Danielle Keats, and Frank A. Pasquale. 2014. "The Scored Society: Due Process for Automated Predictions." Washington Law Review 89. <a href="http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2376209" target="_blank">http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2376209</a>
* Citron, Danielle Keats, Technological Due Process. Washington University Law Review, Vol. 85, pp. 1249-1313, 2007. READ § I.A., II.B.2, III.C.2. <a href="http://ssrn.com/abstract=1012360" target="_blank">http://ssrn.com/abstract=1012360</a>

## Algorithmic audits by researchers
* Buolamwini, J., & Gebru, T. (2018, January). Gender shades: Intersectional accuracy disparities in commercial gender classification. In Conference on fairness, accountability and transparency (pp. 77-91). PMLR. <a href="http://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf">http://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf</a>
* Sweeney, L. Discrimination in Online Ad Delivery. CACM 56(5): 44-54. <a href="https://cacm.acm.org/magazines/2013/5/163753-discrimination-in-online-ad-delivery/abstract" target="_blank">https://cacm.acm.org/magazines/2013/5/163753-discrimination-in-online-ad-delivery/abstract</a>
* Hannak, A., Soeller, G., Lazer, D., Mislove, A., Wilson, C. (2014). Measuring Price Discrimination and Steering on E-commerce Web Sites. (IMC ’14). <a href="http://personalization.ccs.neu.edu/papers/price_discrimination.pdf" target="_blank">http://personalization.ccs.neu.edu/papers/price_discrimination.pdf</a>
* M. Eslami, K. Vaccaro, K. Karahalios, and K. Hamilton. “Be careful; things can be worse than they appear”: Understanding Biased Algorithms and Users’ Behavior around Them in Rating Platforms (ICWSM 2017). <a href="http://social.cs.uiuc.edu/papers/ICWSM17-PrePrint.pdf" target="_blank">http://social.cs.uiuc.edu/papers/ICWSM17-PrePrint.pdf</a>
* Amit Datta, Michael Carl Tschantz, and  Anupam Datta. (2015). Automated Experiments on Ad Privacy Settings: A Tale of Opacity, Choice, and Discrimination. PoPETs 2015: 1. <a href="https://www.degruyter.com/view/j/popets.2015.1.issue-1/popets-2015-0007/popets-2015-0007.xml" target="_blank">https://www.degruyter.com/view/j/popets.2015.1.issue-1/popets-2015-0007/popets-2015-0007.xml</a>
* Qiu, H. and Du, W. "A True Lie about Reed College: U.S News Ranking" <a href="https://raw.githubusercontent.com/huayingq1996/Reed-College-Ranking/master/paper.pdf" target="_blank">https://raw.githubusercontent.com/huayingq1996/Reed-College-Ranking/master/paper.pdf</a>
* Nasr, M., & Tschantz, M. C. (2020). "Bidding strategies with gender nondiscrimination constraints for online ad auctions." In Proceedings of the 2020 Conference on Fairness, Accountability, and Transparency (pp. 337-347). <a href="https://dl.acm.org/doi/pdf/10.1145/3351095.3375783">https://dl.acm.org/doi/pdf/10.1145/3351095.3375783</a>
* Datta, A., Datta, A., Makagon, J., Mulligan, D.K. & Tschantz, M.C.. (2018). "Discrimination in Online Advertising: A Multidisciplinary Inquiry." Proceedings of the 1st Conference on Fairness, Accountability and Transparency, in PMLR 81:20-34. <a href="http://proceedings.mlr.press/v81/datta18a/datta18a.pdf">http://proceedings.mlr.press/v81/datta18a/datta18a.pdf</a>
