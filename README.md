# NLP-with-HF-Transformers

<h1 align="center"> NLP with Hugging Face Transformers</h1>
<p align="center"> # 🌐 Natural Language Processing (NLP)

Natural Language Processing (NLP) adalah salah satu bidang utama dalam kecerdasan buatan (AI) yang memungkinkan mesin untuk memahami dan merespon bahasa manusia secara alami. Dengan NLP, kita dapat membangun aplikasi yang berinteraksi dengan pengguna secara efektif, membantu analisis teks, dan mendukung berbagai fungsi otomatis dalam dunia bisnis, riset, dan kehidupan sehari-hari.

## 🧠 Apa itu NLP?

NLP bertujuan untuk menjembatani komunikasi antara manusia dan komputer. Dengan menggunakan teknik NLP, komputer dapat:
- Menganalisis dan memahami **makna teks**.
- Mengidentifikasi **entitas penting** seperti nama, lokasi, dan organisasi.
- Mengukur **emosi dan sentimen** dalam teks.
- **Menghasilkan teks** yang terdengar alami dalam banyak bahasa.

---

## 🚀 Teknologi & Metode dalam NLP

Beberapa teknologi dan pendekatan utama dalam NLP meliputi:

### 1. **Pembelajaran Mesin (Machine Learning)**
   - Model pembelajaran mesin tradisional seperti Naive Bayes, SVM, dan Random Forest sering digunakan dalam aplikasi NLP klasik.

### 2. **Pembelajaran Mendalam (Deep Learning)**
   - Model neural network seperti LSTM dan CNN membantu komputer dalam memahami konteks dan struktur kalimat.

### 3. **Transformers**  
   - Model **transformer** telah merevolusi NLP dengan memperkenalkan model seperti **BERT**, **GPT**, dan **T5** yang dapat menangani teks panjang dan kompleks, serta mendukung tugas NLP dengan lebih baik.

### 4. **Proses Pra-Pemrosesan Teks**
   - NLP membutuhkan tahap pra-pemrosesan seperti tokenisasi, stemming, lemmatization, dan stop-word removal untuk memastikan data siap digunakan oleh model.

---

## 🔥 Aplikasi NLP dalam Kehidupan Nyata

NLP memiliki berbagai aplikasi yang sangat bermanfaat, seperti:
- **Chatbots & Asisten Virtual** 🤖: Membantu pengguna dengan informasi instan dan layanan pelanggan 24/7.
- **Analisis Sentimen** 📊: Memahami opini publik dari ulasan produk, survei, atau media sosial.
- **Penerjemahan Bahasa** 🌐: Memungkinkan penerjemahan teks atau ucapan secara real-time.
- **Ekstraksi Informasi** 📄: Mengambil informasi penting dari dokumen panjang, seperti laporan keuangan atau artikel.
- **Text Summarization** 📝: Menghasilkan ringkasan dari teks panjang, berguna untuk berita atau laporan.

---

## 🛠️ Alat dan Library yang Digunakan dalam NLP

Berikut adalah beberapa alat dan pustaka utama yang digunakan dalam pengembangan sistem NLP modern:

<p>
  <img src="https://img.shields.io/badge/-NLTK-777BB4?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/-spaCy-09A3D5?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/-Transformers-FF6F00?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/-Hugging%20Face-F7B8D3?style=flat&logo=hugging-face&logoColor=black" />
</p>

---

## 📈 NLP di Era Modern: Model-Model yang Populer

Beberapa model NLP populer yang digunakan dalam proyek-proyek AI saat ini adalah:

- **BERT (Bidirectional Encoder Representations from Transformers)**  
  Memahami konteks secara bidirectional, berguna untuk berbagai tugas NLP seperti NER, Question Answering, dan lainnya.

- **GPT (Generative Pre-trained Transformer)**  
  Menghasilkan teks yang relevan dan natural dalam berbagai konteks, sering digunakan untuk chatbot dan teks generatif.

- **T5 (Text-To-Text Transfer Transformer)**  
  Mengubah semua tugas NLP menjadi masalah “teks ke teks” dan mampu menyelesaikan beragam tugas NLP.

---

## 📊 Statistik NLP

Dengan NLP, kita dapat mengumpulkan dan menganalisis data dari berbagai sumber dalam jumlah besar. Berikut adalah beberapa contoh penggunaan statistik NLP:

- **Analisis sentimen** untuk mengukur opini atau kepuasan pelanggan.
- **Frekuensi kata dan topik** untuk memahami tren yang sedang populer.
- **Klasifikasi teks** untuk mengelompokkan dokumen atau pesan otomatis.

---

## 💻 Bagaimana Mulai Menggunakan NLP di Proyek Ini

1. **Instalasi Library**: Pastikan library berikut sudah diinstal:
   ```bash
   pip install nltk spacy transformers torch</p>

   <div align="center">

<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white">
<img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white">
<img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black">

</div>

<h2 align="center"> ANALISIS </h2>
"# **Analyze**"
      ],
      "metadata": {
        "id": "fE-iXzgGyqKP"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "\n",
        "1. Zero-shot classification is an NLP technique that enables a model to classify text into categories it has not been trained on. The sentence \"Please find the attached report for your review.\" is identified with the label \"work\" (90.15%), indicating that it relates to a work context.\n",
        "\n",
        "2. Text generation is the process of creating new text. The sentence \"Life is a mystery that must be lived with full awareness,\" the model continues with \"since each step of our journey will bring us closer to a future that will end in joy (in our own special world). So many of us will need to be inspired and aware to realize..\"\n",
        "\n",
        "3. Fill-mask enables a model to guess missing words. In the sentence \"The new policy will affect the [MASK] sector significantly,\" the model predicts the word \"private\" with a score of 38.4%.\n",
        "\n",
        "4. Named Entity Recognition (NER) identifies entities in text. In the sentence \"Barack Obama was born on August 4, 1961 in Honolulu, Hawaii,\" the model detects \"Barack Obama\" as a person and \"Honolulu\" and \"Hawaii\" as locations, with confidence scores above 99%.\n",
        "\n",
        "5. Question-answering (QA) enables a model to answer questions based on context. For a sentence about Bali, when asked \"What are some popular tourist spots in Bali?\" the model answers \"Uluwatu Temple, Tanah Lot.\"\n",
        "\n",
        "6. Sentiment analysis classifies emotions in text. The sentence \"The movie had stunning visuals but the plot was quite predictable\" is labeled NEGATIVE with high confidence (99.93%) because, despite the praise, the complaint about the plot is dominant.\n",
        "\n",
        "7. Summarization condenses lengthy text into shorter, meaningful content. A model can summarize a lengthy report to highlight key information, such as the correlation between pollution and health, economic impact, and a recommendation or suggestion.\n",
        "\n",
        "8. Translation involves translating text from one language to another. The original sentence \"Indonesia adalah negara kepulauan terbesar di dunia, terdiri dari lebih dari 17.000 pulau. Negara ini terkenal dengan keanekaragaman budaya dan alamnya.\" is translated as \"Indonesia is the world's largest island nation, made up of over 17,000 islands, known for its cultural and natural diversity.\"\n",
        "\n",
        "Among all these pipeline types, Text Generation and Question-answering (QA) are perhaps the most interesting to me. Text Generation for its creativity and flexibility in producing new content, and QA for its ability to provide direct and relevant answers from existing text, which is highly useful in many practical applications.\n",
        "\n",
        "\n"


        Here’s a brief overview of the image codes (i.e., logos or symbols) associated with some of the tools and libraries mentioned in the context of NLP. These codes are often used in documentation, presentations, or educational material to represent the respective tools visually.

### Image Codes for NLP Tools and Libraries

1. **NLTK (Natural Language Toolkit)**:
   - ![NLTK Logo](https://raw.githubusercontent.com/nltk/nltk/develop/images/nltk_logo.png)

2. **spaCy**:
   - ![spaCy Logo](https://spacy.io/images/spacy-logo.svg)

3. **TensorFlow**:
   - ![TensorFlow Logo](https://www.tensorflow.org/images/tf_logo_social.png)

4. **PyTorch**:
   - ![PyTorch Logo](https://pytorch.org/assets/images/pytorch-logo-dark.svg)

5. **Transformers (by Hugging Face)**:
   - ![Transformers Logo](https://huggingface.co/front/assets/huggingface_logo.svg)

6. **Gensim**:
   - ![Gensim Logo](https://radimrehurek.com/gensim/images/gensim_logo.png)

7. **Flair**:
   - ![Flair Logo](https://raw.githubusercontent.com/flairNLP/flair/master/resources/flair_logo.png)

8. **OpenNLP**:
   - ![OpenNLP Logo](https://opennlp.apache.org/images/logo.png)

9. **AllenNLP**:
   - ![AllenNLP Logo](https://allennlp.org/images/logo.png)

These images can be used in various contexts to represent the respective NLP tools and libraries visually. If you need help using or embedding these images in a specific format, feel free to ask!
