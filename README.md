# UniTD: A Benchmark with Unified Text-Domain for Text-to-Image Person ReID

Here's the official implementation of [ICME 2025] "UniTD: A Benchmark with Unified Text-Domain for Text-to-Image Person ReID".

![图片1](https://github.com/user-attachments/assets/2a7c4d89-c346-488f-baf0-28c48d20f89d)


## Abstract
Text-to-image person re-identification (TIReID) aims to retrieve the corresponding pedestrian image based on a text description. 
Prior research primarily focused on intra-domain TIReID task, where training and testing data are drawn from the same domain. 
However, they disregard domain gaps among various TIReID datasets, leading to performance degradation in cross-domain scenarios. 
To investigate cross-domain problem, this paper analyzes the causes of differences across datasets and empirically proves that the text descriptions from different annotators exhibit significant style discrepancies, even when annotating the same images. 
Motivated by this insight, we propose a benchmark with Unified Text-Domain (UniTD) to reduce the domain gap. 
Specifically, we harness the power of MLLMs to generate textual descriptions with a unified style. 
Moreover, considering the domain differences between UniTD text and real-world query text, we present a Query Text Rewriting method (QTR). 
It utilizes LLMs to rewrite the query text by chain-of-thought, aiming to transfer the style of query text into UniTD style.
Extensive experiments demonstrate that the proposed UniTD benchmark, with its unified text-domain, significantly improves cross-domain performance by 11\%-33\%. Additionally, QTR effectively aligns the style of real-world query text with UniTD, achieving state-of-the-art cross-domain performance.

## Framework
![图片2](https://github.com/user-attachments/assets/61d06685-a42c-438d-b564-973eb4e9064d)


## Text Visualization Comparison
![图片3](https://github.com/user-attachments/assets/3b423287-2890-42f5-9e03-bb8f219f6203)


