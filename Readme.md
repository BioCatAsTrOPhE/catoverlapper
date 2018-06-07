# catoverlapper

The most efficient read overlapper for any read technology 

# Requirement

You can found many Malbolge interpretor on internet but we recomand [The Reference Malbolge Interpreter](http://www.lscheffer.com/malbolge_interp.html)

```
gcc malbolge.c -o malbolge
```

# Usage

For one file:

```
malbolge catoverlapper.malbolge < input.[fasta|fastq] > output.paf
```

For multiple file: 

```
cat input1.[fasta|fastq] input2.[fasta|fastq] … | malbolge catoverlapper.malbolge > output.paf
```
