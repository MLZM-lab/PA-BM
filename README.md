# PA-BM
Boolean models of the virulence networks and quorum sensing systems of Pseudomonas aeruginosa

Pseudomonas aeruginosa is an opportunistic pathogen with an extraordinary metabolic adaptability and a large repertoire of virulence factors that allow it to cause acute and chronic infections. Treatment of P. aeruginosa infections often fail due to its antibiotic resistance mechanisms, thus novel strategies aim at targeting virulence factors instead of growth-related features. However, there is currently not a clear understanding of the dynamic nature inherent to the wiring of its virulence networks. 

We manually reconstructed the signalling and transcriptional regulatory networks of 12 acute (incl. pyocin and elastase) and 8 chronic virulence factors (incl. biofilm), and the 4 quorum sensing (QS) systems of P. aeruginosa. Using Boolean modelling (BM), we unveiled the important roles that stochasticity and node connectivity play in the networks’ inherent dynamicity and robustness. We found that both the static interactions, as well as the time when the interactions take place, are important features in the QS network. We also showed that the virulence factors of the acute networks are under strict repression, or under an activation that is non-strict or oscillatory. On the other hand, the chronic networks favour the repression of the virulence factor, with only moderate activation under certain conditions. 

In conclusion, our in silico-modelling framework provided us with a system-level view of the P. aeruginosa virulence and QS networks to gain new insights into the various mechanisms that support its pathogenicity and response to stressors targeting these networks. Thus, we suggest that BM provides an invaluable tool to guide the design of new treatments against P. aeruginosa.


In this repository you will find the plain text files with the coded Boolean updating rules of our reconstructed networks, as well as the R code that was used for the Boolean analyses.

You can find the publication of this study here: https://ieeexplore.ieee.org/document/9020089
