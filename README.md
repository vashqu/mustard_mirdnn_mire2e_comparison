# MuStARD, mirDNN, and miRe2e Benchmark

This repository contains benchmarking results comparing three state-of-the-art tools for the prediction of pre-miRNA genomic loci:

- **[MuStARD](https://gitlab.com/RBP_Bioinformatics/mustard)** – Multi-branch CNN using sequence, conservation, and structure.
- **[mirDNN](https://github.com/cyones/mirDNN)** – Deep residual CNN for genome-wide pre-miRNA prediction.
- **[miRe2e](https://github.com/sinc-lab/miRe2e)** – Transformer-based, full end-to-end model requiring no manual feature extraction.

## Code Availability

Reproducible code for running the benchmarking experiments will be uploaded soon.

Until then, a **viewer-only version** of the full results and materials is available here:

[Google Drive Folder](https://drive.google.com/drive/folders/1H3RlNo4ZQKTwxWBETGZQnW2JL1OH-vWL?usp=sharing)

If you're interested in running the code or contributing, please contact:

 **Vasilis Chatzitolios**  
`billy.hatzi@gmail.com`

## Evaluation Summary

All tools were benchmarked on the same genomic region (human chromosome 14), using:

- Accuracy, Precision, Recall, F1 Score
- Overlap with known miRNA annotations
- Hotspot intersection analysis
- Runtime and scalability observations

## Citation

If you use this repository or refer to the benchmark, please cite the original works:

- Georgakilas, G.K., Grioni, A., Liakos, K.G. et al. Multi-branch Convolutional Neural Network for Identification of Small Non-coding RNA genomic loci. Sci Rep 10, 9486 (2020). https://doi.org/10.1038/s41598-020-66454-3
- Yones C, Raad J, Bugnon LA, Milone DH, Stegmayer G. High precision in microRNA prediction: A novel genome-wide approach with convolutional deep residual networks. Comput Biol Med. 2021 Jul;134:104448. doi: 10.1016/j.compbiomed.2021.104448. Epub 2021 May 5. PMID: 33979731.
- Raad J, Bugnon LA, Milone DH, Stegmayer G. miRe2e: a full end-to-end deep model based on transformers for prediction of pre-miRNAs. Bioinformatics. 2022 Feb 7;38(5):1191-1197. doi: 10.1093/bioinformatics/btab823. PMID: 34875006.

---

