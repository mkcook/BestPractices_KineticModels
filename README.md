# Best practices in publishing kinetic metabolic models 

This repository contains the source code and necessary files to generate metabolic map visualizations using [SBMLNetwork], as described in our paper published in *[PLOS Computational Biology]*.

## Requirements

This project requires Python 3.9 and Jupyter Notebook. The following Python libraries must also be installed:

- `pandas` (v2.3.0)
- `tellurium` (v2.2.9)
- `sbmlnetwork` (v0.5.8)
- `biopython` (v1.83)
- `scipy` (v1.15.3)

You can install them using `pip`:

```bash
pip install pandas==2.3.0 tellurium==2.2.9 sbmlnetwork==0.5.8 biopython==1.83 scipy==1.15.3
```

## Files

 - `runSBMLNetwork.ipynb`: Jupyter Notebook that runs SBMLNetwork to generate metabolic map diagrams.
 - `SI_4_FullyAnnotatedAntimony_kegg.txt`: Annotated Antimony file of the metabolic model.
 - `ko01100.xml`: XML file with species and reaction coordinates from KEGG's metabolism map.
 - `kegg_labels_add.csv`: Rosetta stone for translating between KEGG IDs and human-readable labels.
 - `Reactions_M3_B_ordered.csv`: Reaction list used to build the metabolic model.

## Use

Clone the repository using:
```bash
 $ git clone `https://github.com/mkcook/BestPractices_KineticModels.git
```
Or download the ZIP archive and extract it.

Then open `runSBMLNetwork.ipynb` in Jupyter Notebook or a compatible editor and run the notebook cells in order.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

   [PLOS Computational Biology]: <placeholder>
   [SBMLNetwork]: <https://www.biorxiv.org/content/10.1101/2025.05.09.653024v1>
