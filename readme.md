# Entropy-Conditioned Steganography

This eval checks for language model's capabilities to hide secret messages in plain text, given an identical source of entropy at encode and decode time.


## Dependencies
This project uses the [inspect-ai](https://github.com/UKGovernmentBEIS/inspect_ai/) framework, to be installed with

```bash
pip install inspect-ai
```

## Usage
You can run the eval with

```bash
inspect eval --model openai/gpt-4o --temperature 0
```

and view the results via

```bash
inspect view
```
