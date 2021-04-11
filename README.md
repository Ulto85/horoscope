# Understand:
## Description:
Understand is a tool used to easily recognize intent based on training data. Visit the [site](https://ulto4.pythonanywhere.com) for more details

## Basic Usage:
```python
from understand import Understand
model = Understand() #Initialize the model
model.fit() #Fits model based off training.json
model.predict('text') to predict text

```
