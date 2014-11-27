repetitive-spirit-inquiry
=========================

Calculate the optimal layout for a ouija board based on English words, to reduce spiritual RSI

Uses top 5000 english words by frequency to calculate most common letter-pairings, then
uses simulated annealing to calculate an optimal(ish) layout, minimising the distance for
the most most common pairs.

Output is an HTML file with embedded SVG.