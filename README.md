# Training_ANN_with_Pytorch
 This repo aims to train neural networks with pytorch. The data are normalized insede the class. The validation is performed automatically. The output model gets the unscaled data and returns the output unscaled (The scaling is performed inside). This way the user do not interact the scaling,; however the user can select to not use the default scaling and scale the data before the training


# Foobar

Foobar is a Python library for dealing with word pluralization.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install -i https://test.pypi.org/simple/ simpleTorch
```

## Usage
A more detailed example in example_of_usage.ipynb
```python
# X array with inputs in np
# F labels in np
# model is the neural net written in pytorch
import simpleTorch.train_ann
train_ann(model, X, F,plot=True)

```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
