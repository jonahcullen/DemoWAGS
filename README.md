# DemoWAGS

**D**emonstration of **e**asy **m**ammalian **o**ptimization for **w**hole **a**nimal **g**enome **s**equencing pipelines

(Importantly this repository acronym/title has nothing to do with [JABBA](https://www.acgt.me/blog/2013/6/23/introducing-jabba-just-another-bogus-bioinformatics-acronym.html))

This repo contains the steps required to setup a snakemake environment in order to process FASTQs to GVCFs and ultimately a joint genotyped VCF, all using a Singularity container.

### Home institution installation and setup

Please see the main repository [WAGS](https://github.com/jonahcullen/wags).

### Demo steps

**Download the equine container**

Due to the size of the Equine genome and associated indices included in the container (and depending on your internet speed) this should take ~2 minutes.

```
wget https://s3.msi.umn.edu/wags/demo/horse_wags.sif
```

**Download the data**

```
wget https://s3.msi.umn.edu/wags/samples.tar.gz
tar -xzvf samples.tar.gz
```

**Clone the WAGS repo**

```
git clone https://github.com/jonahcullen/wags.git
```
