# Algorithmic Auditing Lab for Fall 2021

# Details
* Instructor: R. Stuart Geiger
* Time: 5-6:50pm on Tuesdays
* Place: SOLIS 109

# Description

This seminar is for students interested in empirically investigating real-world algorithmic systems of all kinds, particularly those where the classifiers and/or training data are not publicly available. The first few weeks of the class will include more readings and lectures, when we cover the history of auditing and legal/ethical issues it raises. This includes studying classic audits of non-algorithmic decision systems (e.g. equal opportunity hiring investigations) to contemporary issues around the Computer Fraud and Abuse Act and the IRB. We will learn various approaches to investigate such systems, including auditing via training datasets, code, user reports, API scraping, and sockpuppet accounts. We will read and discuss various algorithmic audits by researchers and regulators.  Then, the second half of the class will be more discussion- and activity-based, as we perform audits on several real-world models whose developers have encouraged public auditing (e.g. Wikipedia’s content moderation classifiers). Students will work towards a final project, where they will conduct their own audits of real-world algorithmic systems and develop strategies for how systems can be designed for auditability.

# Readings
Thanks to auditingalgorithms.science for many of these!

## Classic auditing in non-algorithmic systems

* National Research Council Panel on Measuring Racial Discrimination, The. (2004). Measuring Racial Discrimination. Washington, DC: National Academies Press. http://www.nap.edu/catalog/10887/measuring-racial-discrimination
* Schulman KA, Berlin JA, Harless W, Kerner JF, Sistrunk S, et al. The effect of race and sex on physicians’ recommendations for cardiac catheterization. N. Engl. J. Med. 1999;340(8):618–626.
* Saltman, J. (1975). Implementing Local Housing Laws Through Social Action. Journal of Applied Behavioral Science, 11(1): 39-61.
* Ayres, I. & Siegelman, P. (1995). Race and Gender Discrimination in Bargaining for a New Car. American Economic Review 85(3): 304-321.
* Stuart, G., "Databases, Felons, and Voting: Errors and Bias in the Florida Felons Exclusion List in the 2000 Presidential Elections" (September 2002). KSG Working Paper Series RWP 02-041. Read pp. 22-40. http://ssrn.com/abstract=336540

## Algorithmic auditing frameworks and introductions
* Sandvig, C., Hamilton, K., Karahalios, K., & Langbort, C. (2014). “An Algorithm Audit.” In: Seeta Peña Gangadharan (ed.), Data and Discrimination: Collected Essays, pp. 6-10. Washington, DC: New America Foundation. http://www-personal.umich.edu/~csandvig/research/An%20Algorithm%20Audit.pdf
* Sandvig, Christian, Kevin Hamilton, Karrie Karahalios, and Cedric Langbort. forthcoming. "Auditing Algorithms: Research Methods for Detecting Discrimination on Internet Platforms." Computational Culture. http://www-personal.umich.edu/~csandvig/research/Auditing%20Algorithms%20--%20Sandvig%20--%20ICA%202014%20Data%20and%20Discrimination%20Preconference.pdf
* Diakopoulos, Nicholas. 2015. ‘‘Algorithmic Accountability.’’ Digital Journalism 3 (3): 398-415. http://www.nickdiakopoulos.com/wp-content/uploads/2011/07/algorithmic_accountability_final.pdf
* Data & Society Research Institute. 2014 "Workshop Primer: Algorithmic Accountability" http://www.datasociety.net/pubs/2014-0317/AlgorithmicAccountabilityPrimer.pdf

## Legal criteria for algorithmic systems / auditing as necessary for due process
* Pasquale, Frank. 2006. "Rankings, Reductionism, and Responsibility" Cleveland State Law Review, 54:115+. http://digitalcommons.law.umaryland.edu/fac_pubs/1351/
* Citron, Danielle Keats, and Frank A. Pasquale. 2014. "The Scored Society: Due Process for Automated Predictions." Washington Law Review 89. http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2376209
* Citron, Danielle Keats, Technological Due Process. Washington University Law Review, Vol. 85, pp. 1249-1313, 2007. READ § I.A., II.B.2, III.C.2. http://ssrn.com/abstract=1012360

## Algorithmic audits by researchers
* Sweeney, L. Discrimination in Online Ad Delivery. CACM 56(5): 44-54. https://cacm.acm.org/magazines/2013/5/163753-discrimination-in-online-ad-delivery/abstract
* Hannak, A., Soeller, G., Lazer, D., Mislove, A., Wilson, C. (2014). Measuring Price Discrimination and Steering on E-commerce Web Sites. (IMC ’14). http://personalization.ccs.neu.edu/papers/price_discrimination.pdf
* M. Eslami, K. Vaccaro, K. Karahalios, and K. Hamilton. “Be careful; things can be worse than they appear”: Understanding Biased Algorithms and Users’ Behavior around Them in Rating Platforms (ICWSM 2017). http://social.cs.uiuc.edu/papers/ICWSM17-PrePrint.pdf
* Amit Datta, Michael Carl Tschantz, and  Anupam Datta. (2015). Automated Experiments on Ad Privacy Settings: A Tale of Opacity, Choice, and Discrimination. PoPETs 2015: 1. https://www.degruyter.com/view/j/popets.2015.1.issue-1/popets-2015-0007/popets-2015-0007.xml
