# CORA

CORA is a Python library for **Combinational Regularity Analysis** (CORA). 

## Description

CORA belongs to the group of Configurational Comparative Methods (CCMs; Thiem *et al*. 2016), and is thus closely related to, 
for example, Qualitative Comparative Analysis (QCA; Ragin 1987) and Coincidence Analysis (CNA; Baumgartner 2009). 
Unlike QCA and CNA, however, CORA can analyze multi-output structures without generating redundancies. In addition, 
CORA offers a data-mining approach to solution building that reduces model ambiguities by keeping the number of required 
variables for finding a solution at a minimum. Lastly, CORA includes a standardized visualization module called LOGIGRAM, 
with which logic diagrams can be produced from (systems of) Boolean functions in disjunctive normal form.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install CORA.

```bash
pip install CORA
```
## Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/ZuzanaSebb/551cd0cd72abecf85cd5656bdd29c35a/cora-1-0-0.ipynb)


## References

* Baumgartner, Michael. 2009. "Inferring Causal Complexity." *Sociological Methods & Research* **38** (1):71-101.
* Ragin, Charles C. 1987. *The Comparative Method: Moving beyond Qualitative and Quantitative Strategies*. Berkeley: University of California Press.
* Thiem, Alrik, Michael Baumgartner, and Damien Bol. 2016. "Still Lost in Translation! A Correction of Three Misunderstandings Between Configurational Comparativists and Regressional Analysts." *Comparative Political Studies* **49** (6):742-74.