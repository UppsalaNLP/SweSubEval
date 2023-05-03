# SweSubEval

Evaluation data for subordinate clauses from Swedish literary text from 1800–1930.
The dataset is described in:

> Sara Stymne, Carin  Östman, and David Håkansson (2023) Parser Evaluation for Analyzing Swedish 19th-20th Century Literature. Accepted to The 24th Nordic Conference on Computational Linguistics (Nodalida'23). Tórshavn, Faroe Island. May 22nd-24th, 2023.


## Dataset

The dataset is available in the file "literature-sample-annotated.csv". Each line contains the type of relation, the class (1: the relation occur with the marked word, or 0: the relation does no occur with the marked word), and the annotated sentence, where the a focus word is marked with asterisks. The possible types are:
* *relcl*: the focus word is the head of a relatvie clause, *acl:relcl*
* *cleft*: the focus word is the head of a cleft construction, *acl:cleft*
* *ccomp*: the focus word is the head of a clausal complement, *ccomp*
* *no-aux*: the focus word is the head of a clausal complement where the verb is infinite with a dropped auxilliary verb


## Sampling

All sentences are sampled from works in [Litteraturbanken](https://litteraturbanken.se/). A list of works from which sentences are smapled, is available in the file "list-of-works.csv". Before sampling, the texts were split into speech segment and narrative, based on the occurence of quotation marks.

## Licence

The data is released under the [Creative Commons license, CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/)

![cc-by-nc-sa-image](https://licensebuttons.net/l/by-nc-sa/3.0/88x31.png)


