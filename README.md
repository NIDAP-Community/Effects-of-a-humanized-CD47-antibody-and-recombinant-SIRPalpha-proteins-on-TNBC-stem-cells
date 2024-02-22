# Effects-of-a-humanized-CD47-antibody-and-recombinant-SIRPalpha-proteins-on-TNBC-stem-cells

This code accompanies the paper entitled: "Effects of a humanized CD47 antibody and recombinant SIRPalpha proteins on triple negative breast carcinoma stem cells" (CCBR-699)


To reproduce these results, follow these steps:

1.  Clone this GitHub repo (i.e. the page you are on):
    * ```git clone https://github.com/NIDAP-Community/Effects-of-a-humanized-CD47-antibody-and-recombinant-SIRPalpha-proteins-on-TNBC-stem-cells.git```

2.  The input files for this pipeline will be available upon request. Please reach out to the authors before continue to following steps

3.  Install docker and build the docker container:
    * Navigate to the cloned repository directory. 
    * Move to the ./Docker_file/ directory of this repo

4.  Build the container:
    * ```docker build --tag Effects-of-a-humanized-CD47-antibody-and-recombinant-SIRPalpha-proteins-on-TNBC-stem-cells .```

5.  Navidate to the cloned repository directory, Run the conainer by mounting the ./src/ directory of the repo to /tmp/ in the container:
    * ```docker run -ti -v $(pwd)/src:/mnt Effects-of-a-humanized-CD47-antibody-and-recombinant-SIRPalpha-proteins-on-TNBC-stem-cells```
    
6.  Run the following code.
    * ```cd /mnt```
    * ```bash run_pipeline.sh```

This repository is the location Josh will extract CCBR-699 to.

The final R3 extraction branch for this project is found here:

https://nidap.nih.gov/workspace/vector/view/ri.vector.main.workbook.19324ee7-7869-4b9e-88a4-2e77f2f41199?branch=Cg_and_Si_Co-Analysis_R3
