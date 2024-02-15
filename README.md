# MaithiliNMT: An Open-Source Neural Machine Translation Framework for the Maithili Language

## Description
MaithiliNMT aims to bridge the digital language divide by providing a robust, open-source Neural Machine Translation (NMT) framework specifically for the Maithili language, spoken by millions in India and Nepal. This project leverages the latest advancements in NMT and unsupervised learning to create high-quality translation models that require minimal bilingual data, focusing on enhancing digital accessibility and preserving the linguistic heritage of the Maithili-speaking community.

## Features
- **Unsupervised Learning Approach**: Utilizes cutting-edge unsupervised learning techniques to train models with limited parallel corpora.
- **Lexical Data Augmentation**: Incorporates bilingual lexicons to improve translation accuracy, especially for low-resource languages.
- **Community-Sourced Data**: Leverages data collected and validated by the Maithili-speaking community to ensure relevance and accuracy.
- **Open-Source**: Encourages collaboration and further development within the open-source community.

## Getting Started

### Prerequisites
- Python 3.8 or higher
- PyTorch 1.8.0 or higher
- Transformers library by Hugging Face
- Access to a GPU for training (optional but recommended)

### Installation
1. Clone the repository:
   
```
git clone https://github.com/abhisekjha/MaithiliNMT.git
```

3. Install the required dependencies:
```
pip install -r requirements.txt
```

### Training Your Model
1. Prepare your dataset by following the instructions in the `data_preparation` folder.
2. To start training your model, run:
```
python train.py --config_path configs/train_config.yaml
```
## Usage
For translating text using a pre-trained model:
```
python translate.py --input_text "Your Maithili text here" --model_path "path/to/your/model"
```

## Contributing
We welcome contributions from the community! Please read our contributing guidelines in `CONTRIBUTING.md` for details on how to submit pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

## Acknowledgments
- The Maithili-speaking community for their invaluable contributions and feedback.
- Open-source projects and researchers in the field of NMT for their groundbreaking work and inspiration.

