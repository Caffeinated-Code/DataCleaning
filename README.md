# DataCleaning
Identifying and dealing with/dropping coarse and dirty data using Pandas of Python

Dataset: rawData.xlxs
     Contains ORFs from the left arm of chromosome 11 from Saccharomyces cerevisea.  However, you will notice that there are several errors in the file.  The first row, highlighted in yellow, contains correctly formatted data. The subsequent rows may contains data errors.
     
You should expect to find the following types of information in the columns:
      1.	Row number: use this when you refer to the rows with errors (mandatory)\
      2.  Primary SGDID: a unique identifier for the sequence feature (mandatory);
      3.  Feature type: a phrase that describes the sequence feature   (mandatory);
      4.  Feature name: a name that describes the approximate location of the sequence feature (optional);
      5.	Gene name: a human-friendly name, following the pattern of 3 letters and a number (optional);
      6.  Secondary SGDID: alternate identifiers for the sequence feature  (optional, multiples separated by |);
      7.  Chromosome: the chromosome that the sequence feature is located on (optional);
      8.  Start coordinate: the coordinate number on the chromosome that contains the beginning of the start codon (mandatory);
      9.  Stop coordinate: the coordinate number on the chromosome that  contains the end of the stop codon  (mandatory);
      10. Strand: whether the ORF is on the Watson or Crick strand (mandatory);
      11. Sequence version date: date when the genomic sequence was last modified (optional);
      12. Description: A short summary of the biological role of the ORF (optional);

Python Libraries used:
      1. Pandas;
      2. Numpy;
      3. re;
      4. array;
      5. datetime;
