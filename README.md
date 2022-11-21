# YALE-RESEARCH-WORK

## Ideas for fininte automata

* no edge features as of now.
* 2 node features, 00 for normal, 01 for start state, 11 final state
* Graph has to be connected, how can i ensure that while randomly generating graphs.
* Regression.
* so the outuput is a vector of size same as the string, so the model will output the path taken by the dfa on this string.
* string decided = "001110110101010101111000001010101110100110001001100100111100100001011010000010001101111010100001011011110001010101011111100100110111000011010001111000011001000000100000100";
* string length reduced.

## Issues

* edge features only for some layers in which they are needed.
* Some layers only accept adjaceny matrix so it should have some weight in there.
* overall loss is ok but YES/NO is only 60% accuracy.
* So maybe we can increase the weight of the last element for the output vector.


