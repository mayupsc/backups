# backups
basically the refseq, off and various index 


## 1. SL3.0 structural RNA

```

curl -OL ftp://ftp.ensemblgenomes.org/pub/release-43/plants/fasta/solanum_lycopersicum/ncrna/Solanum_lycopersicum.SL3.0.ncrna.fa.gz

mkdir SL3.0.ncrna
bowtie-build Solanum_lycopersicum.SL3.0.ncrna.fa SL3.0.ncrna/SL3.0.ncrna
```
