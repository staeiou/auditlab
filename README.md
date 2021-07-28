# Details
* Class: DSC 290
* Instructor: R. Stuart Geiger
* Time: 5-6:50pm on Tuesdays
* Place: SOLIS 109

# Description

This seminar is for students interested in empirically investigating the outputs of real-world algorithmic systems of all kinds, particularly those where the code and/or training data are not publicly available. The first few weeks of the class will include more readings and lectures, when we cover the history of auditing and legal/ethical issues it raises. This includes studying classic audits of non-algorithmic decision systems (e.g. equal opportunity hiring investigations) to contemporary issues around the Computer Fraud and Abuse Act and the IRB. We will learn various approaches to investigate such systems, including auditing via training datasets, code, user reports, API scraping, sockpuppet accounts, and headless browsers. We will read and discuss various algorithmic audits by researchers and regulators, which will be a mix of selected readings and readings students choose. The second half of the class will be more discussion- and activity-based, as we perform audits on several real-world models whose developers have encouraged public auditing (e.g. Wikipedia’s content moderation classifiers). Students will work towards a final project, where they will conduct their own audits and develop strategies for how systems can be designed for auditability.

# Prerequsites
There are no official prerequsites to register, but the class will generally assume knowledge of:
* Introductory Statistics: The math and statistics of auditing are not as complex as those used in developing machine learning algorithms, but does involve statistics at the undergraduate level: correlations, hypothesis testing, linear regressions, and analysis of variance (ANOVA) (e.g. what is taught in <a href="https://cogsci.ucsd.edu/~nunez/COGS14B_W17/Syllabus14B_W17.htm">COGS 14B</a>). You don't need to know how to mathematically derive these tests, just enough to be a well-informed user of them.
* Introductory programming for data collection and analysis: A working knowledge of a scripting language like python or R is highly recommended (e.g. what is taught in <a href="https://ucsd-cse8a-w20.github.io/">CSE 8A</a> or <a href="https://www.coursera.org/learn/python-data-analysis#syllabus">this coursera class</a>). Some audit methods involve automated data collection. We will learn how to query APIs and run headless browsers using standard libraries. Jupyter Notebooks will be used for literate programming. This class will be registered for UCSD datahub, which provides a web/cloud-based Jupyter environment in python and R. 
* All students must take and pass the UCSD/CITI IRB Human Subject Protection Training online course (Social and Behavioral Basic Course), by the end of week 2 of the class. This takes about 2-3 hours total and can be taken at any time, even during the summer. Register at <a href="https://citiprogram.org">citiprogram.org</a> (no SSO available) and affiliate with UCSD. See more info at <a href="https://irb.ucsd.edu/CITI_UCSD_Training.pdf">https://irb.ucsd.edu/CITI_UCSD_Training.pdf</a>. If you have passed the course in the past 3 years, your certificate is still valid; if not, you must take the shorter refresher course.

Please get in touch if you have any doubts or concerns about the prerequsites. 

# Potential readings
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
* Bandy, J. (2021). Problematic Machine Behavior: A Systematic Literature Review of Algorithm Audits. Proceedings of the ACM on Human-Computer Interaction, 5(CSCW1), 1-34. <a href="https://dl.acm.org/doi/pdf/10.1145/3449148">https://dl.acm.org/doi/pdf/10.1145/3449148</a>

## The legal and ethical issues of conducting audits
* Raji, I. D., Gebru, T., Mitchell, M., Buolamwini, J., Lee, J., & Denton, E. (2020, February). Saving face: Investigating the ethical concerns of facial recognition auditing. In Proceedings of the AAAI/ACM Conference on AI, Ethics, and Society (pp. 145-151). <a href="https://dl.acm.org/doi/pdf/10.1145/3375627.3375820">https://dl.acm.org/doi/pdf/10.1145/3375627.3375820</a>
* Sandvig v. Barr ruling by the U.S. District Court for D.C.: <a href="https://www.aclu.org/sites/default/files/field_document/sandvig_opinion.pdf" target="_blank">https://www.aclu.org/sites/default/files/field_document/sandvig_opinion.pdf</a>. Read pages 1-2 and 15-28 (part 2 beginning with "II. Interpreting the CFAA")
* Wendler, David; Miller, Franklin G. "Deception in Research." The Oxford Textbook of Clinical Research Ethics. Oxford University Press, New York. (2008) pgs. 320-321.

### The UMN Linux kernel security audit
* Clark, M. 2021. The Verge. "University of Minnesota banned from contributing to Linux kernel." <a href="https://www.theverge.com/2021/4/22/22398156/university-minnesota-linux-kernal-ban-research" target="_blank">https://www.theverge.com/2021/4/22/22398156/university-minnesota-linux-kernal-ban-research</a>
* Linux Foundation Technical Advisory Board. 2021. "An emergency re-review of kernel commits authored by members of the University of Minnesota, due to the Hypocrite Commits research paper." <a href="https://lore.kernel.org/lkml/202105051005.49BFABCE@keescook/" target="_blank">https://lore.kernel.org/lkml/202105051005.49BFABCE@keescook/</a>
* Lu, K., Wu, Q., and Pakki, A. "An open letter to the Linux community - April 24, 2021" <a href="https://cse.umn.edu/cs/open-letter-linux-community-april-24-2021" target="_blank">https://cse.umn.edu/cs/open-letter-linux-community-april-24-2021</a>
* Hacker News Thread. 2021. "They introduce kernel bugs on purpose." <a href="https://news.ycombinator.com/item?id=26887670" target="_blank">https://news.ycombinator.com/item?id=26887670</a>
 
### Legal obligations to audit algorithms used by government agencies
* Pasquale, Frank. 2006. "Rankings, Reductionism, and Responsibility" Cleveland State Law Review, 54:115+. <a href="http://digitalcommons.law.umaryland.edu/fac_pubs/1351/" target="_blank">http://digitalcommons.law.umaryland.edu/fac_pubs/1351/</a>
* Citron, Danielle Keats, and Frank A. Pasquale. 2014. "The Scored Society: Due Process for Automated Predictions." Washington Law Review 89. <a href="http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2376209" target="_blank">http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2376209</a>
* Citron, Danielle Keats, Technological Due Process. Washington University Law Review, Vol. 85, pp. 1249-1313, 2007. READ § I.A., II.B.2, III.C.2. <a href="http://ssrn.com/abstract=1012360" target="_blank">http://ssrn.com/abstract=1012360</a>

## Algorithmic audits 

### Online advertising and pricing
* Sweeney, L. Discrimination in Online Ad Delivery. CACM 56(5): 44-54. <a href="https://cacm.acm.org/magazines/2013/5/163753-discrimination-in-online-ad-delivery/abstract" target="_blank">https://cacm.acm.org/magazines/2013/5/163753-discrimination-in-online-ad-delivery/abstract</a>
* Hannak, A., Soeller, G., Lazer, D., Mislove, A., Wilson, C. (2014). Measuring Price Discrimination and Steering on E-commerce Web Sites. (IMC ’14). <a href="http://personalization.ccs.neu.edu/papers/price_discrimination.pdf" target="_blank">http://personalization.ccs.neu.edu/papers/price_discrimination.pdf</a>
* Amit Datta, Michael Carl Tschantz, and  Anupam Datta. (2015). Automated Experiments on Ad Privacy Settings: A Tale of Opacity, Choice, and Discrimination. PoPETs 2015: 1. <a href="https://www.degruyter.com/view/j/popets.2015.1.issue-1/popets-2015-0007/popets-2015-0007.xml" target="_blank">https://www.degruyter.com/view/j/popets.2015.1.issue-1/popets-2015-0007/popets-2015-0007.xml</a>
* Giridhari Venkatadri, Piotr Sapiezynski, Elissa Redmiles, Alan Mislove, Oana Goga, Michelle Mazurek, and Krishna P. Gummadi. 2019. Auditing Offline Data Brokers via Facebook’s Advertising Platform. The Web Conference 2019. <a href="https://doi.org/10.1145/3308558.3313666">https://doi.org/10.1145/3308558.3313666</a>
* Datta, A., Datta, A., Makagon, J., Mulligan, D.K. & Tschantz, M.C.. (2018). "Discrimination in Online Advertising: A Multidisciplinary Inquiry." Proceedings of the 1st Conference on Fairness, Accountability and Transparency, in PMLR 81:20-34. <a href="http://proceedings.mlr.press/v81/datta18a/datta18a.pdf">http://proceedings.mlr.press/v81/datta18a/datta18a.pdf</a>
* Ali, M., Sapiezynski, P., Bogen, M., Korolova, A., Mislove, A., & Rieke, A. (2019). "Discrimination through optimization: How Facebook's Ad delivery can lead to biased outcomes." Proceedings of the ACM on Human-Computer Interaction, 3(CSCW), 1-30. <a href="https://dl.acm.org/doi/pdf/10.1145/3359301">https://dl.acm.org/doi/pdf/10.1145/3359301</a>

### Facial, biometric, speech recognition
* Buolamwini, J., & Gebru, T. (2018, January). Gender shades: Intersectional accuracy disparities in commercial gender classification. In Conference on fairness, accountability and transparency (pp. 77-91). PMLR. <a href="http://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf">http://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf</a>
* Koenecke, A., Nam, A., Lake, E., Nudell, J., Quartey, M., Mengesha, Z., Toups, C., Rickford, J.R., Jurafsky, D. and Goel, S., 2020. "Racial disparities in automated speech recognition." Proceedings of the National Academy of Sciences, 117(14), pp.7684-7689. <a href="https://www.pnas.org/content/117/14/7684">https://www.pnas.org/content/117/14/7684</a>
* Tatman, R. (2017, April). Gender and dialect bias in YouTube’s automatic captions. In Proceedings of the First ACL Workshop on Ethics in Natural Language Processing (pp. 53-59). <a href="https://www.aclweb.org/anthology/W17-1606.pdf">https://www.aclweb.org/anthology/W17-1606.pdf</a>
* Tatman, R., & Kasten, C. (2017, August). Effects of Talker Dialect, Gender & Race on Accuracy of Bing Speech and YouTube Automatic Captions. In Interspeech (pp. 934-938). <a href="https://www.isca-speech.org/archive/Interspeech_2017/pdfs/1746.PDF">https://www.isca-speech.org/archive/Interspeech_2017/pdfs/1746.PDF</a>
* Raji, I. D., Gebru, T., Mitchell, M., Buolamwini, J., Lee, J., & Denton, E. (2020, February). Saving face: Investigating the ethical concerns of facial recognition auditing. In Proceedings of the AAAI/ACM Conference on AI, Ethics, and Society (pp. 145-151). <a href="https://dl.acm.org/doi/pdf/10.1145/3375627.3375820">https://dl.acm.org/doi/pdf/10.1145/3375627.3375820</a>

### Recommender systems and search engine rankings

* Marc Faddoul, Guillaume Chaslot, and Hany Farid. 2020. A longitudinal analysis of YouTube’s promotion of conspiracy
videos. arxiv:2003.03318 [cs.CY] <a href="https://arxiv.org/abs/2003.0331">https://arxiv.org/abs/2003.0331</a>

* Ulloa, R., Makhortykh, M., & Urman, A. (2021). "Algorithm Auditing at a Large-Scale: Insights from Search Engine Audits." arXiv preprint arXiv:2106.05831. <a href="https://arxiv.org/abs/2106.05831">https://arxiv.org/abs/2106.05831</a>

### Social media and user-generated content (mostly NLP / sentiment analysis)

* M. Eslami, K. Vaccaro, K. Karahalios, and K. Hamilton. “Be careful; things can be worse than they appear”: Understanding Biased Algorithms and Users’ Behavior around Them in Rating Platforms (ICWSM 2017). <a href="http://social.cs.uiuc.edu/papers/ICWSM17-PrePrint.pdf" target="_blank">http://social.cs.uiuc.edu/papers/ICWSM17-PrePrint.pdf</a>
* King, G., Pan, J., & Roberts, M. E. (2014). Reverse-engineering censorship in China: Randomized experimentation and participant observation. Science, 345(6199). <a href="https://science.sciencemag.org/content/345/6199/1251722.abstract">https://science.sciencemag.org/content/345/6199/1251722.abstract</a>
* Blodgett, S. L., & O'Connor, B. (2017). Racial disparity in natural language processing: A case study of social media african-american english. arXiv preprint arXiv:1707.00061.  <a href="https://arxiv.org/pdf/1707.00061.pdf">https://arxiv.org/pdf/1707.00061.pdf</a>
* Kiritchenko, S., & Mohammad, S. M. (2018). Examining gender and race bias in two hundred sentiment analysis systems. arXiv preprint arXiv:1805.04508. <a href="https://arxiv.org/abs/1805.04508">https://arxiv.org/abs/1805.04508</a>
* Rios, A. (2020, April). FuzzE: Fuzzy fairness evaluation of offensive language classifiers on African-American English. In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 34, No. 01, pp. 881-889). <a href="https://doi.org/10.1609/aaai.v34i01.5434">https://doi.org/10.1609/aaai.v34i01.5434 </a>
* Davidson, T., Bhattacharya, D., & Weber, I. (2019). Racial bias in hate speech and abusive language detection datasets. arXiv preprint arXiv:1905.12516. <a href="https://arxiv.org/pdf/1905.12516">https://arxiv.org/pdf/1905.12516</a>

### The ProPublica vs. COMPAS/Northpointe debate on COMPAS criminal risk scores
* Angwin, J., Larson, J., Mattu, S., & Kirchner, L. (2016). Machine bias: There’s software used across the country to predict future criminals. And it’s biased against blacks. ProPublica (2016). <a href="https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing">https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing<a/>
* Dieterich, W., Mendoza, C., & Brennan, T. (2016). COMPAS risk scales: Demonstrating accuracy equity and predictive parity. Northpointe Inc. <a href="https://go.volarisgroup.com/rs/430-MBX-989/images/ProPublica_Commentary_Final_070616.pdf">https://go.volarisgroup.com/rs/430-MBX-989/images/ProPublica_Commentary_Final_070616.pdf</a>
* Angwin, J., & Larson, J. (2016). Technical Response to Northpointe. ProPublica. <a href="https://www.propublica.org/article/technical-response-to-northpointe">https://www.propublica.org/article/technical-response-to-northpointe</a> (and their annotations of the Dieterich et al response: <a href="https://www.documentcloud.org/documents/3248777-Lowenkamp-Fedprobation-sept2016-0.html">https://www.documentcloud.org/documents/3248777-Lowenkamp-Fedprobation-sept2016-0.html</a>
* Flores, A. W., Bechtel, K., & Lowenkamp, C. T. (2016). False positives, false negatives, and false analyses: rejoinder to machine bias: There's software used across the country to predict future criminals. and it's biased against blacks. Federal Probation, 80(2), 38-46. <a href="https://www.crj.org/assets/2017/07/9_Machine_bias_rejoinder.pdf">https://www.crj.org/assets/2017/07/9_Machine_bias_rejoinder.pdf</a>
* Dressel, J., & Farid, H. (2018). The accuracy, fairness, and limits of predicting recidivism. Science advances, 4(1), eaao5580. <a href="https://advances.sciencemag.org/content/advances/4/1/eaao5580.full.pdf">https://advances.sciencemag.org/content/advances/4/1/eaao5580.full.pdf</a>
* Washington, A. L. (2018). How to argue with an algorithm: Lessons from the COMPAS-ProPublica debate. Colo. Tech. LJ, 17, 131. <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3357874">https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3357874</a>

### Other rankings
* Qiu, H. and Du, W. "A True Lie about Reed College: U.S News Ranking" <a href="https://raw.githubusercontent.com/huayingq1996/Reed-College-Ranking/master/paper.pdf" target="_blank">https://raw.githubusercontent.com/huayingq1996/Reed-College-Ranking/master/paper.pdf</a>

