## Covid Hospitalization Assessment

Covid Hospitalization Assessment using Machine Learning Methods (Decision Tree, CNN, MLP)

Project developed as part of the Machine Learning course lectured by Professor Jorge Henriques at the University of Coimbra in the academic year of 2024/2025

#

### Data Used
Data provided by the Professor.

**COVID_IMG**: 600 entries, each entry corresponding to a 21x21 image

**COVID_numerics**: 600 entries, 8 variables (scalars) + targets

#

### Code organization
**DecisionTree**: Filter and identify the most relevant features from the dataset using a Decision Tree algorithm.

**CNN**: Combination of CNN (images) + MLP (numerical data) concatenated models to decide whether the individual should remain hospitalized or be discharged to return home.
This model uses all available variables for decision-making.

**CNN_filtered**: Similar to the CNN model above, but only using the most relevant features identified by the DecisionTree algorithm.

_**Note**: CNN and CNN_filtered models are, in fact, hybrid models._

#

### Development History

This repository keeps a record of all the main changes made throughout the development of the models (pre-processing, fine-tuning, addition of rules, etc.), including the results of the models at each stage.

The final models and results before applying the rule are also available on the "before_rule" folder in this repository.

