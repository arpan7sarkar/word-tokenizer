# Vocabulary for Subword Tokenizer

The vocabulary is dynamically generated as text is processed. It contains:
The vocabulary used in the Subword Tokenizer is dynamically generated as text is processed. Below is an example of how the vocabulary is built and structured:

- **Character Tokens**: Each unique character encountered in the input text.
- **Word Tokens**: Whole words.
- **Subword Tokens**: Subwords generated using a greedy algorithm.
## Vocabulary Structure
- **Character Tokens**: Each unique character encountered in the input text is added to the vocabulary. This ensures that any text can be tokenized, even if it contains uncommon characters.

The vocabulary can be viewed or reset through the user interface.
- **Word Tokens**: Whole words are also added to the vocabulary. This allows the tokenizer to recognize and tokenize entire words when possible, improving efficiency.

- **Subword Tokens**: The tokenizer breaks down words into subwords using a greedy algorithm. Each subword is added to the vocabulary.

## Vocabulary Management

The vocabulary is managed using a `Map` in JavaScript, where each token (character, word, or subword) is associated with a unique identifier. The identifiers are generated sequentially as new tokens are added.

### Example Vocabulary

Here's a simple example of what the vocabulary might look like after processing some text:

```javascript
{
  ''
{
  0: '',
  1: 'h',
  2: 'e',
  3: 'he',
  4: 'l',
  5: 'hel',
  6: 'hell',
  7: 'o',
  8: 'hello',
}
```

In this example, both individual characters and entire words are present in the vocabulary, allowing the tokenizer to flexibly handle various inputs.

## Dynamic Vocabulary Expansion

As more text is processed, new tokens are added to the vocabulary. This allows the tokenizer to adapt to new words and subwords as they are encountered.

## Usage

The vocabulary can be viewed or reset through the user interface, providing insights into how text is being tokenized and allowing for experimentation with different input texts.
