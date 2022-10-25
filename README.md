# Toolbox

Small scripts and bits which you might find useful.

## Contents

+ Indexing genomes

## Indexing genomes

It seems like every package you use in genomics needs to index a genome in its own special way.
This set of scripts aims to make it easier to work with them, by doing the prep for most common packages at once.

In the Indexing-genomes directory, there are two scripts: a standard Bash script for running these on a home machine, and a Slurm script which is designed to run on Rocket.

### Usage
./index-genome.sh genome.fasta

or

sbatch index-genome.slurm genome.fasta

## Copyright

This Source Code Form is subject to the terms of the Mozilla Public
License, v. 2.0. If a copy of the MPL was not distributed with this
file, You can obtain one at https://mozilla.org/MPL/2.0/.

