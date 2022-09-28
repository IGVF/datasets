# SHARE-seq

FASTQ files were derived from [SRR10428400](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR10428400&display=metadata). Metata for that SRA accession was obtained with [`ffq`](https://github.com/pachterlab/ffq/).

```bash
pip install ffq==0.3.0
```

```json
$ ffq SRR10428400
{
    "SRR10428400": {
        "accession": "SRR10428400",
        "experiment": "SRX7124451",
        "study": "SRP229493",
        "sample": "SRS5634094",
        "title": "NextSeq 550 paired end sequencing; GSM4156601: GM12878 rep1 (RNA-Seq); Homo sapiens; RNA-Seq",
        "attributes": {
            "assembly": "hg19_mm10",
            "options": "--max-err-count 10000000",
            "ENA-SPOT-COUNT": 51149975,
            "ENA-BASE-COUNT": 1507354932,
            "ENA-FIRST-PUBLIC": "2021-03-13",
            "ENA-LAST-UPDATE": "2021-10-21"
        },
        "files": {
            "ftp": [
                {
                    "accession": "SRR10428400",
                    "filename": "SRR10428400.fastq.gz",
                    "filetype": "fastq",
                    "filesize": 599230812,
                    "filenumber": 1,
                    "md5": "e65e2d754cc8b46d68b1c7bcb05f310d",
                    "urltype": "ftp",
                    "url": "ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR104/000/SRR10428400/SRR10428400.fastq.gz"
                },
                {
                    "accession": "SRR10428400",
                    "filename": "GM12878.rep1.rna.noRG.bam",
                    "filetype": "bam",
                    "filesize": 1727131568,
                    "filenumber": 1,
                    "md5": "a45af2ada247b38c6593022a627bf371",
                    "urltype": "ftp",
                    "url": "ftp://ftp.sra.ebi.ac.uk/vol1/run/SRR104/SRR10428400/GM12878.rep1.rna.noRG.bam"
                },
                {
                    "accession": "SRR10428400",
                    "filename": "GM12878.rep1.rna.noRG.bam.bai",
                    "filetype": "bam",
                    "filesize": 7036856,
                    "filenumber": 1,
                    "md5": "c95c02e9470211b6c118143bbe6f614c",
                    "urltype": "ftp",
                    "url": "ftp://ftp.sra.ebi.ac.uk/vol1/run/SRR104/SRR10428400/GM12878.rep1.rna.noRG.bam.bai"
                }
            ],
            "aws": [
                {
                    "accession": "SRR10428400",
                    "filename": "GM12878.rep1.rna.noRG.bam.1",
                    "filetype": "bam",
                    "filesize": null,
                    "filenumber": 1,
                    "md5": null,
                    "urltype": "aws",
                    "url": "s3://sra-pub-src-13/SRR10428400/GM12878.rep1.rna.noRG.bam.1"
                },
                {
                    "accession": "SRR10428400",
                    "filename": "SRR10428400",
                    "filetype": "sra",
                    "filesize": null,
                    "filenumber": 1,
                    "md5": null,
                    "urltype": "aws",
                    "url": "https://sra-pub-run-odp.s3.amazonaws.com/sra/SRR10428400/SRR10428400"
                }
            ],
            "gcp": [
                {
                    "accession": "SRR10428400",
                    "filename": "GM12878.rep1.rna.noRG.bam.1",
                    "filetype": "bam",
                    "filesize": null,
                    "filenumber": 1,
                    "md5": null,
                    "urltype": "gcp",
                    "url": "gs://sra-pub-src-9/SRR10428400/GM12878.rep1.rna.noRG.bam.1"
                },
                {
                    "accession": "SRR10428400",
                    "filename": "SRR10428400.1",
                    "filetype": "sra",
                    "filesize": null,
                    "filenumber": 1,
                    "md5": null,
                    "urltype": "gcp",
                    "url": "gs://sra-pub-run-2/SRR10428400/SRR10428400.1"
                }
            ],
            "ncbi": []
        }
    }
}
```
