# Electrochemical Modelling For Li-ion Battery To Account For Deterioration Observed Under Randomised Usage

Welcome to the repository containing the culmination of my internship project at Siemens Energy R&D Gurugram, India. This repository houses the codes developed during my internship period from February to July 2023. The project, titled "Electrochemical Modelling for Li-ion Battery to Account for Deterioration Observed under Randomized Usage," was conducted within the Battery Energy Storage Systems (BESS) Department.

This internship project covers the understanding of battery degradation by involving theoretical insights, code implementation, and validation with a publication. Drawing inspiration from a published experiment [[1]](https://papers.phmsociety.org/index.php/phmconf/article/view/2490), the study focuses on specific cycling processes inducing battery cell degradation. The journey spans understanding the experimental dataset [[2]](https://data.phmsociety.org/nasa/), establishing a theoretical foundation, implemention in Python, and exploring electrochemical modeling with formulas from a reference paper [[3]](https://papers.phmsociety.org/index.php/phmconf/article/view/2252). We further develop a degradation model, optimizing key parameters like total capacity and internal resistance through the Nelder-Mead Method. The model's fidelity is confirmed via comparisons with the publication's results, attesting to its accurate reflection of degradation patterns. Finally, the study enhances the model to predict degradation across various discharge levels. A linear regression analysis compares metrics with the reference publication. Ultimately, the developed model can be used as a synthetic data generator to further create datasets for future ML applications.


## Files in the repository:
* [Documentation](./Documentation/Internship_Report.pdf): Documentation of the work to follow the code with ease.
* [Battery Modelling](./Codes/Battery_Modelling.ipynb): Contains the battery model implementation which is compared with the first occurence pulsed discharge cycle in battery-1 of the experiment.
* [Model Optimization](./Codes/Model_Optimization.ipynb): Contains the optimization of the above model for the same regime.
* [Deterioration Modelling](./Codes/Deterioration_Modelling.ipynb): Covers the application of the optimised model to multiple pulsed discharge regimes in battery-1, 2 and 3.
## Dataset:
Please find the datasets for the 4 batteries in the google drive link [here](https://drive.google.com/drive/folders/14Sf6boPdBeofAuL-2vQRCphdJ64KmzMe?usp=sharing).
##
Feel free to explore the codes and documentation to delve deeper into this enriching journey. Your feedback is invaluable as we collectively navigate the complexities of battery technology.Kindly reach out to me if you have a possible extension in mind, I'd love to be involved in the same! (:
