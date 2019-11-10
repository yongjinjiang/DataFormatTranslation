# About
Neural Machine Translation (NMT) model can be used to map from one sequence to another. They are useful not just for translating human languages (like French->English) but also for tasks like date format translation. Using the so-called attention mechanism in NMT can significantly improve the performance of NMT. In this project, we built a NMT in which the attention mechanism is included, together with one layer of Bidirectional LSTM (before attention) and one layer of LSTM (after attention). This model was trained from scratch with a training set of 10000 pairs of (human readable date, the machine-readable date). Since attention mechanism is intuitively in accordance with the way that human neural system works in cognitive process. It’s great to visualize how the attention mechanism really work in our model by plotting the attention function!  Core packages used:  [keras](https://keras.io/),  [numpy](https://numpy.org/),  [Fake](https://github.com/joke2k/faker).
