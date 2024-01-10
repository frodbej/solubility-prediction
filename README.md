This is a reproduction of the work by [Delaney](https://pubs.acs.org/doi/10.1021/ci034243x).

In this project **linear regression** is applied to predict the solubility of molecules. To achieve that we use the SMILES notation of the molecules in order to obtain some molecular descriptors of interest using **rdkit**.

Specifically, the 4 molecular descriptors employed to predict the solubility (LogS) in the linear regression model are:

* cLogP: Octanol-water partition coefficient.
* MolWt: Molecular weigth
* RB: Number of rotatable bonds
* AP: Aromatic proportion = number of aromatic atoms / number of heavy atoms

After building the initial linear regression model, the **pycaret** module is employed to compare the performance of several machine learning models at once.

## Acknowledgments

This project was inspired by the drug discovery series of [dataprofessor](https://github.com/dataprofessor)
