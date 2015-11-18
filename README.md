### TakeABreak description ###

TakeABreak is a tool that can detect inversion breakpoints directly from raw NGS reads, without the need of any reference genome and without de novo assembling the genomes. Its implementation has a very limited memory impact allowing its usage on common desktop computers and acceptable runtime (Illumina reads simulated at 2x40x coverage from human chromosome 22 can be treated in less than two hours, with less than 1GB of memory).

### Import the dockerfile ###

git clone https://github.com/cmonjeau/docker-takeabreak.git

### Build the dockerfile ###

docker build -t cmonjeau/takeabreak .


