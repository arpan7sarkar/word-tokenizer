# Interactive Subword Tokenizer

Welcome to the Interactive Subword Tokenizer project! This tool allows users to explore subword tokenization interactively. It showcases the tokenization process, vocabulary management, and encoding/decoding of text using a simple web-based interface.

## Features

- **Interactive Tokenization**: Type text and see it tokenized in real-time.
- **Preset Examples**: Load and tokenize preset texts like nursery rhymes, quotes, and tongue twisters.
- **Customizable Vocabulary**: The tokenizer builds and displays its vocabulary as you type.
- **Encoding & Decoding**: Convert text to token IDs and decode them back to text.

## Project Structure

- `index.html`: The main HTML file that defines the structure of the app.
- `style.css`: Custom styles for a clean and modern look using Tailwind CSS.
- `script.js`: JavaScript logic for handling tokenization, event listeners, and UI updates.

## Usage

1. **Open the Project**: Load `index.html` in a web browser.
2. **Type or Paste Text**: In the encoder input, enter the text to tokenize.
3. **View Tokens**: See the subword and numerical tokens generated.
4. **Explore Presets**: Use the dropdown to load and tokenize preset texts.
5. **Reset**: Clear inputs and start over using the reset button.

## Technical Details

- **Subword Tokenizer**: Implemented in JavaScript using a greedy algorithm to break down words into subwords based on a dynamic vocabulary.
- **Vocabulary Management**: Characters, spaces, and words are added to the vocabulary as you type.
- **Responsive Design**: Styled with Tailwind CSS, ensuring the interface is responsive and aesthetically pleasing.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/interactive-subword-tokenizer.git
   ```
2. Navigate to the project directory:
   ```bash
   cd interactive-subword-tokenizer
   ```
3. Open `index.html` in your preferred web browser.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## Acknowledgments

- This project uses [Tailwind CSS](https://tailwindcss.com/) for styling.


Feel free to explore and modify the code to suit your needs. Enjoy tokenizing!
