# Penguin Species Prediction in Maya

This repository contains the resources for an interactive tutorial on using a Machine Learning model within Autodesk Maya to predict penguin species based on various attributes.

## Resources

- **Dataset**: Located in the `dataset` folder, the file `penguins-clean-all.csv` is derived from the Palmer Penguins dataset. It contains measurements for three penguin species: bill length, bill depth, flipper length, and body mass.
  
- **Maya Rig**: Inside the `rig` folder, you'll find `penguin.ma`. It's a rigged Maya model of a penguin. This rig allows users to adjust specific attributes of the penguin, such as flipper length, bill length, bill depth, weight, and size. Using these attributes, the provided Python script predicts which of the three penguin species the model most closely resembles.

## Instructions

1. **Clone the Repository**:  

```bash
git clone https://github.com/BramVR/penguinFiles.git
```

2. **Dataset**:  
Navigate to the `dataset` folder and open `penguins-clean-all.csv` to view the Palmer Penguins dataset. This renowned dataset provides insights into three species of penguins found on a few islands in Antarctica:
- Adelie
- Gentoo
- Chinstrap

3. **Maya Rig**:  
In the `rig` folder, load the `penguin.ma` file in Maya. This rig has been tailored to adjust attributes that directly correspond with the dataset. Alter the attributes and use the Python script to predict the species based on your modifications.

4. **Python Script**:  
The script employs a pre-trained Machine Learning model to predict the penguin species based on the attributes you set in the Maya rig.

5. **Visualization**:  
As you adjust the rig's attributes, the script will give you a prediction of which species the current configuration most closely matches. This interactivity aids in comprehending the relationship between the attributes and the penguin species.

6. **Tutorial**:  
For a detailed walkthrough on setting up and using these resources, visit the tutorial on [Neural Net in Maya](https://bvr.pages.dev/posts/neural_net_in_maya/).

## Contributing

If you identify any bugs or wish to suggest improvements, please open an issue or submit a pull request.
