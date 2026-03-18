

# Lecture 6: RNNs
## GRU:
update (z)  + reset (r)
weighted avg based on z (update gate)
(-) less powerful compared to LSTM, why?
keep value in a bounded magnitude (not suitable for counting for example)
(+) faster at training tho


What are the advantages of using LSTMs and GRUs (over vanilla RNNs)
less severe on vanishing gradients. (depending on the forget gate)

disadvantages:
#parameters -> more data

# Lecture 7: Sequence to sequence
What other tasks might have this property ?
translation, code generation, image captioning

for bidirectional? do we have double dimension? no, we can just have another projection matrix

but for multi - modal we need dataset where there is pair of training data

**back prop happens through both decoder + encoder
