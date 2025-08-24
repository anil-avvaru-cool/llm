## Tokenization
- Read book or any source
- Split
- Assign ids called Tokens for all the words which is called vocabulary
- encode
- decode

## Tokenizer types
- Word based: problem boy and boys, root word is missing
- sub word based example: Byte pair encoding
- Character based

## Byte Pair Encoding(BPE)
- Retain root words and character level tokens
- Reduces the size of the vocabulary
- Iteration stopping will be based on token count or iterations

tiktoken is open source for BPE
https://github.com/openai/tiktoken

## Input target pairs

## Auto regressive/Unsupervised learning/self supervised learning:
 output of the previous iteration is fed as input to the next iteration

 ## Context size
 How many words the input should contain to predict the next word

 ## Stride
 Number of right shift/Sliding window

