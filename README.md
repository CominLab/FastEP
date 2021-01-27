# FastEP

Fast Computation of Entropic Profiles for the Detection of Conservation in Genomes

Abstract:

The information theory has been used for quite some time in the area of computational biology. In this paper we discuss and improve the function Entropic Profile, introduced by Vinga and Almeida. The Entropic Profiler is a function of the genomic location that captures the importance of that region with respect to the whole genome. We pro- vide a linear time linear space algorithm called Fast Entropic Profile, as opposed to the original quadratic implementation. Moreover we propose an alternative normalization that can be also efficiently implemented. We show that Fast EP is suitable for large genomes and for the discovery of motifs with unbounded length.
Software
Here you can find the java application FastEP with some examples.
Unzip the following file: ZIP

Run FastEP using the command:

java -jar FastEP.jar StartingPosition PatternLength Phi WindowLength FastaFile

Using the input sequence contained in "FastaFile" FastEP computes the entropy of all patterns of length "PatternLength" with the normalization parameter "Phi" from position "StartingPosition" till "StartingPosition" + "WindowLength"-1. The output is written into the file "Entropy List i.txt". Where "i" grows with number of queries.

To run the example included type:

java -jar FastEP.jar 178 7 10 100 ecoli.fasta

Licence

The software is freely available for academic use.

For questions about the tool, please contact Matteo Comin.


Reference

Please cite the following papers:

M. Antonello, M. Comin,
"Fast Computation of Entropic Profiles for the Detection of Conservation in Genomes",
Proceedings of Pattern Recognition in Bioinformatics 2013,
Lecture Notes in BIoinformatics (LNBI) 2013, 7986, pp. 277--288.

M. Comin, M. Antonello
"Fast Entropic Profiler: An Information Theoretic Approach for the Discovery of Patterns in Genomes"
IEEE/ACM Transactions on Computational Biology and Bioinformatics, 2014, Vol. 11, No. 3, pp. 500-509 Pdf
(impact factor 1.7)


 

