### nni_examples

- reference code for nni
  - https://github.com/microsoft/nni
  - nnictl : https://github.com/microsoft/nni/blob/master/docs/en_US/Tutorial/Nnictl.md
  - config.yml : https://github.com/microsoft/nni/blob/master/docs/en_US/Tutorial/ExperimentConfig.md#logdir
  - search_space.json : https://github.com/microsoft/nni/blob/master/docs/en_US/Tutorial/SearchSpaceSpec.md
  - mnist pytorch example
    - https://github.com/microsoft/nni/tree/master/examples/trials/mnist-pytorch
    - https://github.com/microsoft/nni/blob/master/examples/trials/mnist-pytorch/mnist.py

- usage
```
$ nnictl create --config config.yml --port 22968 --foreground

$ nnictl trial ls

$ nnictl tensorboard start
```
