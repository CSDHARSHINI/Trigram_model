**Build an N-Gram Language Model**

The implementation is the real test. The design of clean and efficient system from scratch.

How do we store the n-gram counts (e.g., a nested dictionary like counts[w1][w2][w3])?
How do we handle text cleaning, padding, and unknown words?
The hardest part is the generate function. I must correctly convert counts to probabilities and then probabilistically sample from that distribution (not just pick the single most-likely word).

The ideal source for this is Project Gutenberg, which offers thousands of free, public-domain e-books.

We recommend using one of these classic (and popular for NLP) books. They are large enough to produce interesting results but small enough to train quickly. 
**1. Alice's Adventures in Wonderland by Lewis Carroll
2. Pride and Prejudice by Jane Austen
3. Frankenstein Or The Modern Prometheus by Mary Wollstonecraft Shelley
4. A Tale of Two Cities by Charles Dickens**
