java -jar ~/miniconda3/share/trimmomatic-0.39-1/trimmomatic.jar PE B_cepacia_raw_R1.fastq.gz B_cepacia_raw_R2.fastq.gz BCep_R1_paired.fastq.gz BCep_R1_unpaired.fastq.gz BCep_R2_paired.fastq.gz BCep_R2_unpaired.fastq.gz CROP:140 LEADING:10 TRAILING:10 SLIDINGWINDOW:5:20 MINLEN:140 -threads 4

```
export MONO_HOME=/Library/Frameworks/Mono.framework/Versions/5.18.1

export PATH=$PATH:$MONO_HOME/bin
```

