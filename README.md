# HuBMAP-HPA---Hacking-the-Human-Body
Segment multi-organ functional tissue units

Background
--

When you think of “life hacks,” normally you’d imagine productivity techniques. But how about the kind that helps you understand your body at a molecular level? It may be possible! Researchers must first determine the function and relationships among the 37 trillion cells that make up the human body. A better understanding of our cellular composition could help people live healthier, longer lives.

A previous Kaggle competition aimed to annotate cell population neighborhoods that perform an organ’s main physiologic function, also called functional tissue units (FTUs). Manually annotating FTUs (e.g., glomeruli in kidney or alveoli in the lung) is a time-consuming process. In the average kidney, there are over 1 million glomeruli FTUs. While there are existing cell and FTU segmentation methods, we want to push the boundaries by building algorithms that generalize across different organs and are robust across different dataset differences.

The Human BioMolecular Atlas Program (HuBMAP) is working to create a Human Reference Atlas at the cellular level. Sponsored by the National Institutes of Health (NIH), HuBMAP and Indiana University’s Cyberinfrastructure for Network Science Center (CNS) have partnered with institutions across the globe for this endeavor. A major partner is the Human Protein Atlas (HPA), a Swedish research program aiming to map the protein expression in human cells, tissues, and organs, funded by the Knut and Alice Wallenberg Foundation.

In this competition, you’ll identify and segment functional tissue units (FTUs) across five human organs. You'll build your model using a dataset of tissue section images, with the best submissions segmenting FTUs as accurately as possible.

If successful, you'll help accelerate the world’s understanding of the relationships between cell and tissue organization. With a better idea of the relationship of cells, researchers will have more insight into the function of cells that impact human health. Further, the Human Reference Atlas constructed by HuBMAP will be freely available for use by researchers and pharmaceutical companies alike, potentially improving and prolonging human life.

Data Description
--
