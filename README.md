#Consensus-Blockchain2018-Nomas
![alt text](.png)

Nomas is an application that leverages modern Blockchain and Smart Contract technologies to make a platform where cloud provider services can be shareds. Our platform utilizes DeepChem and PyTorch libraries to determine if both parties are engaging fair practices with one another. 

# Example
The python module can be used via command-line arguments.
This requires installing deepchem, and all it's dependencies

calling `'python -h'` will give information
about the command-line arguments
example python call:
`'python --filename 'finaldata.csv'`
`--split_method='index'`
                                         `--training_fraction 0.6` 
                                         `--testing_fraction 0.2`
                                         `--validation_fraction 0.2`
                                         `--confusion_matrix`
                                         `--bbbp_split 0.5 --generate'`

Note: any data for training or predicting must be located in the 'bbbdata' directory.
Note: data must be in the csv format, and include collumn headers: 'smiles' and 'bbb' 

# Try it!
Take a look at our Beta web app [HERE!]()
