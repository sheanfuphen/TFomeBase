# TFomeBase
This is a tool meant to enable researchers who have sequencing runs they are interested in conduct basic alignments on them with a single line of code

This pipeline was constructed on the NYU HPC Greene cluster. Modifications may be required for other users.

The current iteration only performs "pseudo"alignments via Kallisto and Salmon

To run:
sbatch kall4one.sbatch -sra SRRXXXXX -cell_id XXXXXX

cell_ids are user inputted and can be anything. However I strongly recommend standardizing your labeling for easier further analysis. i.e. so that M0 macrophages are not treated differently from Unpolarized Macrophages and so on.
