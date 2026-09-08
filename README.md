# Dataset for sequence tagging in the legal domain

This is Annotares a novel dataset
The files include the Baugesetzbuch (BauGB), the Bundesausbildungsförderungsgesetz (BAföG) und the Bundesdatenschutzgesetz (BDSG). The BauGB and the BAföG are samples with 50 sentences each. The BDSG was annotated completely.

## Krippendorff's Alpha

| Dataset | Annotators | α |
| ------- | ---------- | --- |
| BAföG | All (3) | 0.815 |
| | 00 & 01 | 0.897 |
| | 00 & 02 | 0.685 |
| | 01 & 02 | 0.697 |
| BauGB | All (2) | 0.926 |
| BDSG | All (8) | 0.821 |
| | 00 & 01 | 0.896 |
| | 00 & 02 | 0.592 |
| | 00 & 03 | 0.483 |
| | 00 & 04 | 0.858 |
| | 00 & 05 | 0.826 |
| | 00 & 06 | 0.942 |
| | 00 & 07 | 0.923 |

The BDSG includes the results of the 6 annotators that achieved an Krippendorff's Alpha higher than $0.8$. The BDSG has a Krippendorff's Alpha of $0.893$.

## Corpus Statistics

| Law | Usage | Sentences | Tokens | Rechtsfolge (%) | Tatbestand (%) | None (%) |
| --- | ----- | --------- | ------ | --------------- | -------------- | -------- |
| BAföG | Test | 50 | 2121 | 38.0 | 57.6 | 4.4 |
| BauGB | Test | 50 | 1905 | 46.3 | 46.6 | 7.1 |
| BDSG | Train & Test | 439 | 17524 | 44.3 | 40.6 | 15.1 |
| **Combined** | | **539** | **21550** | **43.8** | **42.8** | **13.4** |

Further information can be found in the paper: "Annotares: A Dataset for Extracting Logical Structures from German Statutory Texts"
