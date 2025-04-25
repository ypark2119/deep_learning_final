# Deep_Learning_Final - Bridging Languages with Deep Learning: Building a Korean-English Translator
By Eunice Tu & Yewon Park

### Project Proposal:
**Objective and Goals:** The objective of this project is to build a deep learning-based language translation model that can accurately translate text from one language to another. Specifically, the project will focus on developing a sequence-to-sequence (Seq2Seq) model using recurrent neural networks (RNNs), attention mechanisms, or Transformer architectures. The goal is to improve translation quality by leveraging modern deep learning techniques, enabling more fluent and context-aware translations compared to traditional rule-based or statistical methods.

**Problem Statement:** Language translation is a big challenge in NLP, especially since it plays a huge role in global communication, education, and business. Traditional translation tools often mess up the context, struggle with idioms, and don’t always get the grammar right when switching between languages. By using deep learning like neural machine translation, we can better understand long-term patterns in language and improve accuracy, making translations sound more natural and fluent.

**Approach:** We plan to use an encoder-decoder architecture as the core framework for our translation model. We will experiment with both LSTM-based Seq2Seq models with attention and Transformer-based models (such as a simplified version of the Transformer architecture used in Google’s translation system). The training process will involve feeding parallel sentences and optimizing the model to minimize translation loss.


### Data Source: 
We will use the AI Hub Korean-English Parallel Corpus, a high-quality dataset provided by the Korean government. It includes professionally translated sentence pairs across various domains such as news, spoken dialogue, legal documents, IT, and patents. Suitable for our project because:
- It contains well-aligned, clean, and diverse Korean-English sentence pairs.
- It covers both formal and informal language, which helps train a more robust translation model.
- It is large enough (~1 million+ pairs) to support deep learning models.
