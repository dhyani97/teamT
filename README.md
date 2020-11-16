# teamT
Align a single fasta file containing two DNA sequences using local alignment.
from Bio.Emboss.Applications import NeedleCommandLine
needle_cline = NeedleCommandline()
needle_cline.asequence="data/alpha.faa"
needle_cline.bsequence="data/beta.faa"
needle_cline.gapopen=10
needle_cline.gapextend=0.5
needle_cline.outfile="needle.txt"
print(needle_cline)

print(needle_cline.outfile)
