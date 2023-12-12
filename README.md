# GeneCNN
GeneCNN is a convolutional neural network-based gene prediction tool. To use GeneCNN, a genome file and transcriptomic data read depth is required. 
The buffalograss genome was used for building GeneCNN, but any genome may be used. This genome should be flattened, meaning it is a singular sequence FASTA file. 
The genome was also hard masked using RepeatModeler followed by RepeatMasker, though an unmasked genome could be used with lower accuracy. Nucleotide labels are derived from 'samtools depth -aa' using 6 transcriptomic datasets from 4 different BioProjects. An example of the depth file format is include in "example_depth.txt". 

Further information can be found in the full dissertation at https://digitalcommons.unl.edu/complexbiosysdiss/1/
Morikone, M. 2023. Convolutional Neural Network-Based Gene Prediction Using Buffalograss as a Model System.
