# Pokemon Type Matchup 

## Description 

This convolutional neural network classifies pokemons by type, using the training data from the [Complete Pokemon Dataset](https://www.kaggle.com/datasets/rounakbanik/pokemon), the network will classify the the pokemon according to it type weakness and strenghts, and resolve it based on the overall value from these attributes.

## Data Preprocessing

The only relevant data for the neural network are the "against_type", "type2", "type2" columns, the existing types are correlated using a pair of arrays, one containing its integer number and another containing its name.

```
# poke_types_names = ['grass', 'fire', 'water', 'bug', 'normal', 'poison', 'electric', 'ground', 'fighting', 'psychic', 'rock', 'ghost', 'ice', 'dragon', 'flying']  

# poke_types_values = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14]
```

The "types" columns are then converted to a integer value matching the poke_types_values array.

The training/test/validation split are 80/10/10.

## How to use

Access the [Google Colab notebook](https://colab.research.google.com/drive/1dH45FG2RxC90I2I5n3xVGtlpuVHwZYii?usp=sharing#scrollTo=d8qoeSKVW1Mw) and follow the steps given, running each code block sequentially.

## Authors

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/D4Cheap">
        <img src="https://github.com/D4Cheap.png" width="100px;"/><br>
        <sub>
          <b>Matheus Giovanny
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/llaet">
        <img src="https://github.com/llaet.png" width="100px;"/><br>
        <sub>
          <b>Bill Gates
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/fran-0106">
        <img src="https://github.com/fran-0106.png" width="100px;"/><br>
        <sub>
          <b>Franciele</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/GabrielMarques369">
        <img src="https://github.com/GabrielMarques369.png" width="100px;"/><br>
        <sub>
          <b>Gabriel Marques</b>
        </sub>
      </a>
    </td>
  </tr>
</table>
