# Analysis of Agile Snails' and Team 7564616D's performance

This repository provides a notebook that does a cursory analysis
of last years' two teams' relative performance.

## Setup

* Clone this repository, including fetching the submodules

      $ git clone --recurse-submodules https://github.com/CDT-AIMLAC/coding-challenge-2022_23-task1

* Change directory into the cloned repository

      $ cd coding-challenge-2022_23-task1

* Download the sample data (not linked for licensing reasons) and extract
  into a `coding_challenge_2022-23_data` directory

* Create a conda environment based on the provided specification

      $ conda env create -f environment.yml


## Usage

The notebook can be opened from the Jupyter UI.

On first execution,
the Agile Snails solution will require a significant amount of time
to generate the data to analyse.
(~30 minutes on a single core.)
This will be cached to disk to avoid delays if restarting the kernel is required.


## Caveats

This solution is provided on a best-effort basis,
and has significant limitations.
Some,
but not all,
of these are highlighted with `# TODO` comments.
