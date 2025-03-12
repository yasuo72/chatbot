# 🤖 Neural Chatbot - Your AI Companion

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Latest-orange)
![NLTK](https://img.shields.io/badge/NLTK-Latest-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 🌟 Overview

Welcome to the Neural Chatbot project - a sophisticated AI-powered conversational agent built with cutting-edge deep learning technologies. This chatbot utilizes natural language processing and neural networks to understand and respond to user queries intelligently.

## 🚀 Features

- **Neural Network Architecture**: Custom-built feed-forward neural network using PyTorch
- **Natural Language Processing**: Advanced text processing using NLTK
- **Intent Recognition**: Sophisticated pattern matching and intent classification
- **Customizable Responses**: Easy-to-modify response patterns via JSON configuration
- **Real-time Chat**: Interactive command-line interface for seamless conversation
- **Web Interface**: Flask-based web application for a modern chat experience

## 🛠️ Technology Stack

- **PyTorch**: For neural network implementation and training
- **NLTK**: Natural Language Processing tasks
- **Python**: Core programming language
- **Flask**: Web application framework
- **JSON**: Intent and response configuration

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/neural-chatbot.git
cd neural-chatbot
```

2. Install required packages:
```bash
pip install torch nltk flask
```

3. Download required NLTK data:
```python
import nltk
nltk.download('punkt')
```

## 🎯 Usage

### Training the Model

```bash
python train.py
```

### Starting the Chat Interface

```bash
python chat.py
```

### Running the Web Application

```bash
python app.py
```

## 🧠 How It Works

1. **Text Processing**: 
   - Tokenization of user input
   - Bag-of-words representation
   - Pattern matching

2. **Neural Network**:
   - Input Layer: Matches vocabulary size
   - Hidden Layer: Customizable neurons
   - Output Layer: Matches number of classes

3. **Response Generation**:
   - Intent classification
   - Probability threshold checking
   - Random response selection from matched intent

## 📁 Project Structure

```
neural-chatbot/
├── train.py         # Model training script
├── chat.py         # CLI chat interface
├── app.py          # Flask web application
├── model.py        # Neural network architecture
├── nltk_utils.py   # Text processing utilities
├── intents.json    # Training data and responses
├── data.pth        # Trained model data
└── templates/      # Web interface templates
```

<h1 align="center">Screenshots</h1>

<p align="center">
  <img src="https://github.com/yasuo72/assests/blob/main/Screenshot%202025-03-12%20092120.png" width="30%" alt="Image 1">
</p>

## ⚙️ Configuration

Modify `intents.json` to customize:
- Chat patterns
- Response templates
- Training data

## 🔮 Future Enhancements

- [ ] Multi-language support
- [ ] Sentiment analysis integration
- [ ] Voice interface
- [ ] Context awareness
- [ ] Dynamic learning capabilities

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📫 Contact

For any queries or suggestions, please open an issue in the repository.

---

<div align="center">
Made with ❤️ and 🤖
</div>
