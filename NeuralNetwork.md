Machine Learning is basically finding patterns in data.

A simple prediction problem


Machine learning in one sentence:


Trying with a guess 

Measure error

Adjust

Repeat


The Neuron: A tiny decision maker

it does 3 things

1. It takes input   eg house size in sq ft
2. Multiplies it by a weight
3. Sum all the weighted inputs
4. Add a bias
5. Applies an activation function to the sum
6. Output the result



Why do we need activation function?

The linearity problem --> Stacking different layers will only result in a linear equation


Words can be represented as a vector of numbers --> Word Embedding

Still word embeddings process each word as a separate entity --> need to process them as a sequence 

Process each word in a sentences as you go (i.e building the understanding of the sentence as you go) --> RNN (Sequence models)

The above works for smaller sentences. As the sentences becomes longer and longer the above approach becomes too slow. To solve this problem we use Transformers.

The transformer idea --> Look at the entire sentence at once and understand the context of the sentence.
The secret of transformer is attention mechanism.--> attending only to relavant words in a sentence.

It can be extended to images by using a self attention mechanism.[Image Transformer]

Also can be extended to audio by using a self attention mechanism.[Audio Transformer]

LLM and SLM are based on transformers.

Transformer is based on self attention mechanism.

HOW chat GPT works ?
Predict the next word in a sentencea and does the same for the next word and so on.

We can scale this to a very large model by using a very large dataset and a very large number of parameters.

Currently in 2026 , Multimodality , Reasning , Agents





