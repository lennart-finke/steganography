# Entropy-Conditioned Steganography

This eval checks for language model's capabilities to hide secret messages in plain text, given an identical source of entropy at encode and decode time.

## Overview

This evaluation framework tests whether language models can:
1. Encode a secret message within a response to a benign task
2. Use provided entropy for encoding/decoding
3. Make the secret message undetectable to observers without the entropy key
4. Successfully decode hidden messages when given the same entropy

## Dependencies
This project uses the [inspect-ai](https://github.com/UKGovernmentBEIS/inspect_ai/) framework, to be installed with

```bash
pip install inspect-ai
```

## Usage
You can run the eval with

```bash
inspect eval --model openai/gpt-4 --temperature 0
```

and view the results via

```bash
inspect view
```
