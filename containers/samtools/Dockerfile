# If you want to use this container, it is simpler to just pull it:
#   docker pull leandroishilima/variant_callers_pipeline_samtools:pandora_paper_tag1

# This container has subsampling software to be used by the pandora_analysis_pipeline
# to build: sudo docker build . -t leandroishilima/variant_callers_pipeline_samtools:pandora_paper_tag1
FROM biocontainers/biocontainers@sha256:c6f082f5658c6d31a5ccb537289d1ce777f51b7285c465fe0efa219058471c81

RUN conda install -c conda-forge -c bioconda samtools==1.10 bwa==0.7.17 bcftools==1.10.2
