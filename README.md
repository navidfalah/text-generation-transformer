# 🐍 Text Generation with Transformers

## 📝 Description
This Python script demonstrates **text generation** using transformer models like **GPT-2**. It explores various decoding strategies, including **greedy search**, **beam search**, **top-k sampling**, and **nucleus sampling (top-p)**. The script also calculates the log-probability of generated sequences to evaluate their quality. 🛠️

---

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/navidfalah/text-generation-transformers.git
   cd text-generation-transformers
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Install additional libraries:
   ```bash
   pip install torch transformers
   ```

---

## 🚀 Usage

1. Run the script:
   ```bash
   python text_generation_transformers.py
   ```

2. The script will:
   - Load the GPT-2 model and tokenizer.
   - Generate text using different decoding strategies.
   - Calculate and display the log-probability of generated sequences.
   - Compare the outputs of greedy search, beam search, top-k sampling, and nucleus sampling.

---

## 📂 File Structure

```
text-generation-transformers/
├── text_generation_transformers.py  # Main script
├── README.md                        # This file
├── requirements.txt                 # Dependencies
└── data/                            # (Optional) Data folder for local inputs
```

---

## 🧩 Key Features

- **Text Generation**:
  - Use GPT-2 for text generation with various decoding strategies.
  - Generate text from a given input prompt.

- **Decoding Strategies**:
  - **Greedy Search**: Selects the most likely token at each step.
  - **Beam Search**: Explores multiple sequences to find the most likely output.
  - **Top-k Sampling**: Samples from the top-k most likely tokens.
  - **Nucleus Sampling (Top-p)**: Samples from the smallest set of tokens whose cumulative probability exceeds `p`.

- **Log-Probability Calculation**:
  - Calculate the log-probability of generated sequences to evaluate their quality.

---

## 📊 Example Outputs

1. **Greedy Search**:
   - Input: "4+5="
   - Output: "4+5=9"

2. **Beam Search**:
   - Input: "In a shocking finding, scientist discovered a herd of unicorns..."
   - Output: "In a shocking finding, scientist discovered a herd of unicorns living in a remote, previously unexplored valley, in the Andes Mountains..."

3. **Top-k Sampling**:
   - Input: "In a shocking finding, scientist discovered a herd of unicorns..."
   - Output: "In a shocking finding, scientist discovered a herd of unicorns living in a remote, previously unexplored valley, in the Andes Mountains..."

4. **Nucleus Sampling (Top-p)**:
   - Input: "In a shocking finding, scientist discovered a herd of unicorns..."
   - Output: "In a shocking finding, scientist discovered a herd of unicorns living in a remote, previously unexplored valley, in the Andes Mountains..."

---

## 🤖 Models Used

- **GPT-2**: A generative pre-trained transformer model for text generation.

---

## 📈 Performance Metrics

- **Log-Probability**: Measures the likelihood of the generated sequence.

---

## 🛠️ Dependencies

- Python 3.x
- Libraries:
  - `torch`, `transformers`
  - `numpy`, `pandas`

---

## 🤝 Contributing

Contributions are welcome! 🎉 Feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m "Add your feature"`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a pull request.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Hugging Face for the `transformers` library.
- OpenAI for the GPT-2 model.

---

## 👤 Author

- **Name**: Navid Falah
- **GitHub**: [navidfalah](https://github.com/navidfalah)
- **Email**: navid.falah7@gmail.com
