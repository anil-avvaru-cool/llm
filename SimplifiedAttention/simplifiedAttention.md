## Simplified Attention

Embedding vector -> Context vector

## Calculation of alignment/similarity of vectors
 dot product of vector


## Step 1 Compute Attention scores
 Dot product of the input/query with respect to other words/elements

## Step 2 Compute Attention weights 
Normalize attention scores to sum up to one.
Normalization is useful to intuitive way of expressing in percentages.

## Step 3 Compute context vectors
Multiply each input vector with corresponding attention weights
Weighted sum of the scaled vectors

## Self attention 

## Why Normalization
- For intuition with percentages
- For computing back propagation

## Key, query, value 

- Convert to 2d matrices

## Normalization of key, query, value
- scale by square root of keys dimension
- softmax

