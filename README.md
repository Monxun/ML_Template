# ML_Project_Template
Boilerplate for ML Projects

# Steps:

1. Place data files for model in input folder
2. Update src/config.py with paths, models, other params
3. Add models to model_selector.py

- Perform exploration using notebooks in notebook directory
- Trained models are saved to models directory by default
- Use run.sh to take advantage of argparse 

# Commands:

# move to src directory
cd /src/

# create folds
python create_folds.py --folds 5

# train model
python train.py --fold 0 --model decision_tree_entropy
