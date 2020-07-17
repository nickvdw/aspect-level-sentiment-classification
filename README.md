# Aspect-level Sentiment Classification using Document-level Knowledge.

In the notebook, we exploit document knowledge for aspect-level sentiment classification. More specifically, we build an attention-based aspect-level sentiment classification model with biLISTM. The biLSTM network learns sentence representations from input sequences. Additionally, an attention network assigns an attention score over a sequence of biLSTM hidden states based on aspect term representations. Then, a fully connected network predicts the sentiment label.

The model is trained based on transfer learning, i.e., we first train the parameters of a model on document-level examples, and we use the learned parameters to initialize and fine-tune the parameters of the aspect-level model.

This project is based on the work proposed by He et al. in [1].

[1] *R. He, WS. Lee & D. Dahlmeier. Exploiting document knowledge for aspect-level sentiment classification. 2018.* https://arxiv.org/abs/1806.04346.
