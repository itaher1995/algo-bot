# algo-bot

This is a repository for algorithmic trading. The goal is to get this to automatically make trades on certain brokerages (i.e. Fidelity.)

## Directory Structure

* `algo-bot` is a folder where all the functions for the algorithmic trading bot will exist.
* `data` is a folder where the immutable datasets will exist. The long term plan is to deprecate this folder and leverage storage on the cloud (i.e. S3).
* `jobs` is the folder that will house the major tasks. These major tasks are generally sourced from the `algo-bot` folder. During development and deployment, all jobs that are necessary will be referenced by scripts in this folder.
* `outputs` is a folder where outputs of our processes will go. Depending on the type of output it may be a temporary output that will be developed when the job is completed.
