## Meeting Notes

EPI2ME software was also shown to Dr. Casey and Dr. Clark

### Challenges/Obstacles

Two main challenges were discussed: the DNA data is in tiny, broken pieces, and there is possible contamination from many sources.

Pod5 files contain the original, large-sized DNA data; however, it's has a large memory footprint.

As of now, the input automatically converts a broken/decomposed DNA nuclotide into either ATCG (which I believe it is automatically making Uracil into Thyamine) and we need to see whether or not the software takes this into account.

### The primary goal is to determine whether the DNA matches the cow genome.

Bioinformatics Team tasks:

    Validating findings

    Starting with cow DNA, then moving to older samples (like pig)

    Ensuring clean data by removing contamination

    Filtering Fastq files to remove overly large sequences, likely to be noise

Dr. Casey suggested testing modern cow DNA to understand normal levels of bacterial contamination, and using segmented versions of it to test the accuracies of the various algorthims when it has the smaller reads.

Shorter DNA fragments may be created from longer ones to test the classification accuracy of algorithms. Trimming unreliable ends and checking base-by-base confidence may improve results.

Informatics Team tasks:

    See if we can find a way to use the larger databases (the "-16" rather than the "-8") to improve results.

    Try to test out Dr. Casey's suggestion

    Research the various formats that are outputed and used by the algorithms (Dr. Clark suggested this) and see what it is about

    Later (way later), set up a searchable database once high-confidence matches are found
