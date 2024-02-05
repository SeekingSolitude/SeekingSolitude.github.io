---
layout: post
title:  "Quantum Computing: Programming the Quantum Dice"
categories: [ Jekyll, tutorial ]
image: assets/images/quantumdice.png
---
The power of quantum computing comes from the superposition of states which allows us to do computation in parallel. From an input of 1 qubit, we can do parallel computation of 2 integers (0 and 1). From an input of 2 qubits, we can do parallel computation of 4 numbers (0, 1, 2, 3) and so on. In general, for an n number, we can do parallel computation of <math xmlns="http://www.w3.org/1998/Math/MathML">
  <msup>
    <mn>2</mn>
    <mi>n</mi>
  </msup>
</math>

A quantum computer allows us to simulate easily the roll of a dice. Imagine, for the sake of simplicity, say we have a 4-faced honest die with faces 0, 1, 2 ,3. Since there are 4 faces, the probability of getting any face is 1/4.