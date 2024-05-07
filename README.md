# Fake News Detection System

In today's age of rapid misinformation dissemination, the identification of fake news has become increasingly crucial. This repository contains a comprehensive approach to detecting fake news by analyzing text, image, and URL inputs. The system employs information retrieval, natural language processing (NLP), and machine learning techniques to scrutinize the authenticity and credibility of news content. 

## Key Features

- **Text Analysis**: Utilizes a Naive Bayes classifier to evaluate the authenticity of news articles based on linguistic indicators associated with misleading or deceptive information.
  
- **Clickbait Detection**: Incorporates a Random Forest model to assess whether a news article exhibits clickbait characteristics, helping identify sensational or misleading content.
  
- **Grammar Validation**: Employs a Named Entity Recognition (NER) pipeline powered by BERT to assess the grammatical accuracy of news articles, enhancing overall credibility.
  
- **Frontend and Backend Integration**: Implements a user-friendly web interface using HTML, CSS, and JavaScript with a Flask API for backend processing.
  
- **Multilayered Validation Process**: Ensures news authenticity through a series of checks including sentence classification, grammar validation, Google News availability, and news relevance assessment.
  
- **URL Security**: Validates SSL certificates, verifies domain registration, and ensures the use of HTTPS to verify the legitimacy of news sources.
  
- **Comprehensive Web Scraping Analysis**: Conducts subjectivity, clickbait, news title validity, and Google News availability tests before scraping user-provided content.
  
- **In-depth Analysis with BARD AI**: Utilizes Google Bard to conduct authenticity and reliability assessments, contributing to the fight against misinformation.

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/fake-news-detection.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Flask application:

    ```bash
    python app.py
    ```

4. Access the web application through your browser at `http://localhost:5000`.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your_feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/your_feature`).
6. Create a new Pull Request.

## Credits

This project was developed by [Your Name](https://github.com/your_username).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
