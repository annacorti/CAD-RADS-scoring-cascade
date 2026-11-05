MV_P consists of predicting a score for each image (from the features extracted) and then performing a majority voting to predict the patient’s class: thus, the patient’s CAD-RADS score will be the most recurrent score among the image-based predictions. MV_C consists of predicting a score for each image and then performing a majority voting at the coronary level to predict an artery-based class: the artery-based score will be the most recurrent score among image-based predictions referring to that coronary artery and, then, the patient’s CAD-RADS score is assigned to the most critical artery-based score. 

Reference: 

[1] Corti A, Lo Iacono F, Ronchetti F, Chiesa M, Pontone G, Colombo GI, Corino VDA. Patient-level CAD-RADS scoring from coronary radiomic features. Sci Rep. 2026 Jan 29;16(1):4330. doi: 10.1038/s41598-025-32352-9. PMID: 41611724; PMCID: PMC12865196.

[2] Corti A, Ronchetti F, Lo Iacono F, Chiesa M, Colombo G, Annoni A, Baggiano A, Carerj ML, Del Torto A, Fazzari F, Formenti A, Junod D, Mancini ME, Maragna R, Marchetti F, Sbordone FP, Tassetti L, Volpe A, Mushtaq S, Corino VDA, Pontone G. Automated CAD-RADS scoring from multiplanar CCTA images using radiomics-driven machine learning. Eur J Radiol. 2025 Oct;191:112320. doi: 10.1016/j.ejrad.2025.112320. Epub 2025 Jul 16. PMID: 40684709.
