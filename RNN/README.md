# RNNpresentation: A presentation about Recurrent Neural Network.

![alt text](gifs/cc-logo.png "CC")


Licensed under [creative commons](https://github.com/felipessalvatore/RNNpresentation/blob/master/LICENSE)

I create [these slides](https://mlime.github.io/files/introduction-recurrent-neural.pdf) together with [@thiagopbueno](http://thiagopbueno.github.io/) for a seminar at USP to explain recurrent neural networks.


## Back Propagation Visualizations

<table style="width:100%">
  <tr>
    <td><img src="/gifs/RnnBackprop.gif"></td>
    <td><img src="/gifs/BPTT.gif"></td>
    <td><img src="/gifs/exploding.gif"></td>
    <td><img src="/gifs/vanishing.gif"></td>
  </tr>
  <tr>
    <td>Back propagation in one time step</td>
    <td>Back propagation through time (BPTT)</td>
    <td>Exploding gradient</td>
    <td>Vanishing gradient</td>
  </tr>
</table>


## Usage

You can find the pdf of the presentation in the folder /src/pdf. But if you want to compile the latex file just run:

```
$ cd src/
$ make
```


