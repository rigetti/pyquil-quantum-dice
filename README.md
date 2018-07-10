# pyquil-quantum-dice

_Getting started with PyQuil: Quantum Dice example_

These examples are based on Dave Yen's blog post: ["How to write a quantum program in 10 lines of code (for beginners)"](https://medium.com/rigetti/how-to-write-a-quantum-program-in-10-lines-of-code-for-beginners-540224ac6b45).


## Running these notebooks in the cloud

To run these example notebooks using http://mybinder.org, go to http://go.rigetti.com/quantum-dice.


## Installing locally

You can also install run the notebooks on your laptop. To create a virtual environment, run:
```
conda env create -n pyquil-demo -f environment.yml
```

This will install all dependencies, such as `pyquil`.

To activate the environment, run:
```
conda ativate pyquil-demo
```

To start the jupyter notebook server, run:
```
jupyter notebook
```

This starts the notebook server, so you can run the example code in the notebooks. Have fun!