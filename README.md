# char-rnn-keras

Multi-layer recurrent neural networks for training and sampling from texts, inspired by [karpathy/char-rnn](https://github.com/karpathy/char-rnn).


### Usage

All input data should be placed in the `data/` directory. The example `input.txt` is taken from the [Nottingham Dataset (Cleaned)](https://github.com/jukedeck/nottingham-dataset).

To train the model with default settings:
```bash
$ python train.py
```

To sample the model:
```bash
$ python sample.py 100
```

Training loss/accuracy is stored in `logs/training_log.csv`.

Ref link:
https://karpathy.github.io/2015/05/21/rnn-effectiveness/
https://folkrnn.org/
https://abc.sourceforge.net/NMD/
