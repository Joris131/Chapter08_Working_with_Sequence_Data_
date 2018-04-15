# Chapter08_Working_with_Sequence_Data_

## Counting the number of sequences of the FASTQ:

    bioawk -cfastx 'END{print NR}' sequence.fq
    
    
