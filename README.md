# UOW-CSCI992-Spring-2019-Team-B
UOW, CSCI992 Professional Project Spring 2019, Team B

Ref:
    https://www.kaggle.com/c/recursion-cellular-image-classification

The cost of some drugs and medical treatments has risen so high in recent years that many patients are having to go without. You can help with a classification project that could make researchers more efficient.

One of the more surprising reasons behind the cost is how long it takes to bring new treatments to market. Despite improvements in technology and science, research and development continues to lag. In fact, finding new treatments takes, on average, more than 10 years and costs hundreds of millions of dollars.

Recursion Pharmaceuticals, creators of the industry’s largest dataset of biological images, generated entirely in-house, believes AI has the potential to dramatically improve and expedite the drug discovery process. More specifically, your efforts could help them understand how drugs interact with human cells.

This project focuses on disentangling experimental noise from real biological signals. Your entry will classify images of cells under one of 1,108 different genetic perturbations. You can help eliminate the noise introduced by technical execution and environmental variation between experiments.

If successful, you could dramatically improve the industry’s ability to model cellular images according to their relevant biology. In turn, applying AI could greatly decrease the cost of treatments, and ensure these treatments get to patients faster.

# DATA Description
One of the main challenges for applying AI to biological microscopy data is that even the most careful replicates of a process will not look identical. This dataset challenges you to develop a model for identifying replicates that is robust to experimental noise.

The same siRNAs (effectively genetic perturbations) have been applied repeatedly to multiple cell lines, for a total of 51 experimental batches. Each batch has four plates, each of which has 308 filled wells. For each well, microscope images were taken at two sites and across six imaging channels. Not every batch will necessarily have every well filled or every siRNA present.

We've condensed this description down to the essentials; for additional details please see RxRx.ai.
