### Overview

Global warming is significantly impacting marine ecosystems by raising water temperatures, increasing acidity, and intensifying UV radiation, all of which pose serious challenges to marine organisms, particularly macroalgae. *Gracilaria gracilis*, a red alga found along Israel's Mediterranean coast, plays a vital role in its ecosystem. As a primary producer, it supports marine life and is also commercially valuable for its bioactive compounds.

Carotenoids, pigments crucial for photosynthesis, also protect algae from light-induced stress. They help absorb excess light and neutralize harmful free radicals, thus safeguarding the photosynthetic machinery. In the context of global warming, which is expected to increase UVB radiation and alter light intensity, understanding how *G. gracilis* modulates carotenoid production is essential for predicting its resilience and adaptability.

Our study aims to investigate the impact of varying light intensities and UV radiation on carotenoid and other natural prodact genes expression in *G. gracilis*, simulating current and future climate scenarios. We will expose the algae to low, medium, and high light and UV levels over six weeks, mimicking natural day-night cycles. Using quantitative PCR (qPCR) with GAPDH as a reference gene, we will measure changes in carotenoid and naturl product gene expression. This research will provide insights into how *G. gracilis* responds to environmental stressors linked to climate change and offer guidance for optimizing its commercial cultivation to produce high-value natural products.

![Gracilaria gracilis](https://github.com/user-attachments/assets/076e778c-cb40-4473-8d23-fb6a8798b6c2)


To study the impact of light and UV radiation on *Gracilaria gracilis*, samples will be collected from the Israeli Mediterranean coast, ensuring that collection times are consistent to minimize variability. After rinsing, these samples will be placed in aerated seawater aquariums. 

In the controlled environment, multiple aquariums will be prepared, each exposed to different light intensities and UV radiation levels using LED lights and UVB lamps. A control group will be maintained with all other environmental factors, such as temperature, salinity, and nutrients, kept constant. Samples will be harvested after 2, 4, and 6 weeks to assess the effects over time.

Carotenoid and natural product biosynthesis genes will be identified through public databases such as [NCBI](https://www.ncbi.nlm.nih.gov/), with homologous genes in *G. gracilis* found using [BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi).

The reference gene for the qPCR process was selected from previous articles, and the first gene selected for testing is thiG which involved in the biosynthesis of thiamine (vitamin B1), you can read more about the selection process [here](https://github.com/OfekRainish/Impact-of-Light-and-Radiation-on-Carotenoid-Gene-Expression-in-the-Red-Alga-Gracilaria-gracilis/blob/main/posts/2024-07-10-Primer%20selection%20for%20qPCR%20Experiment%20-%20class.md).

Specific primers will be designed using [Primer3](https://primer3.ut.ee/), and their specificity will be confirmed through PCR validation. A full protocol on primer design can be found [here](https://github.com/OfekRainish/Impact-of-Light-and-Radiation-on-Carotenoid-Gene-Expression-in-the-Red-Alga-Gracilaria-gracilis/blob/main/posts/2024-07-04-Primer%20Design%20-%20class.md).

For gene expression quantification, RNA will be extracted from the samples and its quality assessed using NanoDrop and gel electrophoresis. This RNA will then be converted into cDNA, and qPCR will be performed using the GAPDH gene for normalization. The resulting data will be analyzed statistically to determine significant differences in gene expression across the various treatment conditions using [this](https://github.com/OfekRainish/Impact-of-Light-and-Radiation-on-Carotenoid-Gene-Expression-in-the-Red-Alga-Gracilaria-gracilis/blob/main/scripts/R%20script%20ggplot.r) R script, and by [this](https://github.com/OfekRainish/Impact-of-Light-and-Radiation-on-Carotenoid-Gene-Expression-in-the-Red-Alga-Gracilaria-gracilis/blob/main/posts/2024-07-05-Protocol%20for%20Analyzing%20qPCR%20Results%20class.md) protocol.



![alt text](images/proposal.png)

### Impact

This research will elucidate *G. gracilis*'s adaptive mechanisms through carotenoid gene expression in response to varying light and radiation levels, enhancing our understanding of macroalgae resilience to climate change. Furthermore, it will provide critical insights for the commercial cultivation of *G. gracilis* for high-value carotenoid production, contributing to the sustainable development of coastal ecosystems and the blue economy.
