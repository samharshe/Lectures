# making sure i understand well the seminal paper.
### https://arxiv.org/abs/1706.03762

### [Attention Is All You Need](https://www.youtube.com/watch?v=iDulhoQ2pro)
i need to review RNN and LSTM architecture.

old-fashioned way: each word's encoder + the previous hidden state gives a prediction for the next hidden state.
you get your last hidden state and put it into a decoder along with the last output of the decoder to get the next output.
sure.

### [Recurrent Neural Networks (RNNs), Clearly Explained!!!](https://www.youtube.com/watch?v=AsNTP8Kwu80)
interlude: i learn RNN architecture better. the explanation in the previous video was bad.
we want an RNN to be flexible in terms of the amount of data it needs to make a prediction.

ok i remember all this reasonably well.

end interlude.

how well does translation work based on explicit encoding of the grammar of langauges? SVO -> OVS; x -> x'; and so on? this has certainly been tried but it would be a fun experiment still.

this video is boring. i'm going straight to Karpathy's code-along. 8:49.