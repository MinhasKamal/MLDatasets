# Titanic

The data set contains passenger information of the “unsinkable” RMS Titanic during her maiden voyage on April 15, 1912.

<img src="https://github.com/user-attachments/assets/c9060133-eeb8-465b-b0a4-096b26870be3" width="300">

## Download
```
wget https://github.com/MinhasKamal/MLDatasets/raw/refs/heads/main/titanic/titanic.csv
```

[inspiration](https://www.kaggle.com/competitions/titanic)

## Variable Notes

**pclass**: A proxy for socio-economic status
1 = Upper
2 = Middle
3 = Lower

**age**: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

**sibsp**: Defines family relations:
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)

**parch**: Defines family relations:
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.
